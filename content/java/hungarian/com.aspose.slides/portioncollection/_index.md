---
title: PortionCollection
second_title: Aspose.Slides Java API-referencia
description: A részek gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/portioncollection/
---
**Öröklés:**
java.lang.Object, com.aspose.slides.DomObject

**Minden megvalósított interfész:**
[com.aspose.slides.IPortionCollection](../../com.aspose.slides/iportioncollection)
```
public final class PortionCollection extends DomObject<Paragraph> implements IPortionCollection
```

A részek gyűjteményét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getCount()](#getCount--) | Megkapja a gyűjteményben ténylegesen lévő elemek számát. |
| [isReadOnly()](#isReadOnly--) | Megkap egy értéket, amely jelzi, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) csak olvasható-e. |
| [get_Item(int index)](#get-Item-int-) | Megkapja az adott indexnél lévő elemet. |
| [set_Item(int index, IPortion value)](#set-Item-int-com.aspose.slides.IPortion-) | Megkapja az adott indexnél lévő elemet. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Hozzáad egy Portion-t a gyűjtemény végéhez. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Megállapítja egy adott elem indexét a Listában. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Beszúr egy Portion-t a gyűjteménybe a megadott indexnél. |
| [clear()](#clear--) | Eltávolítja a gyűjtemény összes elemét. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Megállapítja, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) tartalmaz-e egy adott értéket. |
| [copyTo(IPortion[] array, int arrayIndex)](#copyTo-com.aspose.slides.IPortion---int-) | Átmásolja a [IGenericCollection](../../com.aspose.slides/igenericcollection) elemeit egy tömbbe, egy adott tömbindexnél kezdve. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Eltávolítja egy adott objektum első előfordulását a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ből. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a gyűjteményben a megadott indexnél lévő elemet. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigjárja a gyűjteményt. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |
### getCount() {#getCount--}
```
public final int getCount()
```


Megkapja a gyűjteményben ténylegesen lévő elemek számát. Csak olvasható int.

**Visszatér:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Megkap egy értéket, amely jelzi, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) csak olvasható-e. Csak olvasható boolean.

**Visszatér:**
boolean - igaz, ha a [IGenericCollection](../../com.aspose.slides/igenericcollection) csak olvasható; egyébként hamis.
### get_Item(int index) {#get-Item-int-}
```
public final IPortion get_Item(int index)
```


Megkapja a megadott indexnél lévő elemet.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatér:**
[IPortion](../../com.aspose.slides/iportion)
### set_Item(int index, IPortion value) {#set-Item-int-com.aspose.slides.IPortion-}
```
public final void set_Item(int index, IPortion value)
```


Megkapja a megadott indexnél lévő elemet.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |
| value | [IPortion](../../com.aspose.slides/iportion) |  |
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public final void add(IPortion value)
```


Hozzáad egy Portion-t a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | A hozzáadandó Portion a gyűjtemény végére. |
### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public final int indexOf(IPortion item)
```


Megállapítja egy adott elem indexét a Listában.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Az objektum, amelyet a Listában keresünk. |

**Visszatér:**
int - Az elem indexe, ha megtalálható a listában; egyébként -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public final void insert(int index, IPortion value)
```


Beszúr egy Portion-t a gyűjteménybe a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló index, amelynél a Portion-t be kell szúrni. |
| value | [IPortion](../../com.aspose.slides/iportion) | A beszúrni kívánt Portion. |
### clear() {#clear--}
```
public final void clear()
```


Eltávolítja a gyűjtemény összes elemét.
### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public final boolean contains(IPortion item)
```


Megállapítja, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) tartalmaz-e egy adott értéket.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Az objektum, amelyet a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ben keresünk. |

**Visszatér:**
boolean - igaz, ha az elem megtalálható a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ben; egyébként hamis.
### copyTo(IPortion[] array, int arrayIndex) {#copyTo-com.aspose.slides.IPortion---int-}
```
public final void copyTo(IPortion[] array, int arrayIndex)
```


Átmásolja a [IGenericCollection](../../com.aspose.slides/igenericcollection) elemeit egy tömbbe, egy adott tömbindexnél kezdve.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | [IPortion\[\]](../../com.aspose.slides/iportion) | Az egydimenziós tömb, amely a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ből átmásolt elemek célja. A tömbnek nullától induló indexelése van. |
| arrayIndex | int | A nullától induló index a tömbben, ahol a másolás kezdődik. |
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public final boolean remove(IPortion item)
```


Eltávolítja egy adott objektum első előfordulását a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Az objektum, amelyet a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ből el kell távolítani. |

**Visszatér:**
boolean - igaz, ha az elem sikeresen eltávolítva a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ből; egyébként hamis. Ez a metódus hamis értéket ad vissza, ha az elem nem található az eredeti [IGenericCollection](../../com.aspose.slides/igenericcollection)-ben.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Eltávolítja a gyűjteményben a megadott indexnél lévő elemet.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullától induló index, amelyik elemet el kell távolítani. |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iterator()
```


Visszaad egy enumerátort, amely végigjárja a gyűjteményt.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - Egy IGenericEnumerator, amely a gyűjtemény végigjárására használható.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iteratorJava()
```


Visszaad egy java iterátort a teljes gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - Egy java.util.Iterator a teljes gyűjteményhez.