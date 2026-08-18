---
title: IImageCollection
second_title: Referencia de API de Aspose.Slides para Java
description: Representa la colección de PPImage.
type: docs
url: /es/com.aspose.slides/iimagecollection/
---
**Todas las interfaces implementadas:**
com.aspose.slides.IGenericCollection
```
public interface IImageCollection extends IGenericCollection<IPPImage>
```

Representa la colección de PPImage.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Devuelve la imagen por su índice. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Agrega una imagen a una presentación. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Agrega una imagen a una presentación desde un flujo. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Crea y agrega una imagen a una presentación desde un flujo. |
| [addImage(byte[] buffer)](#addImage-byte---) | Agrega una imagen a una presentación desde el búfer especificado. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Agrega una copia de una imagen de otra presentación. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Agrega una imagen a una presentación desde un objeto SVG. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPPImage get_Item(int index)
```


Devuelve la imagen por su índice.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice. |

**Devuelve:**
[IPPImage](../../com.aspose.slides/ippimage) - Imagen.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public abstract IPPImage addImage(IImage image)
```


Agrega una imagen a una presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Imagen para agregar.

--------------------

Este método convierte los metaficheros WMF/EMF a una imagen PNG raster antes de insertarlos en una presentación. |

**Devuelve:**
[IPPImage](../../com.aspose.slides/ippimage) - Imagen agregada.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public abstract IPPImage addImage(InputStream stream)
```


Agrega una imagen a una presentación desde un flujo.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | Flujo desde el cual agregar la imagen.

--------------------

Este método puede agregar metaficheros WMF/EMF a una presentación sin convertirlos a una imagen PNG raster. |

**Devuelve:**
[IPPImage](../../com.aspose.slides/ippimage) - Imagen agregada.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public abstract IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```


Crea y agrega una imagen a una presentación desde un flujo.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | Flujo desde el cual agregar el archivo de imagen. |
| loadingStreamBehavior | int | El comportamiento que se aplicará al flujo. |

**Devuelve:**
[IPPImage](../../com.aspose.slides/ippimage) - Añadido [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public abstract IPPImage addImage(byte[] buffer)
```


Agrega una imagen a una presentación desde el búfer especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | byte[] | Búfer. |

**Devuelve:**
[IPPImage](../../com.aspose.slides/ippimage) - Imagen agregada.
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public abstract IPPImage addImage(IPPImage imageSource)
```


Agrega una copia de una imagen de otra presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Imagen de origen. |

**Devuelve:**
[IPPImage](../../com.aspose.slides/ippimage) - Imagen agregada.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public abstract IPPImage addImage(ISvgImage svgImage)
```


Agrega una imagen a una presentación desde un objeto SVG.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | objeto de imagen SVG [ISvgImage](../../com.aspose.slides/isvgimage) |

**Devuelve:**
[IPPImage](../../com.aspose.slides/ippimage) - Imagen agregada.