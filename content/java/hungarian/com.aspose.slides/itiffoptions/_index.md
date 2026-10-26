---
title: ITiffOptions
second_title: Aspose.Slides for Java API-referencia
description: Lehetőségeket biztosít, amelyek szabályozzák, hogyan menthető el egy bemutató TIFF formátumban.
type: docs
url: /hu/com.aspose.slides/itiffoptions/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ITiffOptions extends ISaveOptions
```

Lehetőségeket biztosít, amelyek szabályozzák, hogyan menthető el a bemutató TIFF formátumban.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getImageSize()](#getImageSize--) | Meghatározza egy generált TIFF kép méretét. |
| [setImageSize(Dimension value)](#setImageSize-java.awt.Dimension-) | Meghatározza egy generált TIFF kép méretét. |
| [getDpiX()](#getDpiX--) | Meghatározza a vízszintes felbontást pont per hüvelykben. |
| [setDpiX(long value)](#setDpiX-long-) | Meghatározza a vízszintes felbontást pont per hüvelykben. |
| [getDpiY()](#getDpiY--) | Meghatározza a függőleges felbontást pont per hüvelykben. |
| [setDpiY(long value)](#setDpiY-long-) | Meghatározza a függőleges felbontást pont per hüvelykben. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Meghatározza, hogy a generált dokumentum tartalmazzon-e rejtett diákot vagy sem. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Meghatározza, hogy a generált dokumentum tartalmazzon-e rejtett diákot vagy sem. |
| [getCompressionType()](#getCompressionType--) | Meghatározza a tömörítési típust. |
| [setCompressionType(int value)](#setCompressionType-int-) | Meghatározza a tömörítési típust. |
| [getPixelFormat()](#getPixelFormat--) | Meghatározza a képpontformátumot a generált képekhez. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Meghatározza a képpontformátumot a generált képekhez. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Megkapja vagy beállítja a módot, amelyben a diák az oldalra helyeződnek egy bemutató exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Megkapja vagy beállítja a módot, amelyben a diák az oldalra helyeződnek egy bemutató exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Meghatározza az algoritmust egy színes kép fekete-fehérre konvertálásához. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Meghatározza az algoritmust egy színes kép fekete-fehérre konvertálásához. |
| [getInkOptions()](#getInkOptions--) | Lehetőségeket biztosít, amelyek szabályozzák az Ink objektumok megjelenését az exportált dokumentumban. |
### getImageSize() {#getImageSize--}
```
public abstract Dimension getImageSize()
```

Meghatározza egy generált TIFF kép méretét. Alapértelmezett érték 0x0, ami azt jelenti, hogy a generált képméret a bemutató dia mérete alapján lesz kiszámítva. Olvasás/írás java.awt.Dimension.

**Visszatér:**
java.awt.Dimension
### setImageSize(Dimension value) {#setImageSize-java.awt.Dimension-}
```
public abstract void setImageSize(Dimension value)
```

Meghatározza egy generált TIFF kép méretét. Alapértelmezett érték 0x0, ami azt jelenti, hogy a generált képméret a bemutató dia mérete alapján lesz kiszámítva. Olvasás/írás java.awt.Dimension.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.awt.Dimension |  |
### getDpiX() {#getDpiX--}
```
public abstract long getDpiX()
```

Meghatározza a vízszintes felbontást pont per hüvelykben. Olvasás/írás long.

**Visszatér:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public abstract void setDpiX(long value)
```

Meghatározza a vízszintes felbontást pont per hüvelykben. Olvasás/írás long.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |
### getDpiY() {#getDpiY--}
```
public abstract long getDpiY()
```

Meghatározza a függőleges felbontást pont per hüvelykben. Olvasás/írás long.

**Visszatér:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public abstract void setDpiY(long value)
```

Meghatározza a függőleges felbontást pont per hüvelykben. Olvasás/írás long.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Meghatározza, hogy a generált dokumentum tartalmazzon-e rejtett diákot vagy sem. Alapértelmezett érték false.

**Visszatér:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Meghatározza, hogy a generált dokumentum tartalmazzon-e rejtett diákot vagy sem. Alapértelmezett érték false.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getCompressionType() {#getCompressionType--}
```
public abstract int getCompressionType()
```

Meghatározza a tömörítési típust. Olvasás/írás [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Visszatér:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public abstract void setCompressionType(int value)
```

Meghatározza a tömörítési típust. Olvasás/írás [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getPixelFormat() {#getPixelFormat--}
```
public abstract int getPixelFormat()
```

Meghatározza a képpontformátumot a generált képekhez. Olvasás/írás [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Visszatér:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public abstract void setPixelFormat(int value)
```

Meghatározza a képpontformátumot a generált képekhez. Olvasás/írás [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Megkapja vagy beállítja a módot, amelyben a diák az oldalra helyeződnek egy bemutató exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**Visszatér:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Megkapja vagy beállítja a módot, amelyben a diák az oldalra helyeződnek egy bemutató exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |
### getBwConversionMode() {#getBwConversionMode--}
```
public abstract int getBwConversionMode()
```

Meghatározza az algoritmust egy színes kép fekete-fehérre konvertálásához. Ez a beállítás csak akkor lesz alkalmazva, ha a CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) be van állítva [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) vagy [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3). Olvasás/írás [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Alapértelmezett [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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

**Visszatér:**
int
### setBwConversionMode(int value) {#setBwConversionMode-int-}
```
public abstract void setBwConversionMode(int value)
```

Meghatározza az algoritmust egy színes kép fekete-fehérre konvertálásához. Ez a beállítás csak akkor lesz alkalmazva, ha a CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) be van állítva [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) vagy [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3). Olvasás/írás [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Alapértelmezett [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Lehetőségeket biztosít, amelyek szabályozzák az Ink objektumok megjelenését az exportált dokumentumban. Csak olvasható [IInkOptions](../../com.aspose.slides/iinkoptions)

**Visszatér:**
[IInkOptions](../../com.aspose.slides/iinkoptions)