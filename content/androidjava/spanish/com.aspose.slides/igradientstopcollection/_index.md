---
title: IGradientStopCollection
second_title: Referencia de API Java de Aspose.Slides para Android
description: Representa una colección de paradas de degradado.
type: docs
url: /es/com.aspose.slides/igradientstopcollection/
---
**Todas las interfaces implementadas:**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

Representa una colección de paradas de degradado.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Devuelve la parada de degradado por índice. |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | Crea una nueva parada de degradado y la añade al final de la colección. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Crea una nueva parada de degradado y la añade al final de la colección. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Crea una nueva parada de degradado y la añade al final de la colección. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | Crea una nueva parada de degradado y la inserta en el índice especificado de la colección. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Crea una nueva parada de degradado y la inserta en el índice especificado de la colección. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Crea una nueva parada de degradado y la inserta en el índice especificado de la colección. |
| [removeAt(int index)](#removeAt-int-) | Elimina una parada de degradado en el índice especificado. |
| [clear()](#clear--) | Elimina todas las paradas de degradado de una colección. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```

Devuelve la parada de degradado por índice.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public abstract IGradientStop add(float position, Integer color)
```

Crea una nueva parada de degradado y la añade al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | float | Posición de la nueva parada de degradado. |
| color | java.lang.Integer | Color de la nueva parada de degradado. |

**Devuelve:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Índice de la nueva parada de degradado en la colección.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```

Crea una nueva parada de degradado y la añade al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | float | Posición de la nueva parada de degradado. |
| presetColor | int | Color de la nueva parada de degradado. |

**Devuelve:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Índice de la nueva parada de degradado en la colección.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```

Crea una nueva parada de degradado y la añade al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | float | Posición de la nueva parada de degradado. |
| schemeColor | int | Color de la nueva parada de degradado. |

**Devuelve:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Índice de la nueva parada de degradado en la colección.
### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public abstract void insert(int index, float position, Integer color)
```

Crea una nueva parada de degradado y la inserta en el índice especificado de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice en la colección donde se insertará la nueva parada de degradado. |
| position | float | Posición de la nueva parada de degradado. |
| color | java.lang.Integer | Color de la nueva parada de degradado. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```

Crea una nueva parada de degradado y la inserta en el índice especificado de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice en la colección donde se insertará la nueva parada de degradado. |
| position | float | Posición de la nueva parada de degradado. |
| presetColor | int | Color de la nueva parada de degradado. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```

Crea una nueva parada de degradado y la inserta en el índice especificado de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice en la colección donde se insertará la nueva parada de degradado. |
| position | float | Posición de la nueva parada de degradado. |
| schemeColor | int | Color de la nueva parada de degradado. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Elimina una parada de degradado en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de una parada de degradado que debe eliminarse. |

### clear() {#clear--}
```
public abstract void clear()
```

Elimina todas las paradas de degradado de una colección.