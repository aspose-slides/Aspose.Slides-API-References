---
title: Slide
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Bir sunumdaki slaytı temsil eder.
type: docs
url: /tr/com.aspose.slides/slide/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Tüm Gerçekleştirilen Arabirimler:**
[com.aspose.slides.ISlide](../../com.aspose.slides/islide)
```
public final class Slide extends BaseSlide implements ISlide
```

Bir sunumdaki slaytı temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Slaytın HeaderFooter yöneticisini döndürür. |
| [getThemeManager()](#getThemeManager--) | Geçersiz kılan tema yöneticisini döndürür. |
| [getSlideNumber()](#getSlideNumber--) | Slayt numarasını döndürür. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Slayt numarasını döndürür. |
| [getHidden()](#getHidden--) | Belirtilen slaytın slayt gösterisi sırasında gizli olup olmadığını belirler. |
| [setHidden(boolean value)](#setHidden-boolean-) | Belirtilen slaytın slayt gösterisi sırasında gizli olup olmadığını belirler. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Özelleştirilmiş ölçekleme ile bir Thumbnail Image nesnesini döndürür. |
| [getImage()](#getImage--) | Gerçek boyutun %20'si kadar bir Thumbnail Image nesnesini döndürür. |
| [getImage(Size imageSize)](#getImage-com.aspose.slides.android.Size-) | Belirtilen boyutta bir Thumbnail Image nesnesini döndürür. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Belirtilen parametrelerle bir Thumbnail tiff görüntü nesnesini döndürür. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Bir Thumbnail Image nesnesini döndürür. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Özelleştirilmiş ölçekleme ile bir Thumbnail Image nesnesini döndürür. |
| [getImage(IRenderingOptions options, Size imageSize)](#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Belirtilen boyutta bir Thumbnail Image nesnesini döndürür. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Slayt içeriğini bir SVG dosyası olarak kaydeder. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Slayt içeriğini bir SVG dosyası olarak kaydeder. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Slayt içeriğini bir EMF dosyası olarak kaydeder. |
| [remove()](#remove--) | Slaytı sunumdan kaldırır. |
| [getLayoutSlide()](#getLayoutSlide--) | Geçerli slayt için düzen slaytını döndürür veya ayarlar. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Geçerli slayt için düzen slaytını döndürür veya ayarlar. |
| [reset()](#reset--) | LayoutSlide üzerindeki prototipi olan her şeklin konumunu, boyutunu ve biçimlendirmesini sıfırlar. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Not slaytına erişim, ekleme ve kaldırma sağlar. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Belirli bir yazar tarafından eklenen tüm slayt yorumlarını döndürür. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Tüm kabul edilebilir şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip koşulları birleştirir. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ISlideHeaderFooterManager getHeaderFooterManager()
```

Slaytın HeaderFooter yöneticisini döndürür. Salt okunur [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Döndürür:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Geçersiz kılan tema yöneticisini döndürür. Salt okunur [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Döndürür:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)

### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```

Slayt numarasını döndürür. [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) koleksiyonundaki slayt indeksi, her zaman SlideNumber - Presentation.FirstSlideNumber değerine eşittir. Okunabilir/yazılabilir int.

**Döndürür:**
int

### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```

Slayt numarasını döndürür. [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) koleksiyonundaki slayt indeksi, her zaman SlideNumber - Presentation.FirstSlideNumber değerine eşittir. Okunabilir/yazılabilir int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

Belirtilen slaytın slayt gösterisi sırasında gizli olup olmadığını belirler. Okunabilir/yazılabilir boolean.

**Döndürür:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Belirtilen slaytın slayt gösterisi sırasında gizli olup olmadığını belirler. Okunabilir/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir. Okunabilir/yazılabilir boolean.

**Döndürür:**
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir. Okunabilir/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

Özelleştirilmiş ölçekleme ile bir Thumbnail Image nesnesini döndürür.

--------------------

> ```
> The following example shows how to generate thumbnails from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("ThumbnailFromSlide.pptx");
>  try {
>      // İlk slayta eriş
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Tam ölçekli bir görüntü oluştur
>      IImage bmp = sld.getImage(1f, 1f);
>      // Görüntüyü JPEG formatında diske kaydet
>      bmp.save("Thumbnail_out.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to converting slides to bitmap and saving the images in PNG.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Sunumdaki ilk slaytı bir Bitmap nesnesine dönüştürür
>      IImage bmp = pres.getSlides().get_Item(0).getImage();
>      // Görüntüyü PNG formatında kaydeder
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
>          // Tam ölçekli bir görüntü oluştur
>          IImage bmp = sld.getImage(1f, 1f);
>          // Görüntüyü JPEG formatında diske kaydet
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
>      // Boyutları tanımla
>      int desiredX = 1200;
>      int desiredY = 800;
>      // X ve Y'nin ölçekli değerlerini al
>      float ScaleX = (float)(1.0 / pres.getSlideSize().getSize().getWidth()) * desiredX;
>      float ScaleY = (float)(1.0 / pres.getSlideSize().getSize().getHeight()) * desiredY;
>      for (ISlide sld : pres.getSlides())
>      {
>          // Tam ölçekli bir görüntü oluştur
>          IImage bmp = sld.getImage(ScaleX, ScaleY);
>          // Görüntüyü JPEG formatında diske kaydet
>          bmp.save("Slide.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| scaleX | float | Bu Thumbnail'ı x ekseni yönünde ölçeklemek için kullanılacak değer. |
| scaleY | float | Bu Thumbnail'ı y ekseni yönünde ölçeklemek için kullanılacak değer. |

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - IImage object.

### getImage() {#getImage--}
```
public final IImage getImage()
```

Gerçek boyutun %20'si kadar bir Thumbnail Image nesnesini döndürür.

**Döndürür:**
[IImage](../../com.aspose.slides/iimage)

### getImage(Size imageSize) {#getImage-com.aspose.slides.android.Size-}
```
public final IImage getImage(Size imageSize)
```

Belirtilen boyutta bir Thumbnail Image nesnesini döndürür.

--------------------

> ```
> The following example shows how to converting slides to images with custom sizes using C#.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Sunumdaki ilk slaytı belirtilen boyutta bir Bitmap'e dönüştürür
>      IImage bmp = pres.getSlides().get_Item(0).getImage(new com.aspose.slides.android.Size(1820, 1040));
>      // Görüntüyü JPEG formatında kaydeder
>      bmp.save("Slide_0.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageSize | [Size](../../com.aspose.slides.android/size) | Oluşturulacak görüntünün boyutu. |

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Image object.

### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public final IImage getImage(ITiffOptions options)
```

Belirtilen parametrelerle bir Thumbnail tiff görüntü nesnesini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tiff seçenekleri. |

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Image object.

### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public final IImage getImage(IRenderingOptions options)
```

Bir Thumbnail Image nesnesini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Render seçenekleri. |

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Image object.

### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

Özelleştirilmiş ölçekleme ile bir Thumbnail Image nesnesini döndürür.

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
>      // Converts the first slide of the presentation to a android.graphics.Bitmap object
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
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Render seçenekleri. |
| scaleX | float | Bu Thumbnail'ı x ekseni yönünde ölçeklemek için kullanılacak değer. |
| scaleY | float | Bu Thumbnail'ı y ekseni yönünde ölçeklemek için kullanılacak değer. |

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.

### getImage(IRenderingOptions options, Size imageSize) {#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public final IImage getImage(IRenderingOptions options, Size imageSize)
```

Belirtilen boyutta bir Thumbnail Image nesnesini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Render seçenekleri. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Oluşturulacak görüntünün boyutu. |

**Döndürür:**
[IImage](../../com.aspose.slides/iimage) - Image object.

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

Geçerli slayt için düzen slaytını döndürür veya ayarlar. Okunabilir/yazılabilir [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Döndürür:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public final void setLayoutSlide(ILayoutSlide value)
```

Geçerli slayt için düzen slaytını döndürür veya ayarlar. Okunabilir/yazılabilir [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |

### reset() {#reset--}
```
public final void reset()
```

LayoutSlide üzerindeki prototipi olan her şeklin konumunu, boyutunu ve biçimlendirmesini sıfırlar.

### getNotesSlideManager() {#getNotesSlideManager--}
```
public final INotesSlideManager getNotesSlideManager()
```

Not slaytına erişim, ekleme ve kaldırma sağlar. Salt okunur [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Döndürür:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)

### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public final IComment[] getSlideComments(ICommentAuthor author)
```

Belirli bir yazar tarafından eklenen tüm slayt yorumlarını döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Bulunacak yorumların yazarı veya tüm yorumları döndürmek için null. |

**Döndürür:**
com.aspose.slides.IComment[] - Array of [Comment](../../com.aspose.slides/comment).

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

Tüm kabul edilebilir şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip koşulları birleştirir.