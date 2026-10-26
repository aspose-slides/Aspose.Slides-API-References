---
title: Picture
second_title: Aspose.Slides para Android mediante la referencia de la API Java
description: Representa una imagen en una presentación.
type: docs
url: /es/com.aspose.slides/picture/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlidesPicture](../../com.aspose.slides/islidespicture)
```
public final class Picture implements IPVIObject, ISlidesPicture
```

Representa una imagen en una presentación.
## Métodos

| Método | Descripción |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getImage()](#getImage--) | Devuelve o establece la imagen incrustada. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Devuelve o establece la imagen incrustada. |
| [getLinkPathLong()](#getLinkPathLong--) | Devuelve o establece la URL de la imagen vinculada. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Devuelve o establece la URL de la imagen vinculada. |
| [getImageTransform()](#getImageTransform--) | Devuelve la colección de efectos de transformación de imagen. |
| [getPresentation()](#getPresentation--) | Devuelve la presentación. |
| [equals(Object obj)](#equals-java.lang.Object-) | Compara con el objeto especificado. |
| [hashCode()](#hashCode--) | Devuelve el hash. |
| [getSlide()](#getSlide--) | Devuelve la diapositiva padre de una imagen. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Devuelve el objeto Parent_Immediate. Solo lectura IDOMObject.

**Devuelve:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Versión. Solo lectura long.

**Devuelve:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Devuelve el padre IPresentationComponent. Solo lectura [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Devuelve:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getImage() {#getImage--}
```
public final IPPImage getImage()
```

Devuelve o establece la imagen incrustada. Lectura/escritura [IPPImage](../../com.aspose.slides/ippimage).

**Devuelve:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public final void setImage(IPPImage value)
```

Devuelve o establece la imagen incrustada. Lectura/escritura [IPPImage](../../com.aspose.slides/ippimage).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Devuelve o establece la URL de la imagen vinculada. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Devuelve o establece la URL de la imagen vinculada. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |
### getImageTransform() {#getImageTransform--}
```
public final IImageTransformOperationCollection getImageTransform()
```

Devuelve la colección de efectos de transformación de imagen. Solo lectura [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Devuelve:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Devuelve la presentación. Solo lectura [IPresentation](../../com.aspose.slides/ipresentation).

**Devuelve:**
[IPresentation](../../com.aspose.slides/ipresentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Compara con el objeto especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | Objeto a comparar. |

**Devuelve:**
boolean - Verdadero si los objetos son iguales, de lo contrario falso.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Devuelve el hash.

**Devuelve:**
int - Hash.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Devuelve la diapositiva padre de una imagen. Solo lectura [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Devuelve:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)