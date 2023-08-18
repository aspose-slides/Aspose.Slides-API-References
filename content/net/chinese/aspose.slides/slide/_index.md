---
title: Slide
second_title: Aspose.Slides for .NET API 参考
description: 表示演示文稿中的幻灯片
type: docs
weight: 9180
url: /zh/aspose.slides/slide/
---
## Slide class

表示演示文稿中的幻灯片。

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | 返回幻灯片的背景。 只读[`IBackground`](../ibackground)。 |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | 返回幻灯片上 ActiveX 控件的集合。 只读[`IControlCollection`](../icontrolcollection)。 |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | 返回幻灯片的自定义数据。 只读[`ICustomData`](../icustomdata)。 |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | 返回幻灯片的 HeaderFooter 管理器。 只读[`ISlideHeaderFooterManager`](../islideheaderfootermanager)。 |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | 确定幻灯片放映期间是否隐藏指定的幻灯片。 读/写Boolean。 |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | 提供对包含的超链接的轻松访问。 只读[`IHyperlinkQueries`](../ihyperlinkqueries)。 |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | 返回或设置当前幻灯片的布局幻灯片。 读/写[`ILayoutSlide`](../ilayoutslide)。 |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | 返回或设置幻灯片的名称。 读/写String。 |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | 允许访问笔记幻灯片，添加和删除它。 只读[`INotesSlideManager`](../inotesslidemanager)。 |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | 返回 IPresentation 接口。 只读[`IPresentation`](../ipresentation)。 |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | 返回幻灯片的形状。 只读[`IShapeCollection`](../ishapecollection)。 |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | 指定母版幻灯片上的形状是否应显示在幻灯片上。 读/写Boolean。 |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | 返回幻灯片的 ID。 只读UInt32。 |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | 返回幻灯片的数量。 [`Slides`](../presentation/slides)集合中幻灯片的索引始终等于 SlideNumber - Presentation.FirstSlideNumber。 读/写Int32。 |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | 返回包含有关 指定幻灯片在幻灯片放映期间如何前进的信息的转换对象。 只读[`ISlideShowTransition`](../islideshowtransition)。 |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | 返回最重要的主题管理器。 只读[`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager)。 |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | 返回动画时间线对象。 只读[`IAnimationTimeLine`](../ianimationtimeline)。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | 返回此幻灯片的有效主题。 |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | 确定两个 IBaseSlide 实例是否相等。 返回值是根据幻灯片的结构和静态内容计算的。 如果所有形状、样式、文本、动画和其他设置，两张幻灯片相等。等是平等的。比较不考虑唯一标识符值，例如 SlideId 和动态内容，例如日期占位符中的当前日期值。 |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | 查找具有指定替代文本的形状的第一个匹配项。 |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | 返回特定作者添加的所有幻灯片评论。 |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail)() | 返回缩略图图像对象（实际大小的 20%）。 |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail_4)(IRenderingOptions) | 返回缩略图位图对象。 |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail_7)(ITiffOptions) | 返回带有指定参数的 Thumbnail tiff 位图对象。 |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail_9)(Size) | 返回具有指定大小的缩略图位图对象。 |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail_8)(float, float) | 返回具有自定义缩放的缩略图位图对象。 |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail_6)(IRenderingOptions, Size) | 返回具有指定大小的缩略图位图对象。 |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail_5)(IRenderingOptions, float, float) | 返回具有自定义缩放的缩略图位图对象。 |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | 在所有可接受的形状的所有段落中以相同的格式运行连接。 |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | 在所有可接受的形状的所有段落中以相同的格式运行连接。 |
| [Remove](../../aspose.slides/slide/remove)() | 从演示文稿中删除幻灯片。 |
| [RenderToGraphics](../../aspose.slides/slide/rendertographics#rendertographics_3)(IRenderingOptions, Graphics) | 将某些幻灯片呈现给图形对象。 |
| [RenderToGraphics](../../aspose.slides/slide/rendertographics#rendertographics_5)(IRenderingOptions, Graphics, Size) | 使用指定大小将某些幻灯片渲染到 Graphics 对象。 |
| [RenderToGraphics](../../aspose.slides/slide/rendertographics#rendertographics_4)(IRenderingOptions, Graphics, float, float) | 使用自定义缩放将某些幻灯片渲染到 Graphics 对象。 |
| [Reset](../../aspose.slides/slide/reset)() | 重置在 LayoutSlide 上有原型的每个形状的位置、大小和格式。 |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | 将幻灯片的内容保存为 SVG 文件。 |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | 将幻灯片的内容保存为 SVG 文件。 |

### 也可以看看

* class [BaseSlide](../baseslide)
* interface [ISlide](../islide)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
