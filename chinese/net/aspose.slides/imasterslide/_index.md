---
title: IMasterSlide
second_title: Aspose.Slides for .NET API 参考
description: 表示演示文稿中的母版幻灯片
type: docs
weight: 5860
url: /zh/net/aspose.slides/imasterslide/
---
## IMasterSlide interface

表示演示文稿中的母版幻灯片。

```csharp
public interface IMasterSlide : IBaseSlide, IMasterThemeable
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AsIBaseSlide](../../aspose.slides/imasterslide/asibaseslide) { get; } | 允许获取基本 IBaseSlide 接口。 只读[`IBaseSlide`](../ibaseslide). |
| [AsIMasterThemeable](../../aspose.slides/imasterslide/asimasterthemeable) { get; } | 返回 IMasterThemeable 接口。 只读[`IMasterThemeable`](../../aspose.slides.theme/imasterthemeable). |
| [BodyStyle](../../aspose.slides/imasterslide/bodystyle) { get; } | 返回正文的样式。 只读[`ITextStyle`](../itextstyle). |
| [HasDependingSlides](../../aspose.slides/imasterslide/hasdependingslides) { get; } | 如果至少存在一张依赖于该母版幻灯片的幻灯片，则返回 true。 只读Boolean. |
| [HeaderFooterManager](../../aspose.slides/imasterslide/headerfootermanager) { get; } | 返回母版幻灯片的页眉页脚管理器。 只读[`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [LayoutSlides](../../aspose.slides/imasterslide/layoutslides) { get; } | 返回此母版幻灯片的子布局幻灯片的集合。 只读[`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| [OtherStyle](../../aspose.slides/imasterslide/otherstyle) { get; } | 返回其他文本的样式。 只读[`ITextStyle`](../itextstyle). |
| [Preserve](../../aspose.slides/imasterslide/preserve) { get; set; } | 确定当所有 该母版后面的幻灯片都被删除时是否删除相应母版。 注意：Aspose.Slides永远不会自行删除任何未使用的母版， 要实际删除未使用的母版调用[`RemoveUnused`](../imasterslidecollection/removeunused) 读/写Boolean. |
| [TitleStyle](../../aspose.slides/imasterslide/titlestyle) { get; } | 返回标题文本的样式。 只读[`ITextStyle`](../itextstyle). |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/imasterslide/applyexternalthemetodependingslides)(string) | 在当前幻灯片的基础上创建新的母版幻灯片，为其应用外部主题 并将创建的母版幻灯片应用于所有相关幻灯片。 |
| [GetDependingSlides](../../aspose.slides/imasterslide/getdependingslides)() | 返回一个包含所有幻灯片的数组，这些幻灯片取决于此母版幻灯片。 |

### 也可以看看

* interface [IBaseSlide](../ibaseslide)
* interface [IMasterThemeable](../../aspose.slides.theme/imasterthemeable)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
