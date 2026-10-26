---
title: BehaviorPropertyCollection
second_title: Referencia de API de Aspose.Slides para Java
description: Representa propiedades de sincronización para el comportamiento del efecto.
type: docs
url: /es/com.aspose.slides/behaviorpropertycollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
```
public class BehaviorPropertyCollection implements IBehaviorPropertyCollection
```

Representa propiedades de sincronización para el comportamiento del efecto.
## Métodos

| Method | Description |
| --- | --- |
| [size()](#size--) | Devuelve el número de propiedades almacenadas en la colección. |
| [isReadOnly()](#isReadOnly--) | Obtiene un valor que indica si [IGenericCollection](../../com.aspose.slides/igenericcollection) es de solo lectura. |
| [add(IBehaviorProperty item)](#add-com.aspose.slides.IBehaviorProperty-) | Añade una nueva propiedad a la colección. |
| [add(String propertyValue)](#add-java.lang.String-) | Añade una nueva propiedad a la colección. |
| [indexOf(IBehaviorProperty item)](#indexOf-com.aspose.slides.IBehaviorProperty-) | Determina el índice de un elemento específico en la List. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Determina el índice de un elemento específico por el valor de la propiedad en la List. |
| [insert(int index, IBehaviorProperty item)](#insert-int-com.aspose.slides.IBehaviorProperty-) | Inserta una nueva propiedad en la colección en el índice especificado. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Inserta una nueva propiedad (con el valor de propiedad especificado) en la colección en el índice especificado. |
| [copyTo(IBehaviorProperty[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehaviorProperty---int-) | Copia los elementos de [IGenericCollection](../../com.aspose.slides/igenericcollection) a una Array, comenzando en un índice de Array específico. |
| [remove(IBehaviorProperty item)](#remove-com.aspose.slides.IBehaviorProperty-) | Elimina la propiedad especificada de la colección. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Elimina la propiedad especificada de la colección. |
| [removeAt(int index)](#removeAt-int-) | Elimina la propiedad en el índice especificado. |
| [clear()](#clear--) | Elimina todas las propiedades de la colección. |
| [contains(IBehaviorProperty item)](#contains-com.aspose.slides.IBehaviorProperty-) | Determina si [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valor específico. |
| [contains(String propertyValue)](#contains-java.lang.String-) | Determina si [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valor específico. |
| [get_Item(int index)](#get-Item-int-) | Devuelve una propiedad en el índice especificado. |
| [set_Item(int index, IBehaviorProperty value)](#set-Item-int-com.aspose.slides.IBehaviorProperty-) | Establece una propiedad en el índice especificado. |
| [iterator()](#iterator--) | Devuelve un enumerador que recorre la colección. |
| [indexOfItem(IBehaviorProperty item)](#indexOfItem-com.aspose.slides.IBehaviorProperty-) |  |
| [insertItem(int index, IBehaviorProperty item)](#insertItem-int-com.aspose.slides.IBehaviorProperty-) |  |
| [addItem(IBehaviorProperty item)](#addItem-com.aspose.slides.IBehaviorProperty-) |  |
| [containsItem(IBehaviorProperty item)](#containsItem-com.aspose.slides.IBehaviorProperty-) |  |
| [copyToTArray(IBehaviorProperty[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IBehaviorProperty---int-) |  |
| [removeItem(IBehaviorProperty item)](#removeItem-com.aspose.slides.IBehaviorProperty-) |  |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
### size() {#size--}
```
public final int size()
```


Devuelve el número de propiedades almacenadas en la colección. int de solo lectura.

**Devuelve:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Obtiene un valor que indica si [IGenericCollection](../../com.aspose.slides/igenericcollection) es de solo lectura. boolean de solo lectura.

**Devuelve:**
boolean - true if the [IGenericCollection](../../com.aspose.slides/igenericcollection) is read-only; otherwise, false.
### add(IBehaviorProperty item) {#add-com.aspose.slides.IBehaviorProperty-}
```
public final void add(IBehaviorProperty item)
```


Añade una nueva propiedad a la colección.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Property to add. |

### add(String propertyValue) {#add-java.lang.String-}
```
public final void add(String propertyValue)
```


Añade una nueva propiedad a la colección.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyValue | java.lang.String | Value of the property to add. |

### indexOf(IBehaviorProperty item) {#indexOf-com.aspose.slides.IBehaviorProperty-}
```
public final int indexOf(IBehaviorProperty item)
```


Determina el índice de un elemento específico en la List.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | The object to locate in the List. |

**Devuelve:**
int - The index of item if found in the list; otherwise, -1.
### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public final int indexOf(String propertyValue)
```


Determina el índice de un elemento específico por el valor de la propiedad en la List.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyValue | java.lang.String | value of the property |

**Devuelve:**
int - The index of the property with the specified value
### insert(int index, IBehaviorProperty item) {#insert-int-com.aspose.slides.IBehaviorProperty-}
```
public final void insert(int index, IBehaviorProperty item)
```


Inserta una nueva propiedad en la colección en el índice especificado.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index where a new property should be inserted. |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Property to add. |

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public final void insert(int index, String propertyValue)
```


Inserta una nueva propiedad (con el valor de propiedad especificado) en la colección en el índice especificado.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index where a new property should be inserted. |
| propertyValue | java.lang.String | Value of the property to add. |

### copyTo(IBehaviorProperty[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehaviorProperty---int-}
```
public final void copyTo(IBehaviorProperty[] array, int arrayIndex)
```


Copia los elementos de [IGenericCollection](../../com.aspose.slides/igenericcollection) a una Array, comenzando en un índice de Array específico.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) | The one-dimensional Array that is the destination of the elements copied from [IGenericCollection](../../com.aspose.slides/igenericcollection). The Array must have zero-based indexing. |
| arrayIndex | int | The zero-based index in array at which copying begins. |

### remove(IBehaviorProperty item) {#remove-com.aspose.slides.IBehaviorProperty-}
```
public final boolean remove(IBehaviorProperty item)
```


Elimina la propiedad especificada de la colección.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Property to remove. |

**Devuelve:**
boolean
### remove(String propertyValue) {#remove-java.lang.String-}
```
public final boolean remove(String propertyValue)
```


Elimina la propiedad especificada de la colección.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyValue | java.lang.String | Value of the property to remove. |

**Devuelve:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Elimina la propiedad en el índice especificado.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of the property which should be deleted. |

### clear() {#clear--}
```
public final void clear()
```


Elimina todas las propiedades de la colección.

### contains(IBehaviorProperty item) {#contains-com.aspose.slides.IBehaviorProperty-}
```
public final boolean contains(IBehaviorProperty item)
```


Determina si [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valor específico.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | The property to locate in the [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Devuelve:**
boolean - true if item is found in the [IGenericCollection](../../com.aspose.slides/igenericcollection); otherwise, false.
### contains(String propertyValue) {#contains-java.lang.String-}
```
public final boolean contains(String propertyValue)
```


Determina si [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valor específico.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyValue | java.lang.String | Value of the property to locate in the [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Devuelve:**
boolean - true if propertyValue is found in the [IGenericCollection](../../com.aspose.slides/igenericcollection); otherwise, false.
### get_Item(int index) {#get-Item-int-}
```
public final IBehaviorProperty get_Item(int index)
```


Devuelve una propiedad en el índice especificado.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of a property to return. |

**Devuelve:**
[IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) - Animation behavior property.
### set_Item(int index, IBehaviorProperty value) {#set-Item-int-com.aspose.slides.IBehaviorProperty-}
```
public final void set_Item(int index, IBehaviorProperty value)
```


Establece una propiedad en el índice especificado.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of a property to return. |
| value | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iterator()
```


Devuelve un enumerador que recorre la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - A IGenericEnumerator that can be used to iterate through the collection.
### indexOfItem(IBehaviorProperty item) {#indexOfItem-com.aspose.slides.IBehaviorProperty-}
```
public int indexOfItem(IBehaviorProperty item)
```




**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Devuelve:**
int
### insertItem(int index, IBehaviorProperty item) {#insertItem-int-com.aspose.slides.IBehaviorProperty-}
```
public void insertItem(int index, IBehaviorProperty item)
```




**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### addItem(IBehaviorProperty item) {#addItem-com.aspose.slides.IBehaviorProperty-}
```
public void addItem(IBehaviorProperty item)
```




**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### containsItem(IBehaviorProperty item) {#containsItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean containsItem(IBehaviorProperty item)
```




**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Devuelve:**
boolean
### copyToTArray(IBehaviorProperty[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IBehaviorProperty---int-}
```
public void copyToTArray(IBehaviorProperty[] array, int arrayIndex)
```




**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) |  |
| arrayIndex | int |  |

### removeItem(IBehaviorProperty item) {#removeItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean removeItem(IBehaviorProperty item)
```




**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Devuelve:**
boolean
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iteratorJava()
```


Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - An java.util.Iterator for the entire collection.