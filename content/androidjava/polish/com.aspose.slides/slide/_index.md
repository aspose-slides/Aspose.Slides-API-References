---
title: Slide
second_title: Aspose.Slides dla Androida - odwołanie do API Java
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

Reprezentuje slajd w prezentacji.
## Metody

| Metoda | Opis |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Zwraca menedżera HeaderFooter slajdu. |
| [getThemeManager()](#getThemeManager--) | Zwraca menedżera nadpisującego motywu. |
| [getSlideNumber()](#getSlideNumber--) | Zwraca numer slajdu. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Zwraca numer slajdu. |
| [getHidden()](#getHidden--) | Określa, czy dany slajd jest ukryty podczas pokazu slajdów. |
| [setHidden(boolean value)](#setHidden-boolean-) | Określa, czy dany slajd jest ukryty podczas pokazu slajdów. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Określa, czy kształty na slajdzie głównym mają być wyświetlane na slajdach. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Określa, czy kształty na slajdzie głównym mają być wyświetlane na slajdach. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Zwraca obiekt obrazu miniatury z niestandardowym skalowaniem. |
| [getImage()](#getImage--) | Zwraca obiekt obrazu miniatury (20% rzeczywistego rozmiaru). |
| [getImage(Size imageSize)](#getImage-com.aspose.slides.android.Size-) | Zwraca obiekt obrazu miniatury o określonym rozmiarze. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Zwraca obiekt obrazu miniatury tiff o określonych parametrach. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Zwraca obiekt obrazu miniatury. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Zwraca obiekt obrazu miniatury z niestandardowym skalowaniem. |
| [getImage(IRenderingOptions options, Size imageSize)](#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Zwraca obiekt obrazu miniatury o określonym rozmiarze. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Zapisuje zawartość slajdu jako plik SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Zapisuje zawartość slajdu jako plik SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Zapisuje zawartość slajdu jako plik EMF. |
| [remove()](#remove--) | Usuwa slajd z prezentacji. |
| [getLayoutSlide()](#getLayoutSlide--) | Zwraca lub ustawia slajd układu dla bieżącego slajdu. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Zwraca lub ustawia slajd układu dla bieżącego slajdu. |
| [reset()](#reset--) | Resetuje pozycję, rozmiar i formatowanie każdego kształtu, który ma prototyp na LayoutSlide. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Umożliwia dostęp do slajdu notatek, dodawanie i usuwanie go. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Zwraca wszystkie komentarze slajdu dodane przez określonego autora. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Łączy fragmenty z tym samym formatowaniem we wszystkich akapitach we wszystkich dopuszczalnych kształtach. |
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


Zwraca menedżera nadpisującego motywu. Tylko do odczytu [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

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


Zwraca numer slajdu. Indeks slajdu w kolekcji [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) jest zawsze równy SlideNumber - Presentation.FirstSlideNumber. Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getHidden() {#getHidden--}
```
public final boolean getHidden()
```


Określa, czy określony slajd jest ukryty podczas pokazu slajdów. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```


Określa, czy określony slajd jest ukryty podczas pokazu slajdów. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


Określa, czy kształty na slajdzie głównym mają być wyświetlane na slajdach. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


Określa, czy kształty na slajdzie głównym mają być wyświetlane na slajdach. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```


Zwraca obiekt obrazu miniatury z niestandardowym skalowaniem.

--------------------

> ```
> The following example shows how to generate thumbnails from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("ThumbnailFromSlide.pptx");
>  try {
>      // Uzyskaj dostęp do pierwszego slajdu
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Utwórz obraz w pełnej skali
>      IImage bmp = sld.getImage(1f, 1f);
>      // Zapisz obraz na dysku w formacie JPEG
>      bmp.save("Thumbnail_out.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to converting slides to bitmap and saving the images in PNG.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Konwertuje pierwszy slajd w prezentacji na obiekt Bitmap
>      IImage bmp = pres.getSlides().get_Item(0).getImage();
>      // Zapisuje obraz w formacie PNG
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
>          // Utwórz obraz w pełnej skali
>          IImage bmp = sld.getImage(1f, 1f);
>          // Zapisz obraz na dysku w formacie JPEG
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
>      // Zdefiniuj wymiary
>      int desiredX = 1200;
>      int desiredY = 800;
>      // Uzyskaj przeskalowane wartości X i Y
>      float ScaleX = (float)(1.0 / pres.getSlideSize().getSize().getWidth()) * desiredX;
>      float ScaleY = (float)(1.0 / pres.getSlideSize().getSize().getHeight()) * desiredY;
>      for (ISlide sld : pres.getSlides())
>      {
>          // Utwórz obraz w pełnej skali
>          IImage bmp = sld.getImage(ScaleX, ScaleY);
>          // Zapisz obraz na dysku w formacie JPEG
>          bmp.save("Slide.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| scaleX | float | Wartość, o którą skalować tę miniaturę w kierunku osi x. |
| scaleY | float | Wartość, o którą skalować tę miniaturę w kierunku osi y. |

**Zwraca:**
[IImage](../../com.aspose.slides/iimage) - obiekt IImage.
### getImage() {#getImage--}
```
public final IImage getImage()
```


Zwraca obiekt obrazu miniatury (20% rzeczywistego rozmiaru).

**Zwraca:**
[IImage](../../com.aspose.slides/iimage)
### getImage(Size imageSize) {#getImage-com.aspose.slides.android.Size-}
```
public final IImage getImage(Size imageSize)
```


Zwraca obiekt obrazu miniatury o określonym rozmiarze.

--------------------

> ```
> The following example shows how to converting slides to images with custom sizes using C#.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Konwertuje pierwszy slajd w prezentacji na obiekt Bitmap o określonym rozmiarze
>      IImage bmp = pres.getSlides().get_Item(0).getImage(new com.aspose.slides.android.Size(1820, 1040));
>      // Zapisuje obraz w formacie JPEG
>      bmp.save("Slide_0.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| imageSize | [Size](../../com.aspose.slides.android/size) | Rozmiar obrazu do utworzenia. |

**Zwraca:**
[IImage](../../com.aspose.slides/iimage) - obiekt Image.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public final IImage getImage(ITiffOptions options)
```


Zwraca obiekt obrazu miniatury tiff z określonymi parametrami.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Opcje Tiff. |

**Zwraca:**
[IImage](../../com.aspose.slides/iimage) - obiekt Image.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public final IImage getImage(IRenderingOptions options)
```


Zwraca obiekt obrazu miniatury.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opcje renderowania. |

**Zwraca:**
[IImage](../../com.aspose.slides/iimage) - obiekt Image.
### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```


Zwraca obiekt obrazu miniatury z niestandardowym skalowaniem.

--------------------

> ```
> The following example shows how to converting slides With notes and comments to Images.
>  
>  Presentation pres = new Presentation("PresentationNotesComments.pptx");
>  try {
>      // Utwórz opcje renderowania
>      IRenderingOptions options = new RenderingOptions();
>      // Utwórz opcje układu notatek i komentarzy
>      NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
>      // Ustawia pozycję notatek na stronie
>      notesCommentsLayouting.setNotesPosition(NotesPositions.BottomTruncated);
>      // Ustawia pozycję komentarzy na stronie
>      notesCommentsLayouting.setCommentsPosition(CommentsPositions.Right);
>      // Ustawia szerokość obszaru wyjściowego komentarzy
>      notesCommentsLayouting.setCommentsAreaWidth(500);
>      // Ustawia kolor obszaru komentarzy
>      notesCommentsLayouting.setCommentsAreaColor(Color.WHITE);
>      // Ustaw opcje układu dla renderowania
>      options.setSlidesLayoutOptions(notesCommentsLayouting);
>      // Konwertuje pierwszy slajd prezentacji na obiekt android.graphics.Bitmap
>      IImage image = pres.getSlides().get_Item(0).getImage(options, 2f, 2f);
>      // Zapisuje obraz w formacie GIF
>      image.save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opcje renderowania. |
| scaleX | float | Wartość, o którą skalować tę miniaturę w kierunku osi x. |
| scaleY | float | Wartość, o którą skalować tę miniaturę w kierunku osi y. |

**Zwraca:**
[IImage](../../com.aspose.slides/iimage) - obiekty Bitmap.
### getImage(IRenderingOptions options, Size imageSize) {#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public final IImage getImage(IRenderingOptions options, Size imageSize)
```


Zwraca obiekt obrazu miniatury o określonym rozmiarze.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opcje renderowania. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Rozmiar obrazu do utworzenia. |

**Zwraca:**
[IImage](../../com.aspose.slides/iimage) - obiekt Image.
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


Umożliwia dostęp do slajdu notatek, dodawanie i usuwanie go. Tylko do odczytu [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

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
com.aspose.slides.IComment[] - tablica [Comment](../../com.aspose.slides/comment).
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```


Łączy fragmenty z tym samym formatowaniem we wszystkich akapitach we wszystkich dopuszczalnych kształtach.