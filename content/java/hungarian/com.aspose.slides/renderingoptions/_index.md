---
title: RenderingOptions
second_title: Aspose.Slides for Java API-referencia
description: Lehetőségeket biztosít, amelyek szabályozzák, hogyan jelenik meg egy prezentáció/ dia.
type: docs
url: /hu/com.aspose.slides/renderingoptions/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Minden megvalósított interfész:**
[com.aspose.slides.IRenderingOptions](../../com.aspose.slides/irenderingoptions)
```
public class RenderingOptions extends SaveOptions implements IRenderingOptions
```

Lehetőségeket biztosít, amelyek szabályozzák, hogyan jelenik meg egy prezentáció/ dia.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      IRenderingOptions renderingOpts = new RenderingOptions();
>      renderingOpts.getNotesCommentsLayouting().setNotesPosition(NotesPositions.BottomTruncated);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(renderingOpts), "PNG", new File("pres-Original.png"));
> 
>      renderingOpts.setDefaultRegularFont("Arial Black");
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(renderingOpts), "PNG", new File("pres-ArialBlackDefault.png"));
> 
>      renderingOpts.setDefaultRegularFont("Arial Narrow");
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(renderingOpts), "PNG", new File("pres-ArialNarrowDefault.png"));
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [RenderingOptions()](#RenderingOptions--) | Alapértelmezett konstruktor. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Lekérdezi vagy beállítja a módot, ahogyan a diák az oldalon kerülnek elhelyezésre prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Lekérdezi vagy beállítja a módot, ahogyan a diák az oldalon kerülnek elhelyezésre prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Lehetőségeket biztosít, amelyek szabályozzák az Ink objektumok megjelenését az exportált dokumentumban. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Lekérdezi vagy beállítja azt az értéket, amely jelzi, hogy a szöveg ligatúrák használata nélkül van-e megjelenítve. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Lekérdezi vagy beállítja azt az értéket, amely jelzi, hogy a szöveg ligatúrák használata nélkül van-e megjelenítve. |
### RenderingOptions() {#RenderingOptions--}
```
public RenderingOptions()
```


Alapértelmezett konstruktor.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```


Lekérdezi vagy beállítja a módot, ahogyan a diák az oldalon kerülnek elhelyezésre prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
> 
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintSlideNumbers(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      BufferedImage[] handoutSlides = pres.getThumbnails(options);
>      for (int index = 0; index < handoutSlides.length; index++)
>      {
>          ImageIO.write(handoutSlides[index], "PNG", new java.io.File("handout-" + index + ".png"));
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


Lekérdezi vagy beállítja a módot, ahogyan a diák az oldalon kerülnek elhelyezésre prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
> 
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintSlideNumbers(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      BufferedImage[] handoffSlides = pres.getThumbnails(options);
>      for (int index = 0; index < handoffSlides.length; index++)
>      {
>          ImageIO.write(handoffSlides[index], "PNG", new java.io.File("handout-" + index + ".png"));
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```


Lehetőségeket biztosít, amelyek szabályozzák az Ink objektumok megjelenését az exportált dokumentumban. Csak olvasható [IInkOptions](../../com.aspose.slides/iinkoptions)

**Visszatér:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```


Lekérdezi vagy beállítja azt az értéket, amely jelzi, hogy a szöveg ligatúrák használata nélkül van-e megjelenítve. Ha true-ra van állítva, a ligatúrák le lesznek tiltva a megjelenített kimenetben. Alapértelmezés szerint ez a tulajdonság false értékre van beállítva.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      options.setDisableFontLigatures(true);
> 
>      IImage[] renderedSlides = pres.getImages(options);
>      for (int index = 0; index < renderedSlides.length; index++)
>      {
>          IImage slideImage = renderedSlides[index];
>          slideImage.save("slide-" + index + ".png");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```


Lekérdezi vagy beállítja azt az értéket, amely jelzi, hogy a szöveg ligatúrák használata nélkül van-e megjelenítve. Ha true-ra van állítva, a ligatúrák le lesznek tiltva a megjelenített kimenetben. Alapértelmezés szerint ez a tulajdonság false értékre van beállítva.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      options.setDisableFontLigatures(true);
> 
>      IImage[] renderedSlides = pres.getImages(options);
>      for (int index = 0; index < renderedSlides.length; index++)
>      {
>          IImage slideImage = renderedSlides[index];
>          slideImage.save("slide-" + index + ".png");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |