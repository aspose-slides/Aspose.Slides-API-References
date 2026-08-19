---
title: Slide
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een dia in een presentatie voor.
type: docs
url: /nl/com.aspose.slides/slide/
---
**Erfenis:**
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
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Retourneert de HeaderFooter-beheerder van de dia. |
| [getThemeManager()](#getThemeManager--) | Retourneert de overschrijf-thema-beheerder. |
| [getSlideNumber()](#getSlideNumber--) | Retourneert een nummer van de dia. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Retourneert een nummer van de dia. |
| [getHidden()](#getHidden--) | Bepaalt of de opgegeven dia verborgen is tijdens de diavoorstelling. |
| [setHidden(boolean value)](#setHidden-boolean-) | Bepaalt of de opgegeven dia verborgen is tijdens de diavoorstelling. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Geeft aan of vormen op de master-dia getoond moeten worden op dia's of niet. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Geeft aan of vormen op de master-dia getoond moeten worden op dia's of niet. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Retourneert een Thumbnail Image-object met aangepaste schaal. |
| [getImage()](#getImage--) | Retourneert een Thumbnail Image-object (20 % van de werkelijke grootte). |
| [getImage(Dimension imageSize)](#getImage-java.awt.Dimension-) | Retourneert een Thumbnail Image-object met opgegeven grootte. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Retourneert een Thumbnail-tiff-afbeeldingsobject met opgegeven parameters. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Retourneert een Thumbnail Image-object. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Retourneert een Thumbnail Image-object met aangepaste schaal. |
| [getImage(IRenderingOptions options, Dimension imageSize)](#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Retourneert een Thumbnail Image-object met opgegeven grootte. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Slaat de dia-inhoud op als een SVG-bestand. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Slaat de dia-inhoud op als een SVG-bestand. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Slaat de dia-inhoud op als een EMF-bestand. |
| [remove()](#remove--) | Verwijdert dia uit de presentatie. |
| [getLayoutSlide()](#getLayoutSlide--) | Retourneert of stelt de lay-out-dia in voor de huidige dia. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Retourneert of stelt de lay-out-dia in voor de huidige dia. |
| [reset()](#reset--) | Reset de positie, grootte en opmaak van elke vorm die een prototype heeft op LayoutSlide. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Staat toe om de notitiedia te benaderen, toe te voegen en te verwijderen. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Retourneert alle dia-commentaren die door een specifieke auteur zijn toegevoegd. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Voegt runs samen met dezelfde opmaak in alle alinea's in alle geschikte vormen. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ISlideHeaderFooterManager getHeaderFooterManager()
```

Retourneert de HeaderFooter-beheerder van de dia. Alleen-lezen [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Retourneert:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Retourneert de overschrijf-thema-beheerder. Alleen-lezen [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Retourneert:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)

### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```

Retourneert een nummer van de dia. Index van de dia in [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides)-collectie is altijd gelijk aan SlideNumber - Presentation.FirstSlideNumber. Lezen/schrijven int.

**Retourneert:**
int

### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```

Retourneert een nummer van de dia. Index van de dia in [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides)-collectie is altijd gelijk aan SlideNumber - Presentation.FirstSlideNumber. Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

Bepaalt of de opgegeven dia verborgen is tijdens de diavoorstelling. Lezen/schrijven boolean.

**Retourneert:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Bepaalt of de opgegeven dia verborgen is tijdens de diavoorstelling. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Geeft aan of vormen op de master-dia getoond moeten worden op dia's of niet. Lezen/schrijven boolean.

**Retourneert:**
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Geeft aan of vormen op de master-dia getoond moeten worden op dia's of niet. Lezen/schrijven boolean.

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
>      // Toegang tot de eerste dia
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Maak een afbeelding op volledige schaal
>      IImage bmp = sld.getImage(1f, 1f);
>      // Sla de afbeelding op schijf in JPEG-formaat
>      bmp.save("Thumbnail_out.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to converting slides to bitmap and saving the images in PNG.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Converteert de eerste dia in de presentatie naar een Bitmap-object
>      IImage bmp = pres.getSlides().get_Item(0).getImage();
>      // Slaat de afbeelding op in het PNG-formaat
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
>          // Maak een afbeelding op volledige schaal
>          IImage bmp = sld.getImage(1f, 1f);
>          // Sla de afbeelding op schijf in JPEG-formaat
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
>      // Definieer afmetingen
>      int desiredX = 1200;
>      int desiredY = 800;
>      // Haal geschaalde waarden van X en Y op
>      float ScaleX = (float)(1.0 / pres.getSlideSize().getSize().getWidth()) * desiredX;
>      float ScaleY = (float)(1.0 / pres.getSlideSize().getSize().getHeight()) * desiredY;
>      for (ISlide sld : pres.getSlides())
>      {
>          // Maak een afbeelding op volledige schaal
>          IImage bmp = sld.getImage(ScaleX, ScaleY);
>          // Sla de afbeelding op schijf in JPEG-formaat
>          bmp.save("Slide.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| scaleX | float | De waarde waarmee deze Thumbnail in de x-as wordt geschaald. |
| scaleY | float | De waarde waarmee deze Thumbnail in de y-as wordt geschaald. |

**Retourneert:**
[IImage](../../com.aspose.slides/iimage) - IImage object.

### getImage() {#getImage--}
```
public final IImage getImage()
```

Retourneert een Thumbnail Image-object (20 % van de werkelijke grootte).

**Retourneert:**
[IImage](../../com.aspose.slides/iimage)

### getImage(Dimension imageSize) {#getImage-java.awt.Dimension-}
```
public final IImage getImage(Dimension imageSize)
```

Retourneert een Thumbnail Image-object met opgegeven grootte.

--------------------

> ```
> The following example shows how to converting slides to images with custom sizes using C#.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Converteert de eerste dia in de presentatie naar een Bitmap met de opgegeven afmeting
>      IImage bmp = pres.getSlides().get_Item(0).getImage(new Dimension(1820, 1040));
>      // Slaat de afbeelding op in het JPEG-formaat
>      bmp.save("Slide_0.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| imageSize | java.awt.Dimension | Grootte van de te maken afbeelding. |

**Retourneert:**
[IImage](../../com.aspose.slides/iimage) - Image object.

### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public final IImage getImage(ITiffOptions options)
```

Retourneert een Thumbnail-tiff-afbeeldingsobject met opgegeven parameters.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tiff-opties. |

**Retourneert:**
[IImage](../../com.aspose.slides/iimage) - Image object.

### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public final IImage getImage(IRenderingOptions options)
```

Retourneert een Thumbnail Image-object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-opties. |

**Retourneert:**
[IImage](../../com.aspose.slides/iimage) - Image object.

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
>      // Converts the first slide of the presentation to a BufferedImage object
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
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-opties. |
| scaleX | float | De waarde waarmee deze Thumbnail in de x-as wordt geschaald. |
| scaleY | float | De waarde waarmee deze Thumbnail in de y-as wordt geschaald. |

**Retourneert:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.

### getImage(IRenderingOptions options, Dimension imageSize) {#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public final IImage getImage(IRenderingOptions options, Dimension imageSize)
```

Retourneert een Thumbnail Image-object met opgegeven grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-opties. |
| imageSize | java.awt.Dimension | Grootte van de te maken afbeelding. |

**Retourneert:**
[IImage](../../com.aspose.slides/iimage) - Image object.

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

Slaat de dia-inhoud op als een SVG-bestand.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.svg");
>      {
>          // Slaat de eerste dia op als een SVG-bestand
>          pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Doel-stream |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Slaat de dia-inhoud op als een SVG-bestand.

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
| stream | java.io.OutputStream | Doel-stream |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG-generatie-opties |

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

Slaat de dia-inhoud op als een EMF-bestand.

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
| stream | java.io.OutputStream | Doel-stream |

### remove() {#remove--}
```
public final void remove()
```

Verwijdert dia uit de presentatie.

### getLayoutSlide() {#getLayoutSlide--}
```
public final ILayoutSlide getLayoutSlide()
```

Retourneert of stelt de lay-out-dia in voor de huidige dia. Lezen/schrijven [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Retourneert:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public final void setLayoutSlide(ILayoutSlide value)
```

Retourneert of stelt de lay-out-dia in voor de huidige dia. Lezen/schrijven [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

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

Staat toe om de notitiedia te benaderen, toe te voegen en te verwijderen. Alleen-lezen [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Retourneert:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)

### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public final IComment[] getSlideComments(ICommentAuthor author)
```

Retourneert alle dia-commentaren die door een specifieke auteur zijn toegevoegd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Auteur van de te vinden commentaren of null om alle commentaren te retourneren. |

**Retourneert:**
com.aspose.slides.IComment[] - Array of [Comment](../../com.aspose.slides/comment).

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

Voegt runs samen met dezelfde opmaak in alle alinea's in alle geschikte vormen.