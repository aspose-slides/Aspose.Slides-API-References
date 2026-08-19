---
title: IHtmlOptions
second_title: Aspose.Slides voor Java API-referentie
description: Stelt HTML-exportopties voor.
type: docs
url: /nl/com.aspose.slides/ihtmloptions/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtmlOptions extends ISaveOptions
```

Beeldt HTML-exportopties uit.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getHtmlFormatter()](#getHtmlFormatter--) | Retourneert of stelt HTML-sjabloon in. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | Retourneert of stelt HTML-sjabloon in. |
| [getSlideImageFormat()](#getSlideImageFormat--) | Retourneert of stelt opties voor dia-afbeeldingsformaat in. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | Retourneert of stelt opties voor dia-afbeeldingsformaat in. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. |
| [getJpegQuality()](#getJpegQuality--) | Retourneert of stelt een waarde in die de kwaliteit van JPEG-afbeeldingen in een PDF-document bepaalt. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Retourneert of stelt een waarde in die de kwaliteit van JPEG-afbeeldingen in een PDF-document bepaalt. |
| [getPicturesCompression()](#getPicturesCompression--) | Vertegenwoordigt het compressieniveau van afbeeldingen Lezen/Schrijven [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Vertegenwoordigt het compressieniveau van afbeeldingen Lezen/Schrijven [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Een boolean-vlag geeft aan of de bijgesneden delen als onderdeel van het document blijven. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Een boolean-vlag geeft aan of de bijgesneden delen als onderdeel van het document blijven. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | True om breedte- en hoogte-attributen uit de SVG-container uit te sluiten – dit maakt de lay-out responsief. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | True om breedte- en hoogte-attributen uit de SVG-container uit te sluiten – dit maakt de lay-out responsief. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Haalt of stelt een waarde in die aangeeft of tekst wordt gerenderd zonder ligaturen. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Haalt of stelt een waarde in die aangeeft of tekst wordt gerenderd zonder ligaturen. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Haalt of stelt de modus waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) in. |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Haalt of stelt de modus waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) in. |
| [getInkOptions()](#getInkOptions--) | Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document regelen. |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public abstract IHtmlFormatter getHtmlFormatter()
```

Retourneert of stelt HTML-sjabloon in. Lezen/Schrijven [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Retour:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public abstract void setHtmlFormatter(IHtmlFormatter value)
```

Retourneert of stelt HTML-sjabloon in. Lezen/Schrijven [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public abstract ISlideImageFormat getSlideImageFormat()
```

Retourneert of stelt opties voor dia-afbeeldingsformaat in. Lezen/Schrijven [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Retour:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public abstract void setSlideImageFormat(ISlideImageFormat value)
```

Retourneert of stelt opties voor dia-afbeeldingsformaat in. Lezen/Schrijven [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is false.

**Retour:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

Retourneert of stelt een waarde in die de kwaliteit van JPEG-afbeeldingen in een PDF-document bepaalt. Lezen/Schrijven byte.

--------------------

Heeft alleen effect wanneer een document JPEG-afbeeldingen bevat.

Gebruik deze eigenschap om de kwaliteit van de afbeeldingen in een document in te stellen of op te vragen bij het opslaan in PDF-formaat. De waarde kan variëren van 0 tot 100, waarbij 0 de slechtste kwaliteit maar maximale compressie betekent en 100 de beste kwaliteit maar minimale compressie.

De standaardwaarde is **95**.

**Retour:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

Retourneert of stelt een waarde in die de kwaliteit van JPEG-afbeeldingen in een PDF-document bepaalt. Lezen/Schrijven byte.

--------------------

Heeft alleen effect wanneer een document JPEG-afbeeldingen bevat.

Gebruik deze eigenschap om de kwaliteit van de afbeeldingen in een document in te stellen of op te vragen bij het opslaan in PDF-formaat. De waarde kan variëren van 0 tot 100, waarbij 0 de slechtste kwaliteit maar maximale compressie betekent en 100 de beste kwaliteit maar minimale compressie.

De standaardwaarde is **95**.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

Vertegenwoordigt het compressieniveau van afbeeldingen Lezen/Schrijven [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**Retour:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

Vertegenwoordigt het compressieniveau van afbeeldingen Lezen/Schrijven [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

Een boolean-vlag geeft aan of de bijgesneden delen als onderdeel van het document blijven. Als true worden de bijgesneden delen verwijderd, als false worden ze geserialiseerd in het document (wat kan leiden tot een groter bestand). Lezen/Schrijven boolean.

**Retour:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

Een boolean-vlag geeft aan of de bijgesneden delen als onderdeel van het document blijven. Als true worden de bijgesneden delen verwijderd, als false worden ze geserialiseerd in het document (wat kan leiden tot een groter bestand). Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public abstract boolean getSvgResponsiveLayout()
```

True om breedte- en hoogte-attributen uit de SVG-container uit te sluiten – dit maakt de lay-out responsief. False – anders. Lezen/Schrijven boolean.

**Retour:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public abstract void setSvgResponsiveLayout(boolean value)
```

True om breedte- en hoogte-attributen uit de SVG-container uit te sluiten – dit maakt de lay-out responsief. False – anders. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

Haalt of stelt een waarde in die aangeeft of tekst wordt gerenderd zonder ligaturen. Wanneer deze op true wordt gezet, worden ligaturen uitgeschakeld in de gerenderde output. Standaard is deze eigenschap false.

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

**Retour:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

Haalt of stelt een waarde in die aangeeft of tekst wordt gerenderd zonder ligaturen. Wanneer deze op true wordt gezet, worden ligaturen uitgeschakeld in de gerenderde output. Standaard is deze eigenschap false.

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

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Haalt of stelt de modus waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) in.

--------------------

> ```
> Voorbeeld:
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

**Retour:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Haalt of stelt de modus waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) in.

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
public abstract IInkOptions getInkOptions()
```

Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document regelen. Alleen-lezen [IInkOptions](../../com.aspose.slides/iinkoptions)

**Retour:**
[IInkOptions](../../com.aspose.slides/iinkoptions)