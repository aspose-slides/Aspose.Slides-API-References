---
title: AdjustValueCollection
second_title: Aspose.Slides Androidra a Java API-re hivatkozva
description: Alakzatok beállításainak gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/adjustvaluecollection/
---
**Öröklés:**
java.lang.Object, com.aspose.slides.DomObject

**Összes megvalósított interfész:**
[com.aspose.slides.IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
```
public final class AdjustValueCollection extends DomObject<GeometryShape> implements IAdjustValueCollection
```

A forma beállításainak gyűjteményét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [size()](#size--) | Visszaadja a módosítások számát. |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a módosítást az index alapján. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Az összes elemet a gyűjteményből a megadott tömbbe másolja. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált-e (szálbiztos). |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökért. |
| [iterator()](#iterator--) | Visszaad egy enumerátort az egész gyűjteményhez. |
### size() {#size--}
```
public final int size()
```

Visszaadja a módosítások számát. Csak olvasható int.

**Visszatér:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAdjustValue get_Item(int index)
```

Visszaadja a módosítást az index alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | a módosítás indexe. |

**Visszatér:**
[IAdjustValue](../../com.aspose.slides/iadjustvalue) - [AdjustValue](../../com.aspose.slides/adjustvalue).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Az összes elemet a gyűjteményből a megadott tömbbe másolja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cél tömb. |
| index | int | Kezdő index a cél tömbben. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált-e (szálbiztos). Csak olvasható boolean.

**Visszatér:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Visszaad egy szinkronizációs gyökért. Csak olvasható Object.

**Visszatér:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.IEnumerator iterator()
```

Visszaad egy enumerátort az egész gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.IEnumerator