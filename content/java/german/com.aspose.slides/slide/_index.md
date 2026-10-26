---
title: Slide
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine Folie in einer Präsentation dar.
type: docs
url: /de/com.aspose.slides/slide/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISlide](../../com.aspose.slides/islide)
```
public final class Slide extends BaseSlide implements ISlide
```

Stellt eine Folie in einer Präsentation dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Gibt den HeaderFooter manager der Folie zurück. |
| [getThemeManager()](#getThemeManager--) | Gibt den überschreibenden Theme manager zurück. |
| [getSlideNumber()](#getSlideNumber--) | Gibt die Foliennummer zurück. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Gibt die Foliennummer zurück. |
| [getHidden()](#getHidden--) | Bestimmt, ob die angegebene Folie während einer Diashow ausgeblendet ist. |
| [setHidden(boolean value)](#setHidden-boolean-) | Bestimmt, ob die angegebene Folie während einer Diashow ausgeblendet ist. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Legt fest, ob Formen auf der Master-Folien auf Folien angezeigt werden sollen. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Legt fest, ob Formen auf der Master-Folien auf Folien angezeigt werden sollen. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Gibt ein Thumbnail-Image-Objekt mit benutzerdefinierter Skalierung zurück. |
| [getImage()](#getImage--) | Gibt ein Thumbnail-Image-Objekt (20 % der Originalgröße) zurück. |
| [getImage(Dimension imageSize)](#getImage-java.awt.Dimension-) | Gibt ein Thumbnail-Image-Objekt mit angegebener Größe zurück. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Gibt ein Thumbnail-Tiff-Image-Objekt mit angegebenen Parametern zurück. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Gibt ein Thumbnail-Image-Objekt zurück. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Gibt ein Thumbnail-Image-Objekt mit benutzerdefinierter Skalierung zurück. |
| [getImage(IRenderingOptions options, Dimension imageSize)](#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Gibt ein Thumbnail-Image-Objekt mit angegebener Größe zurück. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Speichert den Folieninhalt als SVG-Datei. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Speichert den Folieninhalt als SVG-Datei. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Speichert den Folieninhalt als EMF-Datei. |
| [remove()](#remove--) | Entfernt die Folie aus der Präsentation. |
| [getLayoutSlide()](#getLayoutSlide--) | Gibt das Layout der Folie zurück oder legt es fest. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Gibt das Layout der Folie zurück oder legt es fest. |
| [reset()](#reset--) | Setzt Position, Größe und Formatierung aller Formen zurück, die ein Prototype auf LayoutSlide haben. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Ermöglicht den Zugriff auf die Notizfolie, Hinzufügen und Entfernen. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Gibt alle Folienkommentare des angegebenen Autors zurück. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Führt Läufe mit gleicher Formatierung in allen Absätzen in allen zulässigen Formen zusammen. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ISlideHeaderFooterManager getHeaderFooterManager()
```

Gibt den HeaderFooter manager der Folie zurück. Nur lesend [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Rückgabe:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Gibt den überschreibenden Theme manager zurück. Nur lesend [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Rückgabe:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)

### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```

Gibt die Foliennummer zurück. Der Index der Folie in der [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides)-Sammlung ist immer gleich SlideNumber - Presentation.FirstSlideNumber. Lesen/Schreiben int.

**Rückgabe:**
int

### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```

Setzt die Foliennummer. Der Index der Folie in der [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides)-Sammlung ist immer gleich SlideNumber - Presentation.FirstSlideNumber. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

Bestimmt, ob die angegebene Folie während einer Diashow ausgeblendet ist. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Setzt, ob die angegebene Folie während einer Diashow ausgeblendet ist. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Legt fest, ob Formen auf der Master-Folien auf Folien angezeigt werden sollen. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Setzt, ob Formen auf der Master-Folien auf Folien angezeigt werden sollen. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

Gibt ein Thumbnail-Image-Objekt mit benutzerdefinierter Skalierung zurück.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| scaleX | float | Der Wert, um den dieses Thumbnail in X-Richtung skaliert wird. |
| scaleY | float | Der Wert, um den dieses Thumbnail in Y-Richtung skaliert wird. |

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage) - IImage-Objekt.

### getImage() {#getImage--}
```
public final IImage getImage()
```

Gibt ein Thumbnail-Image-Objekt (20 % der Originalgröße) zurück.

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage)

### getImage(Dimension imageSize) {#getImage-java.awt.Dimension-}
```
public final IImage getImage(Dimension imageSize)
```

Gibt ein Thumbnail-Image-Objekt mit angegebener Größe zurück.

--------------------

> ```
> The following example shows how to converting slides to images with custom sizes using C#.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Konvertiert die erste Folie der Präsentation in ein Bitmap mit der angegebenen Größe
>      IImage bmp = pres.getSlides().get_Item(0).getImage(new Dimension(1820, 1040));
>      // Speichert das Bild im JPEG-Format
>      bmp.save("Slide_0.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageSize | java.awt.Dimension | Größe des zu erstellenden Bildes. |

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage) - Image-Objekt.

### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public final IImage getImage(ITiffOptions options)
```

Gibt ein Thumbnail-Tiff-Image-Objekt mit angegebenen Parametern zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tiff-Optionen. |

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage) - Image-Objekt.

### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public final IImage getImage(IRenderingOptions options)
```

Gibt ein Thumbnail-Image-Objekt zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-Optionen. |

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage) - Image-Objekt.

### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

Gibt ein Thumbnail-Image-Objekt mit benutzerdefinierter Skalierung zurück.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-Optionen. |
| scaleX | float | Der Wert, um den dieses Thumbnail in X-Richtung skaliert wird. |
| scaleY | float | Der Wert, um den dieses Thumbnail in Y-Richtung skaliert wird. |

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage) - Bitmap-Objekte.

### getImage(IRenderingOptions options, Dimension imageSize) {#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public final IImage getImage(IRenderingOptions options, Dimension imageSize)
```

Gibt ein Thumbnail-Image-Objekt mit angegebener Größe zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-Optionen. |
| imageSize | java.awt.Dimension | Größe des zu erstellenden Bildes. |

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage) - Image-Objekt.

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

Speichert den Folieninhalt als SVG-Datei.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.svg");
>      {
>          // Speichert die erste Folie als SVG-Datei
>          pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Ziel-Stream |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Speichert den Folieninhalt als SVG-Datei.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file with options.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide1.svg");
>      SVGOptions options = new SVGOptions();
>      options.setVectorizeText(true);
>      // Speichert die erste Folie als SVG-Datei
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Ziel-Stream |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG-Generierungsoptionen |

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

Speichert den Folieninhalt als EMF-Datei.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into a metafile.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.emf");
>      {
>          // Speichert die erste Folie als Metadatei
>          pres.getSlides().get_Item(0).writeAsEmf(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Ziel-Stream |

### remove() {#remove--}
```
public final void remove()
```

Entfernt die Folie aus der Präsentation.

### getLayoutSlide() {#getLayoutSlide--}
```
public final ILayoutSlide getLayoutSlide()
```

Gibt das Layout der Folie zurück oder legt es fest. Lesen/Schreiben [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Rückgabe:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public final void setLayoutSlide(ILayoutSlide value)
```

Setzt das Layout der Folie oder gibt es zurück. Lesen/Schreiben [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |

### reset() {#reset--}
```
public final void reset()
```

Setzt Position, Größe und Formatierung aller Formen zurück, die ein Prototype auf LayoutSlide haben.

### getNotesSlideManager() {#getNotesSlideManager--}
```
public final INotesSlideManager getNotesSlideManager()
```

Ermöglicht den Zugriff auf die Notizfolie, Hinzufügen und Entfernen. Nur lesend [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Rückgabe:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)

### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public final IComment[] getSlideComments(ICommentAuthor author)
```

Gibt alle Folienkommentare des angegebenen Autors zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Autor der zu findenden Kommentare oder null, um alle Kommentare zurückzugeben. |

**Rückgabe:**
com.aspose.slides.IComment[] - Array von [Comment](../../com.aspose.slides/comment).

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

Führt Läufe mit gleicher Formatierung in allen Absätzen in allen zulässigen Formen zusammen.