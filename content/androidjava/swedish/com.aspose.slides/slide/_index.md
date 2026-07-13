---
title: Slide
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en bild i en presentation.
type: docs
url: /sv/com.aspose.slides/slide/
---
**Arv:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Alla implementerade gränssnitt:**
[com.aspose.slides.ISlide](../../com.aspose.slides/islide)
```
public final class Slide extends BaseSlide implements ISlide
```

Representerar en bild i en presentation.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Returnerar HeaderFooter-hanteraren för bilden. |
| [getThemeManager()](#getThemeManager--) | Returnerar den åsidosättande temahanteraren. |
| [getSlideNumber()](#getSlideNumber--) | Returnerar bildens nummer. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Returnerar bildens nummer. |
| [getHidden()](#getHidden--) | Avgör om den angivna bilden är dold under ett bildspel. |
| [setHidden(boolean value)](#setHidden-boolean-) | Avgör om den angivna bilden är dold under ett bildspel. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Anger om former på huvudinnehållsbilden ska visas på bilder eller inte. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Anger om former på huvudinnehållsbilden ska visas på bilder eller inte. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Returnerar ett Thumbnail-bildobjekt med anpassad skalning. |
| [getImage()](#getImage--) | Returnerar ett Thumbnail-bildobjekt (20 % av verklig storlek). |
| [getImage(Size imageSize)](#getImage-com.aspose.slides.android.Size-) | Returnerar ett Thumbnail-bildobjekt med angiven storlek. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Returnerar ett Thumbnail-tiff-bildobjekt med angivna parametrar. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Returnerar ett Thumbnail-bildobjekt. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Returnerar ett Thumbnail-bildobjekt med anpassad skalning. |
| [getImage(IRenderingOptions options, Size imageSize)](#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Returnerar ett Thumbnail-bildobjekt med angiven storlek. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Sparar bildens innehåll som en SVG-fil. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Sparar bildens innehåll som en SVG-fil. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Sparar bildens innehåll som en EMF-fil. |
| [remove()](#remove--) | Tar bort bilden från presentationen. |
| [getLayoutSlide()](#getLayoutSlide--) | Returnerar eller anger layout-bilden för den aktuella bilden. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Returnerar eller anger layout-bilden för den aktuella bilden. |
| [reset()](#reset--) | Återställer position, storlek och formatering för varje form som har en prototyp på LayoutSlide. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Tillåter åtkomst till noteringsbilden, samt att lägga till och ta bort den. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Returnerar alla bildkommentarer som lagts till av en specifik författare. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Sammanfogar körningar med samma formatering i alla stycken i alla accepterade former. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ISlideHeaderFooterManager getHeaderFooterManager()
```

Returnerar HeaderFooter-hanteraren för bilden. Skrivskyddad [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Returnerar:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Returnerar den åsidosättande temahanteraren. Skrivskyddad [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Returnerar:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)

### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```

Returnerar bildens nummer. Index för bilden i [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides)-samlingen är alltid lika med SlideNumber - Presentation.FirstSlideNumber. Läs/skriv int.

**Returnerar:**
int

### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```

Returnerar bildens nummer. Index för bilden i [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides)-samlingen är alltid lika med SlideNumber - Presentation.FirstSlideNumber. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

Avgör om den angivna bilden är dold under ett bildspel. Läs/skriv boolean.

**Returnerar:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Avgör om den angivna bilden är dold under ett bildspel. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Anger om former på huvudinnehållsbilden ska visas på bilder eller inte. Läs/skriv boolean.

**Returnerar:**
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Anger om former på huvudinnehållsbilden ska visas på bilder eller inte. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

Returnerar ett Thumbnail-bildobjekt med anpassad skalning.

--------------------

> ```
> The following example shows how to generate thumbnails from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("ThumbnailFromSlide.pptx");
>  try {
>      // Åtkomst till den första bilden
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Skapa en fullskalig bild
>      IImage bmp = sld.getImage(1f, 1f);
>      // Spara bilden till disk i JPEG-format
>      bmp.save("Thumbnail_out.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to converting slides to bitmap and saving the images in PNG.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Konverterar den första bilden i presentationen till ett Bitmap-objekt
>      IImage bmp = pres.getSlides().get_Item(0).getImage();
>      // Sparar bilden i PNG-format
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
>          // Skapa en fullskalig bild
>          IImage bmp = sld.getImage(1f, 1f);
>          // Spara bilden till disk i JPEG-format
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
>      // Definiera dimensioner
>      int desiredX = 1200;
>      int desiredY = 800;
>      // Hämta skalade värden för X och Y
>      float ScaleX = (float)(1.0 / pres.getSlideSize().getSize().getWidth()) * desiredX;
>      float ScaleY = (float)(1.0 / pres.getSlideSize().getSize().getHeight()) * desiredY;
>      for (ISlide sld : pres.getSlides())
>      {
>          // Skapa en fullskalig bild
>          IImage bmp = sld.getImage(ScaleX, ScaleY);
>          // Spara bilden till disk i JPEG-format
>          bmp.save("Slide.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scaleX | float | Värdet som denna Thumbnail ska skalas med längs x-axeln. |
| scaleY | float | Värdet som denna Thumbnail ska skalas med längs y-axeln. |

**Returnerar:**
[IImage](../../com.aspose.slides/iimage) - IImage-objekt.

### getImage() {#getImage--}
```
public final IImage getImage()
```

Returnerar ett Thumbnail-bildobjekt (20 % av verklig storlek).

**Returnerar:**
[IImage](../../com.aspose.slides/iimage)

### getImage(Size imageSize) {#getImage-com.aspose.slides.android.Size-}
```
public final IImage getImage(Size imageSize)
```

Returnerar ett Thumbnail-bildobjekt med angiven storlek.

--------------------

> ```
> The following example shows how to converting slides to images with custom sizes using C#.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Konverterar den första bilden i presentationen till en Bitmap med angiven storlek
>      IImage bmp = pres.getSlides().get_Item(0).getImage(new com.aspose.slides.android.Size(1820, 1040));
>      // Sparar bilden i JPEG-format
>      bmp.save("Slide_0.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageSize | [Size](../../com.aspose.slides.android/size) | Storleken på bilden som ska skapas. |

**Returnerar:**
[IImage](../../com.aspose.slides/iimage) - Image-objekt.

### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public final IImage getImage(ITiffOptions options)
```

Returnerar ett Thumbnail-tiff-bildobjekt med angivna parametrar.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tiff-alternativ. |

**Returnerar:**
[IImage](../../com.aspose.slides/iimage) - Image-objekt.

### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public final IImage getImage(IRenderingOptions options)
```

Returnerar ett Thumbnail-bildobjekt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderingsalternativ. |

**Returnerar:**
[IImage](../../com.aspose.slides/iimage) - Image-objekt.

### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

Returnerar ett Thumbnail-bildobjekt med anpassad skalning.

--------------------

> ```
> The following example shows how to converting slides With notes and comments to Images.
>  
>  Presentation pres = new Presentation("PresentationNotesComments.pptx");
>  try {
>      // Skapa renderingsalternativen
>      IRenderingOptions options = new RenderingOptions();
>      // Skapa alternativ för layout av anteckningar och kommentarer
>      NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
>      // Ställer in positionen för anteckningarna på sidan
>      notesCommentsLayouting.setNotesPosition(NotesPositions.BottomTruncated);
>      // Ställer in positionen för kommentarerna på sidan
>      notesCommentsLayouting.setCommentsPosition(CommentsPositions.Right);
>      // Ställer in bredden på kommentarsutmatningsområdet
>      notesCommentsLayouting.setCommentsAreaWidth(500);
>      // Ställer in färgen för kommentarsområdet
>      notesCommentsLayouting.setCommentsAreaColor(Color.WHITE);
>      // Ställ in layoutalternativ för rendering
>      options.setSlidesLayoutOptions(notesCommentsLayouting);
>      // Konverterar den första bilden i presentationen till ett android.graphics.Bitmap-objekt
>      IImage image = pres.getSlides().get_Item(0).getImage(options, 2f, 2f);
>      // Sparar bilden i GIF-format
>      image.save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderingsalternativ. |
| scaleX | float | Värdet som denna Thumbnail ska skalas med längs x-axeln. |
| scaleY | float | Värdet som denna Thumbnail ska skalas med längs y-axeln. |

**Returnerar:**
[IImage](../../com.aspose.slides/iimage) - Bitmap-objekt.

### getImage(IRenderingOptions options, Size imageSize) {#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public final IImage getImage(IRenderingOptions options, Size imageSize)
```

Returnerar ett Thumbnail-bildobjekt med angiven storlek.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderingsalternativ. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Storleken på bilden som ska skapas. |

**Returnerar:**
[IImage](../../com.aspose.slides/iimage) - Image-objekt.

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

Sparar bildens innehåll som en SVG-fil.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.svg");
>      {
>          // Sparar den första bilden som en SVG-fil
>          pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Måldataström |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Sparar bildens innehåll som en SVG-fil.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file with options.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide1.svg");
>      SVGOptions options = new SVGOptions();
>      options.setVectorizeText(true);
>      // Sparar den första bilden som en SVG-fil
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Måldataström |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG-genereringsalternativ |

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

Sparar bildens innehåll som en EMF-fil.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into a metafile.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.emf");
>      {
>          // Sparar den första bilden som en metafil
>          pres.getSlides().get_Item(0).writeAsEmf(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Måldataström |

### remove() {#remove--}
```
public final void remove()
```

Tar bort bilden från presentationen.

### getLayoutSlide() {#getLayoutSlide--}
```
public final ILayoutSlide getLayoutSlide()
```

Returnerar eller anger layout-bilden för den aktuella bilden. Läs/skriv [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Returnerar:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public final void setLayoutSlide(ILayoutSlide value)
```

Returnerar eller anger layout-bilden för den aktuella bilden. Läs/skriv [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |

### reset() {#reset--}
```
public final void reset()
```

Återställer position, storlek och formatering för varje form som har en prototyp på LayoutSlide.

### getNotesSlideManager() {#getNotesSlideManager--}
```
public final INotesSlideManager getNotesSlideManager()
```

Tillåter åtkomst till noteringsbilden, samt att lägga till och ta bort den. Skrivskyddad [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Returnerar:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)

### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public final IComment[] getSlideComments(ICommentAuthor author)
```

Returnerar alla bildkommentarer som lagts till av en specifik författare.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Författaren till kommentarerna som ska hittas eller null för att returnera alla kommentarer. |

**Returnerar:**
com.aspose.slides.IComment[] - Array av [Comment](../../com.aspose.slides/comment).

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

Sammanfogar körningar med samma formatering i alla stycken i alla accepterade former.