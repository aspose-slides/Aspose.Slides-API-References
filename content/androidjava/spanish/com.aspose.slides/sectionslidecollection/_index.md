---
title: SectionSlideCollection
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Representa una colección de diapositivas en la sección.
type: docs
url: /es/com.aspose.slides/sectionslidecollection/
---
**Herencia:**
java.lang.Object, com.aspose.slides.DomObject

**Todas las interfaces implementadas:**
[com.aspose.slides.ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)
```
public final class SectionSlideCollection extends DomObject<Section> implements ISectionSlideCollection
```

Representa una colección de diapositivas en la sección.
## Métodos

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtiene el elemento en el índice especificado. |
| [size()](#size--) | Obtiene la cantidad de elementos realmente contenidos en la colección. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia la colección completa al arreglo especificado. |
| [isSynchronized()](#isSynchronized--) | Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). |
| [getSyncRoot()](#getSyncRoot--) | Devuelve una raíz de sincronización. |
| [iterator()](#iterator--) | Devuelve un enumerador que recorre la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para la colección completa. |
### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

Obtiene el elemento en el índice especificado. Solo lectura [ISlide](../../com.aspose.slides/islide).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[ISlide](../../com.aspose.slides/islide)
### size() {#size--}
```
public final int size()
```

Obtiene la cantidad de elementos realmente contenidos en la colección. Solo lectura int.

**Devuelve:**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia la colección completa al arreglo especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Arreglo destino |
| index | int | Índice en el arreglo destino. |

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
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

Devuelve un enumerador que recorre la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - Un IGenericEnumerator que puede usarse para recorrer la colección.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

Devuelve un iterador java para la colección completa.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - Un java.util.Iterator para la colección completa.