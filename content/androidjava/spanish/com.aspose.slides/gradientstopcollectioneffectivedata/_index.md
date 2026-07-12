---
title: GradientStopCollectionEffectiveData
second_title: Aspose.Slides para Android a través de la API Java
description: Representa una colección de objetos GradientStopData.
type: docs
url: /es/com.aspose.slides/gradientstopcollectioneffectivedata/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
com.aspose.slides.IEffectiveData, [com.aspose.slides.IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)
```
public class GradientStopCollectionEffectiveData implements IEffectiveData, IGradientStopCollectionEffectiveData
```

Representa una colección de objetos GradientStopData.
## Métodos

| Método | Descripción |
| --- | --- |
| [size()](#size--) | Devuelve el número de paradas de degradado en una colección. |
| [get_Item(int index)](#get-Item-int-) | Devuelve la parada de degradado por índice. |
| [iterator()](#iterator--) | Devuelve un enumerador que recorre la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos los elementos de la colección al array especificado. |
| [isSynchronized()](#isSynchronized--) | Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). |
| [getSyncRoot()](#getSyncRoot--) | Devuelve una raíz de sincronización. |
### size() {#size--}
```
public final int size()
```

Devuelve el número de paradas de degradado en una colección. int de solo lectura.

**Devuelve:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IGradientStopEffectiveData get_Item(int index)
```

Devuelve la parada de degradado por índice.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IGradientStopEffectiveData](../../com.aspose.slides/igradientstopeffectivedata)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStopEffectiveData> iterator()
```

Devuelve un enumerador que recorre la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStopEffectiveData> - Un IGenericEnumerator que puede usarse para iterar a través de la colección.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStopEffectiveData> iteratorJava()
```

Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStopEffectiveData> - Un java.util.Iterator para toda la colección.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia todos los elementos de la colección al array especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array de destino. |
| index | int | Índice inicial en el array de destino. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). boolean de solo lectura.

**Devuelve:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Devuelve una raíz de sincronización. Object de solo lectura.

**Devuelve:**
java.lang.Object