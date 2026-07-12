---
title: PortionCollection
second_title: Aspose.Slides Androidra Java API hivatkozás
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
| [getCount()](#getCount--) | A gyűjteményben ténylegesen lévő elemek számát adja vissza. |
| [isReadOnly()](#isReadOnly--) | Azt az értéket adja vissza, amely jelzi, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) csak olvasható-e. |
| [get_Item(int index)](#get-Item-int-) | Az adott indexen lévő elemet adja vissza. |
| [set_Item(int index, IPortion value)](#set-Item-int-com.aspose.slides.IPortion-) | Az adott indexen lévő elemet adja vissza. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Egy Portion-t ad a gyűjtemény végéhez. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Meghatározza egy adott elem indexét a Listában. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Egy Portion-t szúr be a gyűjteménybe a megadott indexnél. |
| [clear()](#clear--) | Eltávolítja a gyűjtemény összes elemét. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Megállapítja, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) tartalmaz-e egy adott értéket. |
| [copyTo(IPortion[] array, int arrayIndex)](#copyTo-com.aspose.slides.IPortion---int-) | A [IGenericCollection](../../com.aspose.slides/igenericcollection) elemeit egy tömbbe másolja, egy adott tömbindexnél kezdve. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Eltávolítja egy adott objektum első előfordulását a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ból. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a gyűjteményben a megadott indexen lévő elemet. |
| [iterator()](#iterator--) | Visszaad egy felsorolót, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |
### getCount() {#getCount--}
```
public final int getCount()
```


A gyűjteményben ténylegesen lévő elemek számát adja vissza. Csak olvasható int.

**Visszatér:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Azt az értéket adja vissza, amely jelzi, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) csak olvasható-e. Csak olvasható boolean.

**Visszatér:**
boolean - igaz, ha a [IGenericCollection](../../com.aspose.slides/igenericcollection) csak olvasható; egyébként hamis.
### get_Item(int index) {#get-Item-int-}
```
public final IPortion get_Item(int index)
```


Az adott indexen lévő elemet adja vissza.

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


Az adott indexen lévő elemet adja vissza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |
| value | [IPortion](../../com.aspose.slides/iportion) |  |
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public final void add(IPortion value)
```


Egy Portion-t ad a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | A hozzáadandó Portion a gyűjtemény végére. |
### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public final int indexOf(IPortion item)
```


Meghatározza egy adott elem indexét a Listában.

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


Egy Portion-t szúr be a gyűjteménybe a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullával kezdődő index, ahová a Portion-t be kell szúrni. |
| value | [IPortion](../../com.aspose.slides/iportion) | A beszúrandó Portion. |
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
| item | [IPortion](../../com.aspose.slides/iportion) | Az objektum, amelyet a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ban keresünk. |

**Visszatér:**
boolean - igaz, ha az elem megtalálható a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ban; egyébként hamis.
### copyTo(IPortion[] array, int arrayIndex) {#copyTo-com.aspose.slides.IPortion---int-}
```
public final void copyTo(IPortion[] array, int arrayIndex)
```


A [IGenericCollection](../../com.aspose.slides/igenericcollection) elemeit egy tömbbe másolja, egy adott tömbindexnél kezdve.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | [IPortion\[\]](../../com.aspose.slides/iportion) | Az egydimenziós tömb, amely a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ból másolt elemek célpontja. A tömbnek nullával kezdődő indexelése kell, hogy legyen. |
| arrayIndex | int | A nullával kezdődő index a tömbben, ahol a másolás kezdődik. |
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public final boolean remove(IPortion item)
```


Eltávolítja egy adott objektum első előfordulását a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Az objektum, amelyet a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ból el kell távolítani. |

**Visszatér:**
boolean - igaz, ha az elem sikeresen el lett távolítva a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ból; egyébként hamis. Ez a metódus hamisat ad vissza, ha az elem nem található az eredeti [IGenericCollection](../../com.aspose.slides/igenericcollection)-ban.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Eltávolítja a gyűjteményben a megadott indexen lévő elemet.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nullával kezdődő index, amelyik elemet el kell távolítani. |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iterator()
```


Visszaad egy felsorolót, amely végigiterál a gyűjteményen.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - Egy IGenericEnumerator, amely a gyűjteményen való iteráláshoz használható.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iteratorJava()
```


Visszaad egy java iterátort a teljes gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - Egy java.util.Iterator a teljes gyűjteményhez.