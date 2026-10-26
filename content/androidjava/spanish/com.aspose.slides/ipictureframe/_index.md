---
title: IPictureFrame
second_title: Referencia de la API de Aspose.Slides para Android mediante Java
description: Representa un marco con una imagen dentro.
type: docs
url: /es/com.aspose.slides/ipictureframe/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IPictureFrame extends IGeometryShape
```

Representa un marco con una imagen dentro.
## Métodos

| Método | Descripción |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | Devuelve los bloqueos de PictureFrame. |
| [getPictureFormat()](#getPictureFormat--) | Devuelve el objeto PictureFillFormat para un marco de imagen. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | Devuelve o establece la escala de altura (relativa al tamaño original de la imagen) del marco de imagen. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | Devuelve o establece la escala de altura (relativa al tamaño original de la imagen) del marco de imagen. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | Devuelve o establece la escala de ancho (relativa al tamaño original de la imagen) del marco de imagen. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | Devuelve o establece la escala de ancho (relativa al tamaño original de la imagen) del marco de imagen. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public abstract IPictureFrameLock getPictureFrameLock()
```


Devuelve los bloqueos de PictureFrame. Solo lectura [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**Devuelve:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getPictureFormat() {#getPictureFormat--}
```
public abstract IPictureFillFormat getPictureFormat()
```


Devuelve el objeto PictureFillFormat para un marco de imagen. Solo lectura [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Devuelve:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public abstract float getRelativeScaleHeight()
```


Devuelve o establece la escala de altura (relativa al tamaño original de la imagen) del marco de imagen. El valor 1.0 corresponde al 100 %. Lectura/escritura float.

**Devuelve:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public abstract void setRelativeScaleHeight(float value)
```


Devuelve o establece la escala de altura (relativa al tamaño original de la imagen) del marco de imagen. El valor 1.0 corresponde al 100 %. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public abstract float getRelativeScaleWidth()
```


Devuelve o establece la escala de ancho (relativa al tamaño original de la imagen) del marco de imagen. El valor 1.0 corresponde al 100 %. Lectura/escritura float.

**Devuelve:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public abstract void setRelativeScaleWidth(float value)
```


Devuelve o establece la escala de ancho (relativa al tamaño original de la imagen) del marco de imagen. El valor 1.0 corresponde al 100 %. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |