---
title: Slide
second_title: Aspose.Slides dla Java – odniesienie API
description: Reprezentuje slajd w prezentacji.
type: docs
url: /pl/com.aspose.slides/slide/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISlide](../../com.aspose.slides/islide)
```
public final class Slide extends BaseSlide implements ISlide
```

Represents a slide in a presentation.
## Metody

| Metoda | Opis |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Zwraca menedżera HeaderFooter slajdu. |
| [getThemeManager()](#getThemeManager--) | Zwraca menedżera nadrzędnego tematu. |
| [getSlideNumber()](#getSlideNumber--) | Zwraca numer slajdu. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Zwraca numer slajdu. |
| [getHidden()](#getHidden--) | Określa, czy podany slajd jest ukryty podczas pokazu slajdów. |
| [setHidden(boolean value)](#setHidden-boolean-) | Określa, czy podany slajd jest ukryty podczas pokazu slajdów. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Określa, czy kształty na slajdzie głównym mają być wyświetlane na slajdach, czy nie. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Określa, czy kształty na slajdzie głównym mają być wyświetlane na slajdach, czy nie. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Zwraca obiekt Thumbnail Image z niestandardowym skalowaniem. |
| [getImage()](#getImage--) | Zwraca obiekt Thumbnail Image (20% rzeczywistego rozmiaru). |
| [getImage(Dimension imageSize)](#getImage-java.awt.Dimension-) | Zwraca obiekt Thumbnail Image o określonym rozmiarze. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Zwraca obiekt Thumbnail tiff image z określonymi parametrami. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Zwraca obiekt Thumbnail Image. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Zwraca obiekt Thumbnail Image z niestandardowym skalowaniem. |
| [getImage(IRenderingOptions options, Dimension imageSize)](#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Zwraca obiekt Thumbnail Image o określonym rozmiarze. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Zapisuje zawartość slajdu jako plik SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Zapisuje zawartość slajdu jako plik SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Zapisuje zawartość slajdu jako plik EMF. |
| [remove()](#remove--) | Usuwa slajd z prezentacji. |
| [getLayoutSlide()](#getLayoutSlide--) | Zwraca lub ustawia slajd układu dla bieżącego slajdu. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Zwraca lub ustawia slajd układu dla bieżącego slajdu. |
| [reset()](#reset--) | Resetuje pozycję, rozmiar i formatowanie każdego kształtu, który ma prototyp na LayoutSlide. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Umożliwia dostęp do slajdu notatek, dodawanie i usuwanie go. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Zwraca wszystkie komentarze slajdu dodane przez określonego autora. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Łączy ciągi znaków o tym samym formatowaniu we wszystkich akapitach we wszystkich dopuszczalnych kształtach. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ISlideHeaderFooterManager getHeaderFooterManager()
```

Zwraca menedżera HeaderFooter slajdu. Tylko do odczytu [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Zwraca:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Zwraca menedżera nadrzędnego tematu. Tylko do odczytu [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Zwraca:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)

### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```

Zwraca numer slajdu. Indeks slajdu w kolekcji [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) jest zawsze równy SlideNumber - Presentation.FirstSlideNumber. Odczyt/zapis int.

**Zwraca:**
int

### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```

Ustawia numer slajdu. Indeks slajdu w kolekcji [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) jest zawsze równy SlideNumber - Presentation.FirstSlideNumber. Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

Określa, czy podany slajd jest ukryty podczas pokazu slajdów. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Ustawia, czy podany slajd jest ukryty podczas pokazu slajdów. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Określa, czy kształty na slajdzie głównym mają być wyświetlane na slajdach, czy nie. Odczyt/zapis boolean.

**Zwraca:**
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Ustawia, czy kształty na slajdzie głównym mają być wyświetlane na slajdach, czy nie. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

Zwraca obiekt Thumbnail Image z niestandardowym skalowaniem.

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

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| scaleX | float | Wartość, o którą skalować ten Thumbnail w kierunku osi x. |
| scaleY | float | Wartość, o którą skalować ten Thumbnail w kierunku osi y. |

**Zwraca:**
[IImage](../../com.aspose.slides/iimage) - IImage object.

### getImage() {#getImage--}
```
public final IImage getImage()
```

Zwraca obiekt Thumbnail Image (20% rzeczywistego rozmiaru).

**Zwraca:**
[IImage](../../com.aspose.slides/iimage)

### getImage(Dimension imageSize) {#getImage-java.awt.Dimension-}
```
public final IImage getImage(Dimension imageSize)
```

Zwraca obiekt Thumbnail Image o określonym rozmiarze.

--------------------

> ```
> The following example shows how to converting slides to images with custom sizes using C#.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Konwertuje pierwszy slajd w prezentacji na obiekt Bitmap o określonym rozmiarze
>      IImage bmp = pres.getSlides().get_Item(0).getImage(new Dimension(1820, 1040));
>      // Zapisuje obraz w formacie JPEG
>      bmp.save("Slide_0.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| imageSize | java.awt.Dimension | Rozmiar obrazu do utworzenia. |

**Zwraca:**
[IImage](../../com.aspose.slides/iimage) - Image object.

### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public final IImage getImage(ITiffOptions options)
```

Zwraca obiekt Thumbnail tiff image z określonymi parametrami.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Opcje TIFF. |

**Zwraca:**
[IImage](../../com.aspose.slides/iimage) - Image object.

### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public final IImage getImage(IRenderingOptions options)
```

Zwraca obiekt Thumbnail Image.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opcje renderowania. |

**Zwraca:**
[IImage](../../com.aspose.slides/iimage) - Image object.

### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

Zwraca obiekt Thumbnail Image z niestandardowym skalowaniem.

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

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opcje renderowania. |
| scaleX | float | Wartość, o którą skalować ten Thumbnail w kierunku osi x. |
| scaleY | float | Wartość, o którą skalować ten Thumbnail w kierunku osi y. |

**Zwraca:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.

### getImage(IRenderingOptions options, Dimension imageSize) {#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public final IImage getImage(IRenderingOptions options, Dimension imageSize)
```

Zwraca obiekt Thumbnail Image o określonym rozmiarze.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opcje renderowania. |
| imageSize | java.awt.Dimension | Rozmiar obrazu do utworzenia. |

**Zwraca:**
[IImage](../../com.aspose.slides/iimage) - Image object.

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

Zapisuje zawartość slajdu jako plik SVG.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.svg");
>      {
>          // Zapisuje pierwszy slajd jako plik SVG
>          pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.OutputStream | Strumień docelowy |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Zapisuje zawartość slajdu jako plik SVG.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file with options.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide1.svg");
>      SVGOptions options = new SVGOptions();
>      options.setVectorizeText(true);
>      // Zapisuje pierwszy slajd jako plik SVG
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.OutputStream | Strumień docelowy |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Opcje generowania SVG |

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

Zapisuje zawartość slajdu jako plik EMF.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into a metafile.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.emf");
>      {
>          // Zapisuje pierwszy slajd jako plik metafile
>          pres.getSlides().get_Item(0).writeAsEmf(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.OutputStream | Strumień docelowy |

### remove() {#remove--}
```
public final void remove()
```

Usuwa slajd z prezentacji.

### getLayoutSlide() {#getLayoutSlide--}
```
public final ILayoutSlide getLayoutSlide()
```

Zwraca lub ustawia slajd układu dla bieżącego slajdu. Odczyt/zapis [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Zwraca:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public final void setLayoutSlide(ILayoutSlide value)
```

Zwraca lub ustawia slajd układu dla bieżącego slajdu. Odczyt/zapis [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |

### reset() {#reset--}
```
public final void reset()
```

Resetuje pozycję, rozmiar i formatowanie każdego kształtu, który ma prototyp na LayoutSlide.

### getNotesSlideManager() {#getNotesSlideManager--}
```
public final INotesSlideManager getNotesSlideManager()
```

Umożliwia dostęp do slajdu z notatkami, dodawanie i usuwanie go. Tylko do odczytu [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Zwraca:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)

### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public final IComment[] getSlideComments(ICommentAuthor author)
```

Zwraca wszystkie komentarze slajdu dodane przez określonego autora.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Autor komentarzy do znalezienia lub null, aby zwrócić wszystkie komentarze. |

**Zwraca:**
com.aspose.slides.IComment[] - Array of [Comment](../../com.aspose.slides/comment).

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

Łączy ciągi znaków o tym samym formatowaniu we wszystkich akapitach we wszystkich dopuszczalnych kształtach.