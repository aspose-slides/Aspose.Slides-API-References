---
title: IPictureFillFormatEffectiveData
second_title: Aspose.Slides para Android a través de la referencia de la API Java
description: Objeto inmutable que contiene las propiedades del relleno de imagen.
type: docs
url: /es/com.aspose.slides/ipicturefillformateffectivedata/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormatEffectiveData extends IFillParamSource
```

Objeto inmutable que contiene las propiedades del relleno de imagen.

--------------------

Esta interfaz se utiliza como parte de [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).
## Métodos

| Método | Descripción |
| --- | --- |
| [getDpi()](#getDpi--) | Devuelve el dpi que se usa para rellenar una imagen. |
| [getPictureFillMode()](#getPictureFillMode--) | Devuelve el modo de relleno de la imagen. |
| [getPicture()](#getPicture--) | Devuelve la imagen. |
| [getCropLeft()](#getCropLeft--) | Devuelve el número de porcentajes del ancho real de la imagen que se recortan del lado izquierdo de la imagen. |
| [getCropTop()](#getCropTop--) | Devuelve el número de porcentajes de la altura real de la imagen que se recortan de la parte superior de la imagen. |
| [getCropRight()](#getCropRight--) | Devuelve el número de porcentajes del ancho real de la imagen que se recortan del lado derecho de la imagen. |
| [getCropBottom()](#getCropBottom--) | Devuelve el número de porcentajes de la altura real de la imagen que se recortan de la parte inferior de la imagen. |
### getDpi() {#getDpi--}
```
public abstract int getDpi()
```


Devuelve el dpi que se usa para rellenar una imagen. Solo lectura int.

**Devuelve:**
int
### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```


Devuelve el modo de relleno de la imagen. Solo lectura [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Devuelve:**
int
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```


Devuelve la imagen. Solo lectura [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**Devuelve:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```


Devuelve el número de porcentajes del ancho real de la imagen que se recortan del lado izquierdo de la imagen. Solo lectura float.

**Devuelve:**
float
### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```


Devuelve el número de porcentajes de la altura real de la imagen que se recortan de la parte superior de la imagen. Solo lectura float.

**Devuelve:**
float
### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```


Devuelve el número de porcentajes del ancho real de la imagen que se recortan del lado derecho de la imagen. Solo lectura float.

**Devuelve:**
float
### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```


Devuelve el número de porcentajes de la altura real de la imagen que se recortan de la parte inferior de la imagen. Solo lectura float.

**Devuelve:**
float