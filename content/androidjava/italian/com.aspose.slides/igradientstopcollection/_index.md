---
title: IGradientStopCollection
second_title: Aspose.Slides per Android via Java API Reference
description: Rappresenta una collezione di gradient stop.
type: docs
url: /it/com.aspose.slides/igradientstopcollection/
---
**Tutte le Interfacce Implementate:**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

Rappresenta una collezione di gradient stop.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce il gradient stop per indice. |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | Crea un nuovo gradient stop e lo aggiunge alla fine della collezione. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Crea un nuovo gradient stop e lo aggiunge alla fine della collezione. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Crea un nuovo gradient stop e lo aggiunge alla fine della collezione. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | Crea un nuovo gradient stop e lo inserisce nell'indice specificato della collezione. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Crea un nuovo gradient stop e lo inserisce nell'indice specificato della collezione. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Crea un nuovo gradient stop e lo inserisce nell'indice specificato della collezione. |
| [removeAt(int index)](#removeAt-int-) | Rimuove un gradient stop all'indice specificato. |
| [clear()](#clear--) | Rimuove tutti i gradient stop da una collezione. |
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
### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public abstract IGradientStop add(float position, Integer color)
```


Crea un nuovo gradient stop e lo aggiunge alla fine della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | float | Posizione del nuovo gradient stop. |
| color | java.lang.Integer | Colore del nuovo gradient stop. |

**Restituisce:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Indice del nuovo gradient stop nella collezione.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```


Crea un nuovo gradient stop e lo aggiunge alla fine della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | float | Posizione del nuovo gradient stop. |
| presetColor | int | Colore del nuovo gradient stop. |

**Restituisce:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Indice del nuovo gradient stop nella collezione.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```


Crea un nuovo gradient stop e lo aggiunge alla fine della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | float | Posizione del nuovo gradient stop. |
| schemeColor | int | Colore del nuovo gradient stop. |

**Restituisce:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Indice del nuovo gradient stop nella collezione.
### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public abstract void insert(int index, float position, Integer color)
```


Crea un nuovo gradient stop e lo inserisce nell'indice specificato della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice nella collezione dove il nuovo gradient stop sarà inserito. |
| position | float | Posizione del nuovo gradient stop. |
| color | java.lang.Integer | Colore del nuovo gradient stop. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```


Crea un nuovo gradient stop e lo inserisce nell'indice specificato della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice nella collezione dove il nuovo gradient stop sarà inserito. |
| position | float | Posizione del nuovo gradient stop. |
| presetColor | int | Colore del nuovo gradient stop. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```


Crea un nuovo gradient stop e lo inserisce nell'indice specificato della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice nella collezione dove il nuovo gradient stop sarà inserito. |
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
| index | int | Indice di un gradient stop da eliminare. |

### clear() {#clear--}
```
public abstract void clear()
```


Rimuove tutti i gradient stop da una collezione.