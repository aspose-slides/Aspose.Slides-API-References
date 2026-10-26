---
title: ImageCollection
second_title: Referência da API Aspose.Slides para Java
description: Representa a coleção de PPImage.
type: docs
url: /pt/com.aspose.slides/imagecollection/
---
**Herança:**
java.lang.Object, com.aspose.slides.DomObject

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IImageCollection](../../com.aspose.slides/iimagecollection)
```
public final class ImageCollection extends DomObject<Presentation> implements IImageCollection
```

Representa a coleção de PPImage.
## Métodos

| Método | Descrição |
| --- | --- |
| [size()](#size--) | Retorna um número de imagens na coleção. |
| [get_Item(int index)](#get-Item-int-) | Obtém o elemento no índice especificado. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Adiciona uma cópia de uma imagem de outra apresentação. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Adiciona uma imagem a uma apresentação. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Adiciona uma imagem a uma apresentação a partir de um fluxo. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Cria e adiciona uma imagem a uma apresentação a partir de um fluxo. |
| [addImage(byte[] buffer)](#addImage-byte---) | Adiciona uma imagem a uma apresentação a partir de um buffer especificado. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Adiciona uma imagem a uma apresentação a partir de um objeto Svg. |
| [iterator()](#iterator--) | Retorna um enumerador que itera sobre a coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterador java para a coleção inteira. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos os elementos da coleção para o array especificado. |
| [isSynchronized()](#isSynchronized--) | Retorna um valor que indica se o acesso à coleção está sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retorna uma raiz de sincronização. |
### size() {#size--}
```
public final int size()
```

Retorna um número de imagens na coleção. Somente leitura  int .

**Retorna:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPPImage get_Item(int index)
```

Obtém o elemento no índice especificado. Somente leitura [IPPImage](../../com.aspose.slides/ippimage).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[IPPImage](../../com.aspose.slides/ippimage)
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public final IPPImage addImage(IPPImage imageSource)
```

Adiciona uma cópia de uma imagem de outra apresentação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Imagem de origem. |

**Retorna:**
[IPPImage](../../com.aspose.slides/ippimage) - Imagem adicionada.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public final IPPImage addImage(IImage image)
```

Adiciona uma imagem a uma apresentação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Imagem a ser adicionada.

--------------------

Este método converte arquivos metafile WMF/EMF para imagem PNG raster antes de inserir em uma apresentação. |

**Retorna:**
[IPPImage](../../com.aspose.slides/ippimage) - Imagem adicionada.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public final IPPImage addImage(InputStream stream)
```

Adiciona uma imagem a uma apresentação a partir de um fluxo.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.InputStream | Fluxo a partir do qual a imagem será adicionada.

--------------------

Este método pode adicionar arquivos metafile WMF/EMF a uma apresentação sem convertê-los para imagem PNG raster. |

**Retorna:**
[IPPImage](../../com.aspose.slides/ippimage) - Imagem adicionada.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public final IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```

Cria e adiciona uma imagem a uma apresentação a partir de um fluxo.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.InputStream | Fluxo a partir do qual o arquivo de imagem será adicionado. |
| loadingStreamBehavior | int | O comportamento que será aplicado ao fluxo. |

**Retorna:**
[IPPImage](../../com.aspose.slides/ippimage) - Adicionada [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public final IPPImage addImage(byte[] buffer)
```

Adiciona uma imagem a uma apresentação a partir de um buffer especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | byte[] | Buffer. |

**Retorna:**
[IPPImage](../../com.aspose.slides/ippimage) - Imagem adicionada.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public final IPPImage addImage(ISvgImage svgImage)
```

Adiciona uma imagem a uma apresentação a partir de um objeto Svg.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Objeto de imagem Svg [ISvgImage](../../com.aspose.slides/isvgimage) |

**Retorna:**
[IPPImage](../../com.aspose.slides/ippimage) - Imagem adicionada.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iterator()
```

Retorna um enumerador que itera sobre a coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iteratorJava()
```

Retorna um iterador java para a coleção inteira.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia todos os elementos da coleção para o array especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array de destino. |
| index | int | Índice inicial no array de destino. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retorna um valor que indica se o acesso à coleção está sincronizado (thread-safe). Somente leitura  boolean .

**Retorna:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retorna uma raiz de sincronização. Somente leitura  Object .

**Retorna:**
java.lang.Object