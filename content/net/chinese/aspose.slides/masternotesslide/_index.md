---
title: MasterNotesSlide
second_title: Aspose.Slides for .NET API 参考
description: 代表笔记的母版幻灯片
type: docs
weight: 7300
url: /zh/aspose.slides/masternotesslide/
---
## MasterNotesSlide class

代表笔记的母版幻灯片。

```csharp
public class MasterNotesSlide : BaseSlide, IMasterNotesSlide
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | 返回幻灯片的背景。 只读[`IBackground`](../ibackground)。 |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | 返回幻灯片上 ActiveX 控件的集合。 只读[`IControlCollection`](../icontrolcollection)。 |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | 返回幻灯片的自定义数据。 只读[`ICustomData`](../icustomdata)。 |
| [HeaderFooterManager](../../aspose.slides/masternotesslide/headerfootermanager) { get; } | 返回主注释幻灯片的 HeaderFooter 管理器。 只读[`IMasterHandoutSlideHeaderFooterManager`](../imasterhandoutslideheaderfootermanager)。 |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | 提供对包含的超链接的轻松访问。 只读[`IHyperlinkQueries`](../ihyperlinkqueries)。 |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | 返回或设置幻灯片的名称。 读/写String。 |
| [NotesStyle](../../aspose.slides/masternotesslide/notesstyle) { get; } | 返回注释文本的样式。 只读[`ITextStyle`](../itextstyle)。 |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | 返回 IPresentation 接口。 只读[`IPresentation`](../ipresentation)。 |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | 返回幻灯片的形状。 只读[`IShapeCollection`](../ishapecollection)。 |
| override [ShowMasterShapes](../../aspose.slides/masternotesslide/showmastershapes) { get; set; } | 指定母版幻灯片上的形状是否应显示在幻灯片上。 对于母版幻灯片本身，此属性始终返回` false` 。 读/写Boolean。 |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | 返回幻灯片的 ID。 只读UInt32。 |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | 返回包含有关 指定幻灯片在幻灯片放映期间如何前进的信息的转换对象。 只读[`ISlideShowTransition`](../islideshowtransition)。 |
| [ThemeManager](../../aspose.slides/masternotesslide/thememanager) { get; } | 返回主题管理器。 只读[`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager)。 |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | 返回动画时间线对象。 只读[`IAnimationTimeLine`](../ianimationtimeline)。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | 返回此幻灯片的有效主题。 |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | 确定两个 IBaseSlide 实例是否相等。 返回值是根据幻灯片的结构和静态内容计算的。 如果所有形状、样式、文本、动画和其他设置，两张幻灯片相等。等是平等的。比较不考虑唯一标识符值，例如 SlideId 和动态内容，例如日期占位符中的当前日期值。 |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | 查找具有指定替代文本的形状的第一个匹配项。 |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | 连接在所有段落中以相同格式运行，所有可接受的形状。 |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | 在所有可接受的形状的所有段落中以相同的格式运行连接。 |

### 也可以看看

* class [BaseSlide](../baseslide)
* interface [IMasterNotesSlide](../imasternotesslide)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
