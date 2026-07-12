---
title: ISVGOptions
second_title: Aspose.Slides para Android a través de la referencia de API de Java
description: Representa una opción SVG.
type: docs
url: /es/com.aspose.slides/isvgoptions/
---
**Todas las Interfaces Implementadas:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISVGOptions extends ISaveOptions
```

Representa opciones SVG.
## Métodos

| Método | Descripción |
| --- | --- |
| [getVectorizeText()](#getVectorizeText--) | Determina si el texto en una diapositiva se guardará como gráficos. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Determina si el texto en una diapositiva se guardará como gráficos. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Devuelve o establece el límite de resolución inferior para la rasterización de metafile. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Devuelve o establece el límite de resolución inferior para la rasterización de metafile. |
| [getDisable3DText()](#getDisable3DText--) | Determina si el texto 3D está deshabilitado en SVG. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Determina si el texto 3D está deshabilitado en SVG. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Deshabilita la división de gradientes FromCornerX y FromCenter. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Deshabilita la división de gradientes FromCornerX y FromCenter. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 no permite definir inserciones para marcadores. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 no permite definir inserciones para marcadores. |
| [getJpegQuality()](#getJpegQuality--) | Determina la calidad de codificación JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Determina la calidad de codificación JPEG. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Devuelve y establece una interfaz de devolución de llamada que permite al usuario controlar la conversión de formas. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Devuelve y establece una interfaz de devolución de llamada que permite al usuario controlar la conversión de formas. |
| [getPicturesCompression()](#getPicturesCompression--) | Representa el nivel de compresión de imágenes Read/write \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Representa el nivel de compresión de imágenes Read/write \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Un indicador booleano que muestra si las partes recortadas permanecen como parte del documento. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Un indicador booleano que muestra si las partes recortadas permanecen como parte del documento. |
| [getUseFrameSize()](#getUseFrameSize--) | Determina si el marco de texto se incluirá en un área de renderizado o no. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Determina si el marco de texto se incluirá en un área de renderizado o no. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Determina si se debe aplicar la rotación especificada de la forma al renderizar o no. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Determina si se debe aplicar la rotación especificada de la forma al renderizar o no. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Determina una forma de manejar fuentes cargadas externamente. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Determina una forma de manejar fuentes cargadas externamente. |
| [getInkOptions()](#getInkOptions--) | Proporciona opciones que controlan el aspecto de los objetos Ink en el documento exportado. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Obtiene o establece un valor que indica si el texto se renderiza sin usar ligaduras. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Obtiene o establece un valor que indica si el texto se renderiza sin usar ligaduras. |
### getVectorizeText() {#getVectorizeText--}
```
public abstract boolean getVectorizeText()
```


Determina si el texto en una diapositiva se guardará como gráficos. Lectura/escritura booleano.

**Devuelve:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public abstract void setVectorizeText(boolean value)
```


Determina si el texto en una diapositiva se guardará como gráficos. Lectura/escritura booleano.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public abstract int getMetafileRasterizationDpi()
```


Devuelve o establece el límite de resolución inferior para la rasterización de metafile. Lectura/escritura entero.

**Devuelve:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public abstract void setMetafileRasterizationDpi(int value)
```


Devuelve o establece el límite de resolución inferior para la rasterización de metafile. Lectura/escritura entero.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public abstract boolean getDisable3DText()
```


Determina si el texto 3D está deshabilitado en SVG. Lectura/escritura booleano.

**Devuelve:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public abstract void setDisable3DText(boolean value)
```


Determina si el texto 3D está deshabilitado en SVG. Lectura/escritura booleano.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public abstract boolean getDisableGradientSplit()
```


Deshabilita la división de gradientes FromCornerX y FromCenter. Lectura/escritura booleano.

**Devuelve:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public abstract void setDisableGradientSplit(boolean value)
```


Deshabilita la división de gradientes FromCornerX y FromCenter. Lectura/escritura booleano.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public abstract boolean getDisableLineEndCropping()
```


SVG 1.1 no permite definir inserciones para marcadores. El motor de escritura SVG de Aspose.Slides tiene una solución alternativa para ese problema: recorta el extremo de la línea con flecha, de modo que la línea no se superponga a los marcadores. Esta opción desactiva dicho comportamiento. Lectura/escritura booleano.

**Devuelve:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public abstract void setDisableLineEndCropping(boolean value)
```


SVG 1.1 no permite definir inserciones para marcadores. El motor de escritura SVG de Aspose.Slides tiene una solución alternativa para ese problema: recorta el extremo de la línea con flecha, de modo que la línea no se superponga a los marcadores. Esta opción desactiva dicho comportamiento. Lectura/escritura booleano.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```


Determina la calidad de codificación JPEG. Lectura/escritura entero.

**Devuelve:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```


Determina la calidad de codificación JPEG. Lectura/escritura entero.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public abstract ISvgShapeFormattingController getShapeFormattingController()
```


Devuelve y establece una interfaz de devolución de llamada que permite al usuario controlar la conversión de formas. Lectura/escritura [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Devuelve:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public abstract void setShapeFormattingController(ISvgShapeFormattingController value)
```


Devuelve y establece una interfaz de devolución de llamada que permite al usuario controlar la conversión de formas. Lectura/escritura [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```


Representa el nivel de compresión de imágenes Read/write \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**Devuelve:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```


Representa el nivel de compresión de imágenes Read/write \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```


Un indicador booleano que muestra si las partes recortadas permanecen como parte del documento. Si es true, las partes recortadas se eliminarán; si es false, se serializarán en el documento (lo que puede producir un archivo más grande). Lectura/escritura booleano.

**Devuelve:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```


Un indicador booleano que muestra si las partes recortadas permanecen como parte del documento. Si es true, las partes recortadas se eliminarán; si es false, se serializarán en el documento (lo que puede producir un archivo más grande). Lectura/escritura booleano.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameSize() {#getUseFrameSize--}
```
public abstract boolean getUseFrameSize()
```


Determina si el marco de texto se incluirá en un área de renderizado o no. Lectura/escritura boolean. Valor predeterminado es false.

**Devuelve:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public abstract void setUseFrameSize(boolean value)
```


Determina si el marco de texto se incluirá en un área de renderizado o no. Lectura/escritura boolean. Valor predeterminado es false.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public abstract boolean getUseFrameRotation()
```


Determina si se debe aplicar la rotación especificada de la forma al renderizar o no. Lectura/escritura boolean. Valor predeterminado es true.

**Devuelve:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public abstract void setUseFrameRotation(boolean value)
```


Determina si se debe aplicar la rotación especificada de la forma al renderizar o no. Lectura/escritura boolean. Valor predeterminado es true.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public abstract int getExternalFontsHandling()
```


Determina una forma de manejar fuentes cargadas externamente. Lectura/escritura [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Devuelve:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public abstract void setExternalFontsHandling(int value)
```


Determina una forma de manejar fuentes cargadas externamente. Lectura/escritura [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```


Proporciona opciones que controlan el aspecto de los objetos Ink en el documento exportado. Solo lectura [IInkOptions](../../com.aspose.slides/iinkoptions)

**Devuelve:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```


Obtiene o establece un valor que indica si el texto se renderiza sin usar ligaduras. Cuando se establece en true, las ligaduras se desactivarán en la salida renderizada. Por defecto, esta propiedad está en false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```


Obtiene o establece un valor que indica si el texto se renderiza sin usar ligaduras. Cuando se establece en true, las ligaduras se desactivarán en la salida renderizada. Por defecto, esta propiedad está en false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |