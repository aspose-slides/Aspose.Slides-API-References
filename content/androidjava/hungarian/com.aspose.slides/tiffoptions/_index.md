---
title: TiffOptions
second_title: Aspose.Slides Androidhoz a Java API hivatkozásban
description: Lehetőségeket biztosít, amelyek szabályozzák, hogyan mentődik a prezentáció TIFF formátumban.
type: docs
url: /hu/com.aspose.slides/tiffoptions/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Minden megvalósított interfész:**
[com.aspose.slides.ITiffOptions](../../com.aspose.slides/itiffoptions)
```
public class TiffOptions extends SaveOptions implements ITiffOptions
```

Lehetőségeket ad meg, amelyek szabályozzák a prezentáció TIFF formátumban való mentését.

--------------------

> ```
> The following example shows how to convert PowerPoint to TIFF with default size.
>  
>  // Példányosít egy Presentation objektumot, amely egy prezentációs fájlt képvisel
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
>      // Tömörítési típus beállítása
>      opts.setCompressionType(TiffCompressionTypes.Default);
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      opts.setSlidesLayoutOptions(notesOptions);
>      // Tömörítési típusok
>      // Default - A (LZW) alapértelmezett tömörítési séma.
>      // None - Nem alkalmaz semmilyen tömörítést.
>      // CCITT3
>      // CCITT4
>      // LZW
>      // RLE
>      // A mélység a tömörítési típustól függ, és nem állítható manuálisan.
>      // A felbontási egység mindig 2 (pont per hüvelyk)
>      // Kép DPI beállítása
>      opts.setDpiX(200);
>      opts.setDpiY(100);
>      // Kép méretének beállítása
>      opts.setImageSize(new com.aspose.slides.android.Size(1728, 1078));
>      // A prezentáció mentése TIFF-be a megadott képmérettel
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
>      // ImagePixelFormat a következő értékeket tartalmazza (a dokumentációból látható):
>      //Format1bppIndexed; // 1 bit képpontonként, indexált.
>      //Format4bppIndexed; // 4 bit képpontonként, indexált.
>      //Format8bppIndexed; // 8 bit képpontonként, indexált.
>      //Format24bppRgb; // 24 bit képpontonként, RGB.
>      //Format32bppArgb; // 32 bit képpontonként, ARGB.
> 
>      // A prezentáció mentése TIFF-be a megadott képmérettel
>      pres.save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [TiffOptions()](#TiffOptions--) | Alapértelmezett konstruktor. |
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Lehetőségeket biztosít, amelyek a kiexportált dokumentumban lévő Ink objektumok megjelenését szabályozzák. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Megadja, hogy a generált dokumentum tartalmazzon rejtett diákot vagy sem. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Megadja, hogy a generált dokumentum tartalmazzon rejtett diákot vagy sem. |
| [getImageSize()](#getImageSize--) | Megadja a generált TIFF kép méretét. |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | Megadja a generált TIFF kép méretét. |
| [getDpiX()](#getDpiX--) | Megadja a vízszintes felbontást pont per hüvelykben. |
| [setDpiX(long value)](#setDpiX-long-) | Megadja a vízszintes felbontást pont per hüvelykben. |
| [getDpiY()](#getDpiY--) | Megadja a függőleges felbontást pont per hüvelykben. |
| [setDpiY(long value)](#setDpiY-long-) | Megadja a függőleges felbontást pont per hüvelykben. |
| [getCompressionType()](#getCompressionType--) | Megadja a tömörítési típust. |
| [setCompressionType(int value)](#setCompressionType-int-) | Megadja a tömörítési típust. |
| [getPixelFormat()](#getPixelFormat--) | Megadja a generált képek képpontformátumát. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Megadja a generált képek képpontformátumát. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Megkapja vagy beállítja a módot, ahogyan a diák az oldalon helyezkednek el egy prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Megkapja vagy beállítja a módot, ahogyan a diák az oldalon helyezkednek el egy prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Megadja az algoritmust, amely színes képet fekete-fehér képpé konvertál. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Megadja az algoritmust, amely színes képet fekete-fehér képpé konvertál. |
### TiffOptions() {#TiffOptions--}
```
public TiffOptions()
```


Alapértelmezett konstruktor.

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```


Lehetőségeket ad meg, amelyek a kiexportált dokumentumban lévő Ink objektumok megjelenését szabályozzák. Csak olvasható [IInkOptions](../../com.aspose.slides/iinkoptions)

**Visszatérési érték:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákot vagy sem. Alapértelmezett érték false.

**Visszatérési érték:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákot vagy sem. Alapértelmezett érték false.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getImageSize() {#getImageSize--}
```
public final Size getImageSize()
```


Megadja a generált TIFF kép méretét. Az alapértelmezett érték 0x0, ami azt jelenti, hogy a generált képméretek a prezentáció dia méretén alapulva lesznek kiszámítva. Olvasás/írás [Size](../../com.aspose.slides.android/size).

**Visszatérési érték:**
[Size](../../com.aspose.slides.android/size)
### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public final void setImageSize(Size value)
```


Megadja a generált TIFF kép méretét. Az alapértelmezett érték 0x0, ami azt jelenti, hogy a generált képméretek a prezentáció dia méretén alapulva lesznek kiszámítva. Olvasás/írás [Size](../../com.aspose.slides.android/size).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getDpiX() {#getDpiX--}
```
public final long getDpiX()
```


Megadja a vízszintes felbontást pont per hüvelykben. Olvasás/írás long.

**Visszatérési érték:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public final void setDpiX(long value)
```


Megadja a vízszintes felbontást pont per hüvelykben. Olvasás/írás long.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public final long getDpiY()
```


Megadja a függőleges felbontást pont per hüvelykben. Olvasás/írás long.

**Visszatérési érték:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public final void setDpiY(long value)
```


Megadja a függőleges felbontást pont per hüvelykben. Olvasás/írás long.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |

### getCompressionType() {#getCompressionType--}
```
public final int getCompressionType()
```


Megadja a tömörítési típust. Olvasás/írás [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Visszatérési érték:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public final void setCompressionType(int value)
```


Megadja a tömörítési típust. Olvasás/írás [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public final int getPixelFormat()
```


Megadja a generált képek képpontformátumát. Olvasás/írás [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Visszatérési érték:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public final void setPixelFormat(int value)
```


Megadja a generált képek képpontformátumát. Olvasás/írás [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```


Megkapja vagy beállítja a módot, ahogyan a diák az oldalon helyezkednek el egy prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**Visszatérési érték:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


Megkapja vagy beállítja a módot, ahogyan a diák az oldalon helyezkednek el egy prezentáció exportálásakor [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public final int getBwConversionMode()
```


Megadja a színes képet fekete-fehér képpé konvertáló algoritmust. Ez az opció csak akkor kerül alkalmazásra, ha a CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) vagy [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) értékre van állítva. Olvasás/írás [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Alapértelmezett érték [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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

**Visszatérési érték:**
int
### setBwConversionMode(int value) {#setBwConversionMode-int-}
```
public final void setBwConversionMode(int value)
```


Megadja a színes képet fekete-fehér képpé konvertáló algoritmust. Ez az opció csak akkor kerül alkalmazásra, ha a CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) vagy [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) értékre van állítva. Olvasás/írás [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Alapértelmezett érték [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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