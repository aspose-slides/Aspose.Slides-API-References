---
title: ITabCollection
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Representa una colección de pestañas.
type: docs
url: /es/com.aspose.slides/itabcollection/
---
**Todas las interfaces implementadas:**
com.aspose.slides.IGenericCollection
```
public interface ITabCollection extends IGenericCollection<ITab>
```

Representa una colección de pestañas.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtiene el elemento en el índice especificado. |
| [add(double position, int align)](#add-double-int-) | Añade una pestaña a la colección. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Añade una pestaña a la colección. |
| [clear()](#clear--) | Elimina todos los elementos de la colección. |
| [removeAt(int index)](#removeAt-int-) | Elimina el elemento en el índice especificado de la colección. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITab get_Item(int index)
```


Obtiene el elemento en el índice especificado. Solo lectura [ITab](../../com.aspose.slides/itab).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public abstract ITab add(double position, int align)
```


Añade una pestaña a la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | double | Posición de la pestaña. |
| align | int | Alineación de la pestaña. |

**Devuelve:**
[ITab](../../com.aspose.slides/itab) - Pestaña añadida.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public abstract int add(ITab value)
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
public abstract void clear()
```


Elimina todos los elementos de la colección.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Elimina el elemento en el índice especificado de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero del elemento a eliminar. |
