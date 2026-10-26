---
title: FillOverlay
second_title: Aspose.Slides para Android a través de la referencia de la API Java
description: Representa un efecto Fill Overlay.
type: docs
url: /es/com.aspose.slides/filloverlay/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Todas las interfaces implementadas:**
[com.aspose.slides.IFillOverlay](../../com.aspose.slides/ifilloverlay), com.aspose.slides.IVisualEffect
```
public final class FillOverlay extends ImageTransformOperation implements IFillOverlay, IVisualEffect
```

Representa un efecto Fill Overlay. Un Fill Overlay puede usarse para especificar un relleno adicional para un objeto y mezclar los dos rellenos juntos.
## Métodos

| Método | Descripción |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Formato de relleno. |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getEffective()](#getEffective--) | Obtiene los datos efectivos del efecto Fill Overlay con la herencia aplicada. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el [FillOverlay](../../com.aspose.slides/filloverlay) especificado es igual al [FillOverlay](../../com.aspose.slides/filloverlay) actual. |
| [hashCode()](#hashCode--) | Sirve como función hash para un tipo particular. |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


Formato de relleno. Solo lectura [IFillFormat](../../com.aspose.slides/ifillformat).

**Devuelve:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBlend() {#getBlend--}
```
public final int getBlend()
```


FillBlendMode. Lectura/escritura [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Devuelve:**
int
### setBlend(int value) {#setBlend-int-}
```
public final void setBlend(int value)
```


FillBlendMode. Lectura/escritura [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IFillOverlayEffectiveData getEffective()
```


Obtiene los datos efectivos del efecto Fill Overlay con la herencia aplicada.

**Devuelve:**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata) - Un [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versión. Solo lectura long.

**Devuelve:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si el [FillOverlay](../../com.aspose.slides/filloverlay) especificado es igual al [FillOverlay](../../com.aspose.slides/filloverlay) actual.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El [FillOverlay](../../com.aspose.slides/filloverlay) a comparar. |

**Devuelve:**
boolean - true si los objetos son iguales; de lo contrario, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Sirve como función hash para un tipo particular.

**Devuelve:**
int - Un código hash para el objeto actual.