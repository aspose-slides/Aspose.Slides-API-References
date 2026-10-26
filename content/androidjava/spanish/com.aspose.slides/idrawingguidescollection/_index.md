---
title: IDrawingGuidesCollection
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Representa una colección de guías de dibujo ajustables.
type: docs
url: /es/com.aspose.slides/idrawingguidescollection/
---
**Todas las interfaces implementadas:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IDrawingGuidesCollection extends System.Collections.Generic.IGenericEnumerable<IDrawingGuide>
```

Representa una colección de guías de dibujo ajustables.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Devuelve la guía de dibujo por índice. |
| [add(byte orientation, float position)](#add-byte-float-) | Agrega la guía de dibujo al final de la colección. |
| [removeAt(int index)](#removeAt-int-) | Elimina la guía de dibujo en el índice especificado. |
| [clear()](#clear--) | Elimina todos los elementos de la colección. |
| [getCount()](#getCount--) | Obtiene el número de todos los elementos de la colección. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDrawingGuide get_Item(int index)
```


Devuelve la guía de dibujo por índice. Solo lectura [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public abstract IDrawingGuide add(byte orientation, float position)
```


Agrega la guía de dibujo al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| orientation | byte | Orientación de la guía de dibujo. |
| position | float | Posición de la guía de dibujo en puntos. |

**Devuelve:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Elimina la guía de dibujo en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de la guía de dibujo que debe eliminarse. |

### clear() {#clear--}
```
public abstract void clear()
```


Elimina todos los elementos de la colección.

### getCount() {#getCount--}
```
public abstract int getCount()
```


Obtiene el número de todos los elementos de la colección. Solo lectura int.

**Devuelve:**
int