---
title: GradientStopCollection
second_title: Aspose.Slides for Java API Referenciája
description: A színátmenet-állomások gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/gradientstopcollection/
---
**Öröklődés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Az összes megvalósított interfész:**
[com.aspose.slides.IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
```
public final class GradientStopCollection extends PVIObject implements IGradientStopCollection
```

Egy színátmenet-állomások gyűjteményét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [size()](#size--) | Visszatér a gyűjteményben lévő színátmenet-állomások számával. |
| [get_Item(int index)](#get-Item-int-) | Visszatér a színátmenet-állomással az index szerint. |
| [add(float position, Color color)](#add-float-java.awt.Color-) | Létrehozza az új színátmenet-állomást és a gyűjtemény végéhez adja. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Létrehozza az új színátmenet-állomást és a gyűjtemény végéhez adja. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Létrehozza az új színátmenet-állomást és a gyűjtemény végéhez adja. |
| [insert(int index, float position, Color color)](#insert-int-float-java.awt.Color-) | Létrehozza az új színátmenet-állomást és a megadott indexnél szúrja be a gyűjteménybe. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Létrehozza az új színátmenet-állomást és a megadott indexnél szúrja be a gyűjteménybe. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Létrehozza az új színátmenet-állomást és a megadott indexnél szúrja be a gyűjteménybe. |
| [removeAt(int index)](#removeAt-int-) | Eltávolít egy színátmenet-állomást a megadott indexnél. |
| [clear()](#clear--) | Eltávolítja az összes színátmenet-állomást a gyűjteményből. |
| [iterator()](#iterator--) | Visszatér egy enumerátorral, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszatér egy java iterátorral a teljes gyűjteményhez. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Átmásolja az összes elemet a gyűjteményből a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszatér egy értékkel, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos). |
| [getSyncRoot()](#getSyncRoot--) | Visszatér a szinkronizáció gyökere. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Verzió. Csak olvasható long.

**Visszatér:**
long
### size() {#size--}
```
public final int size()
```


Visszatér a gyűjteményben lévő színátmenet-állomások számával. Csak olvasható int.

**Visszatér:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IGradientStop get_Item(int index)
```


Visszatér a színátmenet-állomással az index szerint.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatér:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Color color) {#add-float-java.awt.Color-}
```
public final IGradientStop add(float position, Color color)
```


Létrehozza az új színátmenet-állomást és a gyűjtemény végéhez adja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| position | float | Az új színátmenet-állomás pozíciója. |
| color | java.awt.Color | Az új színátmenet-állomás színe. |

**Visszatér:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Az új színátmenet-állomás indexe a gyűjteményben.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public final IGradientStop addPresetColor(float position, int presetColor)
```


Létrehozza az új színátmenet-állomást és a gyűjtemény végéhez adja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| position | float | Az új színátmenet-állomás pozíciója. |
| presetColor | int | Az új színátmenet-állomás színe. |

**Visszatér:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Az új színátmenet-állomás indexe a gyűjteményben.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public final IGradientStop addSchemeColor(float position, int schemeColor)
```


Létrehozza az új színátmenet-állomást és a gyűjtemény végéhez adja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| position | float | Az új színátmenet-állomás pozíciója. |
| schemeColor | int | Az új színátmenet-állomás színe. |

**Visszatér:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Az új színátmenet-állomás indexe a gyűjteményben.
### insert(int index, float position, Color color) {#insert-int-float-java.awt.Color-}
```
public final void insert(int index, float position, Color color)
```


Létrehozza az új színátmenet-állomást és a megadott indexnél szúrja be a gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az index a gyűjteményben, ahová az új színátmenet-állomás kerül. |
| position | float | Az új színátmenet-állomás pozíciója. |
| color | java.awt.Color | Az új színátmenet-állomás színe. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public final void insertPresetColor(int index, float position, int presetColor)
```


Létrehozza az új színátmenet-állomást és a megadott indexnél szúrja be a gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az index a gyűjteményben, ahová az új színátmenet-állomás kerül. |
| position | float | Az új színátmenet-állomás pozíciója. |
| presetColor | int | Az új színátmenet-állomás színe. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public final void insertSchemeColor(int index, float position, int schemeColor)
```


Létrehozza az új színátmenet-állomást és a megadott indexnél szúrja be a gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az index a gyűjteményben, ahová az új színátmenet-állomás kerül. |
| position | float | Az új színátmenet-állomás pozíciója. |
| schemeColor | int | Az új színátmenet-állomás színe. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Eltávolít egy színátmenet-állomást a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A színátmenet-állomás indexe, amelyet törölni kell. |

### clear() {#clear--}
```
public final void clear()
```


Eltávolítja az összes színátmenet-állomást a gyűjteményből.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iterator()
```


Visszatér egy enumerátorral, amely végigiterál a gyűjteményen.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - Egy IGenericEnumerator, amely a gyűjteményen való iteráláshoz használható.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iteratorJava()
```


Visszatér egy java iterátorral a teljes gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - Egy java.util.Iterator a teljes gyűjteményhez.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Átmásolja az összes elemet a gyűjteményből a megadott tömbbe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cél tömb. |
| index | int | Kezdő index a cél tömbben. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Visszatér egy értékkel, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos). Csak olvasható boolean.

**Visszatér:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Visszatér egy szinkronizációs gyökérrel. Csak olvasható Object.

**Visszatér:**
java.lang.Object