---
title: ITiffOptions
second_title: Aspose.Slides pro Java API Reference
description: Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu TIFF.
type: docs
url: /cs/com.aspose.slides/itiffoptions/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ITiffOptions extends ISaveOptions
```

Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu TIFF.
## Metody

| Metoda | Popis |
| --- | --- |
| [getImageSize()](#getImageSize--) | Určuje velikost vygenerovaného TIFF obrázku. |
| [setImageSize(Dimension value)](#setImageSize-java.awt.Dimension-) | Určuje velikost vygenerovaného TIFF obrázku. |
| [getDpiX()](#getDpiX--) | Určuje horizontální rozlišení v bodech na palec. |
| [setDpiX(long value)](#setDpiX-long-) | Určuje horizontální rozlišení v bodech na palec. |
| [getDpiY()](#getDpiY--) | Určuje vertikální rozlišení v bodech na palec. |
| [setDpiY(long value)](#setDpiY-long-) | Určuje vertikální rozlišení v bodech na palec. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Určuje, zda má vygenerovaný dokument zahrnovat skryté snímky, nebo ne. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Určuje, zda má vygenerovaný dokument zahrnovat skryté snímky, nebo ne. |
| [getCompressionType()](#getCompressionType--) | Určuje typ komprese. |
| [setCompressionType(int value)](#setCompressionType-int-) | Určuje typ komprese. |
| [getPixelFormat()](#getPixelFormat--) | Určuje formát pixelů pro vygenerované obrázky. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Určuje formát pixelů pro vygenerované obrázky. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Získá nebo nastaví režim, ve kterém jsou snímky umístěny na stránku při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Získá nebo nastaví režim, ve kterém jsou snímky umístěny na stránku při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Určuje algoritmus pro převod barevného obrázku na černobílý obrázek. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Určuje algoritmus pro převod barevného obrázku na černobílý obrázek. |
| [getInkOptions()](#getInkOptions--) | Poskytuje možnosti, které řídí vzhled Ink objektů v exportovaném dokumentu. |
### getImageSize() {#getImageSize--}
```
public abstract Dimension getImageSize()
```

Určuje velikost vygenerovaného TIFF obrázku. Výchozí hodnota je 0x0, což znamená, že velikosti vygenerovaných obrázků budou vypočítány na základě hodnoty velikosti snímku prezentace. Čtení/zápis java.awt.Dimension.

**Vrací:**
java.awt.Dimension
### setImageSize(Dimension value) {#setImageSize-java.awt.Dimension-}
```
public abstract void setImageSize(Dimension value)
```

Určuje velikost vygenerovaného TIFF obrázku. Výchozí hodnota je 0x0, což znamená, že velikosti vygenerovaných obrázků budou vypočítány na základě hodnoty velikosti snímku prezentace. Čtení/zápis java.awt.Dimension.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.awt.Dimension |  |
### getDpiX() {#getDpiX--}
```
public abstract long getDpiX()
```

Určuje horizontální rozlišení v bodech na palec. Čtení/zápis long.

**Vrací:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public abstract void setDpiX(long value)
```

Určuje horizontální rozlišení v bodech na palec. Čtení/zápis long.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | long |  |
### getDpiY() {#getDpiY--}
```
public abstract long getDpiY()
```

Určuje vertikální rozlišení v bodech na palec. Čtení/zápis long.

**Vrací:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public abstract void setDpiY(long value)
```

Určuje vertikální rozlišení v bodech na palec. Čtení/zápis long.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | long |  |
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Určuje, zda má vygenerovaný dokument zahrnovat skryté snímky, nebo ne. Výchozí hodnota je false.

**Vrací:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Určuje, zda má vygenerovaný dokument zahrnovat skryté snímky, nebo ne. Výchozí hodnota je false.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getCompressionType() {#getCompressionType--}
```
public abstract int getCompressionType()
```

Určuje typ komprese. Čtení/zápis [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Vrací:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public abstract void setCompressionType(int value)
```

Určuje typ komprese. Čtení/zápis [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getPixelFormat() {#getPixelFormat--}
```
public abstract int getPixelFormat()
```

Určuje formát pixelů pro vygenerované obrázky. Čtení/zápis [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Vrací:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public abstract void setPixelFormat(int value)
```

Určuje formát pixelů pro vygenerované obrázky. Čtení/zápis [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Získá nebo nastaví režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Získá nebo nastaví režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public abstract int getBwConversionMode()
```

Určuje algoritmus pro převod barevného obrázku na černobílý obrázek. Tato možnost bude použita pouze pokud je CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) nastaven na [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) nebo [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) Čtení/zápis [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Výchozí hodnota je [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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
public abstract void setBwConversionMode(int value)
```

Určuje algoritmus pro převod barevného obrázku na černobílý obrázek. Tato možnost bude použita pouze pokud je CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) nastaven na [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) nebo [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) Čtení/zápis [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Výchozí hodnota je [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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
### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Poskytuje možnosti, které řídí vzhled Ink objektů v exportovaném dokumentu. Pouze ke čtení [IInkOptions](../../com.aspose.slides/iinkoptions)

**Vrací:**
[IInkOptions](../../com.aspose.slides/iinkoptions)