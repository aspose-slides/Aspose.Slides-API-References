---
title: LineFormatCollection
second_title: Aspose.Slides Androidra a Java API referencián keresztül
description: A vonalstílusok gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/lineformatcollection/
---
**Öröklődés:**  
java.lang.Object, com.aspose.slides.DomObject

**Az összes megvalósított interfész:**  
[com.aspose.slides.ILineFormatCollection](../../com.aspose.slides/ilineformatcollection)  
```
public final class LineFormatCollection extends DomObject<FormatScheme> implements ILineFormatCollection
```

A vonalstílusok gyűjteményét képviseli.

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Megkapja az elemet a megadott indexen. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterálja a gyűjteményt. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |
| [size()](#size--) | Megkapja a gyűjteményben ténylegesen lévő elemek számát. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Átmásolja az összes elemet a gyűjteményből a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált-e (szálbiztos). |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökérobjektumot. |

### get_Item(int index) {#get-Item-int-}
```
public final ILineFormat get_Item(int index)
```

Megkapja az elemet a megadott indexen. Csak olvasható [ILineFormat](../../com.aspose.slides/ilineformat).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILineFormat> iterator()
```

Visszaad egy enumerátort, amely végigiterálja a gyűjteményt.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILineFormat> - Egy IGenericEnumerator, amelyet a gyűjtemény bejárására használhat.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILineFormat> iteratorJava()
```

Visszaad egy java iterátort a teljes gyűjteményhez.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILineFormat> - Egy java.util.Iterator a teljes gyűjteményhez.

### size() {#size--}
```
public final int size()
```

Megkapja a gyűjteményben ténylegesen lévő elemek számát. Csak olvasható int.

**Visszatérési érték:**
int

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Átmásolja az összes elemet a gyűjteményből a megadott tömbbe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cél tömb. |
| index | int | A cél tömbben kezdő index. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált-e (szálbiztos). Csak olvasható boolean.

**Visszatérési érték:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Visszaad egy szinkronizációs gyökérobjektumot. Csak olvasható Object.

**Visszatérési érték:**
java.lang.Object