---
title: ISlide
second_title: Aspose.Slides for Android via Java API 参考
description: 表示演示文稿中的一张幻灯片。
type: docs
url: /zh/com.aspose.slides/islide/
---
**所有实现的接口：**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ISlide extends IBaseSlide, IOverrideThemeable
```

表示演示文稿中的一张幻灯片。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 返回幻灯片的 HeaderFooter 管理器。 |
| [getSlideNumber()](#getSlideNumber--) | 返回幻灯片的编号。 |
| [setSlideNumber(int value)](#setSlideNumber-int-) | 返回幻灯片的编号。 |
| [getHidden()](#getHidden--) | 确定在放映期间指定的幻灯片是否隐藏。 |
| [setHidden(boolean value)](#setHidden-boolean-) | 确定在放映期间指定的幻灯片是否隐藏。 |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | 返回自定义缩放的图像对象。 |
| [getImage()](#getImage--) | 返回缩略图 Image 对象（实际大小的 20%）。 |
| [getImage(Size imageSize)](#getImage-com.aspose.slides.android.Size-) | 返回具有指定尺寸的图像对象。 |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | 返回具有指定参数的缩略图 tiff 位图对象。 |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | 返回缩略图 Bitmap 对象。 |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | 返回自定义缩放的缩略图 Bitmap 对象。 |
| [getImage(IRenderingOptions options, Size imageSize)](#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | 返回具有指定尺寸的缩略图 Bitmap 对象。 |
| [getLayoutSlide()](#getLayoutSlide--) | 返回或设置当前幻灯片的布局幻灯片。 |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | 返回或设置当前幻灯片的布局幻灯片。 |
| [getNotesSlideManager()](#getNotesSlideManager--) | 允许访问备注幻灯片，添加和删除它。 |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | 返回特定作者添加的所有幻灯片评论。 |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | 将幻灯片内容保存为 SVG 文件。 |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | 将幻灯片内容保存为 SVG 文件。 |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | 将幻灯片内容保存为 EMF 文件。 |
| [remove()](#remove--) | 从演示文稿中移除幻灯片。 |
| [reset()](#reset--) | 重置在 LayoutSlide 上具有原型的每个形状的位置、大小和格式。 |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ISlideHeaderFooterManager getHeaderFooterManager()
```

返回幻灯片的 HeaderFooter 管理器。只读 [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)。

**返回：**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)

### getSlideNumber() {#getSlideNumber--}
```
public abstract int getSlideNumber()
```

返回幻灯片的编号。[IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) 集合中幻灯片的索引始终等于 SlideNumber - 1。可读写 int。

**返回：**
int

### setSlideNumber(int value) {#setSlideNumber-int-}
```
public abstract void setSlideNumber(int value)
```

返回幻灯片的编号。[IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) 集合中幻灯片的索引始终等于 SlideNumber - 1。可读写 int。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

确定在放映期间指定的幻灯片是否隐藏。可读写 boolean。

**返回：**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

确定在放映期间指定的幻灯片是否隐藏。可读写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```

返回自定义缩放的图像对象。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| scaleX | float | 在 x 轴方向上缩放此 Thumbnail 的值。 |
| scaleY | float | 在 y 轴方向上缩放此 Thumbnail 的值。 |

**返回：**
[IImage](../../com.aspose.slides/iimage) - Image object android.graphics.Bitmap

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

返回缩略图 Image 对象（实际大小的 20%）。

**返回：**
[IImage](../../com.aspose.slides/iimage) - Image object android.graphics.Bitmap

### getImage(Size imageSize) {#getImage-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(Size imageSize)
```

返回具有指定尺寸的图像对象。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageSize | [Size](../../com.aspose.slides.android/size) | 要创建的图像的大小。 |

**返回：**
[IImage](../../com.aspose.slides/iimage) - Bitmap object.

### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public abstract IImage getImage(ITiffOptions options)
```

返回具有指定参数的缩略图 tiff 位图对象。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tiff 选项。 |

**返回：**
[IImage](../../com.aspose.slides/iimage) - Image object.

### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage getImage(IRenderingOptions options)
```

返回缩略图 Bitmap 对象。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 渲染选项。 |

**返回：**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.

### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

返回自定义缩放的缩略图 Bitmap 对象。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 渲染选项。 |
| scaleX | float | 在 x 轴方向上缩放此 Thumbnail 的值。 |
| scaleY | float | 在 y 轴方向上缩放此 Thumbnail 的值。 |

**返回：**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.

### getImage(IRenderingOptions options, Size imageSize) {#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(IRenderingOptions options, Size imageSize)
```

返回具有指定尺寸的缩略图 Bitmap 对象。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 渲染选项。 |
| imageSize | [Size](../../com.aspose.slides.android/size) | 要创建的图像的大小。 |

**返回：**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.

### getLayoutSlide() {#getLayoutSlide--}
```
public abstract ILayoutSlide getLayoutSlide()
```

返回或设置当前幻灯片的布局幻灯片。可读写 [ILayoutSlide](../../com.aspose.slides/ilayoutslide)。

**返回：**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public abstract void setLayoutSlide(ILayoutSlide value)
```

返回或设置当前幻灯片的布局幻灯片。可读写 [ILayoutSlide](../../com.aspose.slides/ilayoutslide)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |

### getNotesSlideManager() {#getNotesSlideManager--}
```
public abstract INotesSlideManager getNotesSlideManager()
```

允许访问备注幻灯片，添加和删除它。只读 [INotesSlideManager](../../com.aspose.slides/inotesslidemanager)。

**返回：**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)

### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public abstract IComment[] getSlideComments(ICommentAuthor author)
```

返回特定作者添加的所有幻灯片评论。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | 要查找的评论作者，或 null 以返回所有评论。 |

**返回：**
com.aspose.slides.IComment[] - Array of [IComment](../../com.aspose.slides/icomment).

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

将幻灯片内容保存为 SVG 文件。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 目标流 |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

将幻灯片内容保存为 SVG 文件。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 目标流 |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG 生成选项 |

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```

将幻灯片内容保存为 EMF 文件。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 目标流 |

### remove() {#remove--}
```
public abstract void remove()
```

从演示文稿中移除幻灯片。

### reset() {#reset--}
```
public abstract void reset()
```

重置在 LayoutSlide 上具有原型的每个形状的位置、大小和格式。