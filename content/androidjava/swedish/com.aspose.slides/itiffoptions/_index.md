---
title: ITiffOptions
second_title: Aspose.Slides för Android via Java API-referens
description: Tillhandahåller alternativ som styr hur en presentation sparas i TIFF-format.
type: docs
url: /sv/com.aspose.slides/itiffoptions/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ITiffOptions extends ISaveOptions
```

Tillhandahåller alternativ som styr hur en presentation sparas i TIFF-format.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getImageSize()](#getImageSize--) | Anger storleken på en genererad TIFF-bild. |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | Anger storleken på en genererad TIFF-bild. |
| [getDpiX()](#getDpiX--) | Anger den horisontella upplösningen i punkter per tum. |
| [setDpiX(long value)](#setDpiX-long-) | Anger den horisontella upplösningen i punkter per tum. |
| [getDpiY()](#getDpiY--) | Anger den vertikala upplösningen i punkter per tum. |
| [setDpiY(long value)](#setDpiY-long-) | Anger den vertikala upplösningen i punkter per tum. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. |
| [getCompressionType()](#getCompressionType--) | Anger komprimeringstypen. |
| [setCompressionType(int value)](#setCompressionType-int-) | Anger komprimeringstypen. |
| [getPixelFormat()](#getPixelFormat--) | Anger pixelformatet för de genererade bilderna. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Anger pixelformatet för de genererade bilderna. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Hämtar eller anger läget i vilket bilder placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Hämtar eller anger läget i vilket bilder placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Anger algoritmen för att konvertera en färgbild till en svartvit bild. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Anger algoritmen för att konvertera en färgbild till en svartvit bild. |
| [getInkOptions()](#getInkOptions--) | Tillhandahåller alternativ som styr utseendet på bläckobjekt i exporterat dokument. |
### getImageSize() {#getImageSize--}
```
public abstract Size getImageSize()
```


Anger storleken på en genererad TIFF-bild. Standardvärdet är 0x0, vilket betyder att genererade bildstorlekar beräknas baserat på presentationens bildstorlek. Läs/skriv [Size](../../com.aspose.slides.android/size).

**Returnerar:**
[Size](../../com.aspose.slides.android/size)
### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public abstract void setImageSize(Size value)
```


Anger storleken på en genererad TIFF-bild. Standardvärdet är 0x0, vilket betyder att genererade bildstorlekar beräknas baserat på presentationens bildstorlek. Läs/skriv [Size](../../com.aspose.slides.android/size).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getDpiX() {#getDpiX--}
```
public abstract long getDpiX()
```


Anger den horisontella upplösningen i punkter per tum. Läs/skriv long.

**Returnerar:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public abstract void setDpiX(long value)
```


Anger den horisontella upplösningen i punkter per tum. Läs/skriv long.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public abstract long getDpiY()
```


Anger den vertikala upplösningen i punkter per tum. Läs/skriv long.

**Returnerar:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public abstract void setDpiY(long value)
```


Anger den vertikala upplösningen i punkter per tum. Läs/skriv long.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | long |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```


Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. Standard är falskt.

**Returnerar:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```


Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. Standard är falskt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getCompressionType() {#getCompressionType--}
```
public abstract int getCompressionType()
```


Anger komprimeringstypen. Läs/skriv [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Returnerar:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public abstract void setCompressionType(int value)
```


Anger komprimeringstypen. Läs/skriv [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public abstract int getPixelFormat()
```


Anger pixelformatet för de genererade bilderna. Läs/skriv [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Returnerar:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public abstract void setPixelFormat(int value)
```


Anger pixelformatet för de genererade bilderna. Läs/skriv [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```


Hämtar eller anger läget i vilket bilder placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


Hämtar eller anger läget i vilket bilder placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public abstract int getBwConversionMode()
```


Anger algoritmen för att konvertera en färgbild till en svartvit bild. Detta alternativ tillämpas endast om CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) är satt till [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) eller [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3). Läs/skriv [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Standard är [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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
public abstract void setBwConversionMode(int value)
```


Anger algoritmen för att konvertera en färgbild till en svartvit bild. Detta alternativ tillämpas endast om CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) är satt till [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) eller [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3). Läs/skriv [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Standard är [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```


Tillhandahåller alternativ som styr utseendet på bläckobjekt i exporterat dokument. Endast läsning [IInkOptions](../../com.aspose.slides/iinkoptions)

**Returnerar:**
[IInkOptions](../../com.aspose.slides/iinkoptions)