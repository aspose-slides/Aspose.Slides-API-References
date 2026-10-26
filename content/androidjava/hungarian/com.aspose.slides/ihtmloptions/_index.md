---
title: IHtmlOptions
second_title: Aspose.Slides Androidhoz a Java API hivatkozás szerint
description: HTML exportálási beállításokat képvisel.
type: docs
url: /hu/com.aspose.slides/ihtmloptions/
---
**Minden megvalósított interfész:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtmlOptions extends ISaveOptions
```

HTML exportálási beállításokat képvisel.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getHtmlFormatter()](#getHtmlFormatter--) | Visszaadja vagy beállítja a HTML sablont. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | Visszaadja vagy beállítja a HTML sablont. |
| [getSlideImageFormat()](#getSlideImageFormat--) | Visszaadja vagy beállítja a dia képformátum opcióit. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | Visszaadja vagy beállítja a dia képformátum opcióit. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákot vagy sem. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákot vagy sem. |
| [getJpegQuality()](#getJpegQuality--) | Visszaadja vagy beállítja azt az értéket, amely meghatározza a JPEG képek minőségét a PDF-dokumentumban. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Visszaadja vagy beállítja azt az értéket, amely meghatározza a JPEG képek minőségét a PDF-dokumentumban. |
| [getPicturesCompression()](#getPicturesCompression--) | A képek tömörítési szintjét képviseli Olvasás/írás [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | A képek tömörítési szintjét képviseli Olvasás/írás [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Egy logikai jelző jelzi, hogy a levágott részek a dokumentum részét képezik-e. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Egy logikai jelző jelzi, hogy a levágott részek a dokumentum részét képezik-e. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | Igaz, ha ki szeretné zárni a szélesség és magasság attribútumokat az SVG konténerből – ez reszponzív elrendezést eredményez. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | Igaz, ha ki szeretné zárni a szélesség és magasság attribútumokat az SVG konténerből – ez reszponzív elrendezést eredményez. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Megkapja vagy beállítja azt az értéket, amely azt jelzi, hogy a szöveget ligatúrák használata nélkül renderelik-e. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Megkapja vagy beállítja azt az értéket, amely azt jelzi, hogy a szöveget ligatúrák használata nélkül renderelik-e. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Megkapja vagy beállítja azt a módot, amelyben a diák az oldalon elhelyezésre kerülnek egy prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Megkapja vagy beállítja azt a módot, amelyben a diák az oldalon elhelyezésre kerülnek egy prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Lehetőségeket biztosít, amelyek szabályozzák az Ink objektumok megjelenését az exportált dokumentumban. |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public abstract IHtmlFormatter getHtmlFormatter()
```

Visszaadja vagy beállítja a HTML sablont. Olvasás/írás [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Visszatér:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)

### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public abstract void setHtmlFormatter(IHtmlFormatter value)
```

Visszaadja vagy beállítja a HTML sablont. Olvasás/írás [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public abstract ISlideImageFormat getSlideImageFormat()
```

Visszaadja vagy beállítja a dia képformátum opcióit. Olvasás/írás [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Visszatér:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)

### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public abstract void setSlideImageFormat(ISlideImageFormat value)
```

Visszaadja vagy beállítja a dia képformátum opcióit. Olvasás/írás [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákot vagy sem. Alapértelmezett érték hamis.

**Visszatér:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákot vagy sem. Alapértelmezett érték hamis.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

Visszaadja vagy beállítja azt az értéket, amely meghatározza a JPEG képek minőségét a PDF-dokumentumban. Olvasás/írás byte.

--------------------

Csak akkor van hatása, ha a dokumentum JPEG képeket tartalmaz.

Ezt a tulajdonságot használja a képek minőségének lekérdezésére vagy beállítására, amikor PDF formátumba menti a dokumentumot. Az érték 0-tól 100-ig terjedhet, ahol 0 a legrosszabb minőséget, de maximális tömörítést, 100 pedig a legjobb minőséget, de minimális tömörítést jelent.

Az alapértelmezett érték **95**.

**Visszatér:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

Visszaadja vagy beállítja azt az értéket, amely meghatározza a JPEG képek minőségét a PDF-dokumentumban. Olvasás/írás byte.

--------------------

Csak akkor van hatása, ha a dokumentum JPEG képeket tartalmaz.

Ezt a tulajdonságot használja a képek minőségének lekérdezésére vagy beállítására, amikor PDF formátumba menti a dokumentumot. Az érték 0-tól 100-ig terjedhet, ahol 0 a legrosszabb minőséget, de maximális tömörítést, 100 pedig a legjobb minőséget, de minimális tömörítést jelent.

Az alapértelmezett érték **95**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

A képek tömörítési szintjét képviseli Olvasás/írás [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**Visszatér:**
int

### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

A képek tömörítési szintjét képviseli Olvasás/írás [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

Egy logikai jelző jelzi, hogy a levágott részek a dokumentum részét képezik-e. Ha igaz, a levágott részek eltávolításra kerülnek, ha hamis, akkor a dokumentumban sorosítva maradnak (ami nagyobb fájlméretet eredményezhet). Olvasás/írás boolean.

**Visszatér:**
boolean

### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

Egy logikai jelző jelzi, hogy a levágott részek a dokumentum részét képezik-e. Ha igaz, a levágott részek eltávolításra kerülnek, ha hamis, akkor a dokumentumban sorosítva maradnak (ami nagyobb fájlméretet eredményezhet). Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public abstract boolean getSvgResponsiveLayout()
```

Igaz, ha ki szeretné zárni a szélesség és magasság attribútumokat az SVG konténerből – ez reszponzív elrendezést eredményez. Hamis – egyébként. Olvasás/írás boolean.

**Visszatér:**
boolean

### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public abstract void setSvgResponsiveLayout(boolean value)
```

Igaz, ha ki szeretné zárni a szélesség és magasság attribútumokat az SVG konténerből – ez reszponzív elrendezést eredményez. Hamis – egyébként. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

Megkapja vagy beállítja azt az értéket, amely azt jelzi, hogy a szöveget ligatúrák használata nélkül renderelik-e. Ha igazra van állítva, a ligatúrák le lesznek tiltva a renderelt kimenetben. Alapértelmezés szerint ez a tulajdonság hamis.

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

**Visszatér:**
boolean

### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

Megkapja vagy beállítja azt az értéket, amely azt jelzi, hogy a szöveget ligatúrák használata nélkül renderelik-e. Ha igazra van állítva, a ligatúrák le lesznek tiltva a renderelt kimenetben. Alapértelmezés szerint ez a tulajdonság hamis.

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

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Megkapja vagy beállítja azt a módot, amelyben a diák az oldalon elhelyezésre kerülnek egy prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**Visszatér:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Megkapja vagy beállítja azt a módot, amelyben a diák az oldalon elhelyezésre kerülnek egy prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public abstract IInkOptions getInkOptions()
```

Lehetőségeket biztosít, amelyek szabályozzák az Ink objektumok megjelenését az exportált dokumentumban. Csak olvasás [IInkOptions](../../com.aspose.slides/iinkoptions)

**Visszatér:**
[IInkOptions](../../com.aspose.slides/iinkoptions)