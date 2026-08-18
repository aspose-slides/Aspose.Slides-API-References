---
title: Slide
second_title: Aspose.Slides for Java API Referencia
description: Egy diát képvisel egy előadásban.
type: docs
url: /hu/com.aspose.slides/slide/
---
**Öröklés:**  
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Minden megvalósított interfész:**  
[com.aspose.slides.ISlide](../../com.aspose.slides/islide)
```
public final class Slide extends BaseSlide implements ISlide
```

Egy diát képvisel egy előadásban.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Visszaadja a dia HeaderFooter menedzserét. |
| [getThemeManager()](#getThemeManager--) | Visszaadja a felülbíráló téma menedzserét. |
| [getSlideNumber()](#getSlideNumber--) | Visszaadja a dia számát. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Visszaadja a dia számát. |
| [getHidden()](#getHidden--) | Meghatározza, hogy a megadott dia rejtett-e a diavetítés során. |
| [setHidden(boolean value)](#setHidden-boolean-) | Meghatározza, hogy a megadott dia rejtett-e a diavetítés során. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Megadja, hogy a mesterdia alakzatok megjelenjenek-e a diáknál. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Megadja, hogy a mesterdia alakzatok megjelenjenek-e a diáknál. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Visszaad egy egyéni méretezésű Miniatűr Kép objektumot. |
| [getImage()](#getImage--) | Visszaad egy Miniatűr Kép objektumot (a valós méret 20%-a). |
| [getImage(Dimension imageSize)](#getImage-java.awt.Dimension-) | Visszaad egy megadott méretű Miniatűr Kép objektumot. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Visszaad egy megadott paraméterekkel rendelkező Miniatűr tiff kép objektumot. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Visszaad egy Miniatűr Kép objektumot. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Visszaad egy egyéni méretezésű Miniatűr Kép objektumot. |
| [getImage(IRenderingOptions options, Dimension imageSize)](#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Visszaad egy megadott méretű Miniatűr Kép objektumot. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Elmenti a dia tartalmát SVG fájlként. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Elmenti a dia tartalmát SVG fájlként. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Elmenti a dia tartalmát EMF fájlként. |
| [remove()](#remove--) | Eltávolítja a diát az előadásból. |
| [getLayoutSlide()](#getLayoutSlide--) | Visszaadja vagy beállítja az aktuális dia elrendezési diáját. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Visszaadja vagy beállítja az aktuális dia elrendezési diáját. |
| [reset()](#reset--) | Visszaállítja az összes olyan alakzat pozícióját, méretét és formázását, amelynek prototípusa a LayoutSlide-on van. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Lehetővé teszi a jegyzetdia elérését, hozzáadását és eltávolítását. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Visszaadja az adott szerző által hozzáadott összes dia megjegyzést. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Egyesíti a futásokat azonos formázással az összes bekezdésben az összes elfogadható alakzatban. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ISlideHeaderFooterManager getHeaderFooterManager()
```

Visszaadja a dia HeaderFooter menedzserét. Csak olvasható [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Visszatér:**  
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Visszaadja a felülbíráló téma menedzserét. Csak olvasható [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Visszatér:**  
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)

### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```

Visszaadja a dia számát. A [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) gyűjteményben a dia indexe mindig egyenlő a SlideNumber - Presentation.FirstSlideNumber értékkel. Olvasás/írás int.

**Visszatér:**  
int

### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```

Visszaadja a dia számát. A [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) gyűjteményben a dia indexe mindig egyenlő a SlideNumber - Presentation.FirstSlideNumber értékkel. Olvasás/írás int.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

Meghatározza, hogy a megadott dia rejtett-e a diavetítés során. Olvasás/írás boolean.

**Visszatér:**  
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Meghatározza, hogy a megadott dia rejtett-e a diavetítés során. Olvasás/írás boolean.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Megadja, hogy a mesterdia alakzatok megjelenjenek-e a diáknál. Olvasás/írás boolean.

**Visszatér:**  
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Megadja, hogy a mesterdia alakzatok megjelenjenek-e a diáknál. Olvasás/írás boolean.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

Visszaad egy egyéni méretezésű Miniatűr Kép objektumot.

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

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| scaleX | float | Az érték, amellyel a Miniatűrt az x-tengely mentén méretezni kell. |
| scaleY | float | Az érték, amellyel a Miniatűrt az y-tengely mentén méretezni kell. |

**Visszatér:**  
[IImage](../../com.aspose.slides/iimage) – IImage objektum.

### getImage() {#getImage--}
```
public final IImage getImage()
```

Visszaad egy Miniatűr Kép objektumot (a valós méret 20%-a).

**Visszatér:**  
[IImage](../../com.aspose.slides/iimage)

### getImage(Dimension imageSize) {#getImage-java.awt.Dimension-}
```
public final IImage getImage(Dimension imageSize)
```

Visszaad egy megadott méretű Miniatűr Kép objektumot.

--------------------

> ```
> The following example shows how to converting slides to images with custom sizes using C#.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Átalakítja a prezentáció első diáját a megadott mérettel rendelkező Bitmap objektummá
>      IImage bmp = pres.getSlides().get_Item(0).getImage(new Dimension(1820, 1040));
>      // Saves the image in the JPEG format
>      bmp.save("Slide_0.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
> ```

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| imageSize | java.awt.Dimension | A létrehozandó kép mérete. |

**Visszatér:**  
[IImage](../../com.aspose.slides/iimage) – Image objektum.

### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public final IImage getImage(ITiffOptions options)
```

Visszaad egy megadott paraméterekkel rendelkező Miniatűr tiff kép objektumot.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tiff beállítások. |

**Visszatér:**  
[IImage](../../com.aspose.slides/iimage) – Image objektum.

### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public final IImage getImage(IRenderingOptions options)
```

Visszaad egy Miniatűr Kép objektumot.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderelési beállítások. |

**Visszatér:**  
[IImage](../../com.aspose.slides/iimage) – Image objektum.

### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

Visszaad egy egyéni méretezésű Miniatűr Kép objektumot.

--------------------

> ```
> The following example shows how to converting slides With notes and comments to Images.
>  
>  Presentation pres = new Presentation("PresentationNotesComments.pptx");
>  try {
>      // Létrehozza a renderelési beállításokat
>      IRenderingOptions options = new RenderingOptions();
>      // Létrehozza a jegyzetek és megjegyzések elrendezési beállításait
>      NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
>      // Beállítja a jegyzetek pozícióját az oldalon
>      notesCommentsLayouting.setNotesPosition(NotesPositions.BottomTruncated);
>      // Beállítja a megjegyzések pozícióját az oldalon
>      notesCommentsLayouting.setCommentsPosition(CommentsPositions.Right);
>      // Beállítja a megjegyzés kimeneti terület szélességét
>      notesCommentsLayouting.setCommentsAreaWidth(500);
>      // Beállítja a megjegyzés terület színét
>      notesCommentsLayouting.setCommentsAreaColor(Color.WHITE);
>      // Beállítja az elrendezési opciókat a rendereléshez
>      options.setSlidesLayoutOptions(notesCommentsLayouting);
>      // Átalakítja a prezentáció első diáját BufferedImage objektummá
>      IImage image = pres.getSlides().get_Item(0).getImage(options, 2f, 2f);
>      // Mentse a képet GIF formátumban
>      image.save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderelési beállítások. |
| scaleX | float | Az érték, amellyel a Miniatűrt az x-tengely mentén méretezni kell. |
| scaleY | float | Az érték, amellyel a Miniatűrt az y-tengely mentén méretezni kell. |

**Visszatér:**  
[IImage](../../com.aspose.slides/iimage) – Bitmap objektumok.

### getImage(IRenderingOptions options, Dimension imageSize) {#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public final IImage getImage(IRenderingOptions options, Dimension imageSize)
```

Visszaad egy megadott méretű Miniatűr Kép objektumot.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderelési beállítások. |
| imageSize | java.awt.Dimension | A létrehozandó kép mérete. |

**Visszatér:**  
[IImage](../../com.aspose.slides/iimage) – Image objektum.

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

Elmenti a dia tartalmát SVG fájlként.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.svg");
>      {
>          // Elmenti az első diát SVG fájlként
>          pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Célfolyam |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Elmenti a dia tartalmát SVG fájlként.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file with options.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide1.svg");
>      SVGOptions options = new SVGOptions();
>      options.setVectorizeText(true);
>      // Elmenti az első diát SVG fájlként
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Célfolyam |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG generálási beállítások |

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

Elmenti a dia tartalmát EMF fájlként.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into a metafile.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.emf");
>      {
>          // Elmenti az első diát metafájlként
>          pres.getSlides().get_Item(0).writeAsEmf(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Célfolyam |

### remove() {#remove--}
```
public final void remove()
```

Eltávolítja a diát az előadásból.

### getLayoutSlide() {#getLayoutSlide--}
```
public final ILayoutSlide getLayoutSlide()
```

Visszaadja vagy beállítja az aktuális dia elrendezési diáját. Olvasás/írás [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Visszatér:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public final void setLayoutSlide(ILayoutSlide value)
```

Visszaadja vagy beállítja az aktuális dia elrendezési diáját. Olvasás/írás [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |

### reset() {#reset--}
```
public final void reset()
```

Visszaállítja az összes olyan alakzat pozícióját, méretét és formázását, amelynek prototípusa a LayoutSlide-on van.

### getNotesSlideManager() {#getNotesSlideManager--}
```
public final INotesSlideManager getNotesSlideManager()
```

Lehetővé teszi a jegyzetdia elérését, hozzáadását és eltávolítását. Csak olvasható [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Visszatér:**  
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)

### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public final IComment[] getSlideComments(ICommentAuthor author)
```

Visszaadja az adott szerző által hozzáadott összes dia megjegyzést.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | A megtalálandó megjegyzések szerzője, vagy null az összes megjegyzéshez. |

**Visszatér:**  
com.aspose.slides.IComment[] – [Comment](../../com.aspose.slides/comment) tömb.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

Egyesíti a futásokat azonos formázással az összes bekezdésben az összes elfogadható alakzatban.