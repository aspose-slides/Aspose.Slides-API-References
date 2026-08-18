---
title: INormalViewRestoredProperties
second_title: Aspose.Slides for Java API Reference
description: Especifica el dimensionamiento del ancho de la región de diapositiva cuando es un hijo de restoredTop, la altura cuando es un hijo de restoredLeft, de la vista normal cuando la región tiene un tamaño restaurado variable (ni minimizada ni maximizada).
type: docs
url: /es/com.aspose.slides/inormalviewrestoredproperties/
---```
public interface INormalViewRestoredProperties
```

Especifica el dimensionamiento de la región de diapositiva ((ancho cuando es un hijo de restoredTop, altura cuando es un hijo de restoredLeft) de la vista normal, cuando la región tiene un tamaño restaurado variable (ni minimizada ni maximizada).
## Métodos

| Método | Descripción |
| --- | --- |
| [getDimensionSize()](#getDimensionSize--) | Especifica el tamaño de la región de diapositiva (ancho cuando es un hijo de RestoredTop, altura cuando es un hijo de RestoredLeft). |
| [setDimensionSize(float value)](#setDimensionSize-float-) | Especifica el tamaño de la región de diapositiva (ancho cuando es un hijo de RestoredTop, altura cuando es un hijo de RestoredLeft). |
| [getAutoAdjust()](#getAutoAdjust--) | Especifica si el tamaño de la región de contenido lateral debe compensar el nuevo tamaño al cambiar el tamaño de la ventana que contiene la vista dentro de la aplicación Lectura/escritura boolean. |
| [setAutoAdjust(boolean value)](#setAutoAdjust-boolean-) | Especifica si el tamaño de la región de contenido lateral debe compensar el nuevo tamaño al cambiar el tamaño de la ventana que contiene la vista dentro de la aplicación Lectura/escritura boolean. |
### getDimensionSize() {#getDimensionSize--}
```
public abstract float getDimensionSize()
```

Especifica el tamaño de la región de diapositiva (ancho cuando es un hijo de RestoredTop, altura cuando es un hijo de RestoredLeft). Lectura/escritura float.

**Devuelve:**
float
### setDimensionSize(float value) {#setDimensionSize-float-}
```
public abstract void setDimensionSize(float value)
```

Especifica el tamaño de la región de diapositiva (ancho cuando es un hijo de RestoredTop, altura cuando es un hijo de RestoredLeft). Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |
### getAutoAdjust() {#getAutoAdjust--}
```
public abstract boolean getAutoAdjust()
```

Especifica si el tamaño de la región de contenido lateral debe compensar el nuevo tamaño al cambiar el tamaño de la ventana que contiene la vista dentro de la aplicación Lectura/escritura boolean.

**Devuelve:**
boolean
### setAutoAdjust(boolean value) {#setAutoAdjust-boolean-}
```
public abstract void setAutoAdjust(boolean value)
```

Especifica si el tamaño de la región de contenido lateral debe compensar el nuevo tamaño al cambiar el tamaño de la ventana que contiene la vista dentro de la aplicación Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |