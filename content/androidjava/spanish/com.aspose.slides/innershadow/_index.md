---
title: InnerShadow
second_title: Aspose.Slides para Android a través de la referencia API Java
description: Representa un efecto de sombra interior.
type: docs
url: /es/com.aspose.slides/innershadow/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IInnerShadow](../../com.aspose.slides/iinnershadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class InnerShadow implements IInnerShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Representa un efecto de sombra interior.
## Métodos

| Método | Descripción |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Radio de desenfoque. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Radio de desenfoque. |
| [getDirection()](#getDirection--) | Dirección de la sombra. |
| [setDirection(float value)](#setDirection-float-) | Dirección de la sombra. |
| [getDistance()](#getDistance--) | Distancia de la sombra. |
| [setDistance(double value)](#setDistance-double-) | Distancia de la sombra. |
| [getShadowColor()](#getShadowColor--) | Color de la sombra. |
| [getEffective()](#getEffective--) | Obtiene los datos efectivos del efecto de sombra interior con la herencia aplicada. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el [InnerShadow](../../com.aspose.slides/innershadow) especificado es igual al [InnerShadow](../../com.aspose.slides/innershadow) actual. |
| [hashCode()](#hashCode--) | Sirve como función hash para un tipo particular. |
### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```


Radio de desenfoque. Lectura/escritura double.

**Devuelve:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```


Radio de desenfoque. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |
### getDirection() {#getDirection--}
```
public final float getDirection()
```


Dirección de la sombra. Lectura/escritura float.

**Devuelve:**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```


Dirección de la sombra. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public final double getDistance()
```


Distancia de la sombra. Lectura/escritura double.

**Devuelve:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```


Distancia de la sombra. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```


Color de la sombra. Solo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IInnerShadowEffectiveData getEffective()
```


Obtiene los datos efectivos del efecto de sombra interior con la herencia aplicada.

**Devuelve:**
[IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata) - Un [IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata).
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
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si el [InnerShadow](../../com.aspose.slides/innershadow) especificado es igual al [InnerShadow](../../com.aspose.slides/innershadow) actual.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El [InnerShadow](../../com.aspose.slides/innershadow) a comparar. |

**Devuelve:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Sirve como función hash para un tipo particular.

**Devuelve:**
int - A hash code for the current object.