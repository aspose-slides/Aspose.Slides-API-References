---
title: HtmlOptions
second_title: Aspose.Slides Android-hoz Java API referenciája
description: HTML exportálási beállításokat reprezentál.
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

HTML exportálási beállításokat reprezentál.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [HtmlOptions(ILinkEmbedController linkEmbedController)](#HtmlOptions-com.aspose.slides.ILinkEmbedController-) | Létrehoz egy új HtmlOptions objektumot, amely visszahívást definiál. |
| [HtmlOptions()](#HtmlOptions--) | Létrehoz egy új HtmlOptions objektumot egyetlen HTML fájlba mentéshez. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Lekérdezi vagy beállítja azt a módot, ahogy a diák az oldalon elhelyezkednek egy prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Lekérdezi vagy beállítja azt a módot, ahogy a diák az oldalon elhelyezkednek egy prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Lehetőségeket biztosít az exportált dokumentumban található Ink objektumok megjelenésének szabályozásához. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákot vagy sem. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákot vagy sem. |
| [getHtmlFormatter()](#getHtmlFormatter--) | Visszaadja vagy beállítja a HTML sablont. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | Visszaadja vagy beállítja a HTML sablont. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Lekérdezi vagy beállítja azt az értéket, amely jelzi, hogy a szöveg ligatúrák használata nélkül van-e megjelenítve. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Lekérdezi vagy beállítja azt az értéket, amely jelzi, hogy a szöveg ligatúrák használata nélkül van-e megjelenítve. |
| [getSlideImageFormat()](#getSlideImageFormat--) | Visszaadja vagy beállítja a dia képformátum opciókat. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | Visszaadja vagy beállítja a dia képformátum opciókat. |
| [getJpegQuality()](#getJpegQuality--) | Visszaadja vagy beállítja azt az értéket, amely meghatározza a JPEG képek minőségét a PDF dokumentumban. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Visszaadja vagy beállítja azt az értéket, amely meghatározza a JPEG képek minőségét a PDF dokumentumban. |
| [getPicturesCompression()](#getPicturesCompression--) | A képek tömörítési szintjét jelöli |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | A képek tömörítési szintjét jelöli |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Egy boolean jelző, amely azt jelzi, hogy a levágott részek a dokumentum részeként megmaradnak-e. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Egy boolean jelző, amely azt jelzi, hogy a levágott részek a dokumentum részeként megmaradnak-e. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | Igaz, ha a szélesség és magasság attribútumokat ki szeretné zárni az svg konténerből – ez responsív elrendezést eredményez. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | Igaz, ha a szélesség és magasság attribútumokat ki szeretné zárni az svg konténerből – ez responsív elrendezést eredményez. |
### HtmlOptions(ILinkEmbedController linkEmbedController) {#HtmlOptions-com.aspose.slides.ILinkEmbedController-}
```
public HtmlOptions(ILinkEmbedController linkEmbedController)
```

Létrehoz egy új HtmlOptions objektumot, amely visszahívást definiál.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | Visszahívási objektum, amely a projekt mentését irányítja. |

### HtmlOptions() {#HtmlOptions--}
```
public HtmlOptions()
```

Létrehoz egy új HtmlOptions objektumot egyetlen HTML fájlba mentéshez.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Lekérdezi vagy beállítja azt a módot, ahogy a diák az oldalon elhelyezkednek egy prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

Lekérdezi vagy beállítja azt a módot, ahogy a diák az oldalon elhelyezkednek egy prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

Lehetőségeket biztosít az exportált dokumentumban található Ink objektumok megjelenésének szabályozásához. Csak olvasható [IInkOptions](../../com.aspose.slides/iinkoptions)

**Visszatérési érték:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákot vagy sem. Alapértelmezett érték hamis.

**Visszatérési érték:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákot vagy sem. Alapértelmezett érték hamis.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public final IHtmlFormatter getHtmlFormatter()
```

Visszaadja vagy beállítja a HTML sablont. Olvasás/írás [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Visszatérési érték:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public final void setHtmlFormatter(IHtmlFormatter value)
```

Visszaadja vagy beállítja a HTML sablont. Olvasás/írás [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

Lekérdezi vagy beállítja azt az értéket, amely jelzi, hogy a szöveg ligatúrák használata nélkül van-e megjelenítve. Ha igazra állítja, a ligatúrák le lesznek tiltva a megjelenített kimenetben. Alapértelmezés szerint ez a tulajdonság hamis.

--------------------

> ```
> Example:
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

Lekérdezi vagy beállítja azt az értéket, amely jelzi, hogy a szöveg ligatúrák használata nélkül van-e megjelenítve. Ha igazra állítja, a ligatúrák le lesznek tiltva a megjelenített kimenetben. Alapértelmezés szerint ez a tulajdonság hamis.

--------------------

> ```
> Example:
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

Visszaadja vagy beállítja a dia képformátum opciókat. Olvasás/írás [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Visszatérési érték:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public final void setSlideImageFormat(ISlideImageFormat value)
```

Visszaadja vagy beállítja a dia képformátum opciókat. Olvasás/írás [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

Visszaadja vagy beállítja azt az értéket, amely meghatározza a JPEG képek minőségét a PDF dokumentumban. Olvasás/írás byte.

--------------------

Csak akkor van hatása, ha a dokumentum JPEG képeket tartalmaz.

Ezt a tulajdonságot használja a dokumentumban lévő képek minőségének lekérdezésére vagy beállítására PDF formátumban történő mentéskor. Az érték 0 és 100 között változhat, ahol 0 a legrosszabb minőség, de maximális tömörítés, 100 pedig a legjobb minőség, de minimális tömörítés.

Az alapértelmezett érték **95**.

**Visszatérési érték:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

Visszaadja vagy beállítja azt az értéket, amely meghatározza a JPEG képek minőségét a PDF dokumentumban. Olvasás/írás byte.

--------------------

Csak akkor van hatása, ha a dokumentum JPEG képeket tartalmaz.

Ezt a tulajdonságot használja a dokumentumban lévő képek minőségének lekérdezésére vagy beállítására PDF formátumban történő mentéskor. Az érték 0 és 100 között változhat, ahol 0 a legrosszabb minőség, de maximális tömörítés, 100 pedig a legjobb minőség, de minimális tömörítés.

Az alapértelmezett érték **95**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

A képek tömörítési szintjét jelöli

**Visszatérési érték:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

A képek tömörítési szintjét jelöli

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

Egy boolean jelző, amely azt jelzi, hogy a levágott részek a dokumentum részeként megmaradnak-e. Ha igaz, a levágott részek eltávolításra kerülnek, ha hamis, akkor a dokumentumban lesznek sorosítva (ami nagyobb fájlt eredményezhet).

**Visszatérési érték:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

Egy boolean jelző, amely azt jelzi, hogy a levágott részek a dokumentum részeként megmaradnak-e. Ha igaz, a levágott részek eltávolításra kerülnek, ha hamis, akkor a dokumentumban lesznek sorosítva (ami nagyobb fájlt eredményezhet).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public final boolean getSvgResponsiveLayout()
```

Igaz, ha a szélesség és magasság attribútumokat ki szeretné zárni az svg konténerből – ez responsív elrendezést eredményez. Hamis – egyébként. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public final void setSvgResponsiveLayout(boolean value)
```

Igaz, ha a szélesség és magasság attribútumokat ki szeretné zárni az svg konténerből – ez responsív elrendezést eredményez. Hamis – egyébként. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |