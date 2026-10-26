---
title: IPortionCollection
second_title: Aspose.Slides Java API Referencia
description: Egy részeket tartalmazó gyűjteményt képvisel.
type: docs
url: /hu/com.aspose.slides/iportioncollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPortionCollection extends System.Collections.Generic.IGenericEnumerable<IPortion>
```

Represents a collection of a portions.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | A megadott indexű elemet adja vissza. |
| [getCount()](#getCount--) | A gyűjteményben ténylegesen tárolt elemek számát adja vissza. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | A végére ad egy Portion elemet a gyűjteménynek. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Megállapítja egy adott szakasz indexét a gyűjteményben. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Beszújt egy Portion elemet a megadott indexű helyre a gyűjteményben. |
| [clear()](#clear--) | Eltávolítja az összes elemet a gyűjteményből. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Megállapítja, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) tartalmaz-e egy adott értéket. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Eltávolítja egy adott objektum első előfordulását a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ből. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a megadott indexű elemet a gyűjteményből. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPortion get_Item(int index)
```


A megadott indexű elemet adja vissza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatér:**
[IPortion](../../com.aspose.slides/iportion)
### getCount() {#getCount--}
```
public abstract int getCount()
```


A gyűjteményben ténylegesen tárolt elemek számát adja vissza. Csak olvasható int.

**Visszatér:**
int
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public abstract void add(IPortion value)
```


A gyűjtemény végére hozzáadandó Portion.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | A gyűjtemény végére hozzáadandó Portion. |
### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public abstract int indexOf(IPortion item)
```


Megállapítja egy adott szakasz indexét a gyűjteményben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | A keresett szakasz a gyűjteményben. |

**Visszatér:**
int - Az elem indexe, ha megtalálható a gyűjteményben; egyébként -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public abstract void insert(int index, IPortion value)
```


Beszújt egy Portion elemet a megadott indexű helyre a gyűjteményben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A 0-alapú index, ahová a Portion beszúrandó. |
| value | [IPortion](../../com.aspose.slides/iportion) | A beszúrandó Portion. |
### clear() {#clear--}
```
public abstract void clear()
```


Eltávolítja az összes elemet a gyűjteményből.
### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public abstract boolean contains(IPortion item)
```


Megállapítja, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) tartalmaz-e egy adott értéket.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | A keresett objektum a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ban. |

**Visszatér:**
boolean - igaz, ha az elem megtalálható a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ban; egyébként hamis.
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public abstract boolean remove(IPortion item)
```


Eltávolítja egy adott objektum első előfordulását a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | A törlendő objektum a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ból. |

**Visszatér:**
boolean - igaz, ha az elem sikeresen eltávolításra került a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ból; egyébként hamis. Ez a metódus hamis értéket ad vissza, ha az elem nem található az eredeti [IGenericCollection](../../com.aspose.slides/igenericcollection)-ban.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Eltávolítja a megadott indexű elemet a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A 0-alapú index, amelynek az elemét el kell távolítani. |