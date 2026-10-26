---
title: IXpsOptions
second_title: Referencia de la API de Aspose.Slides para Java
description: Proporciona opciones que controlan cómo se guarda una presentación en formato XPS.
type: docs
url: /es/com.aspose.slides/ixpsoptions/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXpsOptions extends ISaveOptions
```

Proporciona opciones que controlan cómo se guarda una presentación en formato XPS.
## Métodos

| Method | Descripción |
| --- | --- |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Verdadero para convertir todos los metarchivos usados en una presentación a imágenes PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Verdadero para convertir todos los metarchivos usados en una presentación a imágenes PNG. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Verdadero para dibujar un marco negro alrededor de cada diapositiva. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Verdadero para dibujar un marco negro alrededor de cada diapositiva. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Especifica si el documento generado debe incluir diapositivas ocultas o no. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Especifica si el documento generado debe incluir diapositivas ocultas o no. |
### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```


Verdadero para convertir todos los metarchivos usados en una presentación a imágenes PNG. Lectura/escritura booleano.

--------------------

El valor predeterminado es **true**.

**Devuelve:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```


Verdadero para convertir todos los metarchivos usados en una presentación a imágenes PNG. Lectura/escritura booleano.

--------------------

El valor predeterminado es **true**.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```


Verdadero para dibujar un marco negro alrededor de cada diapositiva. Lectura/escritura booleano.

--------------------

El valor predeterminado es **false**.

**Devuelve:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```


Verdadero para dibujar un marco negro alrededor de cada diapositiva. Lectura/escritura booleano.

--------------------

El valor predeterminado es **false**.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```


Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es false.

**Devuelve:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```


Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es false.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |