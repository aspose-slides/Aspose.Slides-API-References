---
title: ISlidesPicture
second_title: Aspose.Slides para Android via Referência de API Java
description: Representa uma imagem em uma apresentação.
type: docs
url: /pt/com.aspose.slides/islidespicture/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ISlidesPicture extends ISlideComponent
```

Representa uma imagem em uma apresentação.
## Métodos

| Método | Descrição |
| --- | --- |
| [getImage()](#getImage--) | Retorna ou define a imagem incorporada. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Retorna ou define a imagem incorporada. |
| [getLinkPathLong()](#getLinkPathLong--) | Retorna ou define o URL da imagem vinculada. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Retorna ou define o URL da imagem vinculada. |
| [getImageTransform()](#getImageTransform--) | Retorna a coleção de efeitos de transformação de imagem. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```


Retorna ou define a imagem incorporada. Leitura/gravação [IPPImage](../../com.aspose.slides/ippimage).

**Retorna:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public abstract void setImage(IPPImage value)
```


Retorna ou define a imagem incorporada. Leitura/gravação [IPPImage](../../com.aspose.slides/ippimage).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


Retorna ou define o URL da imagem vinculada. Leitura/gravação String.

**Retorna:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```


Retorna ou define o URL da imagem vinculada. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOperationCollection getImageTransform()
```


Retorna a coleção de efeitos de transformação de imagem. Somente leitura [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Retorna:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)