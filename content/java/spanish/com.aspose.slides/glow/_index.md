---
title: Glow
second_title: Referencia de API de Aspose.Slides para Java
description: Representa un efecto Glow en el que se añade un contorno borroso de color fuera de los bordes del objeto.
type: docs
url: /es/com.aspose.slides/glow/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IGlow](../../com.aspose.slides/iglow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class Glow implements IGlow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Representa un efecto Glow, en el que se añade un contorno borroso de color fuera de los bordes del objeto.
## Métodos

| Método | Descripción |
| --- | --- |
| [getRadius()](#getRadius--) | Radio. |
| [setRadius(double value)](#setRadius-double-) | Radio. |
| [getColor()](#getColor--) | Formato de color. |
| [getEffective()](#getEffective--) | Obtiene los datos efectivos del efecto Glow con la herencia aplicada. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el [Glow](../../com.aspose.slides/glow) especificado es igual al [Glow](../../com.aspose.slides/glow) actual. |
| [hashCode()](#hashCode--) | Sirve como función hash para un tipo particular. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```


Radio. Sólo lectura/escritura double .

**Devuelve:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


Radio. Sólo lectura/escritura double .

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


Formato de color. Sólo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IGlowEffectiveData getEffective()
```


Obtiene los datos efectivos del efecto Glow con la herencia aplicada.

**Devuelve:**
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata) - un [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Devuelve el objeto Parent_Immediate. Sólo lectura IDOMObject.

**Devuelve:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Versión. Sólo lectura long.

**Devuelve:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Devuelve el IPresentationComponent padre. Sólo lectura [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Devuelve:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si el [Glow](../../com.aspose.slides/glow) especificado es igual al [Glow](../../com.aspose.slides/glow) actual.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El [Glow](../../com.aspose.slides/glow) a comparar. |

**Devuelve:**
boolean - true si los objetos son iguales; de lo contrario, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Sirve como función hash para un tipo particular.

**Devuelve:**
int - Un código hash para el objeto actual.