---
title: IGradientStopCollection
second_title: Referencia de la API de Aspose.Slides para Java
description: Representa una colección de puntos de degradado.
type: docs
url: /es/com.aspose.slides/igradientstopcollection/
---
**Todas las interfaces implementadas:**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

Representa una colección de puntos de degradado.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns the gradient stop by index. |
| [add(float position, Color color)](#add-float-java.awt.Color-) | Creates the new gradient stop and adds it to the end of collection. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Creates the new gradient stop and adds it to the end of collection. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Creates the new gradient stop and adds it to the end of collection. |
| [insert(int index, float position, Color color)](#insert-int-float-java.awt.Color-) | Creates the new gradient stop and inserts it at the specified index to the collection. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Creates the new gradient stop and inserts it at the specified index to the collection. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Creates the new gradient stop and inserts it at the specified index to the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes a gradient stop at the specified index. |
| [clear()](#clear--) | Removes all gradient stops from a collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```

Devuelve el punto de degradado por índice.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Color color) {#add-float-java.awt.Color-}
```
public abstract IGradientStop add(float position, Color color)
```

Crea un nuevo punto de degradado y lo agrega al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | float | Posición del nuevo punto de degradado. |
| color | java.awt.Color | Color del nuevo punto de degradado. |

**Devuelve:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Índice del nuevo punto de degradado en la colección.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```

Crea un nuevo punto de degradado y lo agrega al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | float | Posición del nuevo punto de degradado. |
| presetColor | int | Color del nuevo punto de degradado. |

**Devuelve:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Índice del nuevo punto de degradado en la colección.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```

Crea un nuevo punto de degradado y lo agrega al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | float | Posición del nuevo punto de degradado. |
| schemeColor | int | Color del nuevo punto de degradado. |

**Devuelve:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Índice del nuevo punto de degradado en la colección.
### insert(int index, float position, Color color) {#insert-int-float-java.awt.Color-}
```
public abstract void insert(int index, float position, Color color)
```

Crea un nuevo punto de degradado y lo inserta en el índice especificado de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice en la colección donde se insertará el nuevo punto de degradado. |
| position | float | Posición del nuevo punto de degradado. |
| color | java.awt.Color | Color del nuevo punto de degradado. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```

Crea un nuevo punto de degradado y lo inserta en el índice especificado de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice en la colección donde se insertará el nuevo punto de degradado. |
| position | float | Posición del nuevo punto de degradado. |
| presetColor | int | Color del nuevo punto de degradado. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```

Crea un nuevo punto de degradado y lo inserta en el índice especificado de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice en la colección donde se insertará el nuevo punto de degradado. |
| position | float | Posición del nuevo punto de degradado. |
| schemeColor | int | Color del nuevo punto de degradado. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Elimina un punto de degradado en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de un punto de degradado que debe eliminarse. |

### clear() {#clear--}
```
public abstract void clear()
```

Elimina todos los puntos de degradado de una colección.