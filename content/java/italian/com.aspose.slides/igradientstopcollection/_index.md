---
title: IGradientStopCollection
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta una raccolta di gradient stop.
type: docs
url: /it/com.aspose.slides/igradientstopcollection/
---
**Tutte le interfacce implementate:**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

Rappresenta una raccolta di gradient stop.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce il gradient stop per indice. |
| [add(float position, Color color)](#add-float-java.awt.Color-) | Crea il nuovo gradient stop e lo aggiunge alla fine della raccolta. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Crea il nuovo gradient stop e lo aggiunge alla fine della raccolta. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Crea il nuovo gradient stop e lo aggiunge alla fine della raccolta. |
| [insert(int index, float position, Color color)](#insert-int-float-java.awt.Color-) | Crea il nuovo gradient stop e lo inserisce all'indice specificato nella raccolta. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Crea il nuovo gradient stop e lo inserisce all'indice specificato nella raccolta. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Crea il nuovo gradient stop e lo inserisce all'indice specificato nella raccolta. |
| [removeAt(int index)](#removeAt-int-) | Rimuove un gradient stop all'indice specificato. |
| [clear()](#clear--) | Rimuove tutti i gradient stop da una raccolta. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```

Restituisce il gradient stop per indice.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Color color) {#add-float-java.awt.Color-}
```
public abstract IGradientStop add(float position, Color color)
```

Crea il nuovo gradient stop e lo aggiunge alla fine della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | float | Posizione del nuovo gradient stop. |
| color | java.awt.Color | Colore del nuovo gradient stop. |

**Restituisce:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Indice del nuovo gradient stop nella raccolta.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```

Crea il nuovo gradient stop e lo aggiunge alla fine della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | float | Posizione del nuovo gradient stop. |
| presetColor | int | Colore del nuovo gradient stop. |

**Restituisce:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Indice del nuovo gradient stop nella raccolta.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```

Crea il nuovo gradient stop e lo aggiunge alla fine della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | float | Posizione del nuovo gradient stop. |
| schemeColor | int | Colore del nuovo gradient stop. |

**Restituisce:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Indice del nuovo gradient stop nella raccolta.
### insert(int index, float position, Color color) {#insert-int-float-java.awt.Color-}
```
public abstract void insert(int index, float position, Color color)
```

Crea il nuovo gradient stop e lo inserisce all'indice specificato nella raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice nella raccolta dove il nuovo gradient stop verrà inserito. |
| position | float | Posizione del nuovo gradient stop. |
| color | java.awt.Color | Colore del nuovo gradient stop. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```

Crea il nuovo gradient stop e lo inserisce all'indice specificato nella raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice nella raccolta dove il nuovo gradient stop verrà inserito. |
| position | float | Posizione del nuovo gradient stop. |
| presetColor | int | Colore del nuovo gradient stop. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```

Crea il nuovo gradient stop e lo inserisce all'indice specificato nella raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice nella raccolta dove il nuovo gradient stop verrà inserito. |
| position | float | Posizione del nuovo gradient stop. |
| schemeColor | int | Colore del nuovo gradient stop. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Rimuove un gradient stop all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice di un gradient stop che deve essere eliminato. |

### clear() {#clear--}
```
public abstract void clear()
```

Rimuove tutti i gradient stop da una raccolta.