---
title: BehaviorCollection
second_title: Referencia API de Aspose.Slides para Java
description: Representa una colección de efectos de comportamiento.
type: docs
url: /es/com.aspose.slides/behaviorcollection/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
```
public class BehaviorCollection implements IBehaviorCollection
```

Representa una colección de efectos de comportamiento.
## Métodos

| Método | Descripción |
| --- | --- |
| [getCount()](#getCount--) | Devuelve el número de comportamientos en una colección. |
| [isReadOnly()](#isReadOnly--) | Obtiene un valor que indica si [IGenericCollection](../../com.aspose.slides/igenericcollection) es de solo lectura. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Añade un comportamiento nuevo a una colección. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Determina el índice de un elemento específico en la Lista. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Inserta un comportamiento nuevo en una colección en el índice especificado. |
| [copyTo(IBehavior[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehavior---int-) | Copia los elementos de [IGenericCollection](../../com.aspose.slides/igenericcollection) a un Array, comenzando en un índice de Array concreto. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Elimina el comportamiento especificado de una colección. |
| [removeAt(int index)](#removeAt-int-) | Elimina un comportamiento de una colección en el índice especificado. |
| [clear()](#clear--) | Elimina todos los comportamientos de una colección. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Determina si [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valor específico. |
| [get_Item(int index)](#get-Item-int-) | Devuelve un comportamiento en el índice especificado. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Establece un comportamiento en el índice especificado. |
| [iterator()](#iterator--) | Devuelve un enumerador que itera a través de la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
### getCount() {#getCount--}
```
public final int getCount()
```


Devuelve el número de comportamientos en una colección. int de solo lectura.

**Devuelve:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Obtiene un valor que indica si [IGenericCollection](../../com.aspose.slides/igenericcollection) es de solo lectura. boolean de solo lectura.

**Devuelve:**
boolean - verdadero si [IGenericCollection](../../com.aspose.slides/igenericcollection) es de solo lectura; de lo contrario, falso.
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public final void add(IBehavior item)
```


Añade un comportamiento nuevo a una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Comportamiento a añadir. |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public final int indexOf(IBehavior item)
```


Determina el índice de un elemento específico en la Lista.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | El objeto a localizar en la Lista. |

**Devuelve:**
int - El índice del elemento si se encuentra en la lista; de lo contrario, -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public final void insert(int index, IBehavior item)
```


Inserta un comportamiento nuevo en una colección en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice donde se debe insertar el nuevo comportamiento. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Comportamiento a insertar. |

### copyTo(IBehavior[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehavior---int-}
```
public final void copyTo(IBehavior[] array, int arrayIndex)
```


Copia los elementos de [IGenericCollection](../../com.aspose.slides/igenericcollection) a un Array, comenzando en un índice de Array concreto.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | [IBehavior\[\]](../../com.aspose.slides/ibehavior) | El Array unidimensional que es el destino de los elementos copiados de [IGenericCollection](../../com.aspose.slides/igenericcollection). El Array debe tener indexación basada en cero. |
| arrayIndex | int | El índice basado en cero en el array en el que comienza la copia. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public final boolean remove(IBehavior item)
```


Elimina el comportamiento especificado de una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Comportamiento a eliminar. |

**Devuelve:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Elimina un comportamiento de una colección en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de un comportamiento a eliminar. |

### clear() {#clear--}
```
public final void clear()
```


Elimina todos los comportamientos de una colección.

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public final boolean contains(IBehavior item)
```


Determina si [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valor específico.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | El objeto a localizar en [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Devuelve:**
boolean - verdadero si el elemento se encuentra en [IGenericCollection](../../com.aspose.slides/igenericcollection); de lo contrario, falso.
### get_Item(int index) {#get-Item-int-}
```
public final IBehavior get_Item(int index)
```


Devuelve un comportamiento en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de un comportamiento a devolver. |

**Devuelve:**
[IBehavior](../../com.aspose.slides/ibehavior) - comportamiento de animación.
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public final void set_Item(int index, IBehavior value)
```


Establece un comportamiento en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de un comportamiento a establecer. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iterator()
```


Devuelve un enumerador que itera a través de la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - Un IGenericEnumerator que puede usarse para iterar a través de la colección.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iteratorJava()
```


Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - Un java.util.Iterator para toda la colección.