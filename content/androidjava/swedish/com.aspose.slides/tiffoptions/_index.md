---
title: TiffOptions
second_title: Aspose.Slides för Android via Java API-referens
description: Tillhandahåller alternativ som styr hur en presentation sparas i TIFF-format.
type: docs
url: /sv/com.aspose.slides/tiffoptions/
---
**Arv:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Alla implementerade gränssnitt:**
[com.aspose.slides.ITiffOptions](../../com.aspose.slides/itiffoptions)
```
public class TiffOptions extends SaveOptions implements ITiffOptions
```

Tillhandahåller alternativ som styr hur en presentation sparas i TIFF-format.

--------------------

> ```
> The following example shows how to convert PowerPoint to TIFF with default size.
>  
>  // Instansiera ett Presentation-objekt som representerar en presentationsfil
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      // Sparar presentationen till ett TIFF-dokument
>      pres.save("Tiffoutput_out.tiff", SaveFormat.Tiff);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom size.
>  
>  // Instansiera ett Presentation-objekt som representerar en presentationsfil
>  Presentation pres = new Presentation("Convert_Tiff_Custom.pptx");
>  try {
>      // Instansiera TiffOptions-klassen
>      TiffOptions opts = new TiffOptions();
>      // Ställer in komprimeringstyp
>      opts.setCompressionType(TiffCompressionTypes.Default);
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      opts.setSlidesLayoutOptions(notesOptions);
>      // Komprimeringstyper
>      // Default - Anger standardkomprimeringsschemat (LZW).
>      // None - Anger ingen komprimering.
>      // CCITT3
>      // CCITT4
>      // LZW
>      // RLE
>      // Djup beror på komprimeringstypen och kan inte sättas manuellt.
>      // Upplösningsenhet är alltid lika med 2 (punkter per tum)
>      // Ställer in bildens DPI
>      opts.setDpiX(200);
>      opts.setDpiY(100);
>      // Ställ in bildstorlek
>      opts.setImageSize(new com.aspose.slides.android.Size(1728, 1078));
>      // Spara presentationen till TIFF med angiven bildstorlek
>      pres.save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom image pixel format.
>  
>  // Instansiera ett Presentation-objekt som representerar en presentationsfil
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      options.setPixelFormat(ImagePixelFormat.Format8bppIndexed);
> 
>      //ImagePixelFormat innehåller följande värden (som kan ses i dokumentationen):
>      //Format1bppIndexed; // 1 bit per pixel, indexerad.
>      //Format4bppIndexed; // 4 bit per pixel, indexerad.
>      //Format8bppIndexed; // 8 bit per pixel, indexerad.
>      //Format24bppRgb; // 24 bit per pixel, RGB.
>      //Format32bppArgb; // 32 bit per pixel, ARGB.
> 
>      // Spara presentationen till TIFF med angiven bildstorlek
>      pres.save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [TiffOptions()](#TiffOptions--) | Standardkonstruktor. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Tillhandahåller alternativ som styr hur Ink-objekt ser ut i exporterade dokument. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Anger om det genererade dokumentet ska inkludera dolda bildspel eller inte. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Anger om det genererade dokumentet ska inkludera dolda bildspel eller inte. |
| [getImageSize()](#getImageSize--) | Anger storleken på en genererad TIFF-bild. |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | Anger storleken på en genererad TIFF-bild. |
| [getDpiX()](#getDpiX--) | Anger den horisontella upplösningen i punkter per tum. |
| [setDpiX(long value)](#setDpiX-long-) | Anger den horisontella upplösningen i punkter per tum. |
| [getDpiY()](#getDpiY--) | Anger den vertikala upplösningen i punkter per tum. |
| [setDpiY(long value)](#setDpiY-long-) | Anger den vertikala upplösningen i punkter per tum. |
| [getCompressionType()](#getCompressionType--) | Anger komprimeringstypen. |
| [setCompressionType(int value)](#setCompressionType-int-) | Anger komprimeringstypen. |
| [getPixelFormat()](#getPixelFormat--) | Anger pixelformatet för de genererade bilderna. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Anger pixelformatet för de genererade bilderna. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Hämtar eller anger läget som bildspel placeras på sidan när en presentation exporteras [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Hämtar eller anger läget som bildspel placeras på sidan när en presentation exporteras [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Anger algoritmen för att konvertera en färgbild till en svart-vit bild. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Anger algoritmen för att konvertera en färgbild till en svart-vit bild. |
### TiffOptions() {#TiffOptions--}
```
public TiffOptions()
```

Standardkonstruktor.

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Tillhandahåller alternativ som styr hur Ink-objekt ser ut i exporterade dokument. Skrivskyddad [IInkOptions](../../com.aspose.slides/iinkoptions)

**Returnerar:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Anger om det genererade dokumentet ska inkludera dolda bildspel eller inte. Standard är falskt.

**Returnerar:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Anger om det genererade dokumentet ska inkludera dolda bildspel eller inte. Standard är falskt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getImageSize() {#getImageSize--}
```
public final Size getImageSize()
```

Anger storleken på en genererad TIFF-bild. Standardvärdet är 0x0, vilket betyder att de genererade bildstorlekarna beräknas baserat på värdet för presentationsbildens storlek. Läs/skriv [Size](../../com.aspose.slides.android/size).

**Returnerar:**
[Size](../../com.aspose.slides.android/size)
### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public final void setImageSize(Size value)
```

Anger storleken på en genererad TIFF-bild. Standardvärdet är 0x0, vilket betyder att de genererade bildstorlekarna beräknas baserat på värdet för presentationsbildens storlek. Läs/skriv [Size](../../com.aspose.slides.android/size).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getDpiX() {#getDpiX--}
```
public final long getDpiX()
```

Anger den horisontella upplösningen i punkter per tum. Läs/skriv long.

**Returnerar:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public final void setDpiX(long value)
```

Anger den horisontella upplösningen i punkter per tum. Läs/skriv long.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public final long getDpiY()
```

Anger den vertikala upplösningen i punkter per tum. Läs/skriv long.

**Returnerar:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public final void setDpiY(long value)
```

Anger den vertikala upplösningen i punkter per tum. Läs/skriv long.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | long |  |

### getCompressionType() {#getCompressionType--}
```
public final int getCompressionType()
```

Anger komprimeringstypen. Läs/skriv [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Returnerar:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public final void setCompressionType(int value)
```

Anger komprimeringstypen. Läs/skriv [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public final int getPixelFormat()
```

Anger pixelformatet för de genererade bilderna. Läs/skriv [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Returnerar:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public final void setPixelFormat(int value)
```

Anger pixelformatet för de genererade bilderna. Läs/skriv [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Hämtar eller anger läget som bildspel placeras på sidan när en presentation exporteras [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**Returnerar:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Hämtar eller anger läget som bildspel placeras på sidan när en presentation exporteras [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getBwConversionMode() {#getBwConversionMode--}
```
public final int getBwConversionMode()
```

Anger algoritmen för att konvertera en färgbild till en svart-vit bild. Detta alternativ tillämpas endast om CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) är satt till [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) eller [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3). Läs/skriv [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Standard är [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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

**Returnerar:**
int
### setBwConversionMode(int value) {#setBwConversionMode-int-}
```
public final void setBwConversionMode(int value)
```

Anger algoritmen för att konvertera en färgbild till en svart-vit bild. Detta alternativ tillämpas endast om CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) är satt till [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) eller [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3). Läs/skriv [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Standard är [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |