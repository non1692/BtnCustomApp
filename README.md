**Implementation**

Step 1. Add the JitPack repository to your build file

```
	dependencyResolutionManagement {
		repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
		repositories {
			mavenCentral()
			maven { url 'https://jitpack.io' }
		}
	}

```

Step 2. Add the dependency

```
dependencies {
	        implementation 'com.github.non1692:BtnCustomApp:1.0.1'
	}

```


Code
```
    <com.softtek.buttoncustom.CustomButton
        android:id="@+id/btnDemo"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="24dp"
        android:layout_marginEnd="24dp"
        android:layout_marginBottom="100dp"
        android:text="test"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:styledButton="dark" />

```

![image](https://github.com/non1692/BtnCustomApp/assets/17265011/7a9d78e7-22d7-4790-a460-d057bfc07d4e)


