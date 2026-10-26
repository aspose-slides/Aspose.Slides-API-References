---
title: ITiffOptions
second_title: Aspose.Slides voor Java API Referentie
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
## Methodes

| Methode | Beschrijving |
| --- | --- |
| [getImageSize()](#getImageSize--) | Geeft de grootte van een gegenereerde TIFF-afbeelding op. |
| [setImageSize(Dimension value)](#setImageSize-java.awt.Dimension-) | Geeft de grootte van een gegenereerde TIFF-afbeelding op. |
| [getDpiX()](#getDpiX--) | Geeft de horizontale resolutie in dots per inch op. |
| [setDpiX(long value)](#setDpiX-long-) | Geeft de horizontale resolutie in dots per inch op. |
| [getDpiY()](#getDpiY--) | Geeft de verticale resolutie in dots per inch op. |
| [setDpiY(long value)](#setDpiY-long-) | Geeft de verticale resolutie in dots per inch op. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Geeft op of het gegenereerde document verborgen dia’s moet bevatten of niet. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Geeft op of het gegenereerde document verborgen dia’s moet bevatten of niet. |
| [getCompressionType()](#getCompressionType--) | Geeft het compressietype op. |
| [setCompressionType(int value)](#setCompressionType-int-) | Geeft het compressietype op. |
| [getPixelFormat()](#getPixelFormat--) | Geeft het pixelindeling voor de gegenereerde afbeeldingen op. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Geeft het pixelindeling voor de gegenereerde afbeeldingen op. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Haalt de modus op of stelt deze in waarin dia’s op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Haalt de modus op of stelt deze in waarin dia’s op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Geeft het algoritme op voor het converteren van een kleurafbeelding naar een zwart-wit afbeelding. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Geeft het algoritme op voor het converteren van een kleurafbeelding naar een zwart-wit afbeelding. |
| [getInkOptions()](#getInkOptions--) | Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document regelen. |
### getImageSize() {#getImageSize--}
```
public abstract Dimension getImageSize()
```

Geeft de grootte van een gegenereerde TIFF-afbeelding op. Standaardwaarde is 0x0, wat betekent dat de afmetingen van de gegenereerde afbeeldingen worden berekend op basis van de grootte van de presentatiedia. Lezen/Schrijven java.awt.Dimension.

**Retour:**
java.awt.Dimension
### setImageSize(Dimension value) {#setImageSize-java.awt.Dimension-}
```
public abstract void setImageSize(Dimension value)
```

Geeft de grootte van een gegenereerde TIFF-afbeelding op. Standaardwaarde is 0x0, wat betekent dat de afmetingen van de gegenereerde afbeeldingen worden berekend op basis van de grootte van de presentatiedia. Lezen/Schrijven java.awt.Dimension.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.awt.Dimension |  |
### getDpiX() {#getDpiX--}
```
public abstract long getDpiX()
```

Geeft de horizontale resolutie in dots per inch op. Lezen/Schrijven long.

**Retour:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public abstract void setDpiX(long value)
```

Geeft de horizontale resolutie in dots per inch op. Lezen/Schrijven long.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |
### getDpiY() {#getDpiY--}
```
public abstract long getDpiY()
```

Geeft de verticale resolutie in dots per inch op. Lezen/Schrijven long.

**Retour:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public abstract void setDpiY(long value)
```

Geeft de verticale resolutie in dots per inch op. Lezen/Schrijven long.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Geeft op of het gegenereerde document verborgen dia’s moet bevatten of niet. Standaard is false.

**Retour:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Geeft op of het gegenereerde document verborgen dia’s moet bevatten of niet. Standaard is false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getCompressionType() {#getCompressionType--}
```
public abstract int getCompressionType()
```

Geeft het compressietype op. Lezen/Schrijven [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Retour:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public abstract void setCompressionType(int value)
```

Geeft het compressietype op. Lezen/Schrijven [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getPixelFormat() {#getPixelFormat--}
```
public abstract int getPixelFormat()
```

Geeft het pixelindeling voor de gegenereerde afbeeldingen op. Lezen/Schrijven [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Retour:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public abstract void setPixelFormat(int value)
```

Geeft het pixelindeling voor de gegenereerde afbeeldingen op. Lezen/Schrijven [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Haalt de modus op of stelt deze in waarin dia’s op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

Haalt de modus op of stelt deze in waarin dia’s op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

Geeft het algoritme op voor het converteren van een kleurafbeelding naar een zwart-wit afbeelding. Deze optie wordt alleen toegepast als CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) is ingesteld op [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) of [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3). Lezen/Schrijven [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Standaard is [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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

Geeft het algoritme op voor het converteren van een kleurafbeelding naar een zwart-wit afbeelding. Deze optie wordt alleen toegepast als CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) is ingesteld op [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) of [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3). Lezen/Schrijven [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Standaard is [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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

Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document regelen. Alleen-lezen [IInkOptions](../../com.aspose.slides/iinkoptions)

**Retour:**
[IInkOptions](../../com.aspose.slides/iinkoptions)