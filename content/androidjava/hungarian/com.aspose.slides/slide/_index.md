---
title: Slide
second_title: Aspose.Slides Android Java API hivatkozás
description: Egy diát képvisel a prezentációban.
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

Egy diát képvisel a prezentációban.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Visszaadja a dia HeaderFooter managerét. |
| [getThemeManager()](#getThemeManager--) | Visszaadja a felülbíráló theme manager-t. |
| [getSlideNumber()](#getSlideNumber--) | Visszaadja a dia számát. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Visszaadja a dia számát. |
| [getHidden()](#getHidden--) | Megállapítja, hogy a megadott dia rejtett-e a diavetítés során. |
| [setHidden(boolean value)](#setHidden-boolean-) | Megállapítja, hogy a megadott dia rejtett-e a diavetítés során. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Megadja, hogy a master dián lévő alakzatok megjelenjenek-e a diákon vagy sem. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Megadja, hogy a master dián lévő alakzatok megjelenjenek-e a diákon vagy sem. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Visszaad egy Thumbnail Image objektumot egyedi méretezéssel. |
| [getImage()](#getImage--) | Visszaad egy Thumbnail Image objektumot (a valós méret 20%-a). |
| [getImage(Size imageSize)](#getImage-com.aspose.slides.android.Size-) | Visszaad egy Thumbnail Image objektumot a megadott mérettel. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Visszaad egy Thumbnail tiff kép objektumot a megadott paraméterekkel. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Visszaad egy Thumbnail Image objektumot. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Visszaad egy Thumbnail Image objektumot egyedi méretezéssel. |
| [getImage(IRenderingOptions options, Size imageSize)](#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Visszaad egy Thumbnail Image objektumot a megadott mérettel. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | A dia tartalmát SVG fájlként menti. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | A dia tartalmát SVG fájlként menti. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | A dia tartalmát EMF fájlként menti. |
| [remove()](#remove--) | Eltávolítja a diát a prezentációból. |
| [getLayoutSlide()](#getLayoutSlide--) | Visszaadja vagy beállítja a jelenlegi dia elrendezési diáját. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Visszaadja vagy beállítja a jelenlegi dia elrendezési diáját. |
| [reset()](#reset--) | Visszaállítja a pozíciót, méretet és formázást minden olyan alakzatra, amelynek prototípusa van a LayoutSlide-on. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Lehetővé teszi a jegyzetdiához való hozzáférést, hozzáadást és eltávolítását. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Visszaadja az adott szerző által hozzáadott összes dia megjegyzést. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Összekapcsolja a futamokat azonos formázással az összes bekezdésben az összes elfogadható alakzatban. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ISlideHeaderFooterManager getHeaderFooterManager()
```

Visszaadja a dia HeaderFooter managerét. Csak olvasható [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Visszatérési érték:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Visszaadja a felülbíráló theme manager-t. Csak olvasható [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Visszatérési érték:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```

Visszaadja a dia számát. A [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) gyűjteményben a dia indexe mindig egyenlő a SlideNumber – Presentation.FirstSlideNumber értékkel. Olvasás/írás int.

**Visszatérési érték:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```

Visszaadja a dia számát. A [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) gyűjteményben a dia indexe mindig egyenlő a SlideNumber – Presentation.FirstSlideNumber értékkel. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

Megállapítja, hogy a megadott dia rejtett-e a diavetítés során. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Megállapítja, hogy a megadott dia rejtett-e a diavetítés során. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Megadja, hogy a master dián lévő alakzatok megjelenjenek-e a diákon vagy sem. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Megadja, hogy a master dián lévő alakzatok megjelenjenek-e a diákon vagy sem. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

Visszaad egy Thumbnail Image objektumot egyedi méretezéssel.

--------------------

> ```
> The following example shows how to generate thumbnails from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("ThumbnailFromSlide.pptx");
>  try {
>      // Az első diát elérni
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Teljes méretű kép létrehozása
>      IImage bmp = sld.getImage(1f, 1f);
>      // Kép mentése lemezre JPEG formátumban
>      bmp.save("Thumbnail_out.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to converting slides to bitmap and saving the images in PNG.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Átalakítja a prezentáció első diáját Bitmap objektummá
>      IImage bmp = pres.getSlides().get_Item(0).getImage();
>      // Kép mentése PNG formátumban
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
>          // Teljes méretű kép létrehozása
>          IImage bmp = sld.getImage(1f, 1f);
>          // Kép mentése lemezre JPEG formátumban
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
>      // Dimenziók meghatározása
>      int desiredX = 1200;
>      int desiredY = 800;
>      // X és Y méretezett értékeinek lekérése
>      float ScaleX = (float)(1.0 / pres.getSlideSize().getSize().getWidth()) * desiredX;
>      float ScaleY = (float)(1.0 / pres.getSlideSize().getSize().getHeight()) * desiredY;
>      for (ISlide sld : pres.getSlides())
>      {
>          // Teljes méretű kép létrehozása
>          IImage bmp = sld.getImage(ScaleX, ScaleY);
>          // Kép mentése lemezre JPEG formátumban
>          bmp.save("Slide.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| scaleX | float | A Thumbnail X-tengelyben való méretezésének értéke. |
| scaleY | float | A Thumbnail Y-tengelyben való méretezésének értéke. |

**Visszatérési érték:**
[IImage](../../com.aspose.slides/iimage) – IImage objektum.
### getImage() {#getImage--}
```
public final IImage getImage()
```

Visszaad egy Thumbnail Image objektumot (a valós méret 20%-a).

**Visszatérési érték:**
[IImage](../../com.aspose.slides/iimage)
### getImage(Size imageSize) {#getImage-com.aspose.slides.android.Size-}
```
public final IImage getImage(Size imageSize)
```

Visszaad egy Thumbnail Image objektumot a megadott mérettel.

--------------------

> ```
> The following example shows how to converting slides to images with custom sizes using C#.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Átalakítja a prezentáció első diaját egy megadott méretű Bitmap objektummá
>      IImage bmp = pres.getSlides().get_Item(0).getImage(new com.aspose.slides.android.Size(1820, 1040));
>      // Mentse a képet JPEG formátumban
>      bmp.save("Slide_0.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| imageSize | [Size](../../com.aspose.slides.android/size) | A létrehozandó kép mérete. |

**Visszatérési érték:**
[IImage](../../com.aspose.slides/iimage) – Image objektum.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public final IImage getImage(ITiffOptions options)
```

Visszaad egy Thumbnail tiff kép objektumot a megadott paraméterekkel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tiff beállítások. |

**Visszatérési érték:**
[IImage](../../com.aspose.slides/iimage) – Image objektum.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public final IImage getImage(IRenderingOptions options)
```

Visszaad egy Thumbnail Image objektumot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderelési beállítások. |

**Visszatérési érték:**
[IImage](../../com.aspose.slides/iimage) – Image objektum.
### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

Visszaad egy Thumbnail Image objektumot egyedi méretezéssel.

--------------------

> ```
> The following example shows how to converting slides With notes and comments to Images.
>  
>  Presentation pres = new Presentation("PresentationNotesComments.pptx");
>  try {
>      // A renderelési beállítások létrehozása
>      IRenderingOptions options = new RenderingOptions();
>      // Jegyzet- és megjegyzéselrendezési beállítások létrehozása
>      NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
>      // Beállítja a jegyzetek pozícióját az oldalon
>      notesCommentsLayouting.setNotesPosition(NotesPositions.BottomTruncated);
>      // Beállítja a megjegyzések pozícióját az oldalon
>      notesCommentsLayouting.setCommentsPosition(CommentsPositions.Right);
>      // Beállítja a megjegyzés kimeneti terület szélességét
>      notesCommentsLayouting.setCommentsAreaWidth(500);
>      // Beállítja a megjegyzés terület színét
>      notesCommentsLayouting.setCommentsAreaColor(Color.WHITE);
>      // Elrendezési beállítások beállítása a rendereléshez
>      options.setSlidesLayoutOptions(notesCommentsLayouting);
>      // Átalakítja a prezentáció első diáját egy android.graphics.Bitmap objektummá
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
| scaleX | float | A Thumbnail X-tengelyben való méretezésének értéke. |
| scaleY | float | A Thumbnail Y-tengelyben való méretezésének értéke. |

**Visszatérési érték:**
[IImage](../../com.aspose.slides/iimage) – Bitmap objektumok.
### getImage(IRenderingOptions options, Size imageSize) {#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public final IImage getImage(IRenderingOptions options, Size imageSize)
```

Visszaad egy Thumbnail Image objektumot a megadott mérettel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderelési beállítások. |
| imageSize | [Size](../../com.aspose.slides.android/size) | A létrehozandó kép mérete. |

**Visszatérési érték:**
[IImage](../../com.aspose.slides/iimage) – Image objektum.
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

A dia tartalmát SVG fájlként menti.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.svg");
>      {
>          // Az első diát SVG fájlként menti
>          pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Cél stream |
### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

A dia tartalmát SVG fájlként menti.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file with options.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide1.svg");
>      SVGOptions options = new SVGOptions();
>      options.setVectorizeText(true);
>      // Az első diát SVG fájlként menti
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Cél stream |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG generálási beállítások |
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

A dia tartalmát EMF fájlként menti.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into a metafile.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.emf");
>      {
>          // Az első diát metafájlként menti
>          pres.getSlides().get_Item(0).writeAsEmf(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Cél stream |
### remove() {#remove--}
```
public final void remove()
```

Eltávolítja a diát a prezentációból.
### getLayoutSlide() {#getLayoutSlide--}
```
public final ILayoutSlide getLayoutSlide()
```

Visszaadja vagy beállítja a jelenlegi dia elrendezési diáját. Olvasás/írás [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Visszatérési érték:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public final void setLayoutSlide(ILayoutSlide value)
```

Visszaadja vagy beállítja a jelenlegi dia elrendezési diáját. Olvasás/írás [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |
### reset() {#reset--}
```
public final void reset()
```

Visszaállítja a pozíciót, méretet és formázást minden olyan alakzatra, amelynek prototípusa van a LayoutSlide-on.
### getNotesSlideManager() {#getNotesSlideManager--}
```
public final INotesSlideManager getNotesSlideManager()
```

Lehetővé teszi a jegyzetdia elérését, hozzáadását és eltávolítását. Csak olvasható [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Visszatérési érték:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public final IComment[] getSlideComments(ICommentAuthor author)
```

Visszaadja az adott szerző által hozzáadott összes dia megjegyzést.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Megjegyzések szerzője vagy null az összes megjegyzés visszatéréséhez. |

**Visszatérési érték:**
com.aspose.slides.IComment[] – [Comment](../../com.aspose.slides/comment) tömb.
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

Összekapcsolja a futamokat azonos formázással az összes bekezdésben az összes elfogadható alakzatban.