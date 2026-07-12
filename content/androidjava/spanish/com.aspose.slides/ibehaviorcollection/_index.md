---
title: IBehaviorCollection
second_title: Referencia de API Java de Aspose.Slides para Android
description: Representa una colección de efectos de comportamiento.
type: docs
url: /es/com.aspose.slides/ibehaviorcollection/
---
**Todas las interfaces implementadas:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IBehaviorCollection extends System.Collections.Generic.IGenericEnumerable<IBehavior>
```

Representa una colección de efectos de comportamiento.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Devuelve un comportamiento en el índice especificado. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Devuelve un comportamiento en el índice especificado. |
| [getCount()](#getCount--) | Devuelve el número de comportamientos en una colección. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Agrega un comportamiento nuevo a una colección. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Determina el índice de un elemento específico en la Lista. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Inserta un comportamiento nuevo en una colección en el índice especificado. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Elimina el comportamiento especificado de una colección. |
| [removeAt(int index)](#removeAt-int-) | Elimina un comportamiento de una colección en el índice especificado. |
| [clear()](#clear--) | Elimina todos los comportamientos de una colección. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Determina si el [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valor específico. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IBehavior get_Item(int index)
```

Devuelve un comportamiento en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice del comportamiento a devolver. |

**Devuelve:**
[IBehavior](../../com.aspose.slides/ibehavior) - Comportamiento de animación.
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public abstract void set_Item(int index, IBehavior value)
```

Devuelve un comportamiento en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice del comportamiento a devolver. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### getCount() {#getCount--}
```
public abstract int getCount()
```

Devuelve el número de comportamientos en una colección. int de solo lectura.

**Devuelve:**
int
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public abstract void add(IBehavior item)
```

Agrega un comportamiento nuevo a una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Comportamiento a agregar. |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public abstract int indexOf(IBehavior item)
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
public abstract void insert(int index, IBehavior item)
```

Inserta un comportamiento nuevo en una colección en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice donde se debe insertar el nuevo comportamiento. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Comportamiento a insertar. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public abstract boolean remove(IBehavior item)
```

Elimina el comportamiento especificado de una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Comportamiento a eliminar. |

**Devuelve:**
boolean - Verdadero si el comportamiento se eliminó con éxito boolean
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Elimina un comportamiento de una colección en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice del comportamiento a eliminar. |

### clear() {#clear--}
```
public abstract void clear()
```

Elimina todos los comportamientos de una colección.

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public abstract boolean contains(IBehavior item)
```

Determina si el [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valor específico.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | El objeto a localizar en el [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Devuelve:**
boolean - verdadero si el elemento se encuentra en el [IGenericCollection](../../com.aspose.slides/igenericcollection); de lo contrario, falso.