---
title: IImageCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa coleção de PPImage.
type: docs
url: /pt/com.aspose.slides/iimagecollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.slides.IGenericCollection
```
public interface IImageCollection extends IGenericCollection<IPPImage>
```

Representa uma coleção de PPImage.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retorna a imagem pelo seu índice. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Adiciona uma imagem a uma apresentação. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Adiciona uma imagem a uma apresentação a partir de um fluxo. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Cria e adiciona uma imagem a uma apresentação a partir de um fluxo. |
| [addImage(byte[] buffer)](#addImage-byte---) | Adiciona uma imagem a uma apresentação a partir de um buffer especificado. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Adiciona uma cópia de uma imagem de outra apresentação. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Adiciona uma imagem a uma apresentação a partir de um objeto SVG. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPPImage get_Item(int index)
```

Retorna a imagem pelo seu índice.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice. |

**Retorna:**
[IPPImage](../../com.aspose.slides/ippimage) - Image.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public abstract IPPImage addImage(IImage image)
```

Adiciona uma imagem a uma apresentação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Imagem a ser adicionada. |

--------------------

Este método converte arquivos metafile WMF/EMF em imagem PNG raster antes de inseri-los em uma apresentação. |
**Retorna:**
[IPPImage](../../com.aspose.slides/ippimage) - Imagem adicionada.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public abstract IPPImage addImage(InputStream stream)
```

Adiciona uma imagem a uma apresentação a partir de um fluxo.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.InputStream | Fluxo de onde a imagem será adicionada. |

--------------------

Este método pode adicionar arquivos metafile WMF/EMF a uma apresentação sem convertê-los em imagem PNG raster. |
**Retorna:**
[IPPImage](../../com.aspose.slides/ippimage) - Imagem adicionada.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public abstract IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```

Cria e adiciona uma imagem a uma apresentação a partir de um fluxo.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.InputStream | Fluxo de onde o arquivo de imagem será adicionado. |
| loadingStreamBehavior | int | O comportamento que será aplicado ao fluxo. |

**Retorna:**
[IPPImage](../../com.aspose.slides/ippimage) - Adicionado [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public abstract IPPImage addImage(byte[] buffer)
```

Adiciona uma imagem a uma apresentação a partir de um buffer especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | byte[] | Buffer. |

**Retorna:**
[IPPImage](../../com.aspose.slides/ippimage) - Imagem adicionada.
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public abstract IPPImage addImage(IPPImage imageSource)
```

Adiciona uma cópia de uma imagem de outra apresentação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Imagem de origem. |

**Retorna:**
[IPPImage](../../com.aspose.slides/ippimage) - Imagem adicionada.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public abstract IPPImage addImage(ISvgImage svgImage)
```

Adiciona uma imagem a uma apresentação a partir de um objeto SVG.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Objeto de imagem SVG [ISvgImage](../../com.aspose.slides/isvgimage) |

**Retorna:**
[IPPImage](../../com.aspose.slides/ippimage) - Imagem adicionada.