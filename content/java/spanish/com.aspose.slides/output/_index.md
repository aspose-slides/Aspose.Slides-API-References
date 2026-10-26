---
title: Output
second_title: Referencia de API de Aspose.Slides para Java
description: Representa una colección de elementos de salida para IWebDocument.
type: docs
url: /es/com.aspose.slides/output/
---
**Herencia:**
java.lang.Object
```
public final class Output
```

Representa una colección de elementos de salida para IWebDocument.
## Métodos

| Método | Descripción |
| --- | --- |
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | Añade un elemento de salida para el objeto de contexto. |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | Añade un elemento de salida para la imagen. |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | Añade un elemento de salida para la imagen. |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | Añade un elemento de salida para el video. |
| [add(String path, IAudio audio)](#add-java.lang.String-com.aspose.slides.IAudio-) | Añade un elemento de salida para el audio. |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | Crea y añade un elemento de archivo de salida para la fuente especificada. |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | Añade un elemento de salida para el contenido de texto. |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | Asocia un recurso al archivo de salida. |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | Devuelve la ruta para un recurso dado. |
### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```


Añade un elemento de salida para el objeto de contexto.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | java.lang.String | Ruta de salida. |
| templateKey | java.lang.String | La clave de la plantilla utilizada para la transformación del objeto de contexto antes de la salida. |
| contextObject | TContextObject | Objeto de contexto. |

**Devuelve:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object for the context object.
### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```


Añade un elemento de salida para la imagen.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | java.lang.String | Ruta de salida. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Imagen a exportar. |

**Devuelve:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object for the image.
### add(String path, IImage image) {#add-java.lang.String-com.aspose.slides.IImage-}
```
public final IOutputFile add(String path, IImage image)
```


Añade un elemento de salida para la imagen.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | java.lang.String | Ruta de salida. |
| image | [IImage](../../com.aspose.slides/iimage) | Imagen a exportar. |

**Devuelve:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object for the image.
### add(String path, IVideo video) {#add-java.lang.String-com.aspose.slides.IVideo-}
```
public final IOutputFile add(String path, IVideo video)
```


Añade un elemento de salida para el video.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | java.lang.String | Ruta de salida. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Video a exportar. |

**Devuelve:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object for the video.
### add(String path, IAudio audio) {#add-java.lang.String-com.aspose.slides.IAudio-}
```
public final IOutputFile add(String path, IAudio audio)
```


Añade un elemento de salida para el audio.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | java.lang.String | Ruta de salida. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Audio a exportar. |

**Devuelve:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object for the audio.
### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```


Crea y añade un elemento de archivo de salida para la fuente especificada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | java.lang.String | La ruta del archivo donde se guardará la salida de la fuente. |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Los datos de la fuente que se escribirán en la salida. |
| fontStyle | int | El estilo de la fuente (p. ej., Regular, Bold, Italic). |

**Devuelve:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - An [IOutputFile](../../com.aspose.slides/ioutputfile) instance for the generated font.
### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```


Añade un elemento de salida para el contenido de texto.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | java.lang.String | Ruta de salida. |
| textContent | java.lang.String | Contenido a exportar. |

**Devuelve:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) object for the text content.
### bindResource(IOutputFile outputFile, Object obj) {#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-}
```
public final void bindResource(IOutputFile outputFile, Object obj)
```


Asocia un recurso al archivo de salida.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | Archivo de salida. |
| obj | java.lang.Object | Objeto de recurso. |

### getResourcePath(Object obj) {#getResourcePath-java.lang.Object-}
```
public final String getResourcePath(Object obj)
```


Devuelve la ruta para un recurso dado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | Objeto de recurso. |

**Devuelve:**
java.lang.String - Resource path.