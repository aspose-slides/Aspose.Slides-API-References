---
title: IImageCollection
second_title: Referencia de API Java para Aspose.Slides en Android
description: Representa una colección de PPImage.
type: docs
url: /es/com.aspose.slides/iimagecollection/
---
**Todas las interfaces implementadas:**
com.aspose.slides.IGenericCollection
```
public interface IImageCollection extends IGenericCollection<IPPImage>
```

Representa una colección de PPImage.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Devuelve la imagen por su índice. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Añade una imagen a una presentación. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Añade una imagen a una presentación desde stream. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Crea y añade una imagen a una presentación desde stream. |
| [addImage(byte[] buffer)](#addImage-byte---) | Añade una imagen a una presentación desde el búfer especificado. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Añade una copia de una imagen de otra presentación. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Añade una imagen a una presentación desde un objeto SVG. |
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

Añade una imagen a una presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Imagen a añadir.

--------------------

Este método convierte los metarchivos WMF/EMF a una imagen PNG raster antes de insertarla en una presentación. |

**Devuelve:**
[IPPImage](../../com.aspose.slides/ippimage) - Imagen añadida.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public abstract IPPImage addImage(InputStream stream)
```

Añade una imagen a una presentación desde stream.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | Stream del que añadir la imagen.

--------------------

Este método puede añadir metarchivos WMF/EMF a una presentación sin convertirlos a una imagen PNG raster. |

**Devuelve:**
[IPPImage](../../com.aspose.slides/ippimage) - Imagen añadida.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public abstract IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```

Crea y añade una imagen a una presentación desde stream.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | Stream del que añadir el archivo de imagen. |
| loadingStreamBehavior | int | El comportamiento que se aplicará al stream. |

**Devuelve:**
[IPPImage](../../com.aspose.slides/ippimage) - Añadida [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public abstract IPPImage addImage(byte[] buffer)
```

Añade una imagen a una presentación desde el búfer especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | byte[] | Búfer. |

**Devuelve:**
[IPPImage](../../com.aspose.slides/ippimage) - Imagen añadida.
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public abstract IPPImage addImage(IPPImage imageSource)
```

Añade una copia de una imagen de otra presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Imagen fuente. |

**Devuelve:**
[IPPImage](../../com.aspose.slides/ippimage) - Imagen añadida.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public abstract IPPImage addImage(ISvgImage svgImage)
```

Añade una imagen a una presentación desde objeto SVG.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Objeto de imagen SVG [ISvgImage](../../com.aspose.slides/isvgimage) |

**Devuelve:**
[IPPImage](../../com.aspose.slides/ippimage) - Imagen añadida.