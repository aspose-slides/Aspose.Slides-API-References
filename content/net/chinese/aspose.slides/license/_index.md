---
title: License
second_title: Aspose.Sildes for .NET API Reference
description: 提供组件许可的方法。
type: docs
weight: 7440
url: /zh/aspose.slides/license/
---

## License class

提供组件许可的方法。

```csharp
public class License : ILicense
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [License](license)() | 初始化此类的新实例。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [IsLicensed](../../aspose.slides/license/islicensed)() | 检查许可证是否已应用于组件 |
| [ResetLicense](../../aspose.slides/license/resetlicense)() | 重置许可证 |
| [SetLicense](../../aspose.slides/license/setlicense#setlicense)(Stream) | 对组件进行许可。 |
| [SetLicense](../../aspose.slides/license/setlicense#setlicense_1)(string) | 对组件进行许可。 |

### 示例

在此示例中，将尝试在包含组件的文件夹、调用程序集的文件夹、入口程序集的文件夹和调用程序集的嵌入资源中查找名为 MyLicense.lic 的许可证文件。

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### 另见

* 接口 [ILicense](../ilicense)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->