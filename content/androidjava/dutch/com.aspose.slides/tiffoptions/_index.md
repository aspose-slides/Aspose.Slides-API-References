---
title: TiffOptions
second_title: Aspose.Slides voor Android via Java API-referentie
description: Biedt opties die bepalen hoe een presentatie wordt opgeslagen in TIFF-formaat.
type: docs
url: /nl/com.aspose.slides/tiffoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**All Implemented Interfaces:**
[com.aspose.slides.ITiffOptions](../../com.aspose.slides/itiffoptions)
```
public class TiffOptions extends SaveOptions implements ITiffOptions
```

Biedt opties die bepalen hoe een presentatie wordt opgeslagen in TIFF-indeling.

--------------------

> ```
> The following example shows how to convert PowerPoint to TIFF with default size.
>  
>  // Instantieer een Presentation-object dat een presentatiebestand vertegenwoordigt
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      // De presentatie opslaan naar een TIFF-document
>      pres.save("Tiffoutput_out.tiff", SaveFormat.Tiff);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom size.
>  
>  // Instantieer een Presentation-object dat een Presentation-bestand vertegenwoordigt
>  Presentation pres = new Presentation("Convert_Tiff_Custom.pptx");
>  try {
>      // Instantieer de TiffOptions-klasse
>      TiffOptions opts = new TiffOptions();
>      // Instellen van het compressietype
>      opts.setCompressionType(TiffCompressionTypes.Default);
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      opts.setSlidesLayoutOptions(notesOptions);
>      // Compressietypen
>      // Default - Geeft het standaardcompressieschema (LZW) aan.
>      // None - Geeft aan dat er geen compressie is.
>      // CCITT3
>      // CCITT4
>      // LZW
>      // RLE
>      // Diepte is afhankelijk van het compressietype en kan niet handmatig worden ingesteld.
>      // Resolutie-eenheid is altijd gelijk aan 2 (punten per inch)
>      // Instellen van de afbeelding DPI
>      opts.setDpiX(200);
>      opts.setDpiY(100);
>      // Afbeeldingsgrootte instellen
>      opts.setImageSize(new com.aspose.slides.android.Size(1728, 1078));
>      // Sla de presentatie op als TIFF met de opgegeven afbeeldingsgrootte
>      pres.save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom image pixel format.
>  
>  // Instantieer een Presentation-object dat een Presentation-bestand vertegenwoordigt
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      options.setPixelFormat(ImagePixelFormat.Format8bppIndexed);
> 
>      //ImagePixelFormat bevat de volgende waarden (zoals in de documentatie te zien):
>      //Format1bppIndexed; // 1 bit per pixel, geïndexeerd.
>      //Format4bppIndexed; // 4 bits per pixel, geïndexeerd.
>      //Format8bppIndexed; // 8 bits per pixel, geïndexeerd.
>      //Format24bppRgb; // 24 bits per pixel, RGB.
>      //Format32bppArgb; // 32 bits per pixel, ARGB.
> 
>      // Sla de presentatie op als TIFF met de opgegeven afbeeldingsgrootte
>      pres.save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Constructors

| Constructor | Description |
| --- | --- |
| [TiffOptions()](#TiffOptions--) | Standaardconstructor. |
## Methods

| Method | Description |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document regelen. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. |
| [getImageSize()](#getImageSize--) | Geeft de grootte van een gegenereerde TIFF-afbeelding op. |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | Geeft de grootte van een gegenereerde TIFF-afbeelding op. |
| [getDpiX()](#getDpiX--) | Geeft de horizontale resolutie in punten per inch op. |
| [setDpiX(long value)](#setDpiX-long-) | Geeft de horizontale resolutie in punten per inch op. |
| [getDpiY()](#getDpiY--) | Geeft de verticale resolutie in punten per inch op. |
| [setDpiY(long value)](#setDpiY-long-) | Geeft de verticale resolutie in punten per inch op. |
| [getCompressionType()](#getCompressionType--) | Geeft het compressietype op. |
| [setCompressionType(int value)](#setCompressionType-int-) | Geeft het compressietype op. |
| [getPixelFormat()](#getPixelFormat--) | Geeft het pixelformaat voor de gegenereerde afbeeldingen op. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Geeft het pixelformaat voor de gegenereerde afbeeldingen op. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Haalt of stelt de modus in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Haalt of stelt de modus in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Geeft het algoritme op voor het converteren van een kleurenafbeelding naar een zwart-wit afbeelding. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Geeft het algoritme op voor het converteren van een kleurenafbeelding naar een zwart-wit afbeelding. |

### TiffOptions() {#TiffOptions--}
```
public TiffOptions()
```

Standaardconstructor.

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document regelen. Alleen-lezen [IInkOptions](../../com.aspose.slides/iinkoptions)

**Retour:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is false.

**Retour:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getImageSize() {#getImageSize--}
```
public final Size getImageSize()
```

Geeft de grootte van een gegenereerde TIFF-afbeelding op. Standaardwaarde is 0x0, wat betekent dat de afmetingen van de gegenereerde afbeelding worden berekend op basis van de grootte van de presentatiedia. Lezen/Schrijven [Size](../../com.aspose.slides.android/size).

**Retour:**
[Size](../../com.aspose.slides.android/size)
### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public final void setImageSize(Size value)
```

Geeft de grootte van een gegenereerde TIFF-afbeelding op. Standaardwaarde is 0x0, wat betekent dat de afmetingen van de gegenereerde afbeelding worden berekend op basis van de grootte van de presentatiedia. Lezen/Schrijven [Size](../../com.aspose.slides.android/size).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getDpiX() {#getDpiX--}
```
public final long getDpiX()
```

Geeft de horizontale resolutie in punten per inch op. Lezen/Schrijven long.

**Retour:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public final void setDpiX(long value)
```

Geeft de horizontale resolutie in punten per inch op. Lezen/Schrijven long.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public final long getDpiY()
```

Geeft de verticale resolutie in punten per inch op. Lezen/Schrijven long.

**Retour:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public final void setDpiY(long value)
```

Geeft de verticale resolutie in punten per inch op. Lezen/Schrijven long.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getCompressionType() {#getCompressionType--}
```
public final int getCompressionType()
```

Geeft het compressietype op. Lezen/Schrijven [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Retour:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public final void setCompressionType(int value)
```

Geeft het compressietype op. Lezen/Schrijven [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public final int getPixelFormat()
```

Geeft het pixelformaat voor de gegenereerde afbeeldingen op. Lezen/Schrijven [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Retour:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public final void setPixelFormat(int value)
```

Geeft het pixelformaat voor de gegenereerde afbeeldingen op. Lezen/Schrijven [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Haalt of stelt de modus in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

Haalt of stelt de modus in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getBwConversionMode() {#getBwConversionMode--}
```
public final int getBwConversionMode()
```

Geeft het algoritme op voor het converteren van een kleurenafbeelding naar een zwart-wit afbeelding. Deze optie wordt alleen toegepast als CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) is ingesteld op [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) of [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) Lezen/Schrijven [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Standaard is [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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

Geeft het algoritme op voor het converteren van een kleurenafbeelding naar een zwart-wit afbeelding. Deze optie wordt alleen toegepast als CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) is ingesteld op [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) of [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) Lezen/Schrijven [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Standaard is [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |