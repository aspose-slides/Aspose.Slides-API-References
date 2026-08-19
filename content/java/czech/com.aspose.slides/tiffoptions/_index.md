---
title: TiffOptions
second_title: Aspose.Slides pro Java API – reference
description: Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu TIFF.
type: docs
url: /cs/com.aspose.slides/tiffoptions/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Všechny implementované rozhraní:**
[com.aspose.slides.ITiffOptions](../../com.aspose.slides/itiffoptions)
```
public class TiffOptions extends SaveOptions implements ITiffOptions
```

Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu TIFF.

--------------------

> ```
> The following example shows how to convert PowerPoint to TIFF with default size.
>  
>  // Vytvořte objekt Presentation, který představuje soubor prezentace
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      // Uložení prezentace do TIFF dokumentu
>      pres.save("Tiffoutput_out.tiff", SaveFormat.Tiff);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom size.
>  
>  // Vytvořte objekt Presentation, který představuje soubor prezentace
>  Presentation pres = new Presentation("Convert_Tiff_Custom.pptx");
>  try {
>      // Vytvořte instanci třídy TiffOptions
>      TiffOptions opts = new TiffOptions();
>      // Nastavení typu komprese
>      opts.setCompressionType(TiffCompressionTypes.Default);
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      opts.setSlidesLayoutOptions(notesOptions);
>      // Typy komprese
>      // Výchozí - Určuje výchozí schéma komprese (LZW).
>      // Žádná - Určuje, že se žádná komprese nepoužije.
>      // CCITT3
>      // CCITT4
>      // LZW
>      // RLE
>      // Hloubka závisí na typu komprese a nelze ji nastavit ručně.
>      // Jednotka rozlišení je vždy rovna 2 (bodů na palec)
>      // Nastavení DPI obrazu
>      opts.setDpiX(200);
>      opts.setDpiY(100);
>      // Nastavte velikost obrazu
>      opts.setImageSize(new Dimension(1728, 1078));
>      // Uložte prezentaci do TIFF s určenou velikostí obrazu
>      pres.save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom image pixel format.
>  
>  // Vytvořte objekt Presentation, který představuje soubor prezentace
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      options.setPixelFormat(ImagePixelFormat.Format8bppIndexed);
> 
>      //ImagePixelFormat obsahuje následující hodnoty (jak je vidět v dokumentaci):
>      //Format1bppIndexed; // 1 bit na pixel, indexovaný.
>      //Format4bppIndexed; // 4 bity na pixel, indexovaný.
>      //Format8bppIndexed; // 8 bitů na pixel, indexovaný.
>      //Format24bppRgb; // 24 bitů na pixel, RGB.
>      //Format32bppArgb; // 32 bitů na pixel, ARGB.
> 
>      // Uložte prezentaci do TIFF s určenou velikostí obrazu
>      pres.save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktorové metody

| Konstruktor | Popis |
| --- | --- |
| [TiffOptions()](#TiffOptions--) | Výchozí konstruktor. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Poskytuje možnosti, které řídí vzhled objektů Ink v exportovaném dokumentu. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Určuje, zda má vygenerovaný dokument zahrnovat skryté snímky, nebo ne. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Určuje, zda má vygenerovaný dokument zahrnovat skryté snímky, nebo ne. |
| [getImageSize()](#getImageSize--) | Určuje velikost vygenerovaného TIFF obrázku. |
| [setImageSize(Dimension value)](#setImageSize-java.awt.Dimension-) | Určuje velikost vygenerovaného TIFF obrázku. |
| [getDpiX()](#getDpiX--) | Určuje vodorovné rozlišení v bodech na palec. |
| [setDpiX(long value)](#setDpiX-long-) | Určuje vodorovné rozlišení v bodech na palec. |
| [getDpiY()](#getDpiY--) | Určuje svislé rozlišení v bodech na palec. |
| [setDpiY(long value)](#setDpiY-long-) | Určuje svislé rozlišení v bodech na palec. |
| [getCompressionType()](#getCompressionType--) | Určuje typ komprese. |
| [setCompressionType(int value)](#setCompressionType-int-) | Určuje typ komprese. |
| [getPixelFormat()](#getPixelFormat--) | Určuje formát pixelů pro vygenerované obrázky. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Určuje formát pixelů pro vygenerované obrázky. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Získá nebo nastaví režim, ve kterém jsou snímky umístěny na stránku při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Získá nebo nastaví režim, ve kterém jsou snímky umístěny na stránku při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Určuje algoritmus pro převod barevného obrázku na černobílý obrázek. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Určuje algoritmus pro převod barevného obrázku na černobílý obrázek. |
### TiffOptions() {#TiffOptions--}
```
public TiffOptions()
```

Výchozí konstruktor.

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Poskytuje možnosti, které řídí vzhled objektů Ink v exportovaném dokumentu. Pouze pro čtení [IInkOptions](../../com.aspose.slides/iinkoptions)

**Vrací:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Určuje, zda má vygenerovaný dokument zahrnovat skryté snímky, nebo ne. Výchozí hodnota je false.

**Vrací:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Určuje, zda má vygenerovaný dokument zahrnovat skryté snímky, nebo ne. Výchozí hodnota je false.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getImageSize() {#getImageSize--}
```
public final Dimension getImageSize()
```

Určuje velikost vygenerovaného TIFF obrázku. Výchozí hodnota je 0x0, což znamená, že velikosti vygenerovaných obrázků budou vypočteny na základě velikosti snímku prezentace. Čtení/zápis java.awt.Dimension.

**Vrací:**
java.awt.Dimension
### setImageSize(Dimension value) {#setImageSize-java.awt.Dimension-}
```
public final void setImageSize(Dimension value)
```

Určuje velikost vygenerovaného TIFF obrázku. Výchozí hodnota je 0x0, což znamená, že velikosti vygenerovaných obrázků budou vypočteny na základě velikosti snímku prezentace. Čtení/zápis java.awt.Dimension.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.awt.Dimension |  |
### getDpiX() {#getDpiX--}
```
public final long getDpiX()
```

Určuje vodorovné rozlišení v bodech na palec. Čtení/zápis long.

**Vrací:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public final void setDpiX(long value)
```

Určuje vodorovné rozlišení v bodech na palec. Čtení/zápis long.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | long |  |
### getDpiY() {#getDpiY--}
```
public final long getDpiY()
```

Určuje svislé rozlišení v bodech na palec. Čtení/zápis long.

**Vrací:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public final void setDpiY(long value)
```

Určuje svislé rozlišení v bodech na palec. Čtení/zápis long.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | long |  |
### getCompressionType() {#getCompressionType--}
```
public final int getCompressionType()
```

Určuje typ komprese. Čtení/zápis [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Vrací:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public final void setCompressionType(int value)
```

Určuje typ komprese. Čtení/zápis [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getPixelFormat() {#getPixelFormat--}
```
public final int getPixelFormat()
```

Určuje formát pixelů pro vygenerované obrázky. Čtení/zápis [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Vrací:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public final void setPixelFormat(int value)
```

Určuje formát pixelů pro vygenerované obrázky. Čtení/zápis [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Získá nebo nastaví režim, ve kterém jsou snímky umístěny na stránku při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**Vrací:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Získá nebo nastaví režim, ve kterém jsou snímky umístěny na stránku při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |
### getBwConversionMode() {#getBwConversionMode--}
```
public final int getBwConversionMode()
```

Určuje algoritmus pro převod barevného obrázku na černobílý obrázek. Tato možnost bude použita pouze pokud je CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) nastaven na [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) nebo [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3). Čtení/zápis [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Výchozí je [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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

**Vrací:**
int
### setBwConversionMode(int value) {#setBwConversionMode-int-}
```
public final void setBwConversionMode(int value)
```

Určuje algoritmus pro převod barevného obrázku na černobílý obrázek. Tato možnost bude použita pouze pokud je CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) nastaven na [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) nebo [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3). Čtení/zápis [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Výchozí je [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |