---
title: IPortionCollection
second_title: Referencia de la API de Aspose.Slides para Java
description: Representa una colección de porciones.
type: docs
url: /es/com.aspose.slides/iportioncollection/
---
**Todas las interfaces implementadas:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPortionCollection extends System.Collections.Generic.IGenericEnumerable<IPortion>
```

Representa una colección de porciones.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtiene el elemento en el índice especificado. |
| [getCount()](#getCount--) | Obtiene el número de elementos realmente contenidos en la colección. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Agrega una Portion al final de la colección. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Determina el índice de una porción específica en la colección. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Inserta una Portion en la colección en el índice especificado. |
| [clear()](#clear--) | Elimina todos los elementos de la colección. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Determina si el [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valor específico. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Elimina la primera aparición de un objeto específico del [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | Elimina el elemento en el índice especificado de la colección. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPortion get_Item(int index)
```


Obtiene el elemento en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IPortion](../../com.aspose.slides/iportion)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Obtiene el número de elementos realmente contenidos en la colección. Solo lectura int.

**Devuelve:**
int
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public abstract void add(IPortion value)
```


Agrega una Portion al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | La Portion que se agregará al final de la colección. |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public abstract int indexOf(IPortion item)
```


Determina el índice de una porción específica en la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | La porción que se localizará en la colección. |

**Devuelve:**
int - El índice del elemento si se encuentra en la colección; de lo contrario, -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public abstract void insert(int index, IPortion value)
```


Inserta una Portion en la colección en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero en el que se debe insertar la Portion. |
| value | [IPortion](../../com.aspose.slides/iportion) | La Portion que se insertará. |

### clear() {#clear--}
```
public abstract void clear()
```


Elimina todos los elementos de la colección.

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public abstract boolean contains(IPortion item)
```


Determina si el [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valor específico.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | El objeto que se localizará en el [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Devuelve:**
boolean - verdadero si el elemento se encuentra en el [IGenericCollection](../../com.aspose.slides/igenericcollection); de lo contrario, falso.
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public abstract boolean remove(IPortion item)
```


Elimina la primera aparición de un objeto específico del [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | El objeto que se eliminará del [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Devuelve:**
boolean - verdadero si el elemento se eliminó correctamente del [IGenericCollection](../../com.aspose.slides/igenericcollection); de lo contrario, falso. Este método también devuelve falso si el elemento no se encuentra en el [IGenericCollection](../../com.aspose.slides/igenericcollection) original.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Elimina el elemento en el índice especificado de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero del elemento que se eliminará. |