---
title: FontSubstRuleCollection
second_title: Aspose.Slides Androidra Java API hivatkozás
description: A betűtípusok helyettesítésének gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/fontsubstrulecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
```
public class FontSubstRuleCollection implements IFontSubstRuleCollection
```

A betűtípusok helyettesítésének gyűjteményét képviseli.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [FontSubstRuleCollection()](#FontSubstRuleCollection--) |  |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [size()](#size--) | Megkapja a gyűjteményben ténylegesen tárolt elemek számát. |
| [add(IFontSubstRule value)](#add-com.aspose.slides.IFontSubstRule-) | Hozzáadja az új betűtípushelyettesítési szabályt a gyűjteményhez |
| [remove(IFontSubstRule value)](#remove-com.aspose.slides.IFontSubstRule-) | Eltávolítja a megadott objektum első előfordulását a gyűjteményből. |
| [get_Item(int index)](#get-Item-int-) | Visszaadja az elemet a megadott indexen. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Átmásolja az összes elemet a gyűjteményből a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált-e (szálbiztos). |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökeret. |
### FontSubstRuleCollection() {#FontSubstRuleCollection--}
```
public FontSubstRuleCollection()
```


### size() {#size--}
```
public final int size()
```


Megkapja a gyűjteményben ténylegesen tárolt elemek számát. Csak olvasható int.

**Visszatérési érték:**
int
### add(IFontSubstRule value) {#add-com.aspose.slides.IFontSubstRule-}
```
public final void add(IFontSubstRule value)
```


Hozzáadja az új betűtípushelyettesítési szabályt a gyűjteményhez

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |  |

### remove(IFontSubstRule value) {#remove-com.aspose.slides.IFontSubstRule-}
```
public final void remove(IFontSubstRule value)
```


Eltávolítja a megadott objektum első előfordulását a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | A gyűjteményből eltávolítandó betűtípushelyettesítési szabály. |

### get_Item(int index) {#get-Item-int-}
```
public final IFontSubstRule get_Item(int index)
```


Visszaadja az elemet a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontSubstRule> iterator()
```


Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontSubstRule> - Egy IGenericEnumerator, amelyet a gyűjtemény bejárására lehet használni.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontSubstRule> iteratorJava()
```


Visszaad egy java iterátort a teljes gyűjteményhez.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontSubstRule> - Egy java.util.Iterator a teljes gyűjteményhez.
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


Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált-e (szálbiztos). Csak olvasható boolean.

**Visszatérési érték:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Visszaad egy szinkronizációs gyökeret. Csak olvasható Object.

**Visszatérési érték:**
java.lang.Object