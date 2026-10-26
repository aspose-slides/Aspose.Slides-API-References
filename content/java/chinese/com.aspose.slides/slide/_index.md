---
title: Slide
second_title: Aspose.Slides for Java API 参考
description: 表示演示文稿中的幻灯片。
type: docs
url: /zh/com.aspose.slides/slide/
---
**继承:**  
[com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**所有实现的接口:**  
[com.aspose.slides.ISlide](../../com.aspose.slides/islide)
```
public final class Slide extends BaseSlide implements ISlide
```

表示演示文稿中的幻灯片。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 返回幻灯片的 HeaderFooter 管理器。 |
| [getThemeManager()](#getThemeManager--) | 返回覆盖主题的管理器。 |
| [getSlideNumber()](#getSlideNumber--) | 返回幻灯片的编号。 |
| [setSlideNumber(int value)](#setSlideNumber-int-) | 返回幻灯片的编号。 |
| [getHidden()](#getHidden--) | 确定在放映期间指定的幻灯片是否隐藏。 |
| [setHidden(boolean value)](#setHidden-boolean-) | 确定在放映期间指定的幻灯片是否隐藏。 |
| [getShowMasterShapes()](#getShowMasterShapes--) | 指定主幻灯片上的形状是否应在幻灯片中显示。 |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | 指定主幻灯片上的形状是否应在幻灯片中显示。 |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | 返回具有自定义缩放的缩略图图像对象。 |
| [getImage()](#getImage--) | 返回 20% 实际大小的缩略图图像对象。 |
| [getImage(Dimension imageSize)](#getImage-java.awt.Dimension-) | 返回具有指定大小的缩略图图像对象。 |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | 返回具有指定参数的缩略图 tiff 图像对象。 |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | 返回缩略图图像对象。 |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | 返回具有自定义缩放的缩略图图像对象。 |
| [getImage(IRenderingOptions options, Dimension imageSize)](#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | 返回具有指定大小的缩略图图像对象。 |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | 将幻灯片内容保存为 SVG 文件。 |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | 将幻灯片内容保存为 SVG 文件。 |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | 将幻灯片内容保存为 EMF 文件。 |
| [remove()](#remove--) | 从演示文稿中删除幻灯片。 |
| [getLayoutSlide()](#getLayoutSlide--) | 返回或设置当前幻灯片的布局幻灯片。 |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | 返回或设置当前幻灯片的布局幻灯片。 |
| [reset()](#reset--) | 重置在 LayoutSlide 上有原型的每个形状的位置、大小和格式。 |
| [getNotesSlideManager()](#getNotesSlideManager--) | 允许访问备注幻灯片，添加和删除它。 |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | 返回特定作者添加的所有幻灯片评论。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 在所有可接受的形状的所有段落中合并具有相同格式的运行。 |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ISlideHeaderFooterManager getHeaderFooterManager()
```

返回幻灯片的 HeaderFooter 管理器。只读 [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)。

**返回:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

返回覆盖主题的管理器。只读 [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)。

**返回:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)

### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```

返回幻灯片的编号。[Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) 集合中的幻灯片索引始终等于 SlideNumber - Presentation.FirstSlideNumber。可读写 int。

**返回:**
int

### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```

返回幻灯片的编号。[Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) 集合中的幻灯片索引始终等于 SlideNumber - Presentation.FirstSlideNumber。可读写 int。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

确定在放映期间指定的幻灯片是否隐藏。可读写 boolean。

**返回:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

确定在放映期间指定的幻灯片是否隐藏。可读写 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

指定主幻灯片上的形状是否应在幻灯片中显示。可读写 boolean。

**返回:**
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

指定主幻灯片上的形状是否应在幻灯片中显示。可读写 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

返回具有自定义缩放的缩略图图像对象。

--------------------

> ```
> The following example shows how to generate thumbnails from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("ThumbnailFromSlide.pptx");
>  try {
>      // 访问第一张幻灯片
>      ISlide sld = pres.getSlides().get_Item(0);
>      // 创建全尺寸图像
>      IImage bmp = sld.getImage(1f, 1f);
>      // 将图像以 JPEG 格式保存到磁盘
>      bmp.save("Thumbnail_out.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to converting slides to bitmap and saving the images in PNG.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // 将演示文稿中的第一张幻灯片转换为 Bitmap 对象
>      IImage bmp = pres.getSlides().get_Item(0).getImage();
>      // 将图像以 PNG 格式保存
>      bmp.save("Slide_0.png", ImageFormat.Png);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint PPT/PPTX to JPG.
>  
>  Presentation pres = new Presentation("PowerPoint-Presentation.ppt");
>  try {
>      for (ISlide sld : pres.getSlides())
>      {
>          // 创建全尺寸图像
>          IImage bmp = sld.getImage(1f, 1f);
>          // 将图像以 JPEG 格式保存到磁盘
>          bmp.save("Slide_"+sld.getSlideNumber()+"0.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint PPT/PPTX to JPG with customized dimensions.
>  
>  Presentation pres = new Presentation("PowerPoint-Presentation.pptx");
>  try {
>      // 定义尺寸
>      int desiredX = 1200;
>      int desiredY = 800;
>      // 获取 X 和 Y 的缩放值
>      float ScaleX = (float)(1.0 / pres.getSlideSize().getSize().getWidth()) * desiredX;
>      float ScaleY = (float)(1.0 / pres.getSlideSize().getSize().getHeight()) * desiredY;
>      for (ISlide sld : pres.getSlides())
>      {
>          // 创建全尺寸图像
>          IImage bmp = sld.getImage(ScaleX, ScaleY);
>          // 将图像以 JPEG 格式保存到磁盘
>          bmp.save("Slide.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
> ```


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| scaleX | float | 在 x 轴方向上缩放此缩略图的值。 |
| scaleY | float | 在 y 轴方向上缩放此缩略图的值。 |

**返回:**
[IImage](../../com.aspose.slides/iimage) - IImage 对象。

### getImage() {#getImage--}
```
public final IImage getImage()
```

返回 20% 实际大小的缩略图图像对象。

**返回:**
[IImage](../../com.aspose.slides/iimage)

### getImage(Dimension imageSize) {#getImage-java.awt.Dimension-}
```
public final IImage getImage(Dimension imageSize)
```

返回具有指定大小的缩略图图像对象。

--------------------

> ```
> The following example shows how to converting slides to images with custom sizes using C#.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // 将演示文稿中的第一张幻灯片转换为具有指定尺寸的 Bitmap
>      IImage bmp = pres.getSlides().get_Item(0).getImage(new Dimension(1820, 1040));
>      // 以 JPEG 格式保存图像
>      bmp.save("Slide_0.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageSize | java.awt.Dimension | 要创建的图像大小。 |

**返回:**
[IImage](../../com.aspose.slides/iimage) - Image 对象。

### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public final IImage getImage(ITiffOptions options)
```

返回具有指定参数的缩略图 tiff 图像对象。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tiff 选项。 |

**返回:**
[IImage](../../com.aspose.slides/iimage) - Image 对象。

### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public final IImage getImage(IRenderingOptions options)
```

返回缩略图图像对象。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 渲染选项。 |

**返回:**
[IImage](../../com.aspose.slides/iimage) - Image 对象。

### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

返回具有自定义缩放的缩略图图像对象。

--------------------

> ```
> The following example shows how to converting slides With notes and comments to Images.
>  
>  Presentation pres = new Presentation("PresentationNotesComments.pptx");
>  try {
>      // 创建渲染选项
>      IRenderingOptions options = new RenderingOptions();
>      // 创建备注和评论的布局选项
>      NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
>      // 设置页面上备注的位置
>      notesCommentsLayouting.setNotesPosition(NotesPositions.BottomTruncated);
>      // 设置页面上评论的位置
>      notesCommentsLayouting.setCommentsPosition(CommentsPositions.Right);
>      // 设置评论输出区域的宽度
>      notesCommentsLayouting.setCommentsAreaWidth(500);
>      // 设置评论区域的颜色
>      notesCommentsLayouting.setCommentsAreaColor(Color.WHITE);
>      // 设置渲染的布局选项
>      options.setSlidesLayoutOptions(notesCommentsLayouting);
>      // 将演示文稿的第一张幻灯片转换为 BufferedImage 对象
>      IImage image = pres.getSlides().get_Item(0).getImage(options, 2f, 2f);
>      // 以 GIF 格式保存图像
>      image.save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 渲染选项。 |
| scaleX | float | 在 x 轴方向上缩放此缩略图的值。 |
| scaleY | float | 在 y 轴方向上缩放此缩略图的值。 |

**返回:**
[IImage](../../com.aspose.slides/iimage) - Bitmap 对象。

### getImage(IRenderingOptions options, Dimension imageSize) {#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public final IImage getImage(IRenderingOptions options, Dimension imageSize)
```

返回具有指定大小的缩略图图像对象。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 渲染选项。 |
| imageSize | java.awt.Dimension | 要创建的图像大小。 |

**返回:**
[IImage](../../com.aspose.slides/iimage) - Image 对象。

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

将幻灯片内容保存为 SVG 文件。

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.svg");
>      {
>          // 将第一张幻灯片保存为 SVG 文件
>          pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 目标流 |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

将幻灯片内容保存为 SVG 文件。

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file with options.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide1.svg");
>      SVGOptions options = new SVGOptions();
>      options.setVectorizeText(true);
>      // 将第一张幻灯片保存为 SVG 文件
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 目标流 |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG 生成选项 |

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

将幻灯片内容保存为 EMF 文件。

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into a metafile.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.emf");
>      {
>          // 将第一张幻灯片保存为元文件
>          pres.getSlides().get_Item(0).writeAsEmf(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 目标流 |

### remove() {#remove--}
```
public final void remove()
```

从演示文稿中删除幻灯片。

### getLayoutSlide() {#getLayoutSlide--}
```
public final ILayoutSlide getLayoutSlide()
```

返回或设置当前幻灯片的布局幻灯片。可读写 [ILayoutSlide](../../com.aspose.slides/ilayoutslide)。

**返回:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public final void setLayoutSlide(ILayoutSlide value)
```

返回或设置当前幻灯片的布局幻灯片。可读写 [ILayoutSlide](../../com.aspose.slides/ilayoutslide)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |

### reset() {#reset--}
```
public final void reset()
```

重置在 LayoutSlide 上有原型的每个形状的位置、大小和格式。

### getNotesSlideManager() {#getNotesSlideManager--}
```
public final INotesSlideManager getNotesSlideManager()
```

允许访问备注幻灯片，添加和删除它。只读 [INotesSlideManager](../../com.aspose.slides/inotesslidemanager)。

**返回:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)

### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public final IComment[] getSlideComments(ICommentAuthor author)
```

返回特定作者添加的所有幻灯片评论。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | 要查找的评论作者，或为 null 以返回所有评论。 |

**返回:**
com.aspose.slides.IComment[] - [Comment](../../com.aspose.slides/comment) 的数组。

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

在所有可接受的形状的所有段落中合并具有相同格式的运行。