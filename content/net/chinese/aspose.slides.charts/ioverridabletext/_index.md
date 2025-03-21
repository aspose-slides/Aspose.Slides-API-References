---
title: IOverridableText
second_title: Aspose.Slides for .NET API 参考
description: 表示图表的可覆盖文本
type: docs
weight: 2040
url: /zh/aspose.slides.charts/ioverridabletext/
---
## IOverridableText interface

表示图表的可覆盖文本。

```csharp
public interface IOverridableText : IFormattedTextContainer
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ioverridabletext/asiformattedtextcontainer) { get; } | 允许获取基本 IFormattedTextContainer 接口。 只读[`IFormattedTextContainer`](../iformattedtextcontainer)。 |
| [TextFrameForOverriding](../../aspose.slides.charts/ioverridabletext/textframeforoverriding) { get; } | 可以包含格式丰富的文本。如果此属性不为 null，则此 格式化文本值将覆盖自动生成的文本。 自动生成的文本是数据标签的隐含属性，显示 数值轴的单位标签、轴标题、图表标题、趋势线的标签。 自动生成的文本使用 IFormattedTextContainer.TextFormat 属性进行格式化。 只读[`ITextFrame`](../../aspose.slides/itextframe)。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddTextFrameForOverriding](../../aspose.slides.charts/ioverridabletext/addtextframeforoverriding)(string) | 使用参数“text”中的文本初始化 TextFrameForOverriding。 如果 TextFrameForOverriding 已经初始化，则只需更改其文本。 |

### 也可以看看

* interface [IFormattedTextContainer](../iformattedtextcontainer)
* 命名空间 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
