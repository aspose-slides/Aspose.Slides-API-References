---
title: HtmlOptions
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar alternativ för HTML-export.
type: docs
url: /sv/com.aspose.slides/htmloptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**All Implemented Interfaces:**
[com.aspose.slides.IHtmlOptions](../../com.aspose.slides/ihtmloptions)
```
public class HtmlOptions extends SaveOptions implements IHtmlOptions
```

Representerar HTML-exportalternativ.
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [HtmlOptions(ILinkEmbedController linkEmbedController)](#HtmlOptions-com.aspose.slides.ILinkEmbedController-) | Skapar ett nytt HtmlOptions-objekt som specificerar en återanropning. |
| [HtmlOptions()](#HtmlOptions--) | Skapar ett nytt HtmlOptions-objekt för att spara i en enda HTML-fil. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Hämtar eller anger läget där bildspel placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Hämtar eller anger läget där bildspel placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Tillhandahåller alternativ som styr utseendet på Ink-objekt i det exporterade dokumentet. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Anger om det genererade dokumentet ska innehålla dolda bildspel eller inte. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Anger om det genererade dokumentet ska innehålla dolda bildspel eller inte. |
| [getHtmlFormatter()](#getHtmlFormatter--) | Hämtar eller anger HTML-mall. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | Hämtar eller anger HTML-mall. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Hämtar eller anger ett värde som indikerar om text renderas utan ligaturer. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Hämtar eller anger ett värde som indikerar om text renderas utan ligaturer. |
| [getSlideImageFormat()](#getSlideImageFormat--) | Hämtar eller anger alternativ för bildspels bildformat. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | Hämtar eller anger alternativ för bildspels bildformat. |
| [getJpegQuality()](#getJpegQuality--) | Hämtar eller anger ett värde som bestämmer kvaliteten på JPEG-bilder i PDF-dokumentet. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Hämtar eller anger ett värde som bestämmer kvaliteten på JPEG-bilder i PDF-dokumentet. |
| [getPicturesCompression()](#getPicturesCompression--) | Representerar komprimeringsnivån för bilder |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Representerar komprimeringsnivån för bilder |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | En boolesk flagga indikerar om de beskurna delarna förblir en del av dokumentet. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | En boolesk flagga indikerar om de beskurna delarna förblir en del av dokumentet. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | Sant för att utesluta bredd- och höjdattribut från SVG-behållaren – detta gör layouten responsiv. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | Sant för att utesluta bredd- och höjdattribut från SVG-behållaren – detta gör layouten responsiv. |
### HtmlOptions(ILinkEmbedController linkEmbedController) {#HtmlOptions-com.aspose.slides.ILinkEmbedController-}
```
public HtmlOptions(ILinkEmbedController linkEmbedController)
```


Skapar ett nytt HtmlOptions-objekt som specificerar en återanropning.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | Återanropsobjekt som styr sparande av projektet. |

### HtmlOptions() {#HtmlOptions--}
```
public HtmlOptions()
```


Skapar ett nytt HtmlOptions-objekt för att spara i en enda HTML-fil.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```


Hämtar eller anger läget där bildspel placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


Hämtar eller anger läget där bildspel placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public final IInkOptions getInkOptions()
```


Tillhandahåller alternativ som styr utseendet på Ink-objekt i det exporterade dokumentet. Skrivskyddad [IInkOptions](../../com.aspose.slides/iinkoptions)

**Returnerar:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Anger om det genererade dokumentet ska innehålla dolda bildspel eller inte. Standardvärdet är false.

**Returnerar:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Anger om det genererade dokumentet ska innehålla dolda bildspel eller inte. Standardvärdet är false.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public final IHtmlFormatter getHtmlFormatter()
```


Hämtar eller anger HTML-mall. Läs/skriv [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Returnerar:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public final void setHtmlFormatter(IHtmlFormatter value)
```


Hämtar eller anger HTML-mall. Läs/skriv [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```


Hämtar eller anger ett värde som indikerar om text renderas utan ligaturer. När den är satt till true, kommer ligaturer att inaktiveras i den renderade utskriften. Som standard är egenskapen satt till false.

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
public final void setDisableFontLigatures(boolean value)
```


Hämtar eller anger ett värde som indikerar om text renderas utan ligaturer. När den är satt till true, kommer ligaturer att inaktiveras i den renderade utskriften. Som standard är egenskapen satt till false.

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

### getSlideImageFormat() {#getSlideImageFormat--}
```
public final ISlideImageFormat getSlideImageFormat()
```


Hämtar eller anger alternativ för bildspelets bildformat. Läs/skriv [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Returnerar:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public final void setSlideImageFormat(ISlideImageFormat value)
```


Hämtar eller anger alternativ för bildspelets bildformat. Läs/skriv [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```


Hämtar eller anger ett värde som bestämmer kvaliteten på JPEG-bilder i PDF-dokumentet. Läs/skriv byte.

--------------------

Har effekt endast när ett dokument innehåller JPEG-bilder.

Använd den här egenskapen för att hämta eller ange kvaliteten på bilder i ett dokument när du sparar i PDF-format. Värdet kan variera från 0 till 100 där 0 betyder sämst kvalitet men maximal komprimering och 100 betyder bästa kvalitet men minimal komprimering.

Standardvärdet är **95**.

**Returnerar:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```


Hämtar eller anger ett värde som bestämmer kvaliteten på JPEG-bilder i PDF-dokumentet. Läs/skriv byte.

--------------------

Har effekt endast när ett dokument innehåller JPEG-bilder.

Använd den här egenskapen för att hämta eller ange kvaliteten på bilder i ett dokument när du sparar i PDF-format. Värdet kan variera från 0 till 100 där 0 betyder sämst kvalitet men maximal komprimering och 100 betyder bästa kvalitet men minimal komprimering.

Standardvärdet är **95**.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```


Representerar komprimeringsnivån för bilder

**Returnerar:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```


Representerar komprimeringsnivån för bilder

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```


En boolesk flagga indikerar om de beskurna delarna förblir en del av dokumentet. Om true tas de beskurna delarna bort, om false kommer de att serialiseras i dokumentet (vilket kan leda till en större fil)

**Returnerar:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```


En boolesk flagga indikerar om de beskurna delarna förblir en del av dokumentet. Om true tas de beskurna delarna bort, om false kommer de att serialiseras i dokumentet (vilket kan leda till en större fil)

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public final boolean getSvgResponsiveLayout()
```


Sant för att utesluta bredd- och höjdattribut från SVG-behållaren – detta gör layouten responsiv. Falskt – annars. Läs/skriv boolesk.

**Returnerar:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public final void setSvgResponsiveLayout(boolean value)
```


Sant för att utesluta bredd- och höjdattribut från SVG-behållaren – detta gör layouten responsiv. Falskt – annars. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |