---
title: ILicense
second_title: Aspose.Slides for Java API Reference
description: 为组件提供授权方法。
type: docs
url: /zh/com.aspose.slides/ilicense/
---```
public interface ILicense
```

为组件提供授权方法。

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```
## 方法

| 方法 | 描述 |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | 授权组件。 |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | 授权组件。 |
| [resetLicense()](#resetLicense--) | 重置授权 |
| [isLicensed()](#isLicensed--) | 检查组件是否已授权 |
### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public abstract void setLicense(String licenseName)
```


授权组件。

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| licenseName | java.lang.String | 可以是完整或简短的文件名或嵌入式资源的名称。使用空字符串切换到评估模式。

--------------------

尝试在以下位置查找许可证：

1. 明确路径。

2. 组件程序集的文件夹。

3. 客户端调用程序集的文件夹。

4. 入口程序集的文件夹。

5. 客户端调用程序集中的嵌入式资源。 |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public abstract void setLicense(InputStream stream)
```


授权组件。

--------------------

> ```
> License license = new License();
>  license.setLicense(myStream);
> ```


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 包含许可证的流。

--------------------

使用此方法从流加载许可证。 |

### resetLicense() {#resetLicense--}
```
public abstract void resetLicense()
```


重置授权

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

--------------------

使用此方法在组件中重置许可证

### isLicensed() {#isLicensed--}
```
public abstract boolean isLicensed()
```


检查组件是否已授权

**返回:**
boolean - 如果组件已授权则为 true，否则为 false