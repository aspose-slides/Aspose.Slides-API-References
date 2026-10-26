---
title: TiffOptions
second_title: Referencia de API de Aspose.Slides para Android a través de Java
description: Proporciona opciones que controlan cómo se guarda una presentación en formato TIFF.
type: docs
url: /es/com.aspose.slides/tiffoptions/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Todas las interfaces implementadas:**
[com.aspose.slides.ITiffOptions](../../com.aspose.slides/itiffoptions)
```
public class TiffOptions extends SaveOptions implements ITiffOptions
```

Proporciona opciones que controlan cómo se guarda una presentación en formato TIFF.

--------------------

> ```
> The following example shows how to convert PowerPoint to TIFF with default size.
>  
>  // Instanciar un objeto Presentation que representa un archivo de presentación
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      // Guardando la presentación en un documento TIFF
>      pres.save("Tiffoutput_out.tiff", SaveFormat.Tiff);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom size.
>  
>  // Instanciar un objeto Presentation que representa un archivo de Presentación
>  Presentation pres = new Presentation("Convert_Tiff_Custom.pptx");
>  try {
>      // Instanciar la clase TiffOptions
>      TiffOptions opts = new TiffOptions();
>      // Estableciendo el tipo de compresión
>      opts.setCompressionType(TiffCompressionTypes.Default);
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      opts.setSlidesLayoutOptions(notesOptions);
>      // Tipos de compresión
>      // Default - Especifica el esquema de compresión predeterminado (LZW).
>      // None - Especifica sin compresión.
>      // CCITT3
>      // CCITT4
>      // LZW
>      // RLE
>      // La profundidad depende del tipo de compresión y no puede establecerse manualmente.
>      // La unidad de resolución siempre es 2 (puntos por pulgada)
>      // Estableciendo DPI de la imagen
>      opts.setDpiX(200);
>      opts.setDpiY(100);
>      // Establecer tamaño de imagen
>      opts.setImageSize(new com.aspose.slides.android.Size(1728, 1078));
>      // Guardar la presentación en TIFF con el tamaño de imagen especificado
>      pres.save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom image pixel format.
>  
>  // Instanciar un objeto Presentation que representa un archivo de Presentación
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      options.setPixelFormat(ImagePixelFormat.Format8bppIndexed);
> 
>      // ImagePixelFormat contiene los siguientes valores (como se puede ver en la documentación):
>      //Format1bppIndexed; // 1 bits por píxel, indexado.
>      //Format4bppIndexed; // 4 bits por píxel, indexado.
>      //Format8bppIndexed; // 8 bits por píxel, indexado.
>      //Format24bppRgb; // 24 bits por píxel, RGB.
>      //Format32bppArgb; // 32 bits por píxel, ARGB.
> 
>      // Guardar la presentación en TIFF con el tamaño de imagen especificado
>      pres.save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Constructores

| Constructor | Descripción |
| --- | --- |
| [TiffOptions()](#TiffOptions--) | Constructor predeterminado. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Proporciona opciones que controlan la apariencia de los objetos Ink en el documento exportado. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Especifica si el documento generado debe incluir diapositivas ocultas o no. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Especifica si el documento generado debe incluir diapositivas ocultas o no. |
| [getImageSize()](#getImageSize--) | Especifica el tamaño de una imagen TIFF generada. |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | Especifica el tamaño de una imagen TIFF generada. |
| [getDpiX()](#getDpiX--) | Especifica la resolución horizontal en puntos por pulgada. |
| [setDpiX(long value)](#setDpiX-long-) | Especifica la resolución horizontal en puntos por pulgada. |
| [getDpiY()](#getDpiY--) | Especifica la resolución vertical en puntos por pulgada. |
| [setDpiY(long value)](#setDpiY-long-) | Especifica la resolución vertical en puntos por pulgada. |
| [getCompressionType()](#getCompressionType--) | Especifica el tipo de compresión. |
| [setCompressionType(int value)](#setCompressionType-int-) | Especifica el tipo de compresión. |
| [getPixelFormat()](#getPixelFormat--) | Especifica el formato de píxel para las imágenes generadas. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Especifica el formato de píxel para las imágenes generadas. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Especifica el algoritmo para convertir una imagen a color en una imagen en blanco y negro. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Especifica el algoritmo para convertir una imagen a color en una imagen en blanco y negro. |
### TiffOptions() {#TiffOptions--}
```
public TiffOptions()
```

Constructor predeterminado.

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Proporciona opciones que controlan la apariencia de los objetos Ink en el documento exportado. Solo lectura [IInkOptions](../../com.aspose.slides/iinkoptions)

**Devuelve:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es false.

**Devuelve:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es false.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getImageSize() {#getImageSize--}
```
public final Size getImageSize()
```

Especifica el tamaño de una imagen TIFF generada. El valor predeterminado es 0x0, lo que significa que los tamaños de imagen generados se calcularán en función del valor del tamaño de la diapositiva de la presentación. Lectura/escritura [Size](../../com.aspose.slides.android/size).

**Devuelve:**
[Size](../../com.aspose.slides.android/size)
### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public final void setImageSize(Size value)
```

Especifica el tamaño de una imagen TIFF generada. El valor predeterminado es 0x0, lo que significa que los tamaños de imagen generados se calcularán en función del valor del tamaño de la diapositiva de la presentación. Lectura/escritura [Size](../../com.aspose.slides.android/size).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getDpiX() {#getDpiX--}
```
public final long getDpiX()
```

Especifica la resolución horizontal en puntos por pulgada. Lectura/escritura long.

**Devuelve:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public final void setDpiX(long value)
```

Especifica la resolución horizontal en puntos por pulgada. Lectura/escritura long.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public final long getDpiY()
```

Especifica la resolución vertical en puntos por pulgada. Lectura/escritura long.

**Devuelve:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public final void setDpiY(long value)
```

Especifica la resolución vertical en puntos por pulgada. Lectura/escritura long.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | long |  |

### getCompressionType() {#getCompressionType--}
```
public final int getCompressionType()
```

Especifica el tipo de compresión. Lectura/escritura [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Devuelve:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public final void setCompressionType(int value)
```

Especifica el tipo de compresión. Lectura/escritura [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public final int getPixelFormat()
```

Especifica el formato de píxel para las imágenes generadas. Lectura/escritura [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Devuelve:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public final void setPixelFormat(int value)
```

Especifica el formato de píxel para las imágenes generadas. Lectura/escritura [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
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
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
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
public final int getBwConversionMode()
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
public final void setBwConversionMode(int value)
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