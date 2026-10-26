---
title: TiffOptions
second_title: Aspose.Slides voor Java API-referentie
description: Biedt opties die bepalen hoe een presentatie wordt opgeslagen in TIFF-formaat.
type: docs
url: /nl/com.aspose.slides/tiffoptions/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ITiffOptions](../../com.aspose.slides/itiffoptions)
```
public class TiffOptions extends SaveOptions implements ITiffOptions
```

Biedt opties die bepalen hoe een presentatie wordt opgeslagen in TIFF-formaat.

--------------------

> ```
> The following example shows how to convert PowerPoint to TIFF with default size.
>  
>  // Instantieer een Presentation-object dat een presentatie-bestand vertegenwoordigt
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      // Sla de presentatie op als TIFF-document
>      pres.save("Tiffoutput_out.tiff", SaveFormat.Tiff);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom size.
>  
>  // Instantieer een Presentation-object dat een Presentatie-bestand vertegenwoordigt
>  Presentation pres = new Presentation("Convert_Tiff_Custom.pptx");
>  try {
>      // Instantieer de TiffOptions-klasse
>      TiffOptions opts = new TiffOptions();
>      // Instellen van compressietype
>      opts.setCompressionType(TiffCompressionTypes.Default);
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      opts.setSlidesLayoutOptions(notesOptions);
>      // Compressietypen
>      // Default - Geeft het standaard compressieschema (LZW) aan.
>      // None - Geeft aan dat er geen compressie is.
>      // CCITT3
>      // CCITT4
>      // LZW
>      // RLE
>      // Diepte is afhankelijk van het compressietype en kan niet handmatig worden ingesteld.
>      // Resolutie-eenheid is altijd gelijk aan 2 (punten per inch)
>      // Instellen van beeld-DPI
>      opts.setDpiX(200);
>      opts.setDpiY(100);
>      // Stel afbeeldingsgrootte in
>      opts.setImageSize(new Dimension(1728, 1078));
>      // Sla de presentatie op als TIFF met opgegeven afbeeldingsgrootte
>      pres.save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom image pixel format.
>  
>  // Instantieer een Presentation-object dat een Presentatie-bestand vertegenwoordigt
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      options.setPixelFormat(ImagePixelFormat.Format8bppIndexed);
> 
>      //ImagePixelFormat bevat de volgende waarden (zoals uit de documentatie blijkt):
>      //Format1bppIndexed; // 1 bits per pixel, geïndiceerd.
>      //Format4bppIndexed; // 4 bits per pixel, geïndiceerd.
>      //Format8bppIndexed; // 8 bits per pixel, geïndiceerd.
>      //Format24bppRgb; // 24 bits per pixel, RGB.
>      //Format32bppArgb; // 32 bits per pixel, ARGB.
> 
>      // Sla de presentatie op als TIFF met opgegeven afbeeldingsgrootte
>      pres.save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [TiffOptions()](#TiffOptions--) | Standaardconstructor. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document bepalen. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specificeert of het gegenereerde document verborgen dia’s moet bevatten of niet. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specificeert of het gegenereerde document verborgen dia’s moet bevatten of niet. |
| [getImageSize()](#getImageSize--) | Specificeert de grootte van een gegenereerde TIFF-afbeelding. |
| [setImageSize(Dimension value)](#setImageSize-java.awt.Dimension-) | Specificeert de grootte van een gegenereerde TIFF-afbeelding. |
| [getDpiX()](#getDpiX--) | Specificeert de horizontale resolutie in dots per inch. |
| [setDpiX(long value)](#setDpiX-long-) | Specificeert de horizontale resolutie in dots per inch. |
| [getDpiY()](#getDpiY--) | Specificeert de verticale resolutie in dots per inch. |
| [setDpiY(long value)](#setDpiY-long-) | Specificeert de verticale resolutie in dots per inch. |
| [getCompressionType()](#getCompressionType--) | Specificeert het compressietype. |
| [setCompressionType(int value)](#setCompressionType-int-) | Specificeert het compressietype. |
| [getPixelFormat()](#getPixelFormat--) | Specificeert het pixelformaat voor de gegenereerde afbeeldingen. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Specificeert het pixelformaat voor de gegenereerde afbeeldingen. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Haalt op of stelt de modus in waarin dia’s op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Haalt op of stelt de modus in waarin dia’s op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Specificeert het algoritme voor het converteren van een kleurenafbeelding naar een zwart-wit afbeelding. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Specificeert het algoritme voor het converteren van een kleurenafbeelding naar een zwart-wit afbeelding. |
### TiffOptions() {#TiffOptions--}
```
public TiffOptions()
```


Standaardconstructor.

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```


Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document bepalen. Alleen-lezen [IInkOptions](../../com.aspose.slides/iinkoptions)

**Retour:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Specificeert of het gegenereerde document verborgen dia’s moet bevatten of niet. Standaard is false.

**Retour:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Specificeert of het gegenereerde document verborgen dia’s moet bevatten of niet. Standaard is false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getImageSize() {#getImageSize--}
```
public final Dimension getImageSize()
```


Specificeert de grootte van een gegenereerde TIFF-afbeelding. Standaardwaarde is 0x0, wat betekent dat de grootte van de gegenereerde afbeelding wordt berekend op basis van de grootte van de presentatie-dia. Lezen/Schrijven java.awt.Dimension.

**Retour:**
java.awt.Dimension
### setImageSize(Dimension value) {#setImageSize-java.awt.Dimension-}
```
public final void setImageSize(Dimension value)
```


Specificeert de grootte van een tegenereerde TIFF-afbeelding. Standaardwaarde is 0x0, wat betekent dat de grootte van de gegenereerde afbeelding wordt berekend op basis van de grootte van de presentatie-dia. Lezen/Schrijven java.awt.Dimension.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getDpiX() {#getDpiX--}
```
public final long getDpiX()
```


Specificeert de horizontale resolutie in dots per inch. Lezen/Schrijven long.

**Retour:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public final void setDpiX(long value)
```


Specificeert de horizontale resolutie in dots per inch. Lezen/Schrijven long.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public final long getDpiY()
```


Specificeert de verticale resolutie in dots per inch. Lezen/Schrijven long.

**Retour:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public final void setDpiY(long value)
```


Specificeert de verticale resolutie in dots per inch. Lezen/Schrijven long.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |

### getCompressionType() {#getCompressionType--}
```
public final int getCompressionType()
```


Specificeert het compressietype. Lezen/Schrijven [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Retour:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public final void setCompressionType(int value)
```


Specificeert het compressietype. Lezen/Schrijven [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public final int getPixelFormat()
```


Specificeert het pixelformaat voor de gegenereerde afbeeldingen. Lezen/Schrijven [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Retour:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public final void setPixelFormat(int value)
```


Specificeert het pixelformaat voor de gegenereerde afbeeldingen. Lezen/Schrijven [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```


Haalt op of stelt de modus in waarin dia’s op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


Haalt op of stelt de modus in waarin dia’s op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public final int getBwConversionMode()
```


Specificeert het algoritme voor het converteren van een kleurenafbeelding naar een zwart-wit afbeelding. Deze optie wordt alleen toegepast als CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) is ingesteld op [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) of [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) Lezen/Schrijven [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Standaard is [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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
public final void setBwConversionMode(int value)
```


Specificeert het algoritme voor het converteren van een kleurenafbeelding naar een zwart-wit afbeelding. Deze optie wordt alleen toegepast als CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) is ingesteld op [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) of [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) Lezen/Schrijven [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Standaard is [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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