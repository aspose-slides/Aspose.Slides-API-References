---
title: IHtmlOptions
second_title: Aspose.Slides för Java API-referens
description: Representerar ett HTML-exportalternativ.
type: docs
url: /sv/com.aspose.slides/ihtmloptions/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtmlOptions extends ISaveOptions
```

Representerar HTML-exportalternativ.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getHtmlFormatter()](#getHtmlFormatter--) | Returnerar eller anger HTML-mall. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | Returnerar eller anger HTML-mall. |
| [getSlideImageFormat()](#getSlideImageFormat--) | Returnerar eller anger bildformatalternativ för bildspel. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | Returnerar eller anger bildformatalternativ för bildspel. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Anger om det genererade dokumentet ska inkludera dolda bildspel eller inte. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Anger om det genererade dokumentet ska inkludera dolda bildspel eller inte. |
| [getJpegQuality()](#getJpegQuality--) | Returnerar eller anger ett värde som bestämmer kvaliteten på JPEG-bilder i PDF-dokument. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Returnerar eller anger ett värde som bestämmer kvaliteten på JPEG-bilder i PDF-dokument. |
| [getPicturesCompression()](#getPicturesCompression--) | Representerar komprimeringsnivå för bilder Läs/skriv [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Representerar komprimeringsnivå för bilder Läs/skriv [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | En boolesk flagga indikerar om de beskärda delarna förblir som en del av dokumentet. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | En boolesk flagga indikerar om de beskärda delarna förblir som en del av dokumentet. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | Sant för att utesluta bredd- och höjdattribut från SVG-behållaren – detta gör layouten responsiv. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | Sant för att utesluta bredd- och höjdattribut från SVG-behållaren – detta gör layouten responsiv. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Returnerar eller anger ett värde som indikerar om text renderas utan att använda ligaturer. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Returnerar eller anger ett värde som indikerar om text renderas utan att använda ligaturer. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Returnerar eller anger läget som bildspelen placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Returnerar eller anger läget som bildspelen placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Tillhandahåller alternativ som styr utseendet på bläckobjekt i exporterat dokument. |
### getHtmlFormatter() {#getHtmlFormatter--}
```
public abstract IHtmlFormatter getHtmlFormatter()
```


Returnerar eller anger HTML-mall. Läs/skriv [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Returnerar:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public abstract void setHtmlFormatter(IHtmlFormatter value)
```


Returnerar eller anger HTML-mall. Läs/skriv [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public abstract ISlideImageFormat getSlideImageFormat()
```


Returnerar eller anger bildformatalternativ för bildspel. Läs/skriv [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Returnerar:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public abstract void setSlideImageFormat(ISlideImageFormat value)
```


Returnerar eller anger bildformatalternativ för bildspel. Läs/skriv [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```


Anger om det genererade dokumentet ska inkludera dolda bildspel eller inte. Standardvärdet är false.

**Returnerar:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```


Anger om det genererade dokumentet ska inkludera dolda bildspel eller inte. Standardvärdet är false.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```


Returnerar eller anger ett värde som bestämmer kvaliteten på JPEG-bilder i PDF-dokument. Läs/skriv byte.

--------------------

Har endast effekt när ett dokument innehåller JPEG-bilder.

Använd den här egenskapen för att hämta eller ange kvaliteten på bilderna i ett dokument vid sparande i PDF-format. Värdet kan variera från 0 till 100 där 0 betyder sämst kvalitet men maximal komprimering och 100 betyder bästa kvalitet men minimal komprimering.

Standardvärdet är **95**.

**Returnerar:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```


Returnerar eller anger ett värde som bestämmer kvaliteten på JPEG-bilder i PDF-dokument. Läs/skriv byte.

--------------------

Har endast effekt när ett dokument innehåller JPEG-bilder.

Använd den här egenskapen för att hämta eller ange kvaliteten på bilderna i ett dokument vid sparande i PDF-format. Värdet kan variera från 0 till 100 där 0 betyder sämst kvalitet men maximal komprimering och 100 betyder bästa kvalitet men minimal komprimering.

Standardvärdet är **95**.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```


Representerar komprimeringsnivå för bilder Läs/skriv [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**Returnerar:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```


Representerar komprimeringsnivå för bilder Läs/skriv [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```


En boolesk flagga indikerar om de beskärda delarna förblir som en del av dokumentet. Om true tas de beskärda delarna bort, om false kommer de att serialiseras i dokumentet (vilket kan leda till en större fil) Läs/skriv boolean.

**Returnerar:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```


En boolesk flagga indikerar om de beskärda delarna förblir som en del av dokumentet. Om true tas de beskärda delarna bort, om false kommer de att serialiseras i dokumentet (vilket kan leda till en större fil) Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public abstract boolean getSvgResponsiveLayout()
```


Sant för att utesluta bredd- och höjdattribut från SVG-behållaren – detta gör layouten responsiv. Falskt – annars. Läs/skriv boolean.

**Returnerar:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public abstract void setSvgResponsiveLayout(boolean value)
```


Sant för att utesluta bredd- och höjdattribut från SVG-behållaren – detta gör layouten responsiv. Falskt – annars. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```


Returnerar eller anger ett värde som indikerar om text renderas utan att använda ligaturer. När satt till true kommer ligaturer att inaktiveras i den renderade utdata. Som standard är denna egenskap satt till false.

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

**Returnerar:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```


Returnerar eller anger ett värde som indikerar om text renderas utan att använda ligaturer. När satt till true kommer ligaturer att inaktiveras i den renderade utdata. Som standard är denna egenskap satt till false.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```


Returnerar eller anger läget som bildspelen placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**Returnerar:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


Returnerar eller anger läget som bildspelen placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```


Tillhandahåller alternativ som styr utseendet på bläckobjekt i exporterat dokument. Endast läsning [IInkOptions](../../com.aspose.slides/iinkoptions)

**Returnerar:**
[IInkOptions](../../com.aspose.slides/iinkoptions)