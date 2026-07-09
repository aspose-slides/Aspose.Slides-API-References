---
title: ITiffOptions
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Fournit des options qui contrôlent la façon dont une présentation est enregistrée au format TIFF.
type: docs
url: /fr/com.aspose.slides/itiffoptions/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ITiffOptions extends ISaveOptions
```

Fournit des options qui contrôlent la façon dont une présentation est enregistrée au format TIFF.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getImageSize()](#getImageSize--) | Spécifie la taille d'une image TIFF générée. |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | Spécifie la taille d'une image TIFF générée. |
| [getDpiX()](#getDpiX--) | Spécifie la résolution horizontale en points par pouce. |
| [setDpiX(long value)](#setDpiX-long-) | Spécifie la résolution horizontale en points par pouce. |
| [getDpiY()](#getDpiY--) | Spécifie la résolution verticale en points par pouce. |
| [setDpiY(long value)](#setDpiY-long-) | Spécifie la résolution verticale en points par pouce. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Spécifie si le document généré doit inclure les diapositives masquées ou non. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Spécifie si le document généré doit inclure les diapositives masquées ou non. |
| [getCompressionType()](#getCompressionType--) | Spécifie le type de compression. |
| [setCompressionType(int value)](#setCompressionType-int-) | Spécifie le type de compression. |
| [getPixelFormat()](#getPixelFormat--) | Spécifie le format de pixel pour les images générées. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Spécifie le format de pixel pour les images générées. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Spécifie l'algorithme de conversion d'une image couleur en image noir et blanc. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Spécifie l'algorithme de conversion d'une image couleur en image noir et blanc. |
| [getInkOptions()](#getInkOptions--) | Fournit des options qui contrôlent l'apparence des objets Ink dans le document exporté. |
### getImageSize() {#getImageSize--}
```
public abstract Size getImageSize()
```


Spécifie la taille d'une image TIFF générée. La valeur par défaut est 0x0, ce qui signifie que les tailles d'image générées seront calculées en fonction de la valeur de la taille des diapositives de la présentation. Lecture/écriture [Size](../../com.aspose.slides.android/size).

**Renvoie :**
[Size](../../com.aspose.slides.android/size)
### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public abstract void setImageSize(Size value)
```


Spécifie la taille d'une image TIFF générée. La valeur par défaut est 0x0, ce qui signifie que les tailles d'image générées seront calculées en fonction de la valeur de la taille des diapositives de la présentation. Lecture/écriture [Size](../../com.aspose.slides.android/size).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getDpiX() {#getDpiX--}
```
public abstract long getDpiX()
```


Spécifie la résolution horizontale en points par pouce. Lecture/écriture long.

**Renvoie :**
long
### setDpiX(long value) {#setDpiX-long-}
```
public abstract void setDpiX(long value)
```


Spécifie la résolution horizontale en points par pouce. Lecture/écriture long.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public abstract long getDpiY()
```


Spécifie la résolution verticale en points par pouce. Lecture/écriture long.

**Renvoie :**
long
### setDpiY(long value) {#setDpiY-long-}
```
public abstract void setDpiY(long value)
```


Spécifie la résolution verticale en points par pouce. Lecture/écriture long.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | long |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```


Spécifie si le document généré doit inclure les diapositives masquées ou non. La valeur par défaut est false.

**Renvoie :**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```


Spécifie si le document généré doit inclure les diapositives masquées ou non. La valeur par défaut est false.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getCompressionType() {#getCompressionType--}
```
public abstract int getCompressionType()
```


Spécifie le type de compression. Lecture/écriture [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Renvoie :**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public abstract void setCompressionType(int value)
```


Spécifie le type de compression. Lecture/écriture [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public abstract int getPixelFormat()
```


Spécifie le format de pixel pour les images générées. Lecture/écriture [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Renvoie :**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public abstract void setPixelFormat(int value)
```


Spécifie le format de pixel pour les images générées. Lecture/écriture [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
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

**Returns:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getBwConversionMode() {#getBwConversionMode--}
```
public abstract int getBwConversionMode()
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
public abstract void setBwConversionMode(int value)
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()


Fournit des options qui contrôlent l'apparence des objets Ink dans le document exporté. Lecture seule [IInkOptions](../../com.aspose.slides/iinkoptions)

**Renvoie :**
[IInkOptions](../../com.aspose.slides/iinkoptions)