---
title: ITiffOptions
second_title: Referencia de la API de Java de Aspose.Slides para Android
description: Proporciona opciones que controlan cómo se guarda una presentación en formato TIFF.
type: docs
url: /es/com.aspose.slides/itiffoptions/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ITiffOptions extends ISaveOptions
```

Proporciona opciones que controlan cómo se guarda una presentación en formato TIFF.
## Métodos

| Método | Descripción |
| --- | --- |
| [getImageSize()](#getImageSize--) | Especifica el tamaño de una imagen TIFF generada. |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | Especifica el tamaño de una imagen TIFF generada. |
| [getDpiX()](#getDpiX--) | Especifica la resolución horizontal en puntos por pulgada. |
| [setDpiX(long value)](#setDpiX-long-) | Especifica la resolución horizontal en puntos por pulgada. |
| [getDpiY()](#getDpiY--) | Especifica la resolución vertical en puntos por pulgada. |
| [setDpiY(long value)](#setDpiY-long-) | Especifica la resolución vertical en puntos por pulgada. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Especifica si el documento generado debe incluir diapositivas ocultas o no. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Especifica si el documento generado debe incluir diapositivas ocultas o no. |
| [getCompressionType()](#getCompressionType--) | Especifica el tipo de compresión. |
| [setCompressionType(int value)](#setCompressionType-int-) | Especifica el tipo de compresión. |
| [getPixelFormat()](#getPixelFormat--) | Especifica el formato de píxel para las imágenes generadas. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Especifica el formato de píxel para las imágenes generadas. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Especifica el algoritmo para convertir una imagen a color en una imagen en blanco y negro. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Especifica el algoritmo para convertir una imagen a color en una imagen en blanco y negro. |
| [getInkOptions()](#getInkOptions--) | Proporciona opciones que controlan la apariencia de los objetos Ink en el documento exportado. |
### getImageSize() {#getImageSize--}
```
public abstract Size getImageSize()
```

Especifica el tamaño de una imagen TIFF generada. El valor predeterminado es 0x0, lo que significa que los tamaños de imagen generados se calcularán basándose en el valor del tamaño de la diapositiva de la presentación. Lectura/escritura [Size](../../com.aspose.slides.android/size).

**Devuelve:**
[Size](../../com.aspose.slides.android/size)
### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public abstract void setImageSize(Size value)
```

Especifica el tamaño de una imagen TIFF generada. El valor predeterminado es 0x0, lo que significa que los tamaños de imagen generados se calcularán basándose en el valor del tamaño de la diapositiva de la presentación. Lectura/escritura [Size](../../com.aspose.slides.android/size).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |
### getDpiX() {#getDpiX--}
```
public abstract long getDpiX()
```

Especifica la resolución horizontal en puntos por pulgada. Lectura/escritura long.

**Devuelve:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public abstract void setDpiX(long value)
```

Especifica la resolución horizontal en puntos por pulgada. Lectura/escritura long.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | long |  |
### getDpiY() {#getDpiY--}
```
public abstract long getDpiY()
```

Especifica la resolución vertical en puntos por pulgada. Lectura/escritura long.

**Devuelve:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public abstract void setDpiY(long value)
```

Especifica la resolución vertical en puntos por pulgada. Lectura/escritura long.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | long |  |
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es false.

**Devuelve:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es false.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getCompressionType() {#getCompressionType--}
```
public abstract int getCompressionType()
```

Especifica el tipo de compresión. Lectura/escritura [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Devuelve:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public abstract void setCompressionType(int value)
```

Especifica el tipo de compresión. Lectura/escritura [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |
### getPixelFormat() {#getPixelFormat--}
```
public abstract int getPixelFormat()
```

Especifica el formato de píxel para las imágenes generadas. Lectura/escritura [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Devuelve:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public abstract void setPixelFormat(int value)
```

Especifica el formato de píxel para las imágenes generadas. Lectura/escritura [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |
### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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


**Devuelve:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |
### getBwConversionMode() {#getBwConversionMode--}
```
public abstract int getBwConversionMode()
```

Especifica el algoritmo para convertir una imagen a color en una imagen en blanco y negro. Esta opción se aplicará solo si CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) está configurado a [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) o [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) Lectura/escritura [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). El valor predeterminado es [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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


**Devuelve:**
int
### setBwConversionMode(int value) {#setBwConversionMode-int-}
```
public abstract void setBwConversionMode(int value)
```

Especifica el algoritmo para convertir una imagen a color en una imagen en blanco y negro. Esta opción se aplicará solo si CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) está configurado a [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) o [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) Lectura/escritura [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). El valor predeterminado es [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |
### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Proporciona opciones que controlan la apariencia de los objetos Ink en el documento exportado. Solo lectura [IInkOptions](../../com.aspose.slides/iinkoptions)

**Devuelve:**
[IInkOptions](../../com.aspose.slides/iinkoptions)