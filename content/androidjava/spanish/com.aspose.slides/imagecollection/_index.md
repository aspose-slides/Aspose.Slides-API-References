---
title: ImageCollection
second_title: Referencia de API Java de Aspose.Slides para Android
description: Representa una colección de PPImage.
type: docs
url: /es/com.aspose.slides/imagecollection/
---
**Herencia:**
java.lang.Object, com.aspose.slides.DomObject

**Todas las interfaces implementadas:**
[com.aspose.slides.IImageCollection](../../com.aspose.slides/iimagecollection)
```
public final class ImageCollection extends DomObject<Presentation> implements IImageCollection
```

Representa una colección de PPImage.
## Métodos

| Método | Descripción |
| --- | --- |
| [size()](#size--) | Devuelve el número de imágenes en la colección. |
| [get_Item(int index)](#get-Item-int-) | Obtiene el elemento en el índice especificado. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Añade una copia de una imagen de otra presentación. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Añade una imagen a una presentación. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Añade una imagen a una presentación desde un flujo. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Crea y añade una imagen a una presentación desde un flujo. |
| [addImage(byte[] buffer)](#addImage-byte---) | Añade una imagen a una presentación desde el búfer especificado. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Añade una imagen a una presentación desde un objeto Svg. |
| [iterator()](#iterator--) | Devuelve un enumerador que recorre la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos los elementos de la colección al array especificado. |
| [isSynchronized()](#isSynchronized--) | Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para hilos). |
| [getSyncRoot()](#getSyncRoot--) | Devuelve la raíz de sincronización. |
### size() {#size--}
```
public final int size()
```


Devuelve el número de imágenes en la colección. Solo lectura  int .

**Devuelve:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPPImage get_Item(int index)
```


Obtiene el elemento en el índice especificado. Solo lectura [IPPImage](../../com.aspose.slides/ippimage).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IPPImage](../../com.aspose.slides/ippimage)
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public final IPPImage addImage(IPPImage imageSource)
```


Añade una copia de una imagen de otra presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Imagen fuente. |

**Devuelve:**
[IPPImage](../../com.aspose.slides/ippimage) - Imagen añadida.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public final IPPImage addImage(IImage image)
```


Añade una imagen a una presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Imagen a añadir.

--------------------

Este método convierte archivos metafile WMF/EMF a una imagen PNG raster antes de insertarla en una presentación. |

**Devuelve:**
[IPPImage](../../com.aspose.slides/ippimage) - Imagen añadida.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public final IPPImage addImage(InputStream stream)
```


Añade una imagen a una presentación desde un flujo.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | Flujo del que añadir la imagen.

--------------------

Este método puede añadir archivos metafile WMF/EMF a una presentación sin convertirlos a una imagen PNG raster. |

**Devuelve:**
[IPPImage](../../com.aspose.slides/ippimage) - Imagen añadida.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public final IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```


Crea y añade una imagen a una presentación desde un flujo.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | Flujo del que añadir el archivo de imagen. |
| loadingStreamBehavior | int | El comportamiento que se aplicará al flujo. |

**Devuelve:**
[IPPImage](../../com.aspose.slides/ippimage) - Añadida [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public final IPPImage addImage(byte[] buffer)
```


Añade una imagen a una presentación desde el búfer especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | byte[] | Búfer. |

**Devuelve:**
[IPPImage](../../com.aspose.slides/ippimage) - Imagen añadida.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public final IPPImage addImage(ISvgImage svgImage)
```


Añade una imagen a una presentación desde un objeto Svg.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Objeto de imagen Svg [ISvgImage](../../com.aspose.slides/isvgimage) |

**Devuelve:**
[IPPImage](../../com.aspose.slides/ippimage) - Imagen añadida.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iterator()
```


Devuelve un enumerador que recorre la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - Un IGenericEnumerator que puede usarse para recorrer la colección.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iteratorJava()
```


Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - Un java.util.Iterator para toda la colección.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copia todos los elementos de la colección al array especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array de destino. |
| index | int | Índice inicial en el array de destino. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para hilos). Solo lectura  boolean .

**Devuelve:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Devuelve la raíz de sincronización. Solo lectura  Object .

**Devuelve:**
java.lang.Object