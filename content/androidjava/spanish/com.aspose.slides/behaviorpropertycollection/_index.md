---
title: BehaviorPropertyCollection
second_title: Referencia de API Java para Aspose.Slides en Android
description: Representa las propiedades de temporización para el comportamiento del efecto.
type: docs
url: /es/com.aspose.slides/behaviorpropertycollection/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
```
public class BehaviorPropertyCollection implements IBehaviorPropertyCollection
```

Representa las propiedades de temporización para el comportamiento del efecto.

## Métodos

| Método | Descripción |
| --- | --- |
| [size()](#size--) | Devuelve el número de propiedades almacenadas en la colección. |
| [isReadOnly()](#isReadOnly--) | Obtiene un valor que indica si el [IGenericCollection](../../com.aspose.slides/igenericcollection) es de solo lectura. |
| [add(IBehaviorProperty item)](#add-com.aspose.slides.IBehaviorProperty-) | Añade una nueva propiedad a la colección. |
| [add(String propertyValue)](#add-java.lang.String-) | Añade una nueva propiedad a la colección. |
| [indexOf(IBehaviorProperty item)](#indexOf-com.aspose.slides.IBehaviorProperty-) | Determina el índice de un elemento específico en la Lista. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Determina el índice de un elemento específico por valor de propiedad en la Lista. |
| [insert(int index, IBehaviorProperty item)](#insert-int-com.aspose.slides.IBehaviorProperty-) | Inserta una nueva propiedad en la colección en el índice especificado. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Inserta una nueva propiedad (con el valor de propiedad especificado) en la colección en el índice especificado. |
| [copyTo(IBehaviorProperty[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehaviorProperty---int-) | Copia los elementos de [IGenericCollection](../../com.aspose.slides/igenericcollection) a un Array, comenzando en un índice de Array particular. |
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
boolean - true si [IGenericCollection](../../com.aspose.slides/igenericcollection) es de solo lectura; de lo contrario, false.

### add(IBehaviorProperty item) {#add-com.aspose.slides.IBehaviorProperty-}
```
public final void add(IBehaviorProperty item)
```

Añade una nueva propiedad a la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Propiedad a añadir. |

### add(String propertyValue) {#add-java.lang.String-}
```
public final void add(String propertyValue)
```

Añade una nueva propiedad a la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propertyValue | java.lang.String | Valor de la propiedad a añadir. |

### indexOf(IBehaviorProperty item) {#indexOf-com.aspose.slides.IBehaviorProperty-}
```
public final int indexOf(IBehaviorProperty item)
```

Determina el índice de un elemento específico en la Lista.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | El objeto a localizar en la Lista. |

**Devuelve:**
int - El índice del elemento si se encuentra en la lista; de lo contrario, -1.

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public final int indexOf(String propertyValue)
```

Determina el índice de un elemento específico por valor de propiedad en la Lista.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propertyValue | java.lang.String | valor de la propiedad |

**Devuelve:**
int - El índice de la propiedad con el valor especificado

### insert(int index, IBehaviorProperty item) {#insert-int-com.aspose.slides.IBehaviorProperty-}
```
public final void insert(int index, IBehaviorProperty item)
```

Inserta una nueva propiedad en la colección en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice donde se debe insertar una nueva propiedad. |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Propiedad a añadir. |

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public final void insert(int index, String propertyValue)
```

Inserta una nueva propiedad (con el valor de propiedad especificado) en la colección en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice donde se debe insertar una nueva propiedad. |
| propertyValue | java.lang.String | Valor de la propiedad a añadir. |

### copyTo(IBehaviorProperty[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehaviorProperty---int-}
```
public final void copyTo(IBehaviorProperty[] array, int arrayIndex)
```

Copia los elementos de [IGenericCollection](../../com.aspose.slides/igenericcollection) a un Array, comenzando en un índice de Array particular.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) | El Array unidimensional que es el destino de los elementos copiados de [IGenericCollection](../../com.aspose.slides/igenericcollection). El Array debe tener indexación basada en cero. |
| arrayIndex | int | El índice basado en cero en el array donde comienza la copia. |

### remove(IBehaviorProperty item) {#remove-com.aspose.slides.IBehaviorProperty-}
```
public final boolean remove(IBehaviorProperty item)
```

Elimina la propiedad especificada de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Propiedad a eliminar. |

**Devuelve:**
boolean

### remove(String propertyValue) {#remove-java.lang.String-}
```
public final boolean remove(String propertyValue)
```

Elimina la propiedad especificada de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propertyValue | java.lang.String | Valor de la propiedad a eliminar. |

**Devuelve:**
boolean

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Elimina la propiedad en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de la propiedad que debe ser borrada. |

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | La propiedad a localizar en el [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Devuelve:**
boolean - true si el elemento se encuentra en el [IGenericCollection](../../com.aspose.slides/igenericcollection); de lo contrario, false.

### contains(String propertyValue) {#contains-java.lang.String-}
```
public final boolean contains(String propertyValue)
```

Determina si [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valor específico.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propertyValue | java.lang.String | Valor de la propiedad a localizar en el [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Devuelve:**
boolean - true si propertyValue se encuentra en el [IGenericCollection](../../com.aspose.slides/igenericcollection); de lo contrario, false.

### get_Item(int index) {#get-Item-int-}
```
public final IBehaviorProperty get_Item(int index)
```

Devuelve una propiedad en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de una propiedad a devolver. |

**Devuelve:**
[IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) - propiedad de comportamiento de animación.

### set_Item(int index, IBehaviorProperty value) {#set-Item-int-com.aspose.slides.IBehaviorProperty-}
```
public final void set_Item(int index, IBehaviorProperty value)
```

Establece una propiedad en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de una propiedad a devolver. |
| value | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iterator()
```

Devuelve un enumerador que recorre la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - Un IGenericEnumerator que puede usarse para iterar a través de la colección.

### indexOfItem(IBehaviorProperty item) {#indexOfItem-com.aspose.slides.IBehaviorProperty-}
```
public int indexOfItem(IBehaviorProperty item)
```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Devuelve:**
int

### insertItem(int index, IBehaviorProperty item) {#insertItem-int-com.aspose.slides.IBehaviorProperty-}
```
public void insertItem(int index, IBehaviorProperty item)
```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### addItem(IBehaviorProperty item) {#addItem-com.aspose.slides.IBehaviorProperty-}
```
public void addItem(IBehaviorProperty item)
```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### containsItem(IBehaviorProperty item) {#containsItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean containsItem(IBehaviorProperty item)
```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Devuelve:**
boolean

### copyToTArray(IBehaviorProperty[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IBehaviorProperty---int-}
```
public void copyToTArray(IBehaviorProperty[] array, int arrayIndex)
```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) |  |
| arrayIndex | int |  |

### removeItem(IBehaviorProperty item) {#removeItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean removeItem(IBehaviorProperty item)
```

**Parámetros:**
| Parámetro | Tipo | Descripción |
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
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - Un java.util.Iterator para toda la colección.