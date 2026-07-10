---
title: License
second_title: Aspose.Slides for Android via Java API 参考
description: 提供用于授权组件的方法。
type: docs
url: /zh/com.aspose.slides/license/
---
**继承:**  
java.lang.Object

**所有已实现的接口:**  
[com.aspose.slides.ILicense](../../com.aspose.slides/ilicense)  
```
public final class License implements ILicense
```

提供用于授权组件的方法。

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [License()](#License--) | Initializes a new instance of this class. |
## Methods

| Method | Description |
| --- | --- |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licenses the component. |
| [setLicense(String namePath)](#setLicense-java.lang.String-) | Licenses the component. |
| [getVersion()](#getVersion--) | Returns version of Aspose.Slides for Android via Java. |
| [resetLicense()](#resetLicense--) | Reset the license. |
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```


Initializes a new instance of this class.

```
在此示例中，将尝试在以下位置查找名为 MyLicense.lic 的许可证文件：包含组件的文件夹、包含调用程序集的文件夹、入口程序集的文件夹，以及调用程序集的嵌入资源。

```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream stream)
```

Licenses the component.

```
在此示例中，将尝试在以下位置查找名为 MyLicense.lic 的许可证文件：包含组件的文件夹、包含调用程序集的文件夹、入口程序集的文件夹，以及调用程序集的嵌入资源。

```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | A stream that contains the license. Use null to switch to evaluation mode. |

### setLicense(String namePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String namePath)
```

Licenses the component.

```
在此示例中，将尝试在以下位置查找名为 MyLicense.lic 的许可证文件：包含组件的文件夹、包含调用程序集的文件夹、入口程序集的文件夹，以及调用程序集的嵌入资源。

```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| namePath | java.lang.String | Can be a full or short file name or name of an embedded resource. Use an empty string to switch to evaluation mode. |

### getVersion() {#getVersion--}
```
public static final String getVersion()
```

Returns version of Aspose.Slides for Android via Java.

**Returns:**
java.lang.String
### resetLicense() {#resetLicense--}
```
public final void resetLicense()
```

重置许可。使用此方法可以在组件中重置许可。

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
Check if licence is applied to component

**返回:**  
boolean