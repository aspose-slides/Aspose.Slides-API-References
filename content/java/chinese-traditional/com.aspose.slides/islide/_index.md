---
title: ISlide
second_title: Aspose.Slides for Java API 參考
description: 代表簡報中的投影片。
type: docs
url: /zh-hant/com.aspose.slides/islide/
---
**所有已實作的介面：**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ISlide extends IBaseSlide, IOverrideThemeable
```

代表簡報中的投影片。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 返回投影片的 HeaderFooter 管理器。 |
| [getSlideNumber()](#getSlideNumber--) | 返回投影片的編號。 |
| [setSlideNumber(int value)](#setSlideNumber-int-) | 返回投影片的編號。 |
| [getHidden()](#getHidden--) | 判斷指定的投影片在投影片放映期間是否隱藏。 |
| [setHidden(boolean value)](#setHidden-boolean-) | 判斷指定的投影片在投影片放映期間是否隱藏。 |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | 返回具有自訂縮放的影像物件。 |
| [getImage()](#getImage--) | 返回縮圖影像物件（實際大小的 20%）。 |
| [getImage(Dimension imageSize)](#getImage-java.awt.Dimension-) | 返回具有指定大小的影像物件。 |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | 返回具有指定參數的縮圖 TIFF 位圖物件。 |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | 返回縮圖位圖物件。 |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | 返回具有自訂縮放的縮圖位圖物件。 |
| [getImage(IRenderingOptions options, Dimension imageSize)](#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | 返回具有指定大小的縮圖位圖物件。 |
| [getLayoutSlide()](#getLayoutSlide--) | 返回或設定目前投影片的版面投影片。 |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | 返回或設定目前投影片的版面投影片。 |
| [getNotesSlideManager()](#getNotesSlideManager--) | 允許存取備註投影片，並可新增或移除。 |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | 返回由特定作者新增的所有投影片評論。 |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | 將投影片內容儲存為 SVG 檔案。 |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | 將投影片內容儲存為 SVG 檔案。 |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | 將投影片內容儲存為 EMF 檔案。 |
| [remove()](#remove--) | 從簡報中移除投影片。 |
| [reset()](#reset--) | 重設所有在 LayoutSlide 上有原型的形狀之位置、大小與格式。 |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ISlideHeaderFooterManager getHeaderFooterManager()
```

返回投影片的 HeaderFooter 管理器。唯讀 [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)。

**返回值：**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)

### getSlideNumber() {#getSlideNumber--}
```
public abstract int getSlideNumber()
```

返回投影片的編號。[IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) 集合中的投影片索引總是等於 SlideNumber - 1。可讀寫 int。

**返回值：**
int

### setSlideNumber(int value) {#setSlideNumber-int-}
```
public abstract void setSlideNumber(int value)
```

返回投影片的編號。[IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) 集合中的投影片索引總是等於 SlideNumber - 1。可讀寫 int。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

判斷指定的投影片在投影片放映期間是否隱藏。可讀寫 boolean。

**返回值：**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

判斷指定的投影片在投影片放映期間是否隱藏。可讀寫 boolean。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```

返回具有自訂縮放的影像物件。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| scaleX | float | 用於在 X 軸方向縮放此縮圖的值。 |
| scaleY | float | 用於在 Y 軸方向縮放此縮圖的值。 |

**返回值：**
[IImage](../../com.aspose.slides/iimage) - Image object java.awt.image.BufferedImage

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

返回縮圖影像物件（實際大小的 20%）。

**返回值：**
[IImage](../../com.aspose.slides/iimage) - Image object java.awt.image.BufferedImage

### getImage(Dimension imageSize) {#getImage-java.awt.Dimension-}
```
public abstract IImage getImage(Dimension imageSize)
```

返回具有指定大小的影像物件。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| imageSize | java.awt.Dimension | 要建立的影像之大小。 |

**返回值：**
[IImage](../../com.aspose.slides/iimage) - Bitmap object.

### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public abstract IImage getImage(ITiffOptions options)
```

返回具有指定參數的縮圖 TIFF 位圖物件。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tiff 選項。 |

**返回值：**
[IImage](../../com.aspose.slides/iimage) - Image object.

### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage getImage(IRenderingOptions options)
```

返回縮圖位圖物件。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 渲染選項。 |

**返回值：**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.

### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

返回具有自訂縮放的縮圖位圖物件。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 渲染選項。 |
| scaleX | float | 用於在 X 軸方向縮放此縮圖的值。 |
| scaleY | float | 用於在 Y 軸方向縮放此縮圖的值。 |

**返回值：**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.

### getImage(IRenderingOptions options, Dimension imageSize) {#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage getImage(IRenderingOptions options, Dimension imageSize)
```

返回具有指定大小的縮圖位圖物件。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 渲染選項。 |
| imageSize | java.awt.Dimension | 要建立的影像之大小。 |

**返回值：**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.

### getLayoutSlide() {#getLayoutSlide--}
```
public abstract ILayoutSlide getLayoutSlide()
```

返回或設定目前投影片的版面投影片。可讀寫 [ILayoutSlide](../../com.aspose.slides/ilayoutslide)。

**返回值：**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public abstract void setLayoutSlide(ILayoutSlide value)
```

返回或設定目前投影片的版面投影片。可讀寫 [ILayoutSlide](../../com.aspose.slides/ilayoutslide)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |

### getNotesSlideManager() {#getNotesSlideManager--}
```
public abstract INotesSlideManager getNotesSlideManager()
```

允許存取備註投影片，並可新增或移除。唯讀 [INotesSlideManager](../../com.aspose.slides/inotesslidemanager)。

**返回值：**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)

### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public abstract IComment[] getSlideComments(ICommentAuthor author)
```

返回由特定作者新增的所有投影片評論。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | 要查找的評論作者，若為 null 則返回所有評論。 |

**返回值：**
[IComment](../../com.aspose.slides/icomment) 陣列。

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

將投影片內容儲存為 SVG 檔案。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 目標串流 |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

將投影片內容儲存為 SVG 檔案。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 目標串流 |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG 產生選項 |

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```

將投影片內容儲存為 EMF 檔案。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 目標串流 |

### remove() {#remove--}
```
public abstract void remove()
```

從簡報中移除投影片。

### reset() {#reset--}
```
public abstract void reset()
```

重設所有在 LayoutSlide 上有原型的形狀之位置、大小與格式。