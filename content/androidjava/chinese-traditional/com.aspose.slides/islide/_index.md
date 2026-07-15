---
title: ISlide
second_title: Aspose.Slides for Android via Java API 參考
description: 表示簡報中的投影片。
type: docs
url: /zh-hant/com.aspose.slides/islide/
---
**所有已實作的介面：**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ISlide extends IBaseSlide, IOverrideThemeable
```

表示簡報中的投影片。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 傳回投影片的 HeaderFooter 管理器。 |
| [getSlideNumber()](#getSlideNumber--) | 傳回投影片的編號。 |
| [setSlideNumber(int value)](#setSlideNumber-int-) | 傳回投影片的編號。 |
| [getHidden()](#getHidden--) | 判斷指定的投影片在投影片放映期間是否被隱藏。 |
| [setHidden(boolean value)](#setHidden-boolean-) | 判斷指定的投影片在投影片放映期間是否被隱藏。 |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | 傳回具有自訂縮放的影像物件。 |
| [getImage()](#getImage--) | 傳回縮圖影像物件（實際大小的 20%）。 |
| [getImage(Size imageSize)](#getImage-com.aspose.slides.android.Size-) | 傳回具有指定大小的影像物件。 |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | 傳回具有指定參數的縮圖 tiff 位圖物件。 |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | 傳回縮圖 Bitmap 物件。 |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | 傳回具有自訂縮放的縮圖 Bitmap 物件。 |
| [getImage(IRenderingOptions options, Size imageSize)](#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | 傳回具有指定大小的縮圖 Bitmap 物件。 |
| [getLayoutSlide()](#getLayoutSlide--) | 傳回或設定目前投影片的 layout slide。 |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | 傳回或設定目前投影片的 layout slide。 |
| [getNotesSlideManager()](#getNotesSlideManager--) | 允許存取備註投影片，並可新增或移除。 |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | 傳回特定作者所新增的所有投影片註解。 |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | 將投影片內容儲存為 SVG 檔案。 |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | 將投影片內容儲存為 SVG 檔案。 |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | 將投影片內容儲存為 EMF 檔案。 |
| [remove()](#remove--) | 從簡報中移除投影片。 |
| [reset()](#reset--) | 重設在 LayoutSlide 上有原型的每個圖形的位置、大小和格式。 |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ISlideHeaderFooterManager getHeaderFooterManager()
```

傳回投影片的 HeaderFooter 管理器。唯讀 [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)。

**傳回:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)
### getSlideNumber() {#getSlideNumber--}
```
public abstract int getSlideNumber()
```

傳回投影片的編號。[IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) 集合中的投影片索引始終等於 SlideNumber - 1。讀寫 int。

**傳回:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public abstract void setSlideNumber(int value)
```

傳回投影片的編號。[IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) 集合中的投影片索引始終等於 SlideNumber - 1。讀寫 int。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

判斷指定的投影片在投影片放映期間是否被隱藏。讀寫 boolean。

**傳回:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

判斷指定的投影片在投影片放映期間是否被隱藏。讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```

傳回具有自訂縮放的影像物件。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| scaleX | float | 在 x 軸方向上縮放此 Thumbnail 的值。 |
| scaleY | float | 在 y 軸方向上縮放此 Thumbnail 的值。 |

**傳回:**
[IImage](../../com.aspose.slides/iimage) - Image object android.graphics.Bitmap
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

傳回縮圖影像物件（實際大小的 20%）。

**傳回:**
[IImage](../../com.aspose.slides/iimage) - Image object android.graphics.Bitmap
### getImage(Size imageSize) {#getImage-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(Size imageSize)
```

傳回具有指定大小的影像物件。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| imageSize | [Size](../../com.aspose.slides.android/size) | 要建立的影像大小。 |

**傳回:**
[IImage](../../com.aspose.slides/iimage) - Bitmap object.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public abstract IImage getImage(ITiffOptions options)
```

傳回具有指定參數的縮圖 tiff 位圖物件。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tiff 選項。 |

**傳回:**
[IImage](../../com.aspose.slides/iimage) - Image object.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage getImage(IRenderingOptions options)
```

傳回縮圖 Bitmap 物件。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 渲染選項。 |

**傳回:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

傳回具有自訂縮放的縮圖 Bitmap 物件。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 渲染選項。 |
| scaleX | float | 在 x 軸方向上縮放此 Thumbnail 的值。 |
| scaleY | float | 在 y 軸方向上縮放此 Thumbnail 的值。 |

**傳回:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getImage(IRenderingOptions options, Size imageSize) {#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(IRenderingOptions options, Size imageSize)
```

傳回具有指定大小的縮圖 Bitmap 物件。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 渲染選項。 |
| imageSize | [Size](../../com.aspose.slides.android/size) | 要建立的影像大小。 |

**傳回:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getLayoutSlide() {#getLayoutSlide--}
```
public abstract ILayoutSlide getLayoutSlide()
```

傳回或設定目前投影片的 layout slide。讀寫 [ILayoutSlide](../../com.aspose.slides/ilayoutslide)。

**傳回:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public abstract void setLayoutSlide(ILayoutSlide value)
```

傳回或設定目前投影片的 layout slide。讀寫 [ILayoutSlide](../../com.aspose.slides/ilayoutslide)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |
### getNotesSlideManager() {#getNotesSlideManager--}
```
public abstract INotesSlideManager getNotesSlideManager()
```

允許存取 notes slide，並可新增或移除。唯讀 [INotesSlideManager](../../com.aspose.slides/inotesslidemanager)。

**傳回:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public abstract IComment[] getSlideComments(ICommentAuthor author)
```

傳回特定作者所新增的所有投影片註解。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | 要查找的註解作者，若為 null 則返回所有註解。 |

**傳回:**
com.aspose.slides.IComment[] - Array of [IComment](../../com.aspose.slides/icomment).
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

將投影片內容儲存為 SVG 檔案。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 目標串流 |
### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

將投影片內容儲存為 SVG 檔案。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 目標串流 |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG 產生選項 |
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```

將投影片內容儲存為 EMF 檔案。

**參數:**
| 參數 | 類型 | 說明 |
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

重設在 LayoutSlide 上有原型的每個圖形的位置、大小和格式。