---
title: Slide
second_title: Aspose.Slides for Java API Referansı
description: Bir sunumda slaytı temsil eder.
type: docs
url: /tr/com.aspose.slides/slide/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ISlide](../../com.aspose.slides/islide)
```
public final class Slide extends BaseSlide implements ISlide
```

Bir sunumda slaytı temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Slaytın HeaderFooter yöneticisini döndürür. |
| [getThemeManager()](#getThemeManager--) | Üstüne yazılan tema yöneticisini döndürür. |
| [getSlideNumber()](#getSlideNumber--) | Slayt numarasını döndürür. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Slayt numarasını döndürür. |
| [getHidden()](#getHidden--) | Belirtilen slaydın slayt gösterisi sırasında gizli olup olmadığını belirler. |
| [setHidden(boolean value)](#setHidden-boolean-) | Belirtilen slaydın slayt gösterisi sırasında gizli olup olmadığını belirler. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirler. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirler. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Özel ölçekleme ile bir Thumbnail Image nesnesi döndürür. |
| [getImage()](#getImage--) | Gerçek boyutun %20'si kadar bir Thumbnail Image nesnesi döndürür. |
| [getImage(Dimension imageSize)](#getImage-java.awt.Dimension-) | Belirtilen boyutta bir Thumbnail Image nesnesi döndürür. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Belirtilen parametrelerle bir Thumbnail tiff görüntü nesnesi döndürür. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Bir Thumbnail Image nesnesi döndürür. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Özel ölçekleme ile bir Thumbnail Image nesnesi döndürür. |
| [getImage(IRenderingOptions options, Dimension imageSize)](#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Belirtilen boyutta bir Thumbnail Image nesnesi döndürür. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Slayt içeriğini bir SVG dosyası olarak kaydeder. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Slayt içeriğini bir SVG dosyası olarak kaydeder. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Slayt içeriğini bir EMF dosyası olarak kaydeder. |
| [remove()](#remove--) | Slaytı sunumdan kaldırır. |
| [getLayoutSlide()](#getLayoutSlide--) | Geçerli slayt için yerleşim slaydını döndürür veya ayarlar. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Geçerli slayt için yerleşim slaydını döndürür veya ayarlar. |
| [reset()](#reset--) | LayoutSlide üzerinde prototipi olan her şeklin konumunu, boyutunu ve biçimlendirmesini sıfırlar. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Not slaytına erişime izin verir, ekler ve kaldırır. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Belirli yazar tarafından eklenen tüm slayt yorumlarını döndürür. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Tüm uygun şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip run'ları birleştirir. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ISlideHeaderFooterManager getHeaderFooterManager()
```

Slaytın HeaderFooter yöneticisini döndürür. Yalnızca okuma [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Döndürür:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Üstüne yazılan tema yöneticisini döndürür. Yalnızca okuma [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Döndürür:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```

Slayt numarasını döndürür. [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) koleksiyonundaki slayt indeksi her zaman SlideNumber - Presentation.FirstSlideNumber değerine eşittir. Okunabilir/yazılabilir int.

**Döndürür:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```

Slayt numarasını döndürür. [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) koleksiyonundaki slayt indeksi her zaman SlideNumber - Presentation.FirstSlideNumber değerine eşittir. Okunabilir/yazılabilir int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

Belirtilen slaydın slayt gösterisi sırasında gizli olup olmadığını belirler. Okunabilir/yazılabilir boolean.

**Döndürür:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Belirtilen slaydın slayt gösterisi sırasında gizli olup olmadığını belirler. Okunabilir/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirler. Okunabilir/yazılabilir boolean.

**Döndürür:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirler. Okunabilir/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

Özel ölçekleme ile bir Thumbnail Image nesnesi döndürür.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| scaleX | float | X ekseninde bu Thumbnail'in ölçekleme değeri. |
| scaleY | float | Y ekseninde bu Thumbnail'in ölçekleme değeri. |

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - IImage nesnesi.
### getImage() {#getImage--}
```
public final IImage getImage()
```

Gerçek boyutun %20'si kadar bir Thumbnail Image nesnesi döndürür.

**Döndürür:**
[IImage](../../com.aspose.slides/iimage)
### getImage(Dimension imageSize) {#getImage-java.awt.Dimension-}
```
public final IImage getImage(Dimension imageSize)
```

Belirtilen boyutta bir Thumbnail Image nesnesi döndürür.

--------------------

> ```
> The following example shows how to converting slides to images with custom sizes using C#.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Converts the first slide in the presentation to a Bitmap with the specified size
>      IImage bmp = pres.getSlides().get_Item(0).getImage(new Dimension(1820, 1040));
>      // Saves the image in the JPEG format
>      bmp.save("Slide_0.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageSize | java.awt.Dimension | Oluşturulacak görüntünün boyutu. |

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Image nesnesi.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public final IImage getImage(ITiffOptions options)
```

Belirtilen parametrelerle bir Thumbnail tiff görüntü nesnesi döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tiff seçenekleri. |

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Image nesnesi.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public final IImage getImage(IRenderingOptions options)
```

Bir Thumbnail Image nesnesi döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering seçenekleri. |

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Image nesnesi.
### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

Özel ölçekleme ile bir Thumbnail Image nesnesi döndürür.

--------------------

> ```
> The following example shows how to converting slides With notes and comments to Images.
>  
>  Presentation pres = new Presentation("PresentationNotesComments.pptx");
>  try {
>      // Create the rendering options
>      IRenderingOptions options = new RenderingOptions();
>      // Create notes and comments layouting options
>      NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
>      // Sets the position of the notes on the page
>      notesCommentsLayouting.setNotesPosition(NotesPositions.BottomTruncated);
>      // Sets the position of the comments on the page
>      notesCommentsLayouting.setCommentsPosition(CommentsPositions.Right);
>      // Sets the width of the comment output area
>      notesCommentsLayouting.setCommentsAreaWidth(500);
>      // Sets the color for the comments area
>      notesCommentsLayouting.setCommentsAreaColor(Color.WHITE);
>      // Set layout options for rendering
>      options.setSlidesLayoutOptions(notesCommentsLayouting);
>      // Converts the first slide of the presentation to a BufferedImage object
>      IImage image = pres.getSlides().get_Item(0).getImage(options, 2f, 2f);
>      // Saves the image in the GIF format
>      image.save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering seçenekleri. |
| scaleX | float | X ekseninde bu Thumbnail'in ölçekleme değeri. |
| scaleY | float | Y ekseninde bu Thumbnail'in ölçekleme değeri. |

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Bitmap nesneleri.
### getImage(IRenderingOptions options, Dimension imageSize) {#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public final IImage getImage(IRenderingOptions options, Dimension imageSize)
```

Belirtilen boyutta bir Thumbnail Image nesnesi döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering seçenekleri. |
| imageSize | java.awt.Dimension | Oluşturulacak görüntünün boyutu. |

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Image nesnesi.
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

Slayt içeriğini bir SVG dosyası olarak kaydeder.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.svg");
>      {
>          // İlk slaytı bir SVG dosyası olarak kaydeder
>          pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Hedef akış |
### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Slayt içeriğini bir SVG dosyası olarak kaydeder.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file with options.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide1.svg");
>      SVGOptions options = new SVGOptions();
>      options.setVectorizeText(true);
>      // İlk slaytı bir SVG dosyası olarak kaydeder
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Hedef akış |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG oluşturma seçenekleri |
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

Slayt içeriğini bir EMF dosyası olarak kaydeder.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into a metafile.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.emf");
>      {
>          // İlk slaytı bir metafile olarak kaydeder
>          pres.getSlides().get_Item(0).writeAsEmf(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Hedef akış |
### remove() {#remove--}
```
public final void remove()
```

Slaytı sunumdan kaldırır.
### getLayoutSlide() {#getLayoutSlide--}
```
public final ILayoutSlide getLayoutSlide()
```

Geçerli slayt için yerleşim slaydını döndürür veya ayarlar. Okunabilir/yazılabilir [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Döndürür:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public final void setLayoutSlide(ILayoutSlide value)
```

Geçerli slayt için yerleşim slaydını döndürür veya ayarlar. Okunabilir/yazılabilir [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |
### reset() {#reset--}
```
public final void reset()
```

LayoutSlide üzerinde prototipi olan her şeklin konumunu, boyutunu ve biçimlendirmesini sıfırlar.
### getNotesSlideManager() {#getNotesSlideManager--}
```
public final INotesSlideManager getNotesSlideManager()
```

Not slaytına erişime izin verir, ekler ve kaldırır. Yalnızca okuma [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Döndürür:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public final IComment[] getSlideComments(ICommentAuthor author)
```

Belirli yazar tarafından eklenen tüm slayt yorumlarını döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Bulunacak yorumların yazarı veya tüm yorumları döndürmek için null. |

**Döndürür:**
com.aspose.slides.IComment[] - [Comment](../../com.aspose.slides/comment) dizisi.
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

Tüm uygun şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip run'ları birleştirir.