# IconTitleCell

Android仿iOS图标文本单元格

![](http://upload-images.jianshu.io/upload_images/2746415-62ef027258e9fdd2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


## Installing

Users of your library will need add the jitpack.io repository:

```gradle
allprojects {
 repositories {
    jcenter()
    maven { url "https://jitpack.io" }
 }
}
```

and:

```gradle
dependencies {
    compile 'com.github.zhouchupen:IconTitleCell:v.1.0'
}
```

Note: do not add the jitpack.io repository under `buildscript` 

## Adding a sample app 

If you add a sample app to the same repo then your app needs to depend on the library. To do this in your app/build.gradle add a dependency in the form:

```gradle
dependencies {
    compile project(':library')
}
```

where 'library' is the name of your library module.

## Using

You may need this to use the cell.  Put this into your xml file:
```xml
<com.scnu.zhou.widget.IconTitleCell
     android:layout_width="match_parent"
     android:layout_height="wrap_content"
     app:text="设置"
     app:icon="@drawable/icon_setting"
     app:isdivider="false">

</com.scnu.zhou.widget.IconTitleCell>
```
