---
title: ISlidesPicture
second_title: Referencia de API de Aspose.Slides para Java
description: Representa una imagen en una presentación.
type: docs
url: /es/com.aspose.slides/islidespicture/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ISlidesPicture extends ISlideComponent
```

Represents a picture in a presentation.
## Métodos

| Método | Descripción |
| --- | --- |
| [getImage()](#getImage--) | Devuelve o establece la imagen incrustada. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Devuelve o establece la imagen incrustada. |
| [getLinkPathLong()](#getLinkPathLong--) | Devuelve o establece la URL de la imagen vinculada. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Devuelve o establece la URL de la imagen vinculada. |
| [getImageTransform()](#getImageTransform--) | Devuelve la colección de efectos de transformación de imagen. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```


Devuelve o establece la imagen incrustada. Lectura/escritura [IPPImage](../../com.aspose.slides/ippimage).

**Devuelve:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public abstract void setImage(IPPImage value)
```


Devuelve o establece la imagen incrustada. Lectura/escritura [IPPImage](../../com.aspose.slides/ippimage).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


Devuelve o establece la URL de la imagen vinculada. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```


Devuelve o establece la URL de la imagen vinculada. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOperationCollection getImageTransform()
```


Devuelve la colección de efectos de transformación de imagen. Solo lectura [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Devuelve:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)