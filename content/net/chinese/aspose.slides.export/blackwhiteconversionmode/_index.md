---
title: BlackWhiteConversionMode
second_title: Aspose.Sildes for .NET API Reference
description: 提供控制幻灯片图像转换为二值图像的选项。
type: docs
weight: 3560
url: /zh/aspose.slides.export/blackwhiteconversionmode/
---

## BlackWhiteConversionMode枚举

提供控制幻灯片图像如何转换为二值图像的选项。

```csharp
public enum BlackWhiteConversionMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Default | `0` | 指定不使用转换算法。将使用TIFF编码器中实现的算法。（默认） |
| Dithering | `1` | 指定抖动算法（Floyd-Steinberg）。 |
| DitheringFloydSteinberg | `2` | 指定Floyd-Steinberg抖动算法。 |
| Auto | `3` | 指定自动计算的阈值算法（Otsu）。 |
| AutoOtsu | `4` | 指定自动计算的Otsu阈值算法。 |
| Threshold25 | `5` | 指定静态阈值算法（25%）。 |
| Threshold50 | `6` | 指定静态阈值算法（50%）。 |
| Threshold75 | `7` | 指定静态阈值算法（75%）。 |

### 另见

* 命名空间 [Aspose.Slides.Export](../../aspose.slides.export)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->