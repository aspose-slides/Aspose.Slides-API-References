---
title: IGradientStopCollection
second_title: Aspose.Slides Java API-referencia
description: Gradient stop-ok gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/igradientstopcollection/
---
**Minden megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

Gradient stop-ok gyűjteményét képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a gradient stop-ot az index alapján. |
| [add(float position, Color color)](#add-float-java.awt.Color-) | Létrehozza az új gradient stop-ot és a gyűjtemény végéhez adja. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Létrehozza az új gradient stop-ot és a gyűjtemény végéhez adja. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Létrehozza az új gradient stop-ot és a gyűjtemény végéhez adja. |
| [insert(int index, float position, Color color)](#insert-int-float-java.awt.Color-) | Létrehozza az új gradient stop-ot és a megadott indexen beszúrja a gyűjteménybe. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Létrehozza az új gradient stop-ot és a megadott indexen beszúrja a gyűjteménybe. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Létrehozza az új gradient stop-ot és a megadott indexen beszúrja a gyűjteménybe. |
| [removeAt(int index)](#removeAt-int-) | Eltávolít egy gradient stop-ot a megadott indexen. |
| [clear()](#clear--) | Eltávolít minden gradient stop-ot egy gyűjteményből. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```


Visszaadja a gradient stop-ot az index alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Color color) {#add-float-java.awt.Color-}
```
public abstract IGradientStop add(float position, Color color)
```


Létrehozza az új gradient stop-ot és a gyűjtemény végéhez adja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| position | float | Az új gradient stop pozíciója. |
| color | java.awt.Color | Az új gradient stop színe. |

**Visszatérési érték:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Az új gradient stop indexe a gyűjteményben.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```


Létrehozza az új gradient stop-ot és a gyűjtemény végéhez adja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| position | float | Az új gradient stop pozíciója. |
| presetColor | int | Az új gradient stop színe. |

**Visszatérési érték:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Az új gradient stop indexe a gyűjteményben.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```


Létrehozza az új gradient stop-ot és a gyűjtemény végéhez adja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| position | float | Az új gradient stop pozíciója. |
| schemeColor | int | Az új gradient stop színe. |

**Visszatérési érték:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Az új gradient stop indexe a gyűjteményben.
### insert(int index, float position, Color color) {#insert-int-float-java.awt.Color-}
```
public abstract void insert(int index, float position, Color color)
```


Létrehozza az új gradient stop-ot és a megadott indexen beszúrja a gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az index a gyűjteményben, ahová az új gradient stop kerül. |
| position | float | Az új gradient stop pozíciója. |
| color | java.awt.Color | Az új gradient stop színe. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```


Létrehozza az új gradient stop-ot és a megadott indexen beszúrja a gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az index a gyűjteményben, ahová az új gradient stop kerül. |
| position | float | Az új gradient stop pozíciója. |
| presetColor | int | Az új gradient stop színe. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```


Létrehozza az új gradient stop-ot és a megadott indexen beszúrja a gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az index a gyűjteményben, ahová az új gradient stop kerül. |
| position | float | Az új gradient stop pozíciója. |
| schemeColor | int | Az új gradient stop színe. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Eltávolít egy gradient stop-ot a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A gradient stop indexe, amelyet törölni kell. |

### clear() {#clear--}
```
public abstract void clear()
```


Eltávolít minden gradient stop-ot egy gyűjteményből.