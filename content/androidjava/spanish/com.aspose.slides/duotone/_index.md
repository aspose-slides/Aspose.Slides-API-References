---
title: Duotone
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Representa un efecto Duotono.
type: docs
url: /es/com.aspose.slides/duotone/
---

**Herencia:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Todas las interfaces implementadas:**  
[com.aspose.slides.IDuotone](../../com.aspose.slides/iduotone), com.aspose.slides.IVisualEffect  
```
public final class Duotone extends ImageTransformOperation implements IDuotone, IVisualEffect
```

Representa un efecto Duotono. Para cada píxel, combina Color1 y Color2 mediante una interpolación lineal para determinar el nuevo color de ese píxel.

## Métodos

| Método | Descripción |
| --- | --- |
| [getColor1()](#getColor1--) | Devuelve el formato de color objetivo para píxeles oscuros. |
| [getColor2()](#getColor2--) | Devuelve el formato de color objetivo para píxeles claros. |
| [getEffective()](#getEffective--) | Obtiene los datos efectivos del efecto Duotono con la herencia aplicada. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el [Duotone](../../com.aspose.slides/duotone) especificado es igual al [Duotone](../../com.aspose.slides/duotone) actual. |
| [hashCode()](#hashCode--) | Sirve como función hash para un tipo particular. |

### getColor1() {#getColor1--}
```
public final IColorFormat getColor1()
```

Devuelve el formato de color objetivo para píxeles oscuros. Solo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getColor2() {#getColor2--}
```
public final IColorFormat getColor2()
```

Devuelve el formato de color objetivo para píxeles claros. Solo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffective() {#getEffective--}
```
public final IDuotoneEffectiveData getEffective()
```

Obtiene los datos efectivos del efecto Duotono con la herencia aplicada.

**Devuelve:**  
[IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata) - Un [IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata).

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

Determina si el [Duotone](../../com.aspose.slides/duotone) especificado es igual al [Duotone](../../com.aspose.slides/duotone) actual.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El [Duotone](../../com.aspose.slides/duotone) a comparar. |

**Devuelve:**  
boolean - verdadero si los objetos son iguales; de lo contrario, falso.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Sirve como función hash para un tipo particular.

**Devuelve:**  
int - Un código hash para el objeto actual.