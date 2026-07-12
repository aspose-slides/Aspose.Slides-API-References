---
title: ExtraColorSchemeCollection
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: Kiegészítő színsémák gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/extracolorschemecollection/
---
**Öröklődés:**
java.lang.Object

**Összes megvalósított interfész:**
[com.aspose.slides.IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection), com.aspose.slides.IDOMObject
```
public class ExtraColorSchemeCollection implements IExtraColorSchemeCollection, IDOMObject
```

Kiegészítő színsémák gyűjteményét képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [size()](#size--) | Visszaadja a gyűjteményben lévő elemek számát int. |
| [get_Item(int index)](#get-Item-int-) | Visszaad egy szín sémát index szerint. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Átmásolja a gyűjtemény összes elemét a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy az ArrayList elérése szinkronizált (szálbiztos). |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy objektumot, amely a gyűjteményhez való hozzáférés szinkronizálására használható. |
### size() {#size--}
```
public final int size()
```

Visszaadja a gyűjteményben lévő elemek számát. Csak olvasható int.

**Visszatérési érték:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IExtraColorScheme get_Item(int index)
```

Visszaad egy szín sémát index alapján. Csak olvasható [ExtraColorScheme](../../com.aspose.slides/extracolorscheme).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[IExtraColorScheme](../../com.aspose.slides/iextracolorscheme)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszaad egy Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatérési érték:**
com.aspose.slides.IDOMObject
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iterator()
```

Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - Egy IGenericEnumerator, amely a gyűjteményen való iteráláshoz használható.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iteratorJava()
```

Visszaad egy java iterátort a teljes gyűjteményhez.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - Egy java.util.Iterator a teljes gyűjteményhez.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Átmásolja a gyűjtemény összes elemét a megadott tömbbe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cél tömb. |
| index | int | Kezdő index a tömbben. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Visszaad egy értéket, amely jelzi, hogy az ArrayList elérése szinkronizált (szálbiztos). Csak olvasható boolean.

**Visszatérési érték:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Visszaad egy objektumot, amely a gyűjteményhez való hozzáférés szinkronizálására használható. Csak olvasható Object.

Visszaad egy szinkronizációs gyökeret. Csak olvasható Object.

**Visszatérési érték:**
java.lang.Object