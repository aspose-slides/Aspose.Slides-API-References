---
title: SVGOptions
second_title: Aspose.Slides para Android a través de la API de referencia Java
description: Representa una opción SVG.
type: docs
url: /es/com.aspose.slides/svgoptions/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Todas las interfaces implementadas:**
[com.aspose.slides.ISVGOptions](../../com.aspose.slides/isvgoptions), java.lang.Cloneable
```
public final class SVGOptions extends SaveOptions implements ISVGOptions, Cloneable
```

Representa una opción SVG.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [SVGOptions()](#SVGOptions--) | Inicializa una nueva instancia de la clase SVGOptions. |
| [SVGOptions(ILinkEmbedController linkEmbedController)](#SVGOptions-com.aspose.slides.ILinkEmbedController-) | Inicializa una nueva instancia de la clase SVGOptions especificando el objeto controlador de inserción de enlaces. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Proporciona opciones que controlan el aspecto de los objetos Ink en el documento exportado. |
| [getUseFrameSize()](#getUseFrameSize--) | Determina si el marco de texto se incluirá en una zona de renderizado o no. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Determina si el marco de texto se incluirá en una zona de renderizado o no. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Determina si se debe realizar la rotación especificada de la forma al renderizar o no. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Determina si se debe realizar la rotación especificada de la forma al renderizar o no. |
| [getVectorizeText()](#getVectorizeText--) | Determina si el texto en una diapositiva se guardará como gráficos. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Determina si el texto en una diapositiva se guardará como gráficos. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Devuelve o establece el límite inferior de resolución para la rasterización de metafiles. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Devuelve o establece el límite inferior de resolución para la rasterización de metafiles. |
| [getDisable3DText()](#getDisable3DText--) | Determina si el texto 3D está deshabilitado en SVG. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Determina si el texto 3D está deshabilitado en SVG. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Desactiva la división de degradados FromCornerX y FromCenter. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Desactiva la división de degradados FromCornerX y FromCenter. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 carece de la capacidad de definir inserciones para marcadores. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 carece de la capacidad de definir inserciones para marcadores. |
| [getDefault()](#getDefault--) | Devuelve la configuración predeterminada. |
| [getSimple()](#getSimple--) | Devuelve la configuración para la generación del archivo SVG más simple y pequeño. |
| [getWYSIWYG()](#getWYSIWYG--) | Devuelve la configuración para la generación del archivo SVG más preciso. |
| [getJpegQuality()](#getJpegQuality--) | Determina la calidad de codificación JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Determina la calidad de codificación JPEG. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Devuelve y establece una interfaz de devolución de llamada que permite al usuario controlar la conversión de formas. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Devuelve y establece una interfaz de devolución de llamada que permite al usuario controlar la conversión de formas. |
| [getPicturesCompression()](#getPicturesCompression--) | Representa el nivel de compresión de imágenes. |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Representa el nivel de compresión de imágenes. |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Un indicador booleano que indica si las partes recortadas permanecen como parte del documento. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Un indicador booleano que indica si las partes recortadas permanecen como parte del documento. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Determina una forma de manejar fuentes cargadas externamente. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Determina una forma de manejar fuentes cargadas externamente. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Obtiene o establece un valor que indica si el texto se renderiza sin usar ligaduras. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Obtiene o establece un valor que indica si el texto se renderiza sin usar ligaduras. |
### SVGOptions() {#SVGOptions--}
```
public SVGOptions()
```

Inicializa una nueva instancia de la clase SVGOptions.

### SVGOptions(ILinkEmbedController linkEmbedController) {#SVGOptions-com.aspose.slides.ILinkEmbedController-}
```
public SVGOptions(ILinkEmbedController linkEmbedController)
```

Inicializa una nueva instancia de la clase SVGOptions especificando el objeto controlador de inserción de enlaces.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | La referencia al controlador de inserción de enlaces. |

--------------------

El controlador de inserción de enlaces es un objeto delegado que es responsable de tomar decisiones si los recursos (como imágenes) deben incrustarse o referenciarse como recursos externos. |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Proporciona opciones que controlan el aspecto de los objetos Ink en el documento exportado. Solo lectura [IInkOptions](../../com.aspose.slides/iinkoptions)

**Devuelve:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getUseFrameSize() {#getUseFrameSize--}
```
public final boolean getUseFrameSize()
```

Determina si el marco de texto se incluirá en una zona de renderizado o no. Lectura/escritura boolean . Valor predeterminado es false.

**Devuelve:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public final void setUseFrameSize(boolean value)
```

Determina si el marco de texto se incluirá en una zona de renderizado o no. Lectura/escritura boolean . Valor predeterminado es false.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public final boolean getUseFrameRotation()
```

Determina si se debe realizar la rotación especificada de la forma al renderizar o no. Lectura/escritura boolean . Valor predeterminado es true.

**Devuelve:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public final void setUseFrameRotation(boolean value)
```

Determina si se debe realizar la rotación especificada de la forma al renderizar o no. Lectura/escritura boolean . Valor predeterminado es true.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getVectorizeText() {#getVectorizeText--}
```
public final boolean getVectorizeText()
```

Determina si el texto en una diapositiva se guardará como gráficos. Lectura/escritura boolean.

**Devuelve:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public final void setVectorizeText(boolean value)
```

Determina si el texto en una diapositiva se guardará como gráficos. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public final int getMetafileRasterizationDpi()
```

Devuelve o establece el límite inferior de resolución para la rasterización de metafiles. Lectura/escritura int.

**Devuelve:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public final void setMetafileRasterizationDpi(int value)
```

Devuelve o establece el límite inferior de resolución para la rasterización de metafiles. Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public final boolean getDisable3DText()
```

Determina si el texto 3D está deshabilitado en SVG. Lectura/escritura boolean.

**Devuelve:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public final void setDisable3DText(boolean value)
```

Determina si el texto 3D está deshabilitado en SVG. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public final boolean getDisableGradientSplit()
```

Desactiva la división de degradados FromCornerX y FromCenter. Lectura/escritura boolean.

**Devuelve:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public final void setDisableGradientSplit(boolean value)
```

Desactiva la división de degradados FromCornerX y FromCenter. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public final boolean getDisableLineEndCropping()
```

SVG 1.1 carece de la capacidad de definir inserciones para marcadores. El motor de escritura SVG de Aspose.Slides tiene una solución alternativa para ese problema: recorta el extremo de la línea con la flecha, de modo que la línea no se superponga a los marcadores. Esta opción desactiva dicho comportamiento. Lectura/escritura boolean.

**Devuelve:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public final void setDisableLineEndCropping(boolean value)
```

SVG 1.1 carece de la capacidad de definir inserciones para marcadores. El motor de escritura SVG de Aspose.Slides tiene una solución alternativa para ese problema: recorta el extremo de la línea con la flecha, de modo que la línea no se superponga a los marcadores. Esta opción desactiva dicho comportamiento. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getDefault() {#getDefault--}
```
public static SVGOptions getDefault()
```

Devuelve la configuración predeterminada. Solo lectura [SVGOptions](../../com.aspose.slides/svgoptions).

**Devuelve:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getSimple() {#getSimple--}
```
public static SVGOptions getSimple()
```

Devuelve la configuración para la generación del archivo SVG más simple y pequeño. Solo lectura [SVGOptions](../../com.aspose.slides/svgoptions).

**Devuelve:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getWYSIWYG() {#getWYSIWYG--}
```
public static SVGOptions getWYSIWYG()
```

Devuelve la configuración para la generación del archivo SVG más preciso. Solo lectura [SVGOptions](../../com.aspose.slides/svgoptions).

**Devuelve:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

Determina la calidad de codificación JPEG. Lectura/escritura int.

**Devuelve:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

Determina la calidad de codificación JPEG. Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public final ISvgShapeFormattingController getShapeFormattingController()
```

Devuelve y establece una interfaz de devolución de llamada que permite al usuario controlar la conversión de formas. Lectura/escritura [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Devuelve:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public final void setShapeFormattingController(ISvgShapeFormattingController value)
```

Devuelve y establece una interfaz de devolución de llamada que permite al usuario controlar la conversión de formas. Lectura/escritura [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

Representa el nivel de compresión de imágenes.

**Devuelve:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

Representa el nivel de compresión de imágenes.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

Un indicador booleano que indica si las partes recortadas permanecen como parte del documento. Si es true, las partes recortadas se eliminarán; si es false, se serializarán en el documento (lo que puede generar un archivo más grande).

**Devuelve:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

Un indicador booleano que indica si las partes recortadas permanecen como parte del documento. Si es true, las partes recortadas se eliminarán; si es false, se serializarán en el documento (lo que puede generar un archivo más grande).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public final int getExternalFontsHandling()
```

Determina una forma de manejar fuentes cargadas externamente. Lectura/escritura [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Devuelve:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public final void setExternalFontsHandling(int value)
```

Determina una forma de manejar fuentes cargadas externamente. Lectura/escritura [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

Obtiene o establece un valor que indica si el texto se renderiza sin usar ligaduras. Cuando se establece en true, las ligaduras se desactivarán en la salida renderizada. De manera predeterminada, esta propiedad está establecida en false.

--------------------

> ```
> Ejemplo:
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
public final void setDisableFontLigatures(boolean value)
```

Obtiene o establece un valor que indica si el texto se renderiza sin usar ligaduras. Cuando se establece en true, las ligaduras se desactivarán en la salida renderizada. De manera predeterminada, esta propiedad está establecida en false.

--------------------

> ```
> Ejemplo:
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