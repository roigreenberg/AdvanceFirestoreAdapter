How to
To get a Git project into your build:

Step 1. Add the JitPack repository to your build file

Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  
Step 2. Add the dependency

	dependencies {
	        compile 'com.github.roigreenberg:SelectableFirebaseAdapter:0.0.1'
	}


Credits:
This projerct is based on https://github.com/Kernald/recyclerview-sample/tree/master/app/src/main/java/fr/enoent/recyclerviewsample
