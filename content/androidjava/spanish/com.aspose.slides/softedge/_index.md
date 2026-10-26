---
title: SoftEdge
second_title: Aspose.Slides para Android vía referencia de API Java
description: Representa un efecto de borde suave.
type: docs
url: /es/com.aspose.slides/softedge/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.ISoftEdge](../../com.aspose.slides/isoftedge), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class SoftEdge implements ISoftEdge, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Representa un efecto de borde suave. Los bordes de la forma están difuminados, mientras que el relleno no se ve afectado.
## Métodos

| Método | Descripción |
| --- | --- |
| [getRadius()](#getRadius--) | Especifica el radio del desenfoque que se aplicará a los bordes. |
| [setRadius(double value)](#setRadius-double-) | Especifica el radio del desenfoque que se aplicará a los bordes. |
| [getEffective()](#getEffective--) | Obtiene los datos efectivos del efecto Soft Edge con la herencia aplicada. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el [SoftEdge](../../com.aspose.slides/softedge) especificado es igual al [SoftEdge](../../com.aspose.slides/softedge) actual. |
| [hashCode()](#hashCode--) | Sirve como función hash para un tipo particular. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```


Especifica el radio del desenfoque que se aplicará a los bordes. Lectura/escritura double.

**Devuelve:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


Especifica el radio del desenfoque que se aplicará a los bordes. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final ISoftEdgeEffectiveData getEffective()
```


Obtiene los datos efectivos del efecto Soft Edge con la herencia aplicada.

**Devuelve:**
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata) - Un [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata).
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


Devuelve el IPresentationComponent padre. Solo lectura [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Devuelve:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si el [SoftEdge](../../com.aspose.slides/softedge) especificado es igual al [SoftEdge](../../com.aspose.slides/softedge) actual.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El [SoftEdge](../../com.aspose.slides/softedge) a comparar. |

**Devuelve:**
boolean - verdadero si los objetos son iguales; de lo contrario, falso.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Sirve como función hash para un tipo particular.

**Devuelve:**
int - Un código hash para el objeto actual.