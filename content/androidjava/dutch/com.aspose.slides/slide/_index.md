---
title: Slide
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt een dia in een presentatie.
type: docs
url: /nl/com.aspose.slides/slide/
---
**Overerving:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISlide](../../com.aspose.slides/islide)
```
public final class Slide extends BaseSlide implements ISlide
```

Stelt een dia in een presentatie voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Retourneert HeaderFooter manager van de dia. |
| [getThemeManager()](#getThemeManager--) | Retourneert de overriding theme manager. |
| [getSlideNumber()](#getSlideNumber--) | Retourneert een getal van de dia. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Retourneert een getal van de dia. |
| [getHidden()](#getHidden--) | Bepaalt of de opgegeven dia verborgen is tijdens een diavoorstelling. |
| [setHidden(boolean value)](#setHidden-boolean-) | Bepaalt of de opgegeven dia verborgen is tijdens een diavoorstelling. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Specificeert of vormen op de masterslide al dan niet moeten worden weergegeven op dia's. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Specificeert of vormen op de masterslide al dan niet moeten worden weergegeven op dia's. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Retourneert een Thumbnail Image-object met aangepaste schaal. |
| [getImage()](#getImage--) | Retourneert een Thumbnail Image-object (20 % van de werkelijke grootte). |
| [getImage(Size imageSize)](#getImage-com.aspose.slides.android.Size-) | Retourneert een Thumbnail Image-object met opgegeven grootte. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Retourneert een Thumbnail tiff-afbeeldingsobject met opgegeven parameters. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Retourneert een Thumbnail Image-object. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Retourneert een Thumbnail Image-object met aangepaste schaal. |
| [getImage(IRenderingOptions options, Size imageSize)](#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Retourneert een Thumbnail Image-object met opgegeven grootte. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Slaat de inhoud van de dia op als een SVG-bestand. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Slaat de inhoud van de dia op als een SVG-bestand. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Slaat de inhoud van de dia op als een EMF-bestand. |
| [remove()](#remove--) | Verwijdert dia uit de presentatie. |
| [getLayoutSlide()](#getLayoutSlide--) | Retourneert of stelt de layoutslide in voor de huidige dia. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Retourneert of stelt de layoutslide in voor de huidige dia. |
| [reset()](#reset--) | Reset de positie, grootte en opmaak van elke vorm die een prototype heeft op LayoutSlide. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Staat toe om toegang te krijgen tot notitieslide, deze toe te voegen en te verwijderen. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Retourneert alle dia-opmerkingen toegevoegd door een specifieke auteur. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Voegt runs samen met dezelfde opmaak in alle alinea's in alle aanvaardbare vormen. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ISlideHeaderFooterManager getHeaderFooterManager()
```

Retourneert HeaderFooter manager van de dia. Alleen-lezen [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Retourneert:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Retourneert de overriding theme manager. Alleen-lezen [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Retourneert:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```

Retourneert een getal van de dia. Index van de dia in [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) collectie is altijd gelijk aan SlideNumber - Presentation.FirstSlideNumber. Lezen/Schrijven int.

**Retourneert:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```

Stelt een getal van de dia in. Index van de dia in [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) collectie is altijd gelijk aan SlideNumber - Presentation.FirstSlideNumber. Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

Bepaalt of de opgegeven dia verborgen is tijdens een diavoorstelling. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Bepaalt of de opgegeven dia verborgen is tijdens een diavoorstelling. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Specificeert of vormen op de masterslide al dan niet moeten worden weergegeven op dia's. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Specificeert of vormen op de masterslide al dan niet moeten worden weergegeven op dia's. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

Retourneert een Thumbnail Image-object met aangepaste schaal.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| scaleX | float | De waarde waarmee deze Thumbnail wordt geschaald in de x-richting. |
| scaleY | float | De waarde waarmee deze Thumbnail wordt geschaald in de y-richting. |

**Retourneert:**
[IImage](../../com.aspose.slides/iimage) - IImage-object.
### getImage() {#getImage--}
```
public final IImage getImage()
```

Retourneert een Thumbnail Image-object (20 % van de werkelijke grootte).

**Retourneert:**
[IImage](../../com.aspose.slides/iimage)
### getImage(Size imageSize) {#getImage-com.aspose.slides.android.Size-}
```
public final IImage getImage(Size imageSize)
```

Retourneert een Thumbnail Image-object met opgegeven grootte.

--------------------

> ```
> The following example shows how to converting slides to images with custom sizes using C#.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Converts the first slide in the presentation to a Bitmap with the specified size
>      IImage bmp = pres.getSlides().get_Item(0).getImage(new com.aspose.slides.android.Size(1820, 1040));
>      // Saves the image in the JPEG format
>      bmp.save("Slide_0.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| imageSize | [Size](../../com.aspose.slides.android/size) | Grootte van de afbeelding die moet worden gemaakt. |

**Retourneert:**
[IImage](../../com.aspose.slides/iimage) - Image-object.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public final IImage getImage(ITiffOptions options)
```

Retourneert een Thumbnail tiff-afbeeldingsobject met opgegeven parameters.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tiff-opties. |

**Retourneert:**
[IImage](../../com.aspose.slides/iimage) - Image-object.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public final IImage getImage(IRenderingOptions options)
```

Retourneert een Thumbnail Image-object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderingsopties. |

**Retourneert:**
[IImage](../../com.aspose.slides/iimage) - Image-object.
### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

Retourneert een Thumbnail Image-object met aangepaste schaal.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderingsopties. |
| scaleX | float | De waarde waarmee deze Thumbnail wordt geschaald in de x-richting. |
| scaleY | float | De waarde waarmee deze Thumbnail wordt geschaald in de y-richting. |

**Retourneert:**
[IImage](../../com.aspose.slides/iimage) - Bitmap-objecten.
### getImage(IRenderingOptions options, Size imageSize) {#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public final IImage getImage(IRenderingOptions options, Size imageSize)
```

Retourneert een Thumbnail Image-object met opgegeven grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderingsopties. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Grootte van de afbeelding die moet worden gemaakt. |

**Retourneert:**
[IImage](../../com.aspose.slides/iimage) - Image-object.
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

Slaat de inhoud van de dia op als een SVG-bestand.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.svg");
>      {
>          // Slaat de eerste dia op als een SVG bestand
>          pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Doelstream |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Slaat de inhoud van de dia op als een SVG-bestand.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file with options.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide1.svg");
>      SVGOptions options = new SVGOptions();
>      options.setVectorizeText(true);
>      // Slaat de eerste dia op als een SVG-bestand
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Doelstream |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG-generatie-opties |

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

Slaat de inhoud van de dia op als een EMF-bestand.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into a metafile.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.emf");
>      {
>          // Slaat de eerste dia op als een metafile
>          pres.getSlides().get_Item(0).writeAsEmf(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Doelstream |

### remove() {#remove--}
```
public final void remove()
```

Verwijdert dia uit de presentatie.

### getLayoutSlide() {#getLayoutSlide--}
```
public final ILayoutSlide getLayoutSlide()
```

Retourneert of stelt de layoutslide in voor de huidige dia. Lezen/Schrijven [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Retourneert:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public final void setLayoutSlide(ILayoutSlide value)
```

Retourneert of stelt de layoutslide in voor de huidige dia. Lezen/Schrijven [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |

### reset() {#reset--}
```
public final void reset()
```

Reset de positie, grootte en opmaak van elke vorm die een prototype heeft op LayoutSlide.

### getNotesSlideManager() {#getNotesSlideManager--}
```
public final INotesSlideManager getNotesSlideManager()
```

Staat toe om toegang te krijgen tot notitieslide, deze toe te voegen en te verwijderen. Alleen-lezen [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Retourneert:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public final IComment[] getSlideComments(ICommentAuthor author)
```

Retourneert alle dia-opmerkingen toegevoegd door een specifieke auteur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Auteur van de te vinden opmerkingen of null om alle opmerkingen te retourneren. |

**Retourneert:**
com.aspose.slides.IComment[] - Array van [Comment](../../com.aspose.slides/comment).
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

Voegt runs samen met dezelfde opmaak in alle alinea's in alle aanvaardbare vormen.