---
title: IGradientStopCollection
second_title: Aspose.Slides Androidra a Java API hivatkozás
description: A színátmenet-pontok gyűjteményét reprezentálja.
type: docs
url: /hu/com.aspose.slides/igradientstopcollection/
---
**Minden megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

A színátmenet-pontok gyűjteményét reprezentálja.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a színátmenet-pontot index alapján. |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | Létrehozza az új színátmenet-pontot, és a gyűjtemény végéhez adja. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Létrehozza az új színátmenet-pontot, és a gyűjtemény végéhez adja. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Létrehozza az új színátmenet-pontot, és a gyűjtemény végéhez adja. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | Létrehozza az új színátmenet-pontot, és a megadott indexnél szúrja be a gyűjteménybe. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Létrehozza az új színátmenet-pontot, és a megadott indexnél szúrja be a gyűjteménybe. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Létrehozza az új színátmenet-pontot, és a megadott indexnél szúrja be a gyűjteménybe. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a színátmenet-pontot a megadott indexen. |
| [clear()](#clear--) | Eltávolítja az összes színátmenet-pontot egy gyűjteményből. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```

Visszaadja a színátmenet-pontot index alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public abstract IGradientStop add(float position, Integer color)
```

Létrehozza az új színátmenet-pontot, és a gyűjtemény végéhez adja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| position | float | Az új színátmenet-pont pozíciója. |
| color | java.lang.Integer | Az új színátmenet-pont színe. |

**Visszatérési érték:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Az új színátmenet-pont indexe a gyűjteményben.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```

Létrehozza az új színátmenet-pontot, és a gyűjtemény végéhez adja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| position | float | Az új színátmenet-pont pozíciója. |
| presetColor | int | Az új színátmenet-pont színe. |

**Visszatérési érték:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Az új színátmenet-pont indexe a gyűjteményben.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```

Létrehozza az új színátmenet-pontot, és a gyűjtemény végéhez adja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| position | float | Az új színátmenet-pont pozíciója. |
| schemeColor | int | Az új színátmenet-pont színe. |

**Visszatérési érték:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Az új színátmenet-pont indexe a gyűjteményben.
### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public abstract void insert(int index, float position, Integer color)
```

Létrehozza az új színátmenet-pontot, és a megadott indexnél szúrja be a gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az index a gyűjteményben, ahol az új színátmenet-pont be lesz szúrva. |
| position | float | Az új színátmenet-pont pozíciója. |
| color | java.lang.Integer | Az új színátmenet-pont színe. |
### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```

Létrehozza az új színátmenet-pontot, és a megadott indexnél szúrja be a gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az index a gyűjteményben, ahol az új színátmenet-pont be lesz szúrva. |
| position | float | Az új színátmenet-pont pozíciója. |
| presetColor | int | Az új színátmenet-pont színe. |
### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```

Létrehozza az új színátmenet-pontot, és a megadott indexnél szúrja be a gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az index a gyűjteményben, ahol az új színátmenet-pont be lesz szúrva. |
| position | float | Az új színátmenet-pont pozíciója. |
| schemeColor | int | Az új színátmenet-pont színe. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolítja a színátmenet-pontot a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az a színátmenet-pont indexe, amelyet törölni kell. |
### clear() {#clear--}
```
public abstract void clear()
```

Eltávolítja az összes színátmenet-pontot egy gyűjteményből.