---
title: TiffOptions
second_title: Riferimento API Java di Aspose.Slides per Android
description: Fornisce opzioni che controllano come una presentazione viene salvata in formato TIFF.
type: docs
url: /it/com.aspose.slides/tiffoptions/
---
**Eredita da:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Tutte le interfacce implementate:**
[com.aspose.slides.ITiffOptions](../../com.aspose.slides/itiffoptions)
```
public class TiffOptions extends SaveOptions implements ITiffOptions
```

Fornisce opzioni che controllano come una presentazione viene salvata in formato TIFF.

--------------------

> ```
> The following example shows how to convert PowerPoint to TIFF with default size.
>  
>  // Istanzia un oggetto Presentation che rappresenta un file di presentazione
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      // Salva la presentazione in un documento TIFF
>      pres.save("Tiffoutput_out.tiff", SaveFormat.Tiff);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom size.
>  
>  // Istanzia un oggetto Presentation che rappresenta un file Presentation
>  Presentation pres = new Presentation("Convert_Tiff_Custom.pptx");
>  try {
>      // Istanzia la classe TiffOptions
>      TiffOptions opts = new TiffOptions();
>      // Imposta il tipo di compressione
>      opts.setCompressionType(TiffCompressionTypes.Default);
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      opts.setSlidesLayoutOptions(notesOptions);
>      // Tipi di compressione
>      // Default - Specifica lo schema di compressione predefinito (LZW).
>      // None - Specifica nessuna compressione.
>      // CCITT3
>      // CCITT4
>      // LZW
>      // RLE
>      // La profondità dipende dal tipo di compressione e non può essere impostata manualmente.
>      // L'unità di risoluzione è sempre uguale a 2 (punti per pollice)
>      // Impostazione DPI dell'immagine
>      opts.setDpiX(200);
>      opts.setDpiY(100);
>      // Imposta le dimensioni dell'immagine
>      opts.setImageSize(new com.aspose.slides.android.Size(1728, 1078));
>      // Salva la presentazione in TIFF con le dimensioni dell'immagine specificate
>      pres.save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom image pixel format.
>  
>  // Istanzia un oggetto Presentation che rappresenta un file Presentation
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      options.setPixelFormat(ImagePixelFormat.Format8bppIndexed);
> 
>      // ImagePixelFormat contiene i seguenti valori (come mostrato nella documentazione):
>      //Format1bppIndexed; // 1 bit per pixel, indicizzato.
>      //Format4bppIndexed; // 4 bit per pixel, indicizzato.
>      //Format8bppIndexed; // 8 bit per pixel, indicizzato.
>      //Format24bppRgb; // 24 bit per pixel, RGB.
>      //Format32bppArgb; // 32 bit per pixel, ARGB.
> 
>      // Salva la presentazione in TIFF con le dimensioni dell'immagine specificate
>      pres.save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TiffOptions()](#TiffOptions--) | Costruttore predefinito. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Fornisce opzioni che controllano l'aspetto degli oggetti Ink nel documento esportato. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specifica se il documento generato deve includere diapositive nascoste o meno. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specifica se il documento generato deve includere diapositive nascoste o meno. |
| [getImageSize()](#getImageSize--) | Specifica le dimensioni di un'immagine TIFF generata. |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | Specifica le dimensioni di un'immagine TIFF generata. |
| [getDpiX()](#getDpiX--) | Specifica la risoluzione orizzontale in punti per pollice. |
| [setDpiX(long value)](#setDpiX-long-) | Specifica la risoluzione orizzontale in punti per pollice. |
| [getDpiY()](#getDpiY--) | Specifica la risoluzione verticale in punti per pollice. |
| [setDpiY(long value)](#setDpiY-long-) | Specifica la risoluzione verticale in punti per pollice. |
| [getCompressionType()](#getCompressionType--) | Specifica il tipo di compressione. |
| [setCompressionType(int value)](#setCompressionType-int-) | Specifica il tipo di compressione. |
| [getPixelFormat()](#getPixelFormat--) | Specifica il formato pixel per le immagini generate. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Specifica il formato pixel per le immagini generate. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Ottiene o imposta la modalità in cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Ottiene o imposta la modalità in cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Specifica l'algoritmo per convertire un'immagine a colori in un'immagine in bianco e nero. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Specifica l'algoritmo per convertire un'immagine a colori in un'immagine in bianco e nero. |
### TiffOptions() {#TiffOptions--}
```
public TiffOptions()
```


Costruttore predefinito.

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```


Fornisce opzioni che controllano l'aspetto degli oggetti Ink nel documento esportato. Solo lettura [IInkOptions](../../com.aspose.slides/iinkoptions)

**Restituisce:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Specifica se il documento generato deve includere diapositive nascoste o meno. Predefinito è false.

**Restituisce:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Specifica se il documento generato deve includere diapositive nascoste o meno. Predefinito è false.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getImageSize() {#getImageSize--}
```
public final Size getImageSize()
```


Specifica le dimensioni di un'immagine TIFF generata. Il valore predefinito è 0x0, il che significa che le dimensioni dell'immagine generata saranno calcolate in base al valore della dimensione della diapositiva della presentazione. Lettura/scrittura [Size](../../com.aspose.slides.android/size).

**Restituisce:**
[Size](../../com.aspose.slides.android/size)
### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public final void setImageSize(Size value)
```


Specifica le dimensioni di un'immagine TIFF generata. Il valore predefinito è 0x0, il che significa che le dimensioni dell'immagine generata saranno calcolate in base al valore della dimensione della diapositiva della presentazione. Lettura/scrittura [Size](../../com.aspose.slides.android/size).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getDpiX() {#getDpiX--}
```
public final long getDpiX()
```


Specifica la risoluzione orizzontale in punti per pollice. Lettura/scrittura long.

**Restituisce:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public final void setDpiX(long value)
```


Specifica la risoluzione orizzontale in punti per pollice. Lettura/scrittura long.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public final long getDpiY()
```


Specifica la risoluzione verticale in punti per pollice. Lettura/scrittura long.

**Restituisce:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public final void setDpiY(long value)
```


Specifica la risoluzione verticale in punti per pollice. Lettura/scrittura long.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | long |  |

### getCompressionType() {#getCompressionType--}
```
public final int getCompressionType()
```


Specifica il tipo di compressione. Lettura/scrittura [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Restituisce:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public final void setCompressionType(int value)
```


Specifica il tipo di compressione. Lettura/scrittura [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public final int getPixelFormat()
```


Specifica il formato pixel per le immagini generate. Lettura/scrittura [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Restituisce:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public final void setPixelFormat(int value)
```


Specifica il formato pixel per le immagini generate. Lettura/scrittura [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```


Ottiene o imposta la modalità in cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


Ottiene o imposta la modalità in cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public final int getBwConversionMode()
```


Specifica l'algoritmo per convertire un'immagine a colori in un'immagine in bianco e nero. Questa opzione sarà applicata solo se CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) è impostato su [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) o [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) Lettura/scrittura [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Il valore predefinito è [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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
public final void setBwConversionMode(int value)
```


Specifica l'algoritmo per convertire un'immagine a colori in un'immagine in bianco e nero. Questa opzione sarà applicata solo se CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) è impostato su [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) o [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) Lettura/scrittura [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Il valore predefinito è [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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