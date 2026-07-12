---
title: GradientStopCollection
second_title: Aspose.Slides para Android vía referencia de API Java
description: Representa una colección de paradas de degradado.
type: docs
url: /es/com.aspose.slides/gradientstopcollection/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas las interfaces implementadas:**
[com.aspose.slides.IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
```
public final class GradientStopCollection extends PVIObject implements IGradientStopCollection
```

Representa una colección de paradas de degradado.
## Métodos

| Método | Descripción |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [size()](#size--) | Devuelve el número de paradas de degradado en una colección. |
| [get_Item(int index)](#get-Item-int-) | Devuelve la parada de degradado por índice. |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | Crea una nueva parada de degradado y la agrega al final de la colección. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Crea una nueva parada de degradado y la agrega al final de la colección. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Crea una nueva parada de degradado y la agrega al final de la colección. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | Crea una nueva parada de degradado y la inserta en el índice especificado de la colección. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Crea una nueva parada de degradado y la inserta en el índice especificado de la colección. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Crea una nueva parada de degradado y la inserta en el índice especificado de la colección. |
| [removeAt(int index)](#removeAt-int-) | Elimina una parada de degradado en el índice especificado. |
| [clear()](#clear--) | Elimina todas las paradas de degradado de una colección. |
| [iterator()](#iterator--) | Devuelve un enumerador que itera a través de la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos los elementos de la colección al array especificado. |
| [isSynchronized()](#isSynchronized--) | Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). |
| [getSyncRoot()](#getSyncRoot--) | Devuelve una raíz de sincronización. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versión. Solo lectura long.

**Devuelve:**
long
### size() {#size--}
```
public final int size()
```

Devuelve el número de paradas de degradado en una colección. Solo lectura int.

**Devuelve:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IGradientStop get_Item(int index)
```

Devuelve la parada de degradado por índice.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public final IGradientStop add(float position, Integer color)
```

Crea una nueva parada de degradado y la agrega al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | float | Posición de la nueva parada de degradado. |
| color | java.lang.Integer | Color de la nueva parada de degradado. |

**Devuelve:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Índice de la nueva parada de degradado en la colección.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public final IGradientStop addPresetColor(float position, int presetColor)
```

Crea una nueva parada de degradado y la agrega al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | float | Posición de la nueva parada de degradado. |
| presetColor | int | Color de la nueva parada de degradado. |

**Devuelve:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Índice de la nueva parada de degradado en la colección.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public final IGradientStop addSchemeColor(float position, int schemeColor)
```

Crea una nueva parada de degradado y la agrega al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | float | Posición de la nueva parada de degradado. |
| schemeColor | int | Color de la nueva parada de degradado. |

**Devuelve:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Índice de la nueva parada de degradado en la colección.
### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public final void insert(int index, float position, Integer color)
```

Crea una nueva parada de degradado y la inserta en el índice especificado de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice en la colección donde se insertará la nueva parada de degradado. |
| position | float | Posición de la nueva parada de degradado. |
| color | java.lang.Integer | Color de la nueva parada de degradado. |
### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public final void insertPresetColor(int index, float position, int presetColor)
```

Crea una nueva parada de degradado y la inserta en el índice especificado de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice en la colección donde se insertará la nueva parada de degradado. |
| position | float | Posición de la nueva parada de degradado. |
| presetColor | int | Color de la nueva parada de degradado. |
### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public final void insertSchemeColor(int index, float position, int schemeColor)
```

Crea una nueva parada de degradado y la inserta en el índice especificado de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice en la colección donde se insertará la nueva parada de degradado. |
| position | float | Posición de la nueva parada de degradado. |
| schemeColor | int | Color de la nueva parada de degradado. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Elimina una parada de degradado en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de una parada de degradado que debe eliminarse. |
### clear() {#clear--}
```
public final void clear()
```

Elimina todas las paradas de degradado de una colección.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iterator()
```

Devuelve un enumerador que itera a través de la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - Un IGenericEnumerator que puede usarse para iterar a través de la colección.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iteratorJava()
```

Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - Un java.util.Iterator para toda la colección.
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

Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). Solo lectura boolean.

**Devuelve:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Devuelve una raíz de sincronización. Solo lectura Object.

**Devuelve:**
java.lang.Object