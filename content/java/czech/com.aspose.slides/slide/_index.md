---
title: Slide
second_title: Aspose.Slides pro Java – reference API
description: Representuje snímek v prezentaci.
type: docs
url: /cs/com.aspose.slides/slide/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Všechny implementované rozhraní:**
[com.aspose.slides.ISlide](../../com.aspose.slides/islide)
```
public final class Slide extends BaseSlide implements ISlide
```

Representuje snímek v prezentaci.
## Metody

| Metoda | Popis |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Vrací správce HeaderFooter snímku. |
| [getThemeManager()](#getThemeManager--) | Vrací správce přepisujícího motivu. |
| [getSlideNumber()](#getSlideNumber--) | Vrací číslo snímku. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Vrací číslo snímku. |
| [getHidden()](#getHidden--) | Určuje, zda je uvedený snímek během promítání skrytý. |
| [setHidden(boolean value)](#setHidden-boolean-) | Určuje, zda je uvedený snímek během promítání skrytý. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Určuje, zda mají být tvary na hlavním snímku zobrazeny na snímcích, či ne. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Určuje, zda mají být tvary na hlavním snímku zobrazeny na snímcích, či ne. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Vrací objekt Thumbnail Image s vlastním škálováním. |
| [getImage()](#getImage--) | Vrací objekt Thumbnail Image (20 % skutečné velikosti). |
| [getImage(Dimension imageSize)](#getImage-java.awt.Dimension-) | Vrací objekt Thumbnail Image se zadanou velikostí. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Vrací objekt Thumbnail tiff image se zadanými parametry. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Vrací objekt Thumbnail Image. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Vrací objekt Thumbnail Image s vlastním škálováním. |
| [getImage(IRenderingOptions options, Dimension imageSize)](#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Vrací objekt Thumbnail Image se zadanou velikostí. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Ukládá obsah snímku jako soubor SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Ukládá obsah snímku jako soubor SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Ukládá obsah snímku jako soubor EMF. |
| [remove()](#remove--) | Odstraňuje snímek z prezentace. |
| [getLayoutSlide()](#getLayoutSlide--) | Vrací nebo nastavuje rozvržení snímku pro aktuální snímek. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Vrací nebo nastavuje rozvržení snímku pro aktuální snímek. |
| [reset()](#reset--) | Resetuje pozici, velikost a formátování každého tvaru, který má prototyp v LayoutSlide. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Umožňuje přístup k poznámkovému snímku, jeho přidání a odebrání. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Vrací všechny komentáře snímku přidané konkrétním autorem. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Spojuje běhy se stejným formátováním ve všech odstavcích ve všech přijatelnych tvarech. |
### getHeaderFooterManager() {#getHeaderFooterManager--}}
```
public final ISlideHeaderFooterManager getHeaderFooterManager()
```


Vrací správce HeaderFooter snímku. Pouze pro čtení [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Vrací:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)
### getThemeManager() {#getThemeManager--}}
```
public final IOverrideThemeManager getThemeManager()
```


Vrací správce přepisujícího motivu. Pouze pro čtení [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Vrací:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getSlideNumber() {#getSlideNumber--}}
```
public final int getSlideNumber()
```


Vrací číslo snímku. Index snímku v kolekci [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) je vždy roven SlideNumber - Presentation.FirstSlideNumber. Čtení/zápis int.

**Vrací:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```


Vrací číslo snímku. Index snímku v kolekci [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) je vždy roven SlideNumber - Presentation.FirstSlideNumber. Čtení/zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getHidden() {#getHidden--}}
```
public final boolean getHidden()
```


Určuje, zda je uvedený snímek během promítání skrytý. Čtení/zápis boolean.

**Vrací:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```


Určuje, zda je uvedený snímek během promítání skrytý. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getShowMasterShapes() {#getShowMasterShapes--}}
```
public boolean getShowMasterShapes()
```


Určuje, zda mají být tvary na hlavním snímku zobrazeny na snímcích, či ne. Čtení/zápis boolean.

**Vrací:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


Určuje, zda mají být tvary na hlavním snímku zobrazeny na snímcích, či ne. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```


Vrací objekt Thumbnail Image s vlastním škálováním.

--------------------

> ```
> The following example shows how to generate thumbnails from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("ThumbnailFromSlide.pptx");
>  try {
>      // Přístup k prvnímu snímku
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Vytvořit obrázek v plném měřítku
>      IImage bmp = sld.getImage(1f, 1f);
>      // Uložit obrázek na disk ve formátu JPEG
>      bmp.save("Thumbnail_out.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to converting slides to bitmap and saving the images in PNG.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Převede první snímek v prezentaci na objekt Bitmap
>      IImage bmp = pres.getSlides().get_Item(0).getImage();
>      // Uloží obrázek ve formátu PNG
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
>          // Vytvořit obrázek v plném měřítku
>          IImage bmp = sld.getImage(1f, 1f);
>          // Uložit obrázek na disk ve formátu JPEG
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
>      // Definovat rozměry
>      int desiredX = 1200;
>      int desiredY = 800;
>      // Získat škálované hodnoty X a Y
>      float ScaleX = (float)(1.0 / pres.getSlideSize().getSize().getWidth()) * desiredX;
>      float ScaleY = (float)(1.0 / pres.getSlideSize().getSize().getHeight()) * desiredY;
>      for (ISlide sld : pres.getSlides())
>      {
>          // Vytvořit obrázek v plném měřítku
>          IImage bmp = sld.getImage(ScaleX, ScaleY);
>          // Uložit obrázek na disk ve formátu JPEG
>          bmp.save("Slide.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| scaleX | float | Hodnota, o kterou se má tento Thumbnail škálovat ve směru osy x. |
| scaleY | float | Hodnota, o kterou se má tento Thumbnail škálovat ve směru osy y. |

**Vrací:**
[IImage](../../com.aspose.slides/iimage) – IImage object.
### getImage() {#getImage--}}
```
public final IImage getImage()
```


Vrací objekt Thumbnail Image (20 % skutečné velikosti).

**Vrací:**
[IImage](../../com.aspose.slides/iimage)
### getImage(Dimension imageSize) {#getImage-java.awt.Dimension-}
```
public final IImage getImage(Dimension imageSize)
```


Vrací objekt Thumbnail Image se zadanou velikostí.

--------------------

> ```
> The following example shows how to converting slides to images with custom sizes using C#.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Převádí první snímek v prezentaci na Bitmap s určenou velikostí
>      IImage bmp = pres.getSlides().get_Item(0).getImage(new Dimension(1820, 1040));
>      // Uloží obrázek ve formátu JPEG
>      bmp.save("Slide_0.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| imageSize | java.awt.Dimension | Velikost obrazu, který se má vytvořit. |

**Vrací:**
[IImage](../../com.aspose.slides/iimage) – Image object.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public final IImage getImage(ITiffOptions options)
```


Vrací objekt Thumbnail tiff image se zadanými parametry.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tiff options. |

**Vrací:**
[IImage](../../com.aspose.slides/iimage) – Image object.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public final IImage getImage(IRenderingOptions options)
```


Vrací objekt Thumbnail Image.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |

**Vrací:**
[IImage](../../com.aspose.slides/iimage) – Image object.
### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```


Vrací objekt Thumbnail Image s vlastním škálováním.

--------------------

> ```
> The following example shows how to converting slides With notes and comments to Images.
>  
>  Presentation pres = new Presentation("PresentationNotesComments.pptx");
>  try {
>      // Vytvořit možnosti vykreslování
>      IRenderingOptions options = new RenderingOptions();
>      // Vytvořit možnosti rozvržení poznámek a komentářů
>      NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
>      // Nastaví pozici poznámek na stránce
>      notesCommentsLayouting.setNotesPosition(NotesPositions.BottomTruncated);
>      // Nastaví pozici komentářů na stránce
>      notesCommentsLayouting.setCommentsPosition(CommentsPositions.Right);
>      // Nastaví šířku výstupní oblasti komentářů
>      notesCommentsLayouting.setCommentsAreaWidth(500);
>      // Nastaví barvu oblasti komentářů
>      notesCommentsLayouting.setCommentsAreaColor(Color.WHITE);
>      // Nastavit možnosti rozvržení pro vykreslování
>      options.setSlidesLayoutOptions(notesCommentsLayouting);
>      // Převede první snímek prezentace na objekt BufferedImage
>      IImage image = pres.getSlides().get_Item(0).getImage(options, 2f, 2f);
>      // Uloží obrázek ve formátu GIF
>      image.save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| scaleX | float | Hodnota, o kterou se má tento Thumbnail škálovat ve směru osy x. |
| scaleY | float | Hodnota, o kterou se má tento Thumbnail škálovat ve směru osy y. |

**Vrací:**
[IImage](../../com.aspose.slides/iimage) – Bitmap objects.
### getImage(IRenderingOptions options, Dimension imageSize) {#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public final IImage getImage(IRenderingOptions options, Dimension imageSize)
```


Vrací objekt Thumbnail Image se zadanou velikostí.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| imageSize | java.awt.Dimension | Velikost obrazu, který se má vytvořit. |

**Vrací:**
[IImage](../../com.aspose.slides/iimage) – Image object.
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```


Ukládá obsah snímku jako soubor SVG.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.svg");
>      {
>          // Uloží první snímek jako soubor SVG
>          pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.OutputStream | Cílový proud |
### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```


Ukládá obsah snímku jako soubor SVG.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file with options.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide1.svg");
>      SVGOptions options = new SVGOptions();
>      options.setVectorizeText(true);
>      // Uloží první snímek jako soubor SVG
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.OutputStream | Cílový proud |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG generation options |
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```


Ukládá obsah snímku jako soubor EMF.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into a metafile.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.emf");
>      {
>          // Uloží první snímek jako metafil
>          pres.getSlides().get_Item(0).writeAsEmf(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.OutputStream | Cílový proud |
### remove() {#remove--}}
```
public final void remove()
```


Odstraňuje snímek z prezentace.

### getLayoutSlide() {#getLayoutSlide--}}
```
public final ILayoutSlide getLayoutSlide()
```


Vrací nebo nastavuje rozvržení snímku pro aktuální snímek. Čtení/zápis [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Vrací:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public final void setLayoutSlide(ILayoutSlide value)
```


Vrací nebo nastavuje rozvržení snímku pro aktuální snímek. Čtení/zápis [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |
### reset() {#reset--}}
```
public final void reset()
```


Resetuje pozici, velikost a formátování každého tvaru, který má prototyp v LayoutSlide.
### getNotesSlideManager() {#getNotesSlideManager--}}
```
public final INotesSlideManager getNotesSlideManager()
```


Umožňuje přístup k poznámkovému snímku, jeho přidání a odebrání. Pouze pro čtení [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Vrací:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public final IComment[] getSlideComments(ICommentAuthor author)
```


Vrací všechny komentáře snímku přidané konkrétním autorem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Autor komentářů k vyhledání nebo null pro vrácení všech komentářů. |

**Vrací:**
com.aspose.slides.IComment[] – pole [Comment](../../com.aspose.slides/comment).
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}}
```
public void joinPortionsWithSameFormatting()
```


Spojuje běhy se stejným formátováním ve všech odstavcích ve všech přijatelnych tvarech.