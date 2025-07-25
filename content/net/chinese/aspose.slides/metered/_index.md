---
title: Metered
second_title: Aspose.Sildes for .NET API Reference
description: 提供设置计量密钥的方法。
type: docs
weight: 8810
url: /zh/aspose.slides/metered/
---

## Metered class

提供设置计量密钥的方法。

```csharp
public class Metered
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Metered](metered)() | 初始化此类的新实例。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [SetMeteredKey](../../aspose.slides/metered/setmeteredkey)(string, string) | 设置计量的公钥和私钥 |
| static [GetConsumptionCredit](../../aspose.slides/metered/getconsumptioncredit)() | 获取消费信用 |
| static [GetConsumptionQuantity](../../aspose.slides/metered/getconsumptionquantity)() | 获取消费文件大小 |
| static [IsMeteredLicensed](../../aspose.slides/metered/ismeteredlicensed)() | 检查计量是否已获得许可 |

### 示例

在此示例中，将尝试设置计量的公钥和私钥。

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### 另请参阅

* 命名空间 [Aspose.Slides](../../aspose.slides)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->