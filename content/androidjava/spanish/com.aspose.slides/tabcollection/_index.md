---
title: TabCollection
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Representa una colección de pestañas.
type: docs
url: /es/com.aspose.slides/tabcollection/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.ITabCollection](../../com.aspose.slides/itabcollection), com.aspose.slides.IDOMObject
```
public final class TabCollection implements ITabCollection, IDOMObject
```

Representa una colección de pestañas.
## Métodos

| Método | Descripción |
| --- | --- |
| [size()](#size--) | Obtiene el número de elementos realmente contenidos en la colección. |
| [get_Item(int index)](#get-Item-int-) | Obtiene el elemento en el índice especificado. |
| [add(double position, int align)](#add-double-int-) | Añade una pestaña a la colección. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Añade una pestaña a la colección. |
| [clear()](#clear--) | Elimina todos los elementos de la colección. |
| [removeAt(int index)](#removeAt-int-) | Elimina el elemento en el índice especificado de la colección. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si dos instancias de TabsEx son iguales. |
| [iterator()](#iterator--) | Devuelve un enumerador que itera a través de la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos los elementos de la colección al array especificado. |
| [isSynchronized()](#isSynchronized--) | Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). |
| [getSyncRoot()](#getSyncRoot--) | Devuelve una raíz de sincronización. |
### size() {#size--}
```
public final int size()
```


Obtiene el número de elementos realmente contenidos en la colección. Solo lectura int.

**Devuelve:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ITab get_Item(int index)
```


Obtiene el elemento en el índice especificado. Solo lectura [Tab](../../com.aspose.slides/tab).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public final ITab add(double position, int align)
```


Añade una pestaña a la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | double |  |
| align | int |  |

**Devuelve:**
[ITab](../../com.aspose.slides/itab) - Pestaña añadida.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public final int add(ITab value)
```


Añade una pestaña a la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | El objeto Tab que se añadirá al final de la colección. |

**Devuelve:**
int - El índice en el que se añadió la pestaña.
### clear() {#clear--}
```
public final void clear()
```


Elimina todos los elementos de la colección.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Elimina el elemento en el índice especificado de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero del elemento a eliminar. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Devuelve el objeto Parent_Immediate. Solo lectura IDOMObject.

**Devuelve:**
com.aspose.slides.IDOMObject
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si dos instancias de TabsEx son iguales.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El TabsEx a comparar con el TabsEx actual. |

**Devuelve:**
boolean - **true** si el TabsEx especificado es igual al TabsEx actual; de lo contrario, **false**.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iterator()
```


Devuelve un enumerador que itera a través de la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - Un IGenericEnumerator que puede usarse para iterar a través de la colección.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iteratorJava()
```


Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - Un java.util.Iterator para toda la colección.
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