---
title: HtmlOptions
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een HTML-exportoptie voor.
type: docs
url: /nl/com.aspose.slides/htmloptions/
---
**Overerving:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IHtmlOptions](../../com.aspose.slides/ihtmloptions)
```
public class HtmlOptions extends SaveOptions implements IHtmlOptions
```

Stelt een HTML-exportoptie voor.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [HtmlOptions(ILinkEmbedController linkEmbedController)](#HtmlOptions-com.aspose.slides.ILinkEmbedController-) | Maakt een nieuw HtmlOptions-object dat een callback specificeert. |
| [HtmlOptions()](#HtmlOptions--) | Maakt een nieuw HtmlOptions-object voor het opslaan in één HTML-bestand. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Haalt de modus op of stelt deze in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Haalt de modus op of stelt deze in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document regelen. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. |
| [getHtmlFormatter()](#getHtmlFormatter--) | Retourneert of stelt de HTML-sjabloon in. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | Retourneert of stelt de HTML-sjabloon in. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Haalt een waarde op of stelt deze in die aangeeft of tekst wordt gerenderd zonder ligaturen te gebruiken. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of tekst wordt gerenderd zonder ligaturen te gebruiken. |
| [getSlideImageFormat()](#getSlideImageFormat--) | Retourneert of stelt de opties voor het dia-afbeeldingsformaat in. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | Retourneert of stelt de opties voor het dia-afbeeldingsformaat in. |
| [getJpegQuality()](#getJpegQuality--) | Retourneert of stelt een waarde in die de kwaliteit van JPEG-afbeeldingen in een PDF-document bepaalt. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Retourneert of stelt een waarde in die de kwaliteit van JPEG-afbeeldingen in een PDF-document bepaalt. |
| [getPicturesCompression()](#getPicturesCompression--) | Stelt het compressieniveau van afbeeldingen voor |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Stelt het compressieniveau van afbeeldingen voor |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Een booleanvlag geeft aan of de bijgesneden delen deel blijven uitmaken van het document. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Een booleanvlag geeft aan of de bijgesneden delen deel blijven uitmaken van het document. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | True om breedte- en hoogteachters uit de svg-container te verwijderen - dit maakt de lay-out responsief. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | True om breedte- en hoogteachters uit de svg-container te verwijderen - dit maakt de lay-out responsief. |
### HtmlOptions(ILinkEmbedController linkEmbedController) {#HtmlOptions-com.aspose.slides.ILinkEmbedController-}
```
public HtmlOptions(ILinkEmbedController linkEmbedController)
```

Maakt een nieuw HtmlOptions-object dat een callback specificeert.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | Callback-object dat het opslaan van het project beheert. |

### HtmlOptions() {#HtmlOptions--}
```
public HtmlOptions()
```

Maakt een nieuw HtmlOptions-object voor het opslaan in één HTML-bestand.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Haalt de modus op of stelt deze in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**Retourneert:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Haalt de modus op of stelt deze in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document regelen. Alleen-lezen [IInkOptions](../../com.aspose.slides/iinkoptions)

**Retourneert:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is false.

**Retourneert:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public final IHtmlFormatter getHtmlFormatter()
```

Retourneert of stelt de HTML-sjabloon in. Lezen/Schrijven [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Retourneert:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public final void setHtmlFormatter(IHtmlFormatter value)
```

Retourneert of stelt de HTML-sjabloon in. Lezen/Schrijven [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

Haalt een waarde op of stelt deze in die aangeeft of tekst wordt gerenderd zonder ligaturen te gebruiken. Wanneer ingesteld op true, worden ligaturen uitgeschakeld in de gerenderde uitvoer. Standaard is deze eigenschap false.

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

**Retourneert:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

Haalt een waarde op of stelt deze in die aangeeft of tekst wordt gerenderd zonder ligaturen te gebruiken. Wanneer ingesteld op true, worden ligaturen uitgeschakeld in de gerenderde uitvoer. Standaard is deze eigenschap false.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public final ISlideImageFormat getSlideImageFormat()
```

Retourneert of stelt de opties voor het dia-afbeeldingsformaat in. Lezen/Schrijven [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Retourneert:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public final void setSlideImageFormat(ISlideImageFormat value)
```

Retourneert of stelt de opties voor het dia-afbeeldingsformaat in. Lezen/Schrijven [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

Retourneert of stelt een waarde in die de kwaliteit van JPEG-afbeeldingen in een PDF-document bepaalt. Lezen/Schrijven byte.

--------------------

Heeft alleen effect wanneer een document JPEG-afbeeldingen bevat.

Gebruik deze eigenschap om de kwaliteit van de afbeeldingen in een document te krijgen of in te stellen bij het opslaan in PDF-formaat. De waarde kan variëren van 0 tot 100 waarbij 0 de slechtste kwaliteit maar maximale compressie betekent en 100 de beste kwaliteit maar minimale compressie.

De standaardwaarde is **95**.

**Retourneert:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

Retourneert of stelt een waarde in die de kwaliteit van JPEG-afbeeldingen in een PDF-document bepaalt. Lezen/Schrijven byte.

--------------------

Heeft alleen effect wanneer een document JPEG-afbeeldingen bevat.

Gebruik deze eigenschap om de kwaliteit van de afbeeldingen in een document te krijgen of in te stellen bij het opslaan in PDF-formaat. De waarde kan variëren van 0 tot 100 waarbij 0 de slechtste kwaliteit maar maximale compressie betekent en 100 de beste kwaliteit maar minimale compressie.

De standaardwaarde is **95**.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

Stelt het compressieniveau van afbeeldingen voor

**Retourneert:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

Stelt het compressieniveau van afbeeldingen voor

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

Een booleanvlag geeft aan of de bijgesneden delen deel blijven uitmaken van het document. Als true worden de bijgesneden delen verwijderd, als false worden ze geserialiseerd in het document (wat mogelijk kan leiden tot een groter bestand)

**Retourneert:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

Een booleanvlag geeft aan of de bijgesneden delen deel blijven uitmaken van het document. Als true worden de bijgesneden delen verwijderd, als false worden ze geserialiseerd in het document (wat mogelijk kan leiden tot een groter bestand)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public final boolean getSvgResponsiveLayout()
```

True om breedte- en hoogteachters uit de svg-container te verwijderen - dit maakt de lay-out responsief. False - anders. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public final void setSvgResponsiveLayout(boolean value)
```

True om breedte- en hoogteachters uit de svg-container te verwijderen - dit maakt de lay-out responsief. False - anders. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |