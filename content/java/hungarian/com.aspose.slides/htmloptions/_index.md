---
title: HtmlOptions
second_title: Aspose.Slides Java API Referencia
description: HTML exportálási beállításokat képvisel.
type: docs
url: /hu/com.aspose.slides/htmloptions/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Minden megvalósított interfész:**
[com.aspose.slides.IHtmlOptions](../../com.aspose.slides/ihtmloptions)
```
public class HtmlOptions extends SaveOptions implements IHtmlOptions
```

HTML exportálási beállításokat képvisel.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [HtmlOptions(ILinkEmbedController linkEmbedController)](#HtmlOptions-com.aspose.slides.ILinkEmbedController-) | Létrehoz egy új HtmlOptions objektumot, amely meghatározza a visszahívást. |
| [HtmlOptions()](#HtmlOptions--) | Létrehoz egy új HtmlOptions objektumot egyetlen HTML fájlba mentéshez. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Megkapja vagy beállítja azt a módot, ahogyan a diák az oldalon elhelyezkednek egy prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Megkapja vagy beállítja azt a módot, ahogyan a diák az oldalon elhelyezkednek egy prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Beállításokat biztosít, amelyek szabályozzák az Ink objektumok megjelenését az exportált dokumentumban. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákat vagy sem. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákat vagy sem. |
| [getHtmlFormatter()](#getHtmlFormatter--) | Visszaadja vagy beállítja a HTML sablont. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | Visszaadja vagy beállítja a HTML sablont. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Megkapja vagy beállítja azt az értéket, amely jelzi, hogy a szöveg ligatúrák használata nélkül kerül-e renderelésre. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Megkapja vagy beállítja azt az értéket, amely jelzi, hogy a szöveg ligatúrák használata nélkül kerül-e renderelésre. |
| [getSlideImageFormat()](#getSlideImageFormat--) | Visszaadja vagy beállítja a diakép formátum beállításokat. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | Visszaadja vagy beállítja a diakép formátum beállításokat. |
| [getJpegQuality()](#getJpegQuality--) | Visszaadja vagy beállítja azt az értéket, amely meghatározza a JPEG képek minőségét a PDF dokumentumban. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Visszaadja vagy beállítja azt az értéket, amely meghatározza a JPEG képek minőségét a PDF dokumentumban. |
| [getPicturesCompression()](#getPicturesCompression--) | A képek tömörítési szintjét képviseli |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | A képek tömörítési szintjét képviseli |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Egy logikai jelző, amely jelzi, hogy a vágott részek a dokumentum részét képezik-e. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Egy logikai jelző, amely jelzi, hogy a vágott részek a dokumentum részét képezik-e. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | Igaz, ha a szélesség és magasság attribútumokat ki kell hagyni az svg konténerből – ez választható elrendezést eredményez. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | Igaz, ha a szélesség és magasság attribútumokat ki kell hagyni az svg konténerből – ez választható elrendezést eredményez. |
### HtmlOptions(ILinkEmbedController linkEmbedController) {#HtmlOptions-com.aspose.slides.ILinkEmbedController-}
```
public HtmlOptions(ILinkEmbedController linkEmbedController)
```

Létrehoz egy új HtmlOptions objektumot, amely meghatározza a visszahívást.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | Callback object which controls saving project. |

### HtmlOptions() {#HtmlOptions--}
```
public HtmlOptions()
```

Létrehoz egy új HtmlOptions objektumot egyetlen HTML fájlba mentéshez.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Megkapja vagy beállítja azt a módot, ahogyan a diák az oldalon elhelyezkednek egy prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatérési érték:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Megkapja vagy beállítja azt a módot, ahogyan a diák az oldalon elhelyezkednek egy prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.html", SaveFormat.Html, options);
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

Beállításokat biztosít, amelyek szabályozzák az Ink objektumok megjelenését az exportált dokumentumban. Csak olvasható [IInkOptions](../../com.aspose.slides/iinkoptions)

**Visszatérési érték:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákat vagy sem. Alapértelmezett érték: false.

**Visszatérési érték:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákat vagy sem. Alapértelmezett érték: false.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public final IHtmlFormatter getHtmlFormatter()
```

Visszaadja vagy beállítja a HTML sablont. Olvasható/írható [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Visszatérési érték:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public final void setHtmlFormatter(IHtmlFormatter value)
```

Visszaadja vagy beállítja a HTML sablont. Olvasható/írható [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

Megkapja vagy beállítja azt az értéket, amely jelzi, hogy a szöveg ligatúrák használata nélkül kerül-e renderelésre. Ha igazra van állítva, a ligatúrák le lesznek tiltva a megjelenített kimenetben. Alapértelmezés szerint ez a tulajdonság false.

--------------------

> ```
> Példa:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      options.setDisableFontLigatures(true);
>      pres.save("presentation.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatérési érték:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

Megkapja vagy beállítja azt az értéket, amely jelzi, hogy a szöveg ligatúrák használata nélkül kerül-e renderelésre. Ha igazra van állítva, a ligatúrák le lesznek tiltva a megjelenített kimenetben. Alapértelmezés szerint ez a tulajdonság false.

--------------------

> ```
> Példa:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      options.setDisableFontLigatures(true);
>      pres.save("presentation.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public final ISlideImageFormat getSlideImageFormat()
```

Visszaadja vagy beállítja a diakép formátum beállításokat. Olvasható/írható [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Visszatérési érték:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public final void setSlideImageFormat(ISlideImageFormat value)
```

Visszaadja vagy beállítja a diakép formátum beállításokat. Olvasható/írható [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

Visszaadja vagy beállítja azt az értéket, amely meghatározza a JPEG képek minőségét a PDF dokumentumban. Olvasható/írható byte.

**Visszatérési érték:**
byte

Csak akkor hatással van, ha a dokumentum JPEG képeket tartalmaz.

Ezt a tulajdonságot a dokumentum képeinek minőségének lekérdezésére vagy beállítására használja PDF formátumban mentéskor. Az érték 0 és 100 között változhat, ahol 0 a legrosszabb minőséget, de maximális tömörítést jelent, és 100 a legjobb minőséget, de minimális tömörítést.

Az alapértelmezett érték **95**.

**Visszatérési érték:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

Visszaadja vagy beállítja azt az értéket, amely meghatározza a JPEG képek minőségét a PDF dokumentumban. Olvasható/írható byte.

Csak akkor hatással van, ha a dokumentum JPEG képeket tartalmaz.

Ezt a tulajdonságot a dokumentum képeinek minőségének lekérdezésére vagy beállítására használja PDF formátumban mentéskor. Az érték 0 és 100 között változhat, ahol 0 a legrosszabb minőséget, de maximális tömörítést jelent, és 100 a legjobb minőséget, de minimális tömörítést.

Az alapértelmezett érték **95**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

A képek tömörítési szintjét képviseli

**Visszatérési érték:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

A képek tömörítési szintjét képviseli

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

Egy logikai jelző, amely jelzi, hogy a vágott részek a dokumentum részét képezik-e. Ha igaz, a vágott részek eltávolításra kerülnek, ha hamis, a dokumentumban lesznek sorosítva (ami nagyobb fájlhoz vezethet).

**Visszatérési érték:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

Egy logikai jelző, amely jelzi, hogy a vágott részek a dokumentum részét képezik-e. Ha igaz, a vágott részek eltávolításra kerülnek, ha hamis, a dokumentumban lesznek sorosítva (ami nagyobb fájlhoz vezethet).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public final boolean getSvgResponsiveLayout()
```

Igaz, ha a szélesség és magasság attribútumokat kizárja az svg konténerből – ez responszív elrendezést eredményez. Hamis – egyébként. Olvasható/írható logikai.

**Visszatérési érték:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public final void setSvgResponsiveLayout(boolean value)
```

Igaz, ha a szélesség és magasság attribútumokat kizárja az svg konténerből – ez responszív elrendezést eredményez. Hamis – egyébként. Olvasható/írható logikai.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |