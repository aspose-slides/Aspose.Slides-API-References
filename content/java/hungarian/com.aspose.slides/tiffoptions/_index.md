---
title: TiffOptions
second_title: Aspose.Slides for Java API referencia
description: Lehetőségeket biztosít, amelyek szabályozzák, hogyan mentődik a prezentáció TIFF formátumban.
type: docs
url: /hu/com.aspose.slides/tiffoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**All Implemented Interfaces:**
[com.aspose.slides.ITiffOptions](../../com.aspose.slides/itiffoptions)
```
public class TiffOptions extends SaveOptions implements ITiffOptions
```

Olyan lehetőségeket biztosít, amelyek szabályozzák, hogyan mentődik a prezentáció TIFF formátumban.

--------------------

> ```
> The following example shows how to convert PowerPoint to TIFF with default size.
>  
>  // Példányosít egy Presentation objektumot, amely egy prezentáció fájlt képvisel
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      // A prezentáció mentése TIFF dokumentumba
>      pres.save("Tiffoutput_out.tiff", SaveFormat.Tiff);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom size.
>  
>  // Példányosít egy Presentation objektumot, amely egy Presentation fájlt képvisel
>  Presentation pres = new Presentation("Convert_Tiff_Custom.pptx");
>  try {
>      // Példányosítja a TiffOptions osztályt
>      TiffOptions opts = new TiffOptions();
>      // A tömörítés típusának beállítása
>      opts.setCompressionType(TiffCompressionTypes.Default);
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      opts.setSlidesLayoutOptions(notesOptions);
>      // Tömörítési típusok
>      // Default - A alapértelmezett tömörítési séma (LZW) meghatározása.
>      // None - Nincs tömörítés.
>      // CCITT3
>      // CCITT4
>      // LZW
>      // RLE
>      // A mélység a tömörítési típustól függ, és manuálisan nem állítható be.
>      // A felbontási egység mindig 2 (pont per hüvelyk) értékű.
>      // Képek DPI beállítása
>      opts.setDpiX(200);
>      opts.setDpiY(100);
>      // Kép méretének beállítása
>      opts.setImageSize(new Dimension(1728, 1078));
>      // Mentse a prezentációt TIFF-be a megadott képmérettel
>      pres.save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom image pixel format.
>  
>  // Példányosít egy Presentation objektumot, amely egy Presentation fájlt képvisel
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      options.setPixelFormat(ImagePixelFormat.Format8bppIndexed);
> 
>      //Az ImagePixelFormat a következő értékeket tartalmazza (ahogy a dokumentációban látható):
>      //Format1bppIndexed; // 1 bit/képpont, indexelt.
>      //Format4bppIndexed; // 4 bit/képpont, indexelt.
>      //Format8bppIndexed; // 8 bit/képpont, indexelt.
>      //Format24bppRgb; // 24 bit/képpont, RGB.
>      //Format32bppArgb; // 32 bit/képpont, ARGB.
> 
>      // Mentse a prezentációt TIFF-be a megadott képmérettel
>      pres.save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [TiffOptions()](#TiffOptions--) | Alapértelmezett konstruktor. |
## Methods

| Method | Description |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Olyan lehetőségeket biztosít, amelyek szabályozzák a tintás objektumok megjelenését az exportált dokumentumban. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Meghatározza, hogy a létrehozott dokumentum tartalmazzon-e rejtett diákat vagy sem. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Meghatározza, hogy a létrehozott dokumentum tartalmazzon-e rejtett diákat vagy sem. |
| [getImageSize()](#getImageSize--) | Meghatározza a létrehozott TIFF kép méretét. |
| [setImageSize(Dimension value)](#setImageSize-java.awt.Dimension-) | Meghatározza a létrehozott TIFF kép méretét. |
| [getDpiX()](#getDpiX--) | Meghatározza a vízszintes felbontást pont per hüvelykben. |
| [setDpiX(long value)](#setDpiX-long-) | Meghatározza a vízszintes felbontást pont per hüvelykben. |
| [getDpiY()](#getDpiY--) | Meghatározza a függőleges felbontást pont per hüvelykben. |
| [setDpiY(long value)](#setDpiY-long-) | Meghatározza a függőleges felbontást pont per hüvelykben. |
| [getCompressionType()](#getCompressionType--) | Meghatározza a tömörítés típusát. |
| [setCompressionType(int value)](#setCompressionType-int-) | Meghatározza a tömörítés típusát. |
| [getPixelFormat()](#getPixelFormat--) | Meghatározza a képpontformátumot a létrehozott képekhez. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Meghatározza a képpontformátumot a létrehozott képekhez. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Lekéri vagy beállítja a módot, ahogyan a diák elhelyezésre kerülnek az oldalon a prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Lekéri vagy beállítja a módot, ahogyan a diák elhelyezésre kerülnek az oldalon a prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Meghatározza az algoritmust, amely a színes képet fekete-fehér képpé alakítja. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Meghatározza az algoritmust, amely a színes képet fekete-fehér képpé alakítja. |
### TiffOptions() {#TiffOptions--}
```
public TiffOptions()
```


Alapértelmezett konstruktor.

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```


Olyan lehetőségeket biztosít, amelyek szabályozzák a tintás objektumok megjelenését az exportált dokumentumban. Csak olvasható [IInkOptions](../../com.aspose.slides/iinkoptions)

**Returns:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Meghatározza, hogy a létrehozott dokumentum tartalmazzon-e rejtett diákat vagy sem. Alapértelmezett érték false.

**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Meghatározza, hogy a létrehozott dokumentum tartalmazzon-e rejtett diákat vagy sem. Alapértelmezett érték false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getImageSize() {#getImageSize--}
```
public final Dimension getImageSize()
```


Meghatározza a létrehozott TIFF kép méretét. Alapértelmezett érték 0x0, ami azt jelenti, hogy a kép mérete a prezentáció diák méretéből lesz kiszámítva. Olvasható/írható java.awt.Dimension.

**Returns:**
java.awt.Dimension
### setImageSize(Dimension value) {#setImageSize-java.awt.Dimension-}
```
public final void setImageSize(Dimension value)
```


Meghatározza a létrehozott TIFF kép méretét. Alapértelmezett érték 0x0, ami azt jelenti, hogy a kép mérete a prezentáció diák méretéből lesz kiszámítva. Olvasható/írható java.awt.Dimension.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getDpiX() {#getDpiX--}
```
public final long getDpiX()
```


Meghatározza a vízszintes felbontást pont per hüvelykben. Olvasható/írható long.

**Returns:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public final void setDpiX(long value)
```


Meghatározza a vízszintes felbontást pont per hüvelykben. Olvasható/írható long.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public final long getDpiY()
```


Meghatározza a függőleges felbontást pont per hüvelykben. Olvasható/írható long.

**Returns:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public final void setDpiY(long value)
```


Meghatározza a függőleges felbontást pont per hüvelykben. Olvasható/írható long.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getCompressionType() {#getCompressionType--}
```
public final int getCompressionType()
```


Meghatározza a tömörítés típusát. Olvasható/írható [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Returns:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public final void setCompressionType(int value)
```


Meghatározza a tömörítés típusát. Olvasható/írható [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public final int getPixelFormat()
```


Meghatározza a képpontformátumot a létrehozott képekhez. Olvasható/írható [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Returns:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public final void setPixelFormat(int value)
```


Meghatározza a képpontformátumot a létrehozott képekhez. Olvasható/írható [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```


Lekéri vagy beállítja a módot, ahogyan a diák elhelyezésre kerülnek az oldalon a prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**Returns:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


Lekéri vagy beállítja a módot, ahogyan a diák elhelyezésre kerülnek az oldalon a prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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


Meghatározza az algoritmust, amely a színes képet fekete-fehér képpé alakítja. Ez a beállítás csak akkor kerül alkalmazásra, ha a CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) vagy [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) értékre van állítva. Olvasható/írható [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Alapértelmezett [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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

**Returns:**
int
### setBwConversionMode(int value) {#setBwConversionMode-int-}
```
public final void setBwConversionMode(int value)
```


Meghatározza az algoritmust, amely a színes képet fekete-fehér képpé alakítja. Ez a beállítás csak akkor kerül alkalmazásra, ha a CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) vagy [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) értékre van állítva. Olvasható/írható [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Alapértelmezett [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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