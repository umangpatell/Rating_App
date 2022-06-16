# Rating_App
This is the demo app

> Step 1. Add the JitPack repository to your build file

```gradle
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  
  > Step 2. Add the dependency
  
  ```gradle
  dependencies {
	        implementation 'com.github.umangpatell:Rating_App:Tag'
	}
