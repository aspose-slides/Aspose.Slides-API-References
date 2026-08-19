---
title: TiffOptions
second_title: Riferimento API di Aspose.Slides per Java
description: Fornisce opzioni che controllano come una presentazione viene salvata in formato TIFF.
type: docs
url: /it/com.aspose.slides/tiffoptions/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Tutte le interfacce implementate:**
[com.aspose.slides.ITiffOptions](../../com.aspose.slides/itiffoptions)
```
public class TiffOptions extends SaveOptions implements ITiffOptions
```

Fornisce opzioni che controllano come una presentazione viene salvata nel formato TIFF.

--------------------

> ```
> The following example shows how to convert PowerPoint to TIFF with default size.
>  
>  // Istanziare un oggetto Presentation che rappresenta un file di presentazione
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      // Salvataggio della presentazione in documento TIFF
>      pres.save("Tiffoutput_out.tiff", SaveFormat.Tiff);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom size.
>  
>  // Istanziare un oggetto Presentation che rappresenta un file di presentazione
>  Presentation pres = new Presentation("Convert_Tiff_Custom.pptx");
>  try {
>      // Istanziare la classe TiffOptions
>      TiffOptions opts = new TiffOptions();
>      // Impostazione del tipo di compressione
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
>      // Impostazione DPI immagine
>      opts.setDpiX(200);
>      opts.setDpiY(100);
>      // Imposta dimensione immagine
>      opts.setImageSize(new Dimension(1728, 1078));
>      // Salva la presentazione in TIFF con la dimensione immagine specificata
>      pres.save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom image pixel format.
>  
>  // Istanziare un oggetto Presentation che rappresenta un file di presentazione
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      options.setPixelFormat(ImagePixelFormat.Format8bppIndexed);
> 
>      //ImagePixelFormat contiene i seguenti valori (come si può vedere dalla documentazione):
>      //Format1bppIndexed; // 1 bit per pixel, indicizzato.
>      //Format4bppIndexed; // 4 bit per pixel, indicizzato.
>      //Format8bppIndexed; // 8 bit per pixel, indicizzato.
>      //Format24bppRgb; // 24 bit per pixel, RGB.
>      //Format32bppArgb; // 32 bit per pixel, ARGB.
> 
>      // Salva la presentazione in TIFF con la dimensione immagine specificata
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
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specificare se il documento generato deve includere diapositive nascoste o meno. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specificare se il documento generato deve includere diapositive nascoste o meno. |
| [getImageSize()](#getImageSize--) | Specificare le dimensioni di un'immagine TIFF generata. |
| [setImageSize(Dimension value)](#setImageSize-java.awt.Dimension-) | Specificare le dimensioni di un'immagine TIFF generata. |
| [getDpiX()](#getDpiX--) | Specificare la risoluzione orizzontale in punti per pollice. |
| [setDpiX(long value)](#setDpiX-long-) | Specificare la risoluzione orizzontale in punti per pollice. |
| [getDpiY()](#getDpiY--) | Specificare la risoluzione verticale in punti per pollice. |
| [setDpiY(long value)](#setDpiY-long-) | Specificare la risoluzione verticale in punti per pollice. |
| [getCompressionType()](#getCompressionType--) | Specificare il tipo di compressione. |
| [setCompressionType(int value)](#setCompressionType-int-) | Specificare il tipo di compressione. |
| [getPixelFormat()](#getPixelFormat--) | Specificare il formato pixel per le immagini generate. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Specificare il formato pixel per le immagini generate. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Ottiene o imposta la modalità in cui le diapositive vengono posizionate nella pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Ottiene o imposta la modalità in cui le diapositive vengono posizionate nella pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Specificare l'algoritmo per convertire un'immagine a colori in un'immagine in bianco e nero. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Specificare l'algoritmo per convertire un'immagine a colori in un'immagine in bianco e nero. |
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

Specificare se il documento generato deve includere diapositive nascoste o meno. Il valore predefinito è false.

**Restituisce:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Specificare se il documento generato deve includere diapositive nascoste o meno. Il valore predefinito è false.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getImageSize() {#getImageSize--}
```
public final Dimension getImageSize()
```

Specificare le dimensioni di un'immagine TIFF generata. Il valore predefinito è 0x0, il che significa che le dimensioni delle immagini generate saranno calcolate in base al valore della dimensione della diapositiva della presentazione. Lettura/scrittura java.awt.Dimension.

**Restituisce:**
java.awt.Dimension
### setImageSize(Dimension value) {#setImageSize-java.awt.Dimension-}
```
public final void setImageSize(Dimension value)
```

Specificare le dimensioni di un'immagine TIFF generata. Il valore predefinito è 0x0, il che significa che le dimensioni delle immagini generate saranno calcolate in base al valore della dimensione della diapositiva della presentazione. Lettura/scrittura java.awt.Dimension.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.awt.Dimension |  |
### getDpiX() {#getDpiX--}
```
public final long getDpiX()
```

Specificare la risoluzione orizzontale in punti per pollice. Lettura/scrittura long.

**Restituisce:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public final void setDpiX(long value)
```

Specificare la risoluzione orizzontale in punti per pollice. Lettura/scrittura long.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | long |  |
### getDpiY() {#getDpiY--}
```
public final long getDpiY()
```

Specificare la risoluzione verticale in punti per pollice. Lettura/scrittura long.

**Restituisce:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public final void setDpiY(long value)
```

Specificare la risoluzione verticale in punti per pollice. Lettura/scrittura long.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | long |  |
### getCompressionType() {#getCompressionType--}
```
public final int getCompressionType()
```

Specificare il tipo di compressione. Lettura/scrittura [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Restituisce:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public final void setCompressionType(int value)
```

Specificare il tipo di compressione. Lettura/scrittura [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getPixelFormat() {#getPixelFormat--}
```
public final int getPixelFormat()
```

Specificare il formato pixel per le immagini generate. Lettura/scrittura [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Restituisce:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public final void setPixelFormat(int value)
```

Specificare il formato pixel per le immagini generate. Lettura/scrittura [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Ottiene o imposta la modalità in cui le diapositive vengono posizionate nella pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

Ottiene o imposta la modalità in cui le diapositive vengono posizionate nella pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

Specificare l'algoritmo per convertire un'immagine a colori in un'immagine in bianco e nero. Questa opzione verrà applicata solo se CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) è impostato su [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) o [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) Lettura/scrittura [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Il valore predefinito è [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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

Specificare l'algoritmo per convertire un'immagine a colori in un'immagine in bianco e nero. Questa opzione verrà applicata solo se CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) è impostato su [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) o [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) Lettura/scrittura [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Il valore predefinito è [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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