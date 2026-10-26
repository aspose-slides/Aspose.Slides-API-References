---
title: ColorOperationCollection
second_title: Aspose.Slides para Android mediante la referencia de la API Java
description: Representa una colección de operaciones de transformación de color.
type: docs
url: /es/com.aspose.slides/coloroperationcollection/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
```
public final class ColorOperationCollection implements IColorOperationCollection
```

Representa una colección de operaciones de transformación de color.
## Métodos

| Método | Descripción |
| --- | --- |
| [size()](#size--) | Devuelve el número de operaciones en una colección. |
| [get_Item(int index)](#get-Item-int-) | Devuelve o establece la operación en el índice especificado. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Devuelve o establece la operación en el índice especificado. |
| [add(int operation, float parameter)](#add-int-float-) | Añade una nueva operación al final de la colección. |
| [add(int operation)](#add-int-) | Añade una nueva operación al final de la colección. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Inserta la nueva operación en una colección. |
| [insert(int position, int operation)](#insert-int-int-) | Inserta la nueva operación en una colección. |
| [removeAt(int index)](#removeAt-int-) | Elimina la operación de color de una colección. |
| [clear()](#clear--) | Elimina todas las operaciones de color. |
| [iterator()](#iterator--) | Devuelve un enumerador que itera a través de la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para la colección completa. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos los elementos de la colección al array especificado. |
| [isSynchronized()](#isSynchronized--) | Devuelve un valor que indica si el acceso a la colección está sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Devuelve una raíz de sincronización. |
| [deepClone()](#deepClone--) | Crea una copia de una colección ColorOperationCollection. |
| [cloneT()](#cloneT--) | Clona el objeto actual |

### size() {#size--}
```
public final int size()
```

Devuelve el número de operaciones en una colección. Solo lectura int.

**Devuelve:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColorOperation get_Item(int index)
```

Devuelve o establece la operación en el índice especificado. Lectura/escritura [ColorOperation](../../com.aspose.slides/coloroperation).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public final void set_Item(int index, IColorOperation value)
```

Devuelve o establece la operación en el índice especificado. Lectura/escritura [ColorOperation](../../com.aspose.slides/coloroperation).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public final IColorOperation add(int operation, float parameter)
```

Añade una nueva operación al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| operation | int | Tipo de operación. |
| parameter | float | Parámetro de la operación. |

**Devuelve:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Operación agregada.
### add(int operation) {#add-int-}
```
public final IColorOperation add(int operation)
```

Añade una nueva operación al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| operation | int | Tipo de operación. |

**Devuelve:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Operación agregada.
### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public final IColorOperation insert(int position, int operation, float parameter)
```

Inserta la nueva operación en una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | int | El índice donde se insertará la operación. |
| operation | int | Tipo de operación. |
| parameter | float | Parámetro de la operación. |

**Devuelve:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Operación insertada.
### insert(int position, int operation) {#insert-int-int-}
```
public final IColorOperation insert(int position, int operation)
```

Inserta la nueva operación en una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | int | El índice donde se insertará la operación. |
| operation | int | Tipo de operación. |

**Devuelve:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Operación insertada.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Elimina la operación de color de una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de la operación de color a eliminar. |

### clear() {#clear--}
```
public final void clear()
```

Elimina todas las operaciones de color.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iterator()
```

Devuelve un enumerador que itera a través de la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - Un IGenericEnumerator que puede usarse para iterar a través de la colección.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iteratorJava()
```

Devuelve un iterador java para la colección completa.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - Un java.util.Iterator para la colección completa.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia todos los elementos de la colección al array especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array de destino. |
| index | int | Índice de inicio en el array de destino. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Devuelve un valor que indica si el acceso a la colección está sincronizado (thread-safe). Solo lectura boolean.

**Devuelve:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Devuelve una raíz de sincronización. Solo lectura Object.

**Devuelve:**
java.lang.Object
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Crea una copia de una colección ColorOperationCollection.

**Devuelve:**
java.lang.Object - Nueva colección [ColorOperationCollection](../../com.aspose.slides/coloroperationcollection).
### cloneT() {#cloneT--}
```
public final IColorOperationCollection cloneT()
```

Clona el objeto actual

**Devuelve:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection) - Clon