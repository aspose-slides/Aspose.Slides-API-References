---
title: TiffOptions
second_title: Aspose.Slides pour Android via la référence API Java
description: Fournit des options qui contrôlent la façon dont une présentation est enregistrée au format TIFF.
type: docs
url: /fr/com.aspose.slides/tiffoptions/
---
**Héritage:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Toutes les interfaces implémentées:**
[com.aspose.slides.ITiffOptions](../../com.aspose.slides/itiffoptions)
```
public class TiffOptions extends SaveOptions implements ITiffOptions
```

Fournit des options qui contrôlent la façon dont une présentation est enregistrée au format TIFF.

--------------------

> ```
> The following example shows how to convert PowerPoint to TIFF with default size.
>  
>  // Instancie un objet Presentation qui représente un fichier de présentation
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      // Enregistre la présentation au format TIFF
>      pres.save("Tiffoutput_out.tiff", SaveFormat.Tiff);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom size.
>  
>  // Instancie un objet Presentation qui représente un fichier Presentation
>  Presentation pres = new Presentation("Convert_Tiff_Custom.pptx");
>  try {
>      // Instancie la classe TiffOptions
>      TiffOptions opts = new TiffOptions();
>      // Définit le type de compression
>      opts.setCompressionType(TiffCompressionTypes.Default);
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      opts.setSlidesLayoutOptions(notesOptions);
>      // Types de compression
>      // Default - Spécifie le schéma de compression par défaut (LZW).
>      // None - Spécifie aucune compression.
>      // CCITT3
>      // CCITT4
>      // LZW
>      // RLE
>      // La profondeur dépend du type de compression et ne peut pas être définie manuellement.
>      // L'unité de résolution est toujours égale à 2 (points par pouce)
>      // Définit le DPI de l'image
>      opts.setDpiX(200);
>      opts.setDpiY(100);
>      // Définit la taille de l'image
>      opts.setImageSize(new com.aspose.slides.android.Size(1728, 1078));
>      // Enregistre la présentation au format TIFF avec la taille d'image spécifiée
>      pres.save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom image pixel format.
>  
>  // Instancie un objet Presentation qui représente un fichier Presentation
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      options.setPixelFormat(ImagePixelFormat.Format8bppIndexed);
> 
>      // ImagePixelFormat contient les valeurs suivantes (comme indiqué dans la documentation) :
>      //Format1bppIndexed; // 1 bit par pixel, indexé.
>      //Format4bppIndexed; // 4 bits par pixel, indexé.
>      //Format8bppIndexed; // 8 bits par pixel, indexé.
>      //Format24bppRgb; // 24 bits par pixel, RGB.
>      //Format32bppArgb; // 32 bits par pixel, ARGB.
> 
>      // Enregistre la présentation au format TIFF avec la taille d'image spécifiée
>      pres.save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [TiffOptions()](#TiffOptions--) | Default constructor. |
## Methods

| Method | Description |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Provides options that control the look of Ink objects in exported document. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specifies whether the generated document should include hidden slides or not. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specifies whether the generated document should include hidden slides or not. |
| [getImageSize()](#getImageSize--) | Specifies size of a generated TIFF image. |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | Specifies size of a generated TIFF image. |
| [getDpiX()](#getDpiX--) | Specifies the horizontal resolution in dots per inch. |
| [setDpiX(long value)](#setDpiX-long-) | Specifies the horizontal resolution in dots per inch. |
| [getDpiY()](#getDpiY--) | Specifies the vertical resolution in dots per inch. |
| [setDpiY(long value)](#setDpiY-long-) | Specifies the vertical resolution in dots per inch. |
| [getCompressionType()](#getCompressionType--) | Specifies the compression type. |
| [setCompressionType(int value)](#setCompressionType-int-) | Specifies the compression type. |
| [getPixelFormat()](#getPixelFormat--) | Specifies the pixel format for the generated images. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Specifies the pixel format for the generated images. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Gets or sets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Gets or sets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Specifies the algorithm for converting a color image into a black and white image. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Specifies the algorithm for converting a color image into a black and white image. |
### TiffOptions() {#TiffOptions--}
```
public TiffOptions()
```

Default constructor.

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Provides options that control the look of Ink objects in exported document. Read-only [IInkOptions](../../com.aspose.slides/iinkoptions)

**Returns:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Specifies whether the generated document should include hidden slides or not. Default is false.

**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Specifies whether the generated document should include hidden slides or not. Default is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getImageSize() {#getImageSize--}
```
public final Size getImageSize()
```

Specifies size of a generated TIFF image. Default value is 0x0, what means that generated image sizes will be calculated based on presentation slide size value. Read/write [Size](../../com.aspose.slides.android/size).

**Returns:**
[Size](../../com.aspose.slides.android/size)
### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public final void setImageSize(Size value)
```

Specifies size of a generated TIFF image. Default value is 0x0, what means that generated image sizes will be calculated based on presentation slide size value. Read/write [Size](../../com.aspose.slides.android/size).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getDpiX() {#getDpiX--}
```
public final long getDpiX()
```

Specifies the horizontal resolution in dots per inch. Read/write long.

**Returns:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public final void setDpiX(long value)
```

Specifies the horizontal resolution in dots per inch. Read/write long.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public final long getDpiY()
```

Specifies the vertical resolution in dots per inch. Read/write long.

**Returns:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public final void setDpiY(long value)
```

Specifies the vertical resolution in dots per inch. Read/write long.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getCompressionType() {#getCompressionType--}
```
public final int getCompressionType()
```

Specifies the compression type. Read/write [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Returns:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public final void setCompressionType(int value)
```
Specifies the compression type. Read/write [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public final int getPixelFormat()
```

Specifies the pixel format for the generated images. Read/write [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Returns:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public final void setPixelFormat(int value)
```

Specifies the pixel format for the generated images. Read/write [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```
Gets or sets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Exemple :
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

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getBwConversionMode() {#getBwConversionMode--}
```
public final int getBwConversionMode()
```

Specifies the algorithm for converting a color image into a black and white image. This option will applied only if  CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) is set to [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes#CCITT4) or [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes#CCITT3) Read/write [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Default is [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode#Default).

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

Spécifie l'algorithme de conversion d'une image couleur en image noir et blanc. Cette option n'est appliquée que si CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) est défini sur [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) ou [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) Lecture/écriture [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). La valeur par défaut est [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |