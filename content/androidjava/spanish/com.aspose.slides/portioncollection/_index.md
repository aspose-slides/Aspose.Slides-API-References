---
title: PortionCollection
second_title: Referencia de API Java de Aspose.Slides para Android
description: Representa una colección de porciones.
type: docs
url: /es/com.aspose.slides/portioncollection/
---
**Herencia:**
java.lang.Object, com.aspose.slides.DomObject

**Todas las interfaces implementadas:**
[com.aspose.slides.IPortionCollection](../../com.aspose.slides/iportioncollection)
```
public final class PortionCollection extends DomObject<Paragraph> implements IPortionCollection
```

Representa una colección de porciones.
## Métodos

| Método | Descripción |
| --- | --- |
| [getCount()](#getCount--) | Obtiene el número de elementos realmente contenidos en la colección. |
| [isReadOnly()](#isReadOnly--) | Obtiene un valor que indica si el [IGenericCollection](../../com.aspose.slides/igenericcollection) es de solo lectura. |
| [get_Item(int index)](#get-Item-int-) | Obtiene el elemento en el índice especificado. |
| [set_Item(int index, IPortion value)](#set-Item-int-com.aspose.slides.IPortion-) | Obtiene el elemento en el índice especificado. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Añade una Portion al final de la colección. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Determina el índice de un elemento específico en la List. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Inserta una Portion en la colección en el índice especificado. |
| [clear()](#clear--) | Elimina todos los elementos de la colección. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Determina si el [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valor específico. |
| [copyTo(IPortion[] array, int arrayIndex)](#copyTo-com.aspose.slides.IPortion---int-) | Copia los elementos del [IGenericCollection](../../com.aspose.slides/igenericcollection) a un Array, comenzando en un índice de Array particular. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Elimina la primera aparición de un objeto específico del [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | Elimina el elemento en el índice especificado de la colección. |
| [iterator()](#iterator--) | Devuelve un enumerador que itera a través de la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
### getCount() {#getCount--}
```
public final int getCount()
```


Obtiene el número de elementos realmente contenidos en la colección. int de solo lectura.

**Devuelve:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Obtiene un valor que indica si el [IGenericCollection](../../com.aspose.slides/igenericcollection) es de solo lectura. boolean de solo lectura.

**Devuelve:**
boolean - true if the [IGenericCollection](../../com.aspose.slides/igenericcollection) is read-only; otherwise, false.
### get_Item(int index) {#get-Item-int-}
```
public final IPortion get_Item(int index)
```


Obtiene el elemento en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IPortion](../../com.aspose.slides/iportion)
### set_Item(int index, IPortion value) {#set-Item-int-com.aspose.slides.IPortion-}
```
public final void set_Item(int index, IPortion value)
```


Obtiene el elemento en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |
| value | [IPortion](../../com.aspose.slides/iportion) |  |

### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public final void add(IPortion value)
```


Añade una Portion al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | La Portion a añadir al final de la colección. |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public final int indexOf(IPortion item)
```


Determina el índice de un elemento específico en la List.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | El objeto a localizar en la List. |

**Devuelve:**
int - El índice del elemento si se encuentra en la lista; de lo contrario, -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public final void insert(int index, IPortion value)
```


Inserta una Portion en la colección en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero donde la Portion debe insertarse. |
| value | [IPortion](../../com.aspose.slides/iportion) | La Portion a insertar. |

### clear() {#clear--}
```
public final void clear()
```


Elimina todos los elementos de la colección.

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public final boolean contains(IPortion item)
```


Determina si el [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valor específico.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | El objeto a localizar en el [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Devuelve:**
boolean - true if item is found in the [IGenericCollection](../../com.aspose.slides/igenericcollection); otherwise, false.
### copyTo(IPortion[] array, int arrayIndex) {#copyTo-com.aspose.slides.IPortion---int-}
```
public final void copyTo(IPortion[] array, int arrayIndex)
```


Copia los elementos del [IGenericCollection](../../com.aspose.slides/igenericcollection) a un Array, comenzando en un índice de Array particular.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | [IPortion\[\]](../../com.aspose.slides/iportion) | El Array unidimensional que es el destino de los elementos copiados de [IGenericCollection](../../com.aspose.slides/igenericcollection). El Array debe tener indexación basada en cero. |
| arrayIndex | int | El índice basado en cero en el arreglo donde comienza la copia. |

### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public final boolean remove(IPortion item)
```


Elimina la primera aparición de un objeto específico del [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | El objeto a eliminar del [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Devuelve:**
boolean - true if item was successfully removed from the [IGenericCollection](../../com.aspose.slides/igenericcollection); otherwise, false. This method also returns false if item is not found in the original [IGenericCollection](../../com.aspose.slides/igenericcollection).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Elimina el elemento en el índice especificado de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero del elemento a eliminar. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iterator()
```


Devuelve un enumerador que itera a través de la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iteratorJava()
```


Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - An java.util.Iterator for the entire collection.