---
title: ITiffOptions
second_title: Aspose.Slides voor Android via Java API-referentie
description: Biedt opties die bepalen hoe een presentatie wordt opgeslagen in TIFF-indeling.
type: docs
url: /nl/com.aspose.slides/itiffoptions/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ITiffOptions extends ISaveOptions
```

Biedt opties die bepalen hoe een presentatie wordt opgeslagen in TIFF-indeling.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getImageSize()](#getImageSize--) | Specificeert de grootte van een gegenereerde TIFF-afbeelding. |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | Specificeert de grootte van een gegenereerde TIFF-afbeelding. |
| [getDpiX()](#getDpiX--) | Specificeert de horizontale resolutie in punten per inch. |
| [setDpiX(long value)](#setDpiX-long-) | Specificeert de horizontale resolutie in punten per inch. |
| [getDpiY()](#getDpiY--) | Specificeert de verticale resolutie in punten per inch. |
| [setDpiY(long value)](#setDpiY-long-) | Specificeert de verticale resolutie in punten per inch. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. |
| [getCompressionType()](#getCompressionType--) | Specificeert het compressietype. |
| [setCompressionType(int value)](#setCompressionType-int-) | Specificeert het compressietype. |
| [getPixelFormat()](#getPixelFormat--) | Specificeert het pixelformaat voor de gegenereerde afbeeldingen. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Specificeert het pixelformaat voor de gegenereerde afbeeldingen. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Haalt op of stelt de modus in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Haalt op of stelt de modus in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Specificeert het algoritme voor het omzetten van een kleurenafbeelding naar een zwart-wit afbeelding. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Specificeert het algoritme voor het omzetten van een kleurenafbeelding naar een zwart-wit afbeelding. |
| [getInkOptions()](#getInkOptions--) | Biedt opties die de weergave van Ink-objecten in het geëxporteerde document regelen. |
### getImageSize() {#getImageSize--}
```
public abstract Size getImageSize()
```


Specificeert de grootte van een gegenereerde TIFF-afbeelding. Standaardwaarde is 0x0, wat betekent dat de gegenereerde afbeeldingsgroottes worden berekend op basis van de grootte van de presentatiedia. Lezen/schrijven [Size](../../com.aspose.slides.android/size).

**Retour:**
[Size](../../com.aspose.slides.android/size)
### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public abstract void setImageSize(Size value)
```


Specificeert de grootte van een gegenereerde TIFF-afbeelding. Standaardwaarde is 0x0, wat betekent dat de gegenereerde afbeeldingsgroottes worden berekend op basis van de grootte van de presentatiedia. Lezen/schrijven [Size](../../com.aspose.slides.android/size).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getDpiX() {#getDpiX--}
```
public abstract long getDpiX()
```


Specificeert de horizontale resolutie in punten per inch. Lezen/schrijven long.

**Retour:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public abstract void setDpiX(long value)
```


Specificeert de horizontale resolutie in punten per inch. Lezen/schrijven long.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public abstract long getDpiY()
```


Specificeert de verticale resolutie in punten per inch. Lezen/schrijven long.

**Retour:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public abstract void setDpiY(long value)
```


Specificeert de verticale resolutie in punten per inch. Lezen/schrijven long.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |

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

### getCompressionType() {#getCompressionType--}
```
public abstract int getCompressionType()
```


Specificeert het compressietype. Lezen/schrijven [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Retour:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public abstract void setCompressionType(int value)
```


Specificeert het compressietype. Lezen/schrijven [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public abstract int getPixelFormat()
```


Specificeert het pixelformaat voor de gegenereerde afbeeldingen. Lezen/schrijven [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Retour:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public abstract void setPixelFormat(int value)
```


Specificeert het pixelformaat voor de gegenereerde afbeeldingen. Lezen/schrijven [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```


Haalt op of stelt de modus in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.tiff", SaveFormat.Tiff, options);
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


Haalt op of stelt de modus in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getBwConversionMode() {#getBwConversionMode--}
```
public abstract int getBwConversionMode()
```


Specificeert het algoritme voor het omzetten van een kleurenafbeelding naar een zwart-wit afbeelding. Deze optie wordt alleen toegepast als CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionMode(int)) is ingesteld op [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) of [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) Lezen/schrijven [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Standaard is [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

--------------------

> ```
> TiffOptions tiffOptions = new TiffOptions();
>  tiffOptions.setCompressionType(TiffCompressionTypes.CCITT4);
>  tiffOptions.setBwConversionMode(BlackWhiteConversionMode.Dithering);
>  Presentation presentation = new Presentation();
>  try {
>      presentation.save(tiffFilePath, SaveFormat.Tiff, tiffOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Retour:**
int
### setBwConversionMode(int value) {#setBwConversionMode-int-}
```
public abstract void setBwConversionMode(int value)
```


Specificeert het algoritme voor het omzetten van een kleurenafbeelding naar een zwart-wit afbeelding. Deze optie wordt alleen toegepast als CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionMode(int)) is ingesteld op [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) of [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) Lezen/schrijven [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Standaard is [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

--------------------

> ```
> TiffOptions tiffOptions = new TiffOptions();
>  tiffOptions.setCompressionType(TiffCompressionTypes.CCITT4);
>  tiffOptions.setBwConversionMode(BlackWhiteConversionMode.Dithering);
>  Presentation presentation = new Presentation();
>  try {
>      presentation.save(tiffFilePath, SaveFormat.Tiff, tiffOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```


Biedt opties die de weergave van Ink-objecten in het geëxporteerde document regelen. Alleen-lezen [IInkOptions](../../com.aspose.slides/iinkoptions)

**Retour:**
[IInkOptions](../../com.aspose.slides/iinkoptions)