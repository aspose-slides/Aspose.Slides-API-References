---
title: IColorOperationCollection
second_title: Aspose.Slides para Android vía Java API Reference
description: Representa una colección de operaciones de transformación de color.
type: docs
url: /es/com.aspose.slides/icoloroperationcollection/
---
**Todas las Interfaces Implementadas:**
com.aspose.slides.IGenericCloneable, com.aspose.slides.IGenericCollection
```
public interface IColorOperationCollection extends IGenericCloneable<IColorOperationCollection>, IGenericCollection<IColorOperation>
```

Representa una colección de operaciones de transformación de color.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Devuelve o establece la operación en el índice especificado. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Devuelve o establece la operación en el índice especificado. |
| [add(int operation, float parameter)](#add-int-float-) | Agrega una nueva operación al final de la colección. |
| [add(int operation)](#add-int-) | Agrega una nueva operación al final de la colección. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Inserta la nueva operación en una colección. |
| [insert(int position, int operation)](#insert-int-int-) | Inserta la nueva operación en una colección. |
| [removeAt(int index)](#removeAt-int-) | Elimina la operación de color de una colección. |
| [clear()](#clear--) | Elimina todas las operaciones de color. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColorOperation get_Item(int index)
```


Devuelve o establece la operación en el índice especificado. Lectura/escritura [IColorOperation](../../com.aspose.slides/icoloroperation).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public abstract void set_Item(int index, IColorOperation value)
```


Devuelve o establece la operación en el índice especificado. Lectura/escritura [IColorOperation](../../com.aspose.slides/icoloroperation).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public abstract IColorOperation add(int operation, float parameter)
```


Agrega una nueva operación al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| operation | int | Tipo de operación. |
| parameter | float | Parámetro de la operación. |

**Devuelve:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Operación añadida.
### add(int operation) {#add-int-}
```
public abstract IColorOperation add(int operation)
```


Agrega una nueva operación al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| operation | int | Tipo de operación. |

**Devuelve:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Operación añadida.
### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public abstract IColorOperation insert(int position, int operation, float parameter)
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
public abstract IColorOperation insert(int position, int operation)
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
public abstract void removeAt(int index)
```


Elimina la operación de color de una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de la operación de color a eliminar. |

### clear() {#clear--}
```
public abstract void clear()
```


Elimina todas las operaciones de color.