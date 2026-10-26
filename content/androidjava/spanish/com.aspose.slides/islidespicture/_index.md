---
title: ISlidesPicture
second_title: Aspose.Slides para Android a través de la API Java
description: Representa una imagen en una presentación.
type: docs
url: /es/com.aspose.slides/islidespicture/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ISlidesPicture extends ISlideComponent
```

Representa una imagen en una presentación.
## Métodos

| Método | Descripción |
| --- | --- |
| [getImage()](#getImage--) | Devuelve o establece la imagen incrustada. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Devuelve o establece la imagen incrustada. |
| [getLinkPathLong()](#getLinkPathLong--) | Devuelve o establece la URL de la imagen vinculada. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Devuelve o establece la URL de la imagen vinculada. |
| [getImageTransform()](#getImageTransform--) | Devuelve la colección de efectos de transformación de la imagen. |
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

Devuelve la colección de efectos de transformación de la imagen. Sólo lectura [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Devuelve:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)