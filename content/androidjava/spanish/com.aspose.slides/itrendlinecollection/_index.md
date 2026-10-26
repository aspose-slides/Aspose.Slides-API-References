---
title: ITrendlineCollection
second_title: Aspose.Slides para Android a través de la referencia de la API Java
description: Representa una colección de TrendlineEx
type: docs
url: /es/com.aspose.slides/itrendlinecollection/
---
**Todas las interfaces implementadas:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ITrendlineCollection extends System.Collections.Generic.IGenericEnumerable<ITrendline>
```

Representa una colección de TrendlineEx
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtiene el elemento en el índice especificado. |
| [getCount()](#getCount--) | Obtiene el número de elementos realmente contenidos en la colección. |
| [add(int trendlineType)](#add-int-) | Agrega la nueva Trendline al final de una colección y la devuelve. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Elimina el valor especificado. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITrendline get_Item(int index)
```

Obtiene el elemento en el índice especificado. Solo lectura [ITrendline](../../com.aspose.slides/itrendline).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[ITrendline](../../com.aspose.slides/itrendline)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Obtiene el número de elementos realmente contenidos en la colección. Solo lectura int.

**Devuelve:**
int
### add(int trendlineType) {#add-int-}
```
public abstract ITrendline add(int trendlineType)
```

Agrega la nueva Trendline al final de una colección y la devuelve.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| trendlineType | int | Tipo de Trendline [TrendlineType](../../com.aspose.slides/trendlinetype) |

**Devuelve:**
[ITrendline](../../com.aspose.slides/itrendline) - Nueva Trendline [ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public abstract void remove(ITrendline value)
```

Elimina el valor especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) | Trendline a eliminar [ITrendline](../../com.aspose.slides/itrendline) |