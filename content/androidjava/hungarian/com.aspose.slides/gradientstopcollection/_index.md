---
title: GradientStopCollection
second_title: Aspose.Slides Androidra a Java API hivatkozás segítségével
description: Egy színátmenet pontok gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/gradientstopcollection/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Minden megvalósított interfész:**
[com.aspose.slides.IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
```
public final class GradientStopCollection extends PVIObject implements IGradientStopCollection
```

Képviseli a színátmenet pontok gyűjteményét.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [size()](#size--) | Visszaadja a színátmenet pontok számát egy gyűjteményben. |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a színátmenet pontot index alapján. |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | Létrehozza az új színátmenet pontot és hozzáadja a gyűjtemény végéhez. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Létrehozza az új színátmenet pontot és hozzáadja a gyűjtemény végéhez. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Létrehozza az új színátmenet pontot és hozzáadja a gyűjtemény végéhez. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | Létrehozza az új színátmenet pontot és a megadott indexen illeszti be a gyűjteménybe. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Létrehozza az új színátmenet pontot és a megadott indexen illeszti be a gyűjteménybe. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Létrehozza az új színátmenet pontot és a megadott indexen illeszti be a gyűjteménybe. |
| [removeAt(int index)](#removeAt-int-) | Eltávolít egy színátmenet pontot a megadott indexen. |
| [clear()](#clear--) | Eltávolítja az összes színátmenet pontot egy gyűjteményből. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy Java iterátort az egész gyűjteményhez. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Átmásolja a gyűjtemény összes elemét a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos). |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökérobjektumot. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Verzió. Írásvédett long.

**Visszatérési érték:**
long
### size() {#size--}
```
public final int size()
```


Visszaadja a színátmenet pontok számát egy gyűjteményben. Írásvédett  int .

**Visszatérési érték:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IGradientStop get_Item(int index)
```


Visszaadja a színátmenet pontot index alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public final IGradientStop add(float position, Integer color)
```


Létrehozza az új színátmenet pontot és hozzáadja a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| position | float | Az új színátmenet pont pozíciója. |
| color | java.lang.Integer | Az új színátmenet pont színe. |

**Visszatérési érték:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Az új színátmenet pont indexe a gyűjteményben.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public final IGradientStop addPresetColor(float position, int presetColor)
```


Létrehozza az új színátmenet pontot és hozzáadja a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| position | float | Az új színátmenet pont pozíciója. |
| presetColor | int | Az új színátmenet pont színe. |

**Visszatérési érték:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Az új színátmenet pont indexe a gyűjteményben.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public final IGradientStop addSchemeColor(float position, int schemeColor)
```


Létrehozza az új színátmenet pontot és hozzáadja a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| position | float | Az új színátmenet pont pozíciója. |
| schemeColor | int | Az új színátmenet pont színe. |

**Visszatérési érték:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Az új színátmenet pont indexe a gyűjteményben.
### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public final void insert(int index, float position, Integer color)
```


Létrehozza az új színátmenet pontot és a megadott indexen illeszti be a gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az index a gyűjteményben, ahol az új színátmenet pont beszúrásra kerül. |
| position | float | Az új színátmenet pont pozíciója. |
| color | java.lang.Integer | Az új színátmenet pont színe. |
### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public final void insertPresetColor(int index, float position, int presetColor)
```


Létrehozza az új színátmenet pontot és a megadott indexen illeszti be a gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az index a gyűjteményben, ahol az új színátmenet pont beszúrásra kerül. |
| position | float | Az új színátmenet pont pozíciója. |
| presetColor | int | Az új színátmenet pont színe. |
### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public final void insertSchemeColor(int index, float position, int schemeColor)
```


Létrehozza az új színátmenet pontot és a megadott indexen illeszti be a gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az index a gyűjteményben, ahol az új színátmenet pont beszúrásra kerül. |
| position | float | Az új színátmenet pont pozíciója. |
| schemeColor | int | Az új színátmenet pont színe. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Eltávolít egy színátmenet pontot a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A törlendő színátmenet pont indexe. |
### clear() {#clear--}
```
public final void clear()
```


Eltávolítja az összes színátmenet pontot egy gyűjteményből.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iterator()
```


Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - Egy IGenericEnumerator, amelyet a gyűjtemény bejárásához lehet használni.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iteratorJava()
```


Visszaad egy Java iterátort az egész gyűjteményhez.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - Egy java.util.Iterator az egész gyűjteményhez.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Átmásolja a gyűjtemény összes elemét a megadott tömbbe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cél tömb. |
| index | int | Kezdő index a cél tömbben. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos). Írásvédett  boolean .

**Visszatérési érték:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Visszaad egy szinkronizációs gyökérobjektumot. Írásvédett Object.

**Visszatérési érték:**
java.lang.Object