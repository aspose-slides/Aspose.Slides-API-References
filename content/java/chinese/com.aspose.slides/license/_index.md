---
title: License
second_title: Aspose.Slides for Java API 参考
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
在本示例中，将尝试查找名为 MyLicense.lic 的许可证文件
 在包含组件的文件夹中，在包含调用程序集的文件夹中，
 在入口程序集的文件夹中，然后在调用程序集的嵌入资源中。
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [License()](#License--) | 初始化此类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | 授权组件。 |
| [setLicense(String namePath)](#setLicense-java.lang.String-) | 授权组件。 |
| [getVersion()](#getVersion--) | 返回 Aspose.Slides for Java 的版本。 |
| [resetLicense()](#resetLicense--) | 重置许可证。 |
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```

初始化此类的新实例。

```
在本示例中，将尝试查找名为 MyLicense.lic 的许可证文件
 在包含组件的文件夹中，在包含调用程序集的文件夹中，
 在入口程序集的文件夹中，然后在调用程序集的嵌入资源中。
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

授权组件。

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

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 包含许可证的流。使用 null 切换到评估模式。 |

### setLicense(String namePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String namePath)
```

授权组件。

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

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| namePath | java.lang.String | 可以是完整或简短的文件名或嵌入资源的名称。使用空字符串切换到评估模式。 |

### getVersion() {#getVersion--}
```
public static final String getVersion()
```

返回 Aspose.Slides for Java 的版本。

**返回值:**
java.lang.String
### resetLicense() {#resetLicense--}
```
public final void resetLicense()
```

重置许可证。使用此方法在组件中重置许可证。

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```


### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```

检查组件是否已应用许可证

**返回值:**
boolean