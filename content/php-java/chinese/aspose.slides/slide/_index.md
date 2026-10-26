---
title: Slide
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs
url: /zh/aspose.slides/slide/
---
## Slide 类

  表示演示文稿中的幻灯片。
 
### getHeaderFooterManager {#getHeaderFooterManager}

| 名称 | 描述 |
| --- | --- |
| getHeaderFooterManager () | 返回该幻灯片的 HeaderFooter 管理器。只读 ISlideHeaderFooterManager。 |

**返回值：**
[SlideHeaderFooterManager](../slideheaderfootermanager)

---


### getHidden {#getHidden}

| 名称 | 描述 |
| --- | --- |
| getHidden () | 确定在幻灯片放映期间指定的幻灯片是否隐藏。读/写 boolean。 |

**返回值：**
boolean

---


### getImage {#getImage}

| 名称 | 描述 |
| --- | --- |
| getImage (float, float) | 返回具有自定义缩放的缩略图 Image 对象。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| scaleX | float | 在 X 轴方向上缩放此缩略图的值。 |
| scaleY | float | 在 Y 轴方向上缩放此缩略图的值。 |

**返回值：**
IImage

---


### getImage {#getImage}

| 名称 | 描述 |
| --- | --- |
| getImage () | 返回一个缩略图 Image 对象（实际大小的 20%）。 |

**返回值：**
IImage

---


### getImage {#getImage}

| 名称 | 描述 |
| --- | --- |
| getImage (Dimension) | 返回具有指定大小的缩略图 Image 对象。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| imageSize | Dimension | 要创建的图像的大小。 |

**返回值：**
IImage

---


### getImage {#getImage}

| 名称 | 描述 |
| --- | --- |
| getImage ([TiffOptions](../tiffoptions)) | 返回具有指定参数的缩略图 tiff 图像对象。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| options | [TiffOptions](../tiffoptions) | Tiff 选项。 |

**返回值：**
IImage

**异常**

| 错误 | 条件 |
| --- | --- |
| InvalidOperationException | 当 options.SlideLayoutOption 为 NotesCommentsLayoutingOptions 且其属性 NotesPosition 取值 NotesPositions.BottomFull 时抛出。 |

---


### getImage {#getImage}

| 名称 | 描述 |
| --- | --- |
| getImage ([RenderingOptions](../renderingoptions)) | 返回缩略图 Image 对象。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | 渲染选项。 |

**返回值：**
IImage

**异常**

| 错误 | 条件 |
| --- | --- |
| InvalidOperationException | 当 notesCommentsLayouting.NotesPosition 取值 NotesPositions.BottomFull 时抛出。 |

---


### getImage {#getImage}

| 名称 | 描述 |
| --- | --- |
| getImage ([RenderingOptions](../renderingoptions), float, float) | 返回具有自定义缩放的缩略图 Image 对象。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | 渲染选项。 |
| scaleX | float | 在 X 轴方向上缩放此缩略图的值。 |
| scaleY | float | 在 Y 轴方向上缩放此缩略图的值。 |

**返回值：**
IImage

**异常**

| 错误 | 条件 |
| --- | --- |
| InvalidOperationException | 当 notesCommentsLayouting.NotesPosition 取值 NotesPositions.BottomFull 时抛出。 |

---


### getImage {#getImage}

| 名称 | 描述 |
| --- | --- |
| getImage ([RenderingOptions](../renderingoptions), Dimension) | 返回具有指定大小的缩略图 Image 对象。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | 渲染选项。 |
| imageSize | Dimension | 要创建的图像的大小。 |

**返回值：**
IImage

**异常**

| 错误 | 条件 |
| --- | --- |
| InvalidOperationException | 当 options.SlideLayoutOption 为 NotesCommentsLayoutingOptions 且其属性 NotesPosition 取值 NotesPositions.BottomFull 时抛出。 |

---


### getLayoutSlide {#getLayoutSlide}

| 名称 | 描述 |
| --- | --- |
| getLayoutSlide () | 返回或设置当前幻灯片的布局幻灯片。读/写 ILayoutSlide。 |

**返回值：**
[LayoutSlide](../layoutslide)

---


### getNotesSlideManager {#getNotesSlideManager}

| 名称 | 描述 |
| --- | --- |
| getNotesSlideManager () | 允许访问备注幻灯片，添加和移除它。只读 INotesSlideManager。 |

**返回值：**
[NotesSlideManager](../notesslidemanager)

---


### getShowMasterShapes {#getShowMasterShapes}

| 名称 | 描述 |
| --- | --- |
| getShowMasterShapes () | 指定是否在幻灯片上显示母版幻灯片的形状。读/写 boolean。 |

**返回值：**
boolean

---


### getSlideComments {#getSlideComments}

| 名称 | 描述 |
| --- | --- |
| getSlideComments ([CommentAuthor](../commentauthor)) | 返回指定作者添加的所有幻灯片评论。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| author | [CommentAuthor](../commentauthor) | 要查找的评论作者，或 null 表示返回所有评论。 |

**返回值：**
[Comment](../comment), [ModernComment](../moderncomment)

---


### getSlideNumber {#getSlideNumber}

| 名称 | 描述 |
| --- | --- |
| getSlideNumber () | 返回幻灯片的编号。Presentation#getSlides 集合中的索引始终等于 SlideNumber - Presentation.FirstSlideNumber。读/写 int。 |

**返回值：**
int

---


### getThemeManager {#getThemeManager}

| 名称 | 描述 |
| --- | --- |
| getThemeManager () | 返回覆盖的主题管理器。只读 IOverrideThemeManager。 |

**返回值：**
[SlideThemeManager](../slidethememanager), [LayoutSlideThemeManager](../layoutslidethememanager), [ChartThemeManager](../chartthememanager), [BaseOverrideThemeManager](../baseoverridethememanager), [NotesSlideThemeManager](../notesslidethememanager)

---


### joinPortionsWithSameFormatting {#joinPortionsWithSameFormatting}

| 名称 | 描述 |
| --- | --- |
| joinPortionsWithSameFormatting () | 合并所有可接受形状中所有段落的具有相同格式的运行。 |

**返回值：**
void

---


### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove () | 从演示文稿中移除幻灯片。 |

**返回值：**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| PptxEditException | 如果幻灯片已从演示文稿中移除则抛出。 |

---


### reset {#reset}

| 名称 | 描述 |
| --- | --- |
| reset () | 重置在 LayoutSlide 上具有原型的每个形状的位置、大小和格式。 |

**返回值：**
void

---


### setHidden {#setHidden}

| 名称 | 描述 |
| --- | --- |
| setHidden (boolean) | 确定在幻灯片放映期间指定的幻灯片是否隐藏。读/写 boolean。 |

**返回值：**
void

---


### setLayoutSlide {#setLayoutSlide}

| 名称 | 描述 |
| --- | --- |
| setLayoutSlide ([LayoutSlide](../layoutslide)) | 返回或设置当前幻灯片的布局幻灯片。读/写 ILayoutSlide。 |

**返回值：**
void

---


### setShowMasterShapes {#setShowMasterShapes}

| 名称 | 描述 |
| --- | --- |
| setShowMasterShapes (boolean) | 指定是否在幻灯片上显示母版幻灯片的形状。读/写 boolean。 |

**返回值：**
void

---


### setSlideNumber {#setSlideNumber}

| 名称 | 描述 |
| --- | --- |
| setSlideNumber (int) | 返回幻灯片的编号。Presentation#getSlides 集合中的索引始终等于 SlideNumber - Presentation.FirstSlideNumber。读/写 int。 |

**返回值：**
void

---


### writeAsEmf {#writeAsEmf}

| 名称 | 描述 |
| --- | --- |
| writeAsEmf (OutputStream) | 将幻灯片内容保存为 EMF 文件。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | OutputStream | 目标流 |

**返回值：**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentNullException | 目标流为 {@code null} 时抛出。 |

---


### writeAsSvg {#writeAsSvg}

| 名称 | 描述 |
| --- | --- |
| writeAsSvg (OutputStream) | 将幻灯片内容保存为 SVG 文件。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | OutputStream | 目标流 |

**返回值：**
void

---


### writeAsSvg {#writeAsSvg}

| 名称 | 描述 |
| --- | --- |
| writeAsSvg (OutputStream, [SVGOptions](../svgoptions)) | 将幻灯片内容保存为 SVG 文件。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | OutputStream | 目标流 |
| svgOptions | [SVGOptions](../svgoptions) | SVG 生成选项 |

**返回值：**
void

---