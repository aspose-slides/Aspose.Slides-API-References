---
title: TiffOptions
second_title: Référence de l'API Aspose.Slides for Java
description: Fournit des options qui contrôlent la manière dont une présentation est enregistrée au format TIFF.
type: docs
url: /fr/com.aspose.slides/tiffoptions/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Toutes les interfaces implémentées :**
[com.aspose.slides.ITiffOptions](../../com.aspose.slides/itiffoptions)
```
public class TiffOptions extends SaveOptions implements ITiffOptions
```

Fournit des options qui contrôlent la manière dont une présentation est enregistrée au format TIFF.

--------------------

> ```
> The following example shows how to convert PowerPoint to TIFF with default size.
>  
>  // Instancie un objet Presentation qui représente un fichier de présentation
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      // Sauvegarde de la présentation au format TIFF
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
>      // Définition du type de compression
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
>      // Définition du DPI de l'image
>      opts.setDpiX(200);
>      opts.setDpiY(100);
>      // Définir la taille de l'image
>      opts.setImageSize(new Dimension(1728, 1078));
>      // Enregistrer la présentation au format TIFF avec la taille d'image spécifiée
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
>      //ImagePixelFormat contient les valeurs suivantes (comme indiqué dans la documentation) :
>      //Format1bppIndexed; // 1 bits par pixel, indexé.
>      //Format4bppIndexed; // 4 bits par pixel, indexé.
>      //Format8bppIndexed; // 8 bits par pixel, indexé.
>      //Format24bppRgb; // 24 bits par pixel, RGB.
>      //Format32bppArgb; // 32 bits par pixel, ARGB.
> 
>      // Enregistrer la présentation au format TIFF avec la taille d'image spécifiée
>      pres.save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TiffOptions()](#TiffOptions--) | Constructeur par défaut. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Fournit des options qui contrôlent l'apparence des objets Ink dans le document exporté. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Spécifie si le document généré doit inclure les diapositives masquées ou non. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Spécifie si le document généré doit inclure les diapositives masquées ou non. |
| [getImageSize()](#getImageSize--) | Spécifie la taille d'une image TIFF générée. |
| [setImageSize(Dimension value)](#setImageSize-java.awt.Dimension-) | Spécifie la taille d'une image TIFF générée. |
| [getDpiX()](#getDpiX--) | Spécifie la résolution horizontale en points par pouce. |
| [setDpiX(long value)](#setDpiX-long-) | Spécifie la résolution horizontale en points par pouce. |
| [getDpiY()](#getDpiY--) | Spécifie la résolution verticale en points par pouce. |
| [setDpiY(long value)](#setDpiY-long-) | Spécifie la résolution verticale en points par pouce. |
| [getCompressionType()](#getCompressionType--) | Spécifie le type de compression. |
| [setCompressionType(int value)](#setCompressionType-int-) | Spécifie le type de compression. |
| [getPixelFormat()](#getPixelFormat--) | Spécifie le format pixel pour les images générées. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Spécifie le format pixel pour les images générées. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Spécifie l'algorithme de conversion d'une image couleur en image noir et blanc. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Spécifie l'algorithme de conversion d'une image couleur en image noir et blanc. |
### TiffOptions() {#TiffOptions--}
```
public TiffOptions()
```


Constructeur par défaut.

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```


Fournit des options qui contrôlent l'apparence des objets Ink dans le document exporté. Lecture seule [IInkOptions](../../com.aspose.slides/iinkoptions)

**Renvoie :**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Spécifie si le document généré doit inclure les diapositives masquées ou non. La valeur par défaut est false.

**Renvoie :**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Spécifie si le document généré doit inclure les diapositives masquées ou non. La valeur par défaut est false.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getImageSize() {#getImageSize--}
```
public final Dimension getImageSize()
```


Spécifie la taille d'une image TIFF générée. La valeur par défaut est 0x0, ce qui signifie que les tailles d'images générées seront calculées en fonction de la taille des diapositives de la présentation. Lecture/écriture java.awt.Dimension.

**Renvoie :**
java.awt.Dimension
### setImageSize(Dimension value) {#setImageSize-java.awt.Dimension-}
```
public final void setImageSize(Dimension value)
```


Spécifie la taille d'une image TIFF générée. La valeur par défaut est 0x0, ce qui signifie que les tailles d'images générées seront calculées en fonction de la taille des diapositives de la présentation. Lecture/écriture java.awt.Dimension.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getDpiX() {#getDpiX--}
```
public final long getDpiX()
```


Spécifie la résolution horizontale en points par pouce. Lecture/écriture long.

**Renvoie :**
long
### setDpiX(long value) {#setDpiX-long-}
```
public final void setDpiX(long value)
```


Spécifie la résolution horizontale en points par pouce. Lecture/écriture long.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public final long getDpiY()
```


Spécifie la résolution verticale en points par pouce. Lecture/écriture long.

**Renvoie :**
long
### setDpiY(long value) {#setDpiY-long-}
```
public final void setDpiY(long value)
```


Spécifie la résolution verticale en points par pouce. Lecture/écriture long.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | long |  |

### getCompressionType() {#getCompressionType--}
```
public final int getCompressionType()
```


Spécifie le type de compression. Lecture/écriture [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Renvoie :**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public final void setCompressionType(int value)
```


Spécifie le type de compression. Lecture/écriture [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public final int getPixelFormat()
```


Spécifie le format pixel pour les images générées. Lecture/écriture [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Renvoie :**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public final void setPixelFormat(int value)
```


Spécifie le format pixel pour les images générées. Lecture/écriture [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```


Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**Renvoie :**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getBwConversionMode() {#getBwConversionMode--}
```
public final int getBwConversionMode()
```


Spécifie l'algorithme de conversion d'une image couleur en image noir et blanc. Cette option ne sera appliquée que si CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) est défini sur [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) ou [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) Lecture/écriture [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). La valeur par défaut est [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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

**Renvoie :**
int
### setBwConversionMode(int value) {#setBwConversionMode-int-}
```
public final void setBwConversionMode(int value)
```


Spécifie l'algorithme de conversion d'une image couleur en image noir et blanc. Cette option ne sera appliquée que si CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) est défini sur [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) ou [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) Lecture/écriture [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). La valeur par défaut est [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |