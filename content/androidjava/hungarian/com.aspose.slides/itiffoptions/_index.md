---
title: ITiffOptions
second_title: Aspose.Slides Android számára Java API referencia
description: Beállításokat biztosít, amelyek szabályozzák, hogy a prezentáció hogyan kerül mentésre TIFF formátumban.
type: docs
url: /hu/com.aspose.slides/itiffoptions/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ITiffOptions extends ISaveOptions
```

Beállításokat biztosít, amelyek szabályozzák, hogyan mentődik egy prezentáció TIFF formátumban.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getImageSize()](#getImageSize--) | Megadja a generált TIFF kép méretét. |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | Megadja a generált TIFF kép méretét. |
| [getDpiX()](#getDpiX--) | Megadja a vízszintes felbontást pont per hüvelykben. |
| [setDpiX(long value)](#setDpiX-long-) | Megadja a vízszintes felbontást pont per hüvelykben. |
| [getDpiY()](#getDpiY--) | Megadja a függőleges felbontást pont per hüvelykben. |
| [setDpiY(long value)](#setDpiY-long-) | Megadja a függőleges felbontást pont per hüvelykben. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Megadja, hogy a generált dokumentumban legyenek-e rejtett diák vagy sem. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Megadja, hogy a generált dokumentumban legyenek-e rejtett diák vagy sem. |
| [getCompressionType()](#getCompressionType--) | Megadja a tömörítés típusát. |
| [setCompressionType(int value)](#setCompressionType-int-) | Megadja a tömörítés típusát. |
| [getPixelFormat()](#getPixelFormat--) | Megadja a generált képek pixelformátumát. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Megadja a generált képek pixelformátumát. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Lekéri vagy beállítja azt a módot, ahogy a diák az oldalon elhelyezésre kerülnek a prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Lekéri vagy beállítja azt a módot, ahogy a diák az oldalon elhelyezésre kerülnek a prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Megadja az algoritmust egy színes kép fekete-fehér képpé konvertálásához. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Megadja az algoritmust egy színes kép fekete-fehér képpé konvertálásához. |
| [getInkOptions()](#getInkOptions--) | Beállításokat biztosít, amelyek szabályozzák az Ink objektumok megjelenését az exportált dokumentumban. |
### getImageSize() {#getImageSize--}
```
public abstract Size getImageSize()
```

Megadja a generált TIFF kép méretét. Az alapértelmezett érték 0x0, ami azt jelenti, hogy a generált képméretek a prezentáció diákméretének értéke alapján kerülnek kiszámításra. Olvasás/írás [Size](../../com.aspose.slides.android/size).

**Visszatér:**  
[Size](../../com.aspose.slides.android/size)
### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public abstract void setImageSize(Size value)
```

Megadja a generált TIFF kép méretét. Az alapértelmezett érték 0x0, ami azt jelenti, hogy a generált képméretek a prezentáció diákméretének értéke alapján kerülnek kiszámításra. Olvasás/írás [Size](../../com.aspose.slides.android/size).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |
### getDpiX() {#getDpiX--}
```
public abstract long getDpiX()
```

Megadja a vízszintes felbontást pont per hüvelykben. Olvasás/írás long.

**Visszatér:**  
long
### setDpiX(long value) {#setDpiX-long-}
```
public abstract void setDpiX(long value)
```

Megadja a vízszintes felbontást pont per hüvelykben. Olvasás/írás long.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |
### getDpiY() {#getDpiY--}
```
public abstract long getDpiY()
```

Megadja a függőleges felbontást pont per hüvelykben. Olvasás/írás long.

**Visszatér:**  
long
### setDpiY(long value) {#setDpiY-long-}
```
public abstract void setDpiY(long value)
```

Megadja a függőleges felbontást pont per hüvelykben. Olvasás/írás long.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Megadja, hogy a generált dokumentumban legyenek-e rejtett diák vagy sem. Alapértelmezett érték false.

**Visszatér:**  
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Megadja, hogy a generált dokumentumban legyenek-e rejtett diák vagy sem. Alapértelmezett érték false.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getCompressionType() {#getCompressionType--}
```
public abstract int getCompressionType()
```

Megadja a tömörítés típusát. Olvasás/írás [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Visszatér:**  
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public abstract void setCompressionType(int value)
```

Megadja a tömörítés típusát. Olvasás/írás [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getPixelFormat() {#getPixelFormat--}
```
public abstract int getPixelFormat()
```

Megadja a generált képek pixelformátumát. Olvasás/írás [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Visszatér:**  
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public abstract void setPixelFormat(int value)
```

Megadja a generált képek pixelformátumát. Olvasás/írás [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Lekéri vagy beállítja azt a módot, ahogy a diák az oldalon elhelyezésre kerülnek a prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Példa:
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

Lekéri vagy beállítja azt a módot, ahogy a diák az oldalon elhelyezésre kerülnek a prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Példa:
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

Megadja az algoritmust egy színes kép fekete-fehér képpé konvertálásához. Ez az opció csak akkor lesz alkalmazva, ha a CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) vagy [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) értékre van állítva. Olvasás/írás [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Alapértelmezett érték [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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

Megadja az algoritmust egy színes kép fekete-fehér képpé konvertálásához. Ez az opció csak akkor lesz alkalmazva, ha a CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) vagy [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) értékre van állítva. Olvasás/írás [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Alapértelmezett érték [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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

Beállításokat biztosít, amelyek szabályozzák az Ink objektumok megjelenését az exportált dokumentumban. Csak olvasható [IInkOptions](../../com.aspose.slides/iinkoptions)

**Visszatér:**  
[IInkOptions](../../com.aspose.slides/iinkoptions)