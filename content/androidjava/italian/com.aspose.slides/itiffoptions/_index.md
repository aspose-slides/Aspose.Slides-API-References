---
title: ITiffOptions
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Fornisce opzioni che controllano come una presentazione viene salvata in formato TIFF.
type: docs
url: /it/com.aspose.slides/itiffoptions/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ITiffOptions extends ISaveOptions
```

Fornisce opzioni che controllano come una presentazione viene salvata in formato TIFF.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getImageSize()](#getImageSize--) | Specifica la dimensione di un'immagine TIFF generata. |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | Specifica la dimensione di un'immagine TIFF generata. |
| [getDpiX()](#getDpiX--) | Specifica la risoluzione orizzontale in punti per pollice. |
| [setDpiX(long value)](#setDpiX-long-) | Specifica la risoluzione orizzontale in punti per pollice. |
| [getDpiY()](#getDpiY--) | Specifica la risoluzione verticale in punti per pollice. |
| [setDpiY(long value)](#setDpiY-long-) | Specifica la risoluzione verticale in punti per pollice. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specifica se il documento generato deve includere le diapositive nascoste o meno. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specifica se il documento generato deve includere le diapositive nascoste o meno. |
| [getCompressionType()](#getCompressionType--) | Specifica il tipo di compressione. |
| [setCompressionType(int value)](#setCompressionType-int-) | Specifica il tipo di compressione. |
| [getPixelFormat()](#getPixelFormat--) | Specifica il formato pixel per le immagini generate. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Specifica il formato pixel per le immagini generate. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Ottiene o imposta la modalità in cui le diapositive vengono posizzionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Ottiene o imposta la modalità in cui le diapositive vengono posizzionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Specifica l'algoritmo per la conversione di un'immagine a colori in un'immagine in bianco e nero. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Specifica l'algoritmo per la conversione di un'immagine a colori in un'immagine in bianco e nero. |
| [getInkOptions()](#getInkOptions--) | Fornisce opzioni che controllano l'aspetto degli oggetti Ink nel documento esportato. |

### getImageSize() {#getImageSize--}
```
public abstract Size getImageSize()
```

Specifica la dimensione di un'immagine TIFF generata. Il valore predefinito è 0x0, il che significa che le dimensioni dell'immagine generata verranno calcolate in base al valore della dimensione della diapositiva della presentazione. Lettura/Scrittura [Size](../../com.aspose.slides.android/size).

**Restituisce:**
[Size](../../com.aspose.slides.android/size)

### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public abstract void setImageSize(Size value)
```

Specifica la dimensione di un'immagine TIFF generata. Il valore predefinito è 0x0, il che significa che le dimensioni dell'immagine generata verranno calcolate in base al valore della dimensione della diapositiva della presentazione. Lettura/Scrittura [Size](../../com.aspose.slides.android/size).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getDpiX() {#getDpiX--}
```
public abstract long getDpiX()
```

Specifică la risoluzione orizzontale in punti per pollice. Lettura/Scrittura long.

**Restituisce:**
long

### setDpiX(long value) {#setDpiX-long-}
```
public abstract void setDpiX(long value)
```

Specifică la risoluzione orizzontale in punti per pollice. Lettura/Scrittura long.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public abstract long getDpiY()
```

Specifică la risoluzione verticale in punti per pollice. Lettura/Scrittura long.

**Restituisce:**
long

### setDpiY(long value) {#setDpiY-long-}
```
public abstract void setDpiY(long value)
```

Specifică la risoluzione verticale in punti per pollice. Lettura/Scrittura long.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | long |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Specifică se il documento generato deve includere le diapositive nascoste o meno. Il valore predefinito è false.

**Restituisce:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Specifică se il documento generato deve includere le diapositive nascoste o meno. Il valore predefinito è false.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getCompressionType() {#getCompressionType--}
```
public abstract int getCompressionType()
```

Specifică il tipo di compressione. Lettura/Scrittura [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Restituisce:**
int

### setCompressionType(int value) {#setCompressionType-int-}
```
public abstract void setCompressionType(int value)
```

Specifică il tipo di compressione. Lettura/Scrittura [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public abstract int getPixelFormat()
```

Specifică il formato pixel per le immagini generate. Lettura/Scrittura [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Restituisce:**
int

### setPixelFormat(int value) {#setPixelFormat-int-}
```
public abstract void setPixelFormat(int value)
```

Specifică il formato pixel per le immagini generate. Lettura/Scrittura [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Ottiene o imposta la modalità in cui le diapositive vengono posizzionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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


**Restituisce:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Ottiene o imposta la modalità in cui le diapositive vengono posizzionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getBwConversionMode() {#getBwConversionMode--}
```
public abstract int getBwConversionMode()
```

Specifică l'algoritmo per la conversione di un'immagine a colori in un'immagine in bianco e nero. Questa opzione verrà applicata solo se CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) è impostato a [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) o [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) Lettura/Scrittura [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Il valore predefinito è [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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


**Restituisce:**
int

### setBwConversionMode(int value) {#setBwConversionMode-int-}
```
public abstract void setBwConversionMode(int value)
```

Specifică l'algoritmo per la conversione di un'immagine a colori in un'immagine in bianco e nero. Questa opzione verrà applicata solo se CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) è impostato a [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) o [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) Lettura/Scrittura [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Il valore predefinito è [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Fornisce opzioni che controllano l'aspetto degli oggetti Ink nel documento esportato. Sola lettura [IInkOptions](../../com.aspose.slides/iinkoptions)

**Restituisce:**
[IInkOptions](../../com.aspose.slides/iinkoptions)