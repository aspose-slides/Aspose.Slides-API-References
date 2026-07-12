---
title: Picture
second_title: Aspose.Slides for Android via Referência da API Java
description: Representa uma imagem em uma apresentação.
type: docs
url: /pt/com.aspose.slides/picture/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlidesPicture](../../com.aspose.slides/islidespicture)
```
public final class Picture implements IPVIObject, ISlidesPicture
```

Representa uma imagem em uma apresentação.
## Métodos

| Método | Descrição |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getImage()](#getImage--) | Retorna ou define a imagem incorporada. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Retorna ou define a imagem incorporada. |
| [getLinkPathLong()](#getLinkPathLong--) | Retorna ou define a URL da imagem vinculada. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Retorna ou define a URL da imagem vinculada. |
| [getImageTransform()](#getImageTransform--) | Retorna a coleção de efeitos de transformação de imagem. |
| [getPresentation()](#getPresentation--) | Retorna a apresentação. |
| [equals(Object obj)](#equals-java.lang.Object-) | Compara com o objeto especificado. |
| [hashCode()](#hashCode--) | Retorna o hash. |
| [getSlide()](#getSlide--) | Retorna o slide pai de uma imagem. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retorna o objeto Parent_Immediate. Somente leitura IDOMObject.

**Retorna:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Versão. Somente leitura long.

**Retorna:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Retorna o pai IPresentationComponent. Somente leitura [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Retorna:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getImage() {#getImage--}
```
public final IPPImage getImage()
```

Retorna ou define a imagem incorporada. Leitura/gravação [IPPImage](../../com.aspose.slides/ippimage).

**Retorna:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public final void setImage(IPPImage value)
```

Retorna ou define a imagem incorporada. Leitura/gravação [IPPImage](../../com.aspose.slides/ippimage).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Retorna ou define a URL da imagem vinculada. Leitura/gravação String.

**Retorna:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Retorna ou define a URL da imagem vinculada. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getImageTransform() {#getImageTransform--}
```
public final IImageTransformOperationCollection getImageTransform()
```

Retorna a coleção de efeitos de transformação de imagem. Somente leitura [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Retorna:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Retorna a apresentação. Somente leitura [IPresentation](../../com.aspose.slides/ipresentation).

**Retorna:**
[IPresentation](../../com.aspose.slides/ipresentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Compara com o objeto especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | java.lang.Object | Objeto a ser comparado. |

**Retorna:**
boolean - Verdadeiro se os objetos forem iguais, caso contrário falso.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Retorna o hash.

**Retorna:**
int - Hash.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Retorna o slide pai de uma imagem. Somente leitura [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Retorna:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)