---
title: Slide
second_title: Aspose.Slides for Java API 參考文件
description: 表示簡報中的投影片。
type: docs
url: /zh-hant/com.aspose.slides/slide/
---
**繼承：**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**全部已實作的介面：**
[com.aspose.slides.ISlide](../../com.aspose.slides/islide)
```
public final class Slide extends BaseSlide implements ISlide
```

表示簡報中的投影片。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 傳回投影片的 HeaderFooter 管理員。 |
| [getThemeManager()](#getThemeManager--) | 傳回覆寫的佈景主題管理員。 |
| [getSlideNumber()](#getSlideNumber--) | 傳回投影片的編號。 |
| [setSlideNumber(int value)](#setSlideNumber-int-) | 傳回投影片的編號。 |
| [getHidden()](#getHidden--) | 判斷指定的投影片在投影片放映期間是否隱藏。 |
| [setHidden(boolean value)](#setHidden-boolean-) | 判斷指定的投影片在投影片放映期間是否隱藏。 |
| [getShowMasterShapes()](#getShowMasterShapes--) | 指定母片上的圖形是否應顯示於投影片上。 |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | 指定母片上的圖形是否應顯示於投影片上。 |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | 傳回具有自訂縮放的縮圖圖像物件。 |
| [getImage()](#getImage--) | 傳回縮圖圖像物件（實際大小的 20%）。 |
| [getImage(Dimension imageSize)](#getImage-java.awt.Dimension-) | 傳回具有指定尺寸的縮圖圖像物件。 |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | 傳回具有指定參數的縮圖 TIFF 圖像物件。 |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | 傳回縮圖圖像物件。 |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | 傳回具有自訂縮放的縮圖圖像物件。 |
| [getImage(IRenderingOptions options, Dimension imageSize)](#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | 傳回具有指定尺寸的縮圖圖像物件。 |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | 將投影片內容儲存為 SVG 檔案。 |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | 將投影片內容儲存為 SVG 檔案。 |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | 將投影片內容儲存為 EMF 檔案。 |
| [remove()](#remove--) | 從簡報中移除投影片。 |
| [getLayoutSlide()](#getLayoutSlide--) | 傳回或設定目前投影片的版面配置投影片。 |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | 傳回或設定目前投影片的版面配置投影片。 |
| [reset()](#reset--) | 重設在 LayoutSlide 上具有原型的每個圖形的位置、大小與格式設定。 |
| [getNotesSlideManager()](#getNotesSlideManager--) | 允許存取備註投影片，並可新增或移除。 |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | 傳回特定作者新增的所有投影片註解。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 合併所有可接受圖形中所有段落的相同格式文字執行。 |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ISlideHeaderFooterManager getHeaderFooterManager()
```


傳回投影片的 HeaderFooter 管理員。 唯讀 [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)。

**傳回：**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```


傳回覆寫的佈景主題管理員。 唯讀 [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)。

**傳回：**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```


傳回投影片的編號。[Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) 集合中的投影片索引始終等於 SlideNumber - Presentation.FirstSlideNumber。 可讀寫 int。

**傳回：**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```


傳回投影片的編號。[Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) 集合中的投影片索引始終等於 SlideNumber - Presentation.FirstSlideNumber。 可讀寫 int。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getHidden() {#getHidden--}
```
public final boolean getHidden()
```


判斷指定的投影片在投影片放映期間是否隱藏。 可讀寫 boolean。

**傳回：**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```


判斷指定的投影片在投影片放映期間是否隱藏。 可讀寫 boolean。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


指定母片上的圖形是否應顯示於投影片上。 可讀寫 boolean。

**傳回：**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


指定母片上的圖形是否應顯示於投影片上。 可讀寫 boolean。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```


傳回具有自訂縮放的縮圖圖像物件。

--------------------

> ```
> The following example shows how to generate thumbnails from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("ThumbnailFromSlide.pptx");
>  try {
>      // Access the first slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Create a full scale image
>      IImage bmp = sld.getImage(1f, 1f);
>      // Save the image to disk in JPEG format
>      bmp.save("Thumbnail_out.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to converting slides to bitmap and saving the images in PNG.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Converts the first slide in the presentation to a Bitmap object
>      IImage bmp = pres.getSlides().get_Item(0).getImage();
>      // Saves the image in the PNG format
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
>          // Create a full scale image
>          IImage bmp = sld.getImage(1f, 1f);
>          // Save the image to disk in JPEG format
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
>      // Define dimensions
>      int desiredX = 1200;
>      int desiredY = 800;
>      // Get scaled values of X and Y
>      float ScaleX = (float)(1.0 / pres.getSlideSize().getSize().getWidth()) * desiredX;
>      float ScaleY = (float)(1.0 / pres.getSlideSize().getSize().getHeight()) * desiredY;
>      for (ISlide sld : pres.getSlides())
>      {
>          // Create a full scale image
>          IImage bmp = sld.getImage(ScaleX, ScaleY);
>          // Save the image to disk in JPEG format
>          bmp.save("Slide.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| scaleX | float | 在 x 軸方向上縮放此縮圖的值。 |
| scaleY | float | 在 y 軸方向上縮放此縮圖的值。 |

**傳回：**
[IImage](../../com.aspose.slides/iimage) - IImage object.
### getImage() {#getImage--}
```
public final IImage getImage()
```


傳回縮圖圖像物件（實際大小的 20%）。

**傳回：**
[IImage](../../com.aspose.slides/iimage)
### getImage(Dimension imageSize) {#getImage-java.awt.Dimension-}
```
public final IImage getImage(Dimension imageSize)
```


傳回具有指定尺寸的縮圖圖像物件。

--------------------

> ```
> The following example shows how to converting slides to images with custom sizes using C#.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // 將簡報中的第一張投影片轉換為指定尺寸的 Bitmap
>      IImage bmp = pres.getSlides().get_Item(0).getImage(new Dimension(1820, 1040));
>      // 以 JPEG 格式儲存影像
>      bmp.save("Slide_0.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| imageSize | java.awt.Dimension | 要建立的圖像大小。 |

**傳回：**
[IImage](../../com.aspose.slides/iimage) - Image object.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public final IImage getImage(ITiffOptions options)
```


傳回具有指定參數的縮圖 TIFF 圖像物件。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tiff 選項。 |

**傳回：**
[IImage](../../com.aspose.slides/iimage) - Image object.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public final IImage getImage(IRenderingOptions options)
```


傳回縮圖圖像物件。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 呈現選項。 |

**傳回：**
[IImage](../../com.aspose.slides/iimage) - Image object.
### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```


傳回具有自訂縮放的縮圖圖像物件。

--------------------

> ```
> The following example shows how to converting slides With notes and comments to Images.
>  
>  Presentation pres = new Presentation("PresentationNotesComments.pptx");
>  try {
>      // 建立渲染選項
>      IRenderingOptions options = new RenderingOptions();
>      // 建立備註與評論版面配置選項
>      NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
>      // 設定頁面上備註的位置
>      notesCommentsLayouting.setNotesPosition(NotesPositions.BottomTruncated);
>      // 設定頁面上評論的位置
>      notesCommentsLayouting.setCommentsPosition(CommentsPositions.Right);
>      // 設定評論輸出區域的寬度
>      notesCommentsLayouting.setCommentsAreaWidth(500);
>      // 設定評論區域的顏色
>      notesCommentsLayouting.setCommentsAreaColor(Color.WHITE);
>      // 設定渲染的版面配置選項
>      options.setSlidesLayoutOptions(notesCommentsLayouting);
>      // 將簡報的第一張投影片轉換為 BufferedImage 物件
>      IImage image = pres.getSlides().get_Item(0).getImage(options, 2f, 2f);
>      // 以 GIF 格式儲存影像
>      image.save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 呈現選項。 |
| scaleX | float | 在 x 軸方向上縮放此縮圖的值。 |
| scaleY | float | 在 y 軸方向上縮放此縮圖的值。 |

**傳回：**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getImage(IRenderingOptions options, Dimension imageSize) {#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public final IImage getImage(IRenderingOptions options, Dimension imageSize)
```


傳回具有指定尺寸的縮圖圖像物件。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 呈現選項。 |
| imageSize | java.awt.Dimension | 要建立的圖像大小。 |

**傳回：**
[IImage](../../com.aspose.slides/iimage) - Image object.
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```


將投影片內容儲存為 SVG 檔案。

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.svg");
>      {
>          // 將第一張投影片儲存為 SVG 檔案
>          pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 目標串流 |
### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```


將投影片內容儲存為 SVG 檔案。

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file with options.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide1.svg");
>      SVGOptions options = new SVGOptions();
>      options.setVectorizeText(true);
>      // 將第一張投影片儲存為 SVG 檔案
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 目標串流 |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG 產生選項 |
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```


將投影片內容儲存為 EMF 檔案。

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into a metafile.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.emf");
>      {
>          // 將第一張投影片儲存為 metafille
>          pres.getSlides().get_Item(0).writeAsEmf(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 目標串流 |
### remove() {#remove--}
```
public final void remove()
```


從簡報中移除投影片。

### getLayoutSlide() {#getLayoutSlide--}
```
public final ILayoutSlide getLayoutSlide()
```


傳回或設定目前投影片的版面配置投影片。 可讀寫 [ILayoutSlide](../../com.aspose.slides/ilayoutslide)。

**傳回：**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public final void setLayoutSlide(ILayoutSlide value)
```


傳回或設定目前投影片的版面配置投影片。 可讀寫 [ILayoutSlide](../../com.aspose.slides/ilayoutslide)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |
### reset() {#reset--}
```
public final void reset()
```


重設在 LayoutSlide 上具有原型的每個圖形的位置、大小與格式設定。
### getNotesSlideManager() {#getNotesSlideManager--}
```
public final INotesSlideManager getNotesSlideManager()
```


允許存取備註投影片，並可新增或移除。 唯讀 [INotesSlideManager](../../com.aspose.slides/inotesslidemanager)。

**傳回：**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public final IComment[] getSlideComments(ICommentAuthor author)
```


傳回特定作者新增的所有投影片註解。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | 要搜尋的註解作者，若為 null 則傳回所有註解。 |

**傳回：**
com.aspose.slides.IComment[] - Array of [Comment](../../com.aspose.slides/comment).
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```


合併所有可接受圖形中所有段落的相同格式文字執行。