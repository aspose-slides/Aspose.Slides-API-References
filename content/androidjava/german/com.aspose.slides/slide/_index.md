---
title: Slide
second_title: Aspose.Slides für Android über die Java-API-Referenz
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
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Gibt den HeaderFooter-Manager der Folie zurück. |
| [getThemeManager()](#getThemeManager--) | Gibt den überschreibenden Themen-Manager zurück. |
| [getSlideNumber()](#getSlideNumber--) | Gibt die Nummer der Folie zurück. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Gibt die Nummer der Folie zurück. |
| [getHidden()](#getHidden--) | Ermittelt, ob die angegebene Folie während einer Diashow verborgen ist. |
| [setHidden(boolean value)](#setHidden-boolean-) | Ermittelt, ob die angegebene Folie während einer Diashow verborgen ist. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Gibt an, ob Formen auf der Masterfolie auf den Folien angezeigt werden sollen oder nicht. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Gibt an, ob Formen auf der Masterfolie auf den Folien angezeigt werden sollen oder nicht. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Gibt ein Thumbnail-Image-Objekt mit benutzerdefinierter Skalierung zurück. |
| [getImage()](#getImage--) | Gibt ein Thumbnail-Image-Objekt (20 % der Originalgröße) zurück. |
| [getImage(Size imageSize)](#getImage-com.aspose.slides.android.Size-) | Gibt ein Thumbnail-Image-Objekt mit angegebener Größe zurück. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Gibt ein Thumbnail-TIFF-Bildobjekt mit angegebenen Parametern zurück. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Gibt ein Thumbnail-Image-Objekt zurück. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Gibt ein Thumbnail-Image-Objekt mit benutzerdefinierter Skalierung zurück. |
| [getImage(IRenderingOptions options, Size imageSize)](#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Gibt ein Thumbnail-Image-Objekt mit angegebener Größe zurück. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Speichert den Folieninhalt als SVG-Datei. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Speichert den Folieninhalt als SVG-Datei. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Speichert den Folieninhalt als EMF-Datei. |
| [remove()](#remove--) | Entfernt die Folie aus der Präsentation. |
| [getLayoutSlide()](#getLayoutSlide--) | Gibt das Layout der aktuellen Folie zurück oder legt es fest. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Gibt das Layout der aktuellen Folie zurück oder legt es fest. |
| [reset()](#reset--) | Setzt Position, Größe und Formatierung aller Formen zurück, die eine Vorlage auf LayoutSlide haben. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Ermöglicht den Zugriff auf die Notizfolie, das Hinzufügen und Entfernen. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Gibt alle Folienkommentare zurück, die von einem bestimmten Autor hinzugefügt wurden. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Verbindet Textabschnitte mit gleicher Formatierung in allen Absätzen aller zulässigen Formen. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ISlideHeaderFooterManager getHeaderFooterManager()
```

Gibt den HeaderFooter-Manager der Folie zurück. Nur lesbar [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Rückgabe:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Gibt den überschreibenden Themen-Manager zurück. Nur lesbar [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Rückgabe:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```

Gibt die Nummer der Folie zurück. Der Index der Folie in der [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides)-Sammlung ist immer gleich SlideNumber - Presentation.FirstSlideNumber. Lese/Schreib int.

**Rückgabe:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```

Setzt die Nummer der Folie. Der Index der Folie in der [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides)-Sammlung ist immer gleich SlideNumber - Presentation.FirstSlideNumber. Lese/Schreib int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

Ermittelt, ob die angegebene Folie während einer Diashow verborgen ist. Lese/Schreib boolean.

**Rückgabe:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Ermittelt, ob die angegebene Folie während einer Diashow verborgen ist. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Gibt an, ob Formen auf der Masterfolie auf den Folien angezeigt werden sollen oder nicht. Lese/Schreib boolean.

**Rückgabe:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Gibt an, ob Formen auf der Masterfolie auf den Folien angezeigt werden sollen oder nicht. Lese/Schreib boolean.

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
>      // Greift auf die erste Folie zu
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Erstellt ein Bild in voller Größe
>      IImage bmp = sld.getImage(1f, 1f);
>      // Speichert das Bild auf der Festplatte im JPEG-Format
>      bmp.save("Thumbnail_out.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to converting slides to bitmap and saving the images in PNG.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Konvertiert die erste Folie der Präsentation in ein Bitmap-Objekt
>      IImage bmp = pres.getSlides().get_Item(0).getImage();
>      // Speichert das Bild im PNG-Format
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
>          // Erstellt ein Bild in voller Größe
>          IImage bmp = sld.getImage(1f, 1f);
>          // Speichert das Bild auf der Festplatte im JPEG-Format
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
>      // Definiert die Abmessungen
>      int desiredX = 1200;
>      int desiredY = 800;
>      // Ermittelt skalierte Werte von X und Y
>      float ScaleX = (float)(1.0 / pres.getSlideSize().getSize().getWidth()) * desiredX;
>      float ScaleY = (float)(1.0 / pres.getSlideSize().getSize().getHeight()) * desiredY;
>      for (ISlide sld : pres.getSlides())
>      {
>          // Erstellt ein Bild in voller Größe
>          IImage bmp = sld.getImage(ScaleX, ScaleY);
>          // Speichert das Bild auf der Festplatte im JPEG-Format
>          bmp.save("Slide.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| scaleX | float | Der Wert, um den dieses Thumbnail in x-Richtung skaliert wird. |
| scaleY | float | Der Wert, um den dieses Thumbnail in y-Richtung skaliert wird. |

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage) - IImage object.
### getImage() {#getImage--}
```
public final IImage getImage()
```

Gibt ein Thumbnail-Image-Objekt (20 % der Originalgröße) zurück.

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage)
### getImage(Size imageSize) {#getImage-com.aspose.slides.android.Size-}
```
public final IImage getImage(Size imageSize)
```

Gibt ein Thumbnail-Image-Objekt mit angegebener Größe zurück.

--------------------

> ```
> The following example shows how to converting slides to images with custom sizes using C#.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Konvertiert die erste Folie der Präsentation in ein Bitmap mit der angegebenen Größe
>      IImage bmp = pres.getSlides().get_Item(0).getImage(new com.aspose.slides.android.Size(1820, 1040));
>      // Speichert das Bild im JPEG-Format
>      bmp.save("Slide_0.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageSize | [Size](../../com.aspose.slides.android/size) | Größe des zu erstellenden Bildes. |

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage) - Image object.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public final IImage getImage(ITiffOptions options)
```

Gibt ein Thumbnail-TIFF-Bildobjekt mit angegebenen Parametern zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | TIFF-Optionen. |

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage) - Image object.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public final IImage getImage(IRenderingOptions options)
```

Gibt ein Thumbnail-Image-Objekt zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderoptionen. |

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage) - Image object.
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
>      // Erstelle die Rendering-Optionen
>      IRenderingOptions options = new RenderingOptions();
>      // Erstelle Layout-Optionen für Notizen und Kommentare
>      NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
>      // Setzt die Position der Notizen auf der Seite
>      notesCommentsLayouting.setNotesPosition(NotesPositions.BottomTruncated);
>      // Setzt die Position der Kommentare auf der Seite
>      notesCommentsLayouting.setCommentsPosition(CommentsPositions.Right);
>      // Setzt die Breite des Kommentar-Ausgabebereichs
>      notesCommentsLayouting.setCommentsAreaWidth(500);
>      // Setzt die Farbe für den Kommentarbereich
>      notesCommentsLayouting.setCommentsAreaColor(Color.WHITE);
>      // Setzt Layoutoptionen für das Rendering
>      options.setSlidesLayoutOptions(notesCommentsLayouting);
>      // Konvertiert die erste Folie der Präsentation in ein android.graphics.Bitmap-Objekt
>      IImage image = pres.getSlides().get_Item(0).getImage(options, 2f, 2f);
>      // Speichert das Bild im GIF-Format
>      image.save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderoptionen. |
| scaleX | float | Der Wert, um den dieses Thumbnail in x-Richtung skaliert wird. |
| scaleY | float | Der Wert, um den dieses Thumbnail in y-Richtung skaliert wird. |

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getImage(IRenderingOptions options, Size imageSize) {#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public final IImage getImage(IRenderingOptions options, Size imageSize)
```

Gibt ein Thumbnail-Image-Objekt mit angegebener Größe zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderoptionen. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Größe des zu erstellenden Bildes. |

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage) - Image object.
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

Gibt das Layout der aktuellen Folie zurück oder legt es fest. Lese/Schreib [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Rückgabe:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public final void setLayoutSlide(ILayoutSlide value)
```

Setzt das Layout der aktuellen Folie. Lese/Schreib [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |
### reset() {#reset--}
```
public final void reset()
```

Setzt Position, Größe und Formatierung aller Formen zurück, die eine Vorlage auf LayoutSlide haben.

### getNotesSlideManager() {#getNotesSlideManager--}
```
public final INotesSlideManager getNotesSlideManager()
```

Ermöglicht den Zugriff auf die Notizfolie, das Hinzufügen und Entfernen. Nur lesbar [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Rückgabe:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public final IComment[] getSlideComments(ICommentAuthor author)
```

Gibt alle Folienkommentare zurück, die von einem bestimmten Autor hinzugefügt wurden.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Autor der zu findenden Kommentare oder null, um alle Kommentare zurückzugeben. |

**Rückgabe:**
com.aspose.slides.IComment[] - Array of [Comment](../../com.aspose.slides/comment).
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

Verbindet Textabschnitte mit gleicher Formatierung in allen Absätzen aller zulässigen Formen.