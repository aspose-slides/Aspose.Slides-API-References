---
title: IPortionCollection
second_title: Aspose.Slides Androidra a Java API-referencia szerint
description: Egy Portion gyűjteményt képvisel.
type: docs
url: /hu/com.aspose.slides/iportioncollection/
---
**Minden megvalósított interfész:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPortionCollection extends System.Collections.Generic.IGenericEnumerable<IPortion>
```

Egy Portion gyűjteményét képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja az elemet a megadott indexnél. |
| [getCount()](#getCount--) | Visszaadja a gyűjteményben ténylegesen lévő elemek számát. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Hozzáad egy Portion-t a gyűjtemény végéhez. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Megállapítja egy adott Portion indexét a gyűjteményben. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Beszúr egy Portion-t a gyűjteménybe a megadott indexnél. |
| [clear()](#clear--) | Eltávolítja az összes elemet a gyűjteményből. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Megállapítja, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) tartalmaz-e egy adott értéket. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Eltávolítja egy adott objektum első előfordulását a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ból. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja az elemet a gyűjtemény megadott indexén. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPortion get_Item(int index)
```


Visszaadja az elemet a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[IPortion](../../com.aspose.slides/iportion)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Visszaadja a gyűjteményben ténylegesen lévő elemek számát. Csak olvasható int.

**Visszatérési érték:**
int
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public abstract void add(IPortion value)
```


Hozzáad egy Portion-t a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | A Portion, amelyet a gyűjtemény végéhez adunk hozzá. |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public abstract int indexOf(IPortion item)
```


Megállapítja egy adott Portion indexét a gyűjteményben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | A Portion, amelyet a gyűjteményben keresünk. |

**Visszatérési érték:**
int – A megtalált elem indexe a gyűjteményben; egyébként -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public abstract void insert(int index, IPortion value)
```


Beszúr egy Portion-t a gyűjteménybe a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nulla-alapú index, amelynél a Portiont be kell szúrni. |
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
| item | [IPortion](../../com.aspose.slides/iportion) | Az objektum, amelyet a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ban keresünk. |

**Visszatérési érték:**
boolean – igaz, ha az elem megtalálható a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ban; egyébként hamis.
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public abstract boolean remove(IPortion item)
```


Eltávolítja egy adott objektum első előfordulását a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Az objektum, amelyet a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ból eltávolítunk. |

**Visszatérési érték:**
boolean – igaz, ha az elem sikeresen eltávolításra került a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ból; egyébként hamis. Ez a metódus hamis értéket ad vissza, ha az elem nem található az eredeti [IGenericCollection](../../com.aspose.slides/igenericcollection)-ban.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Eltávolítja az elemet a gyűjtemény megadott indexén.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A eltávolítandó elem nulla-alapú indexe. |