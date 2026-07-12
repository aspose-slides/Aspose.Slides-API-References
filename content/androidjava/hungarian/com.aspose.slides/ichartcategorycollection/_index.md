---
title: IChartCategoryCollection
second_title: Aspose.Slides Androidra a Java API hivatkozás
description: Gyűjteményt képvisel
type: docs
url: /hu/com.aspose.slides/ichartcategorycollection/
---
**Az összes megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface IChartCategoryCollection extends IGenericCollection<IChartCategory>
```

A [IChartCategory](../../com.aspose.slides/ichartcategory) gyűjteményét képviseli
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a megadott indexű elemet. |
| [getUseCells()](#getUseCells--) | Ha igaz, akkor a munkalap a kategóriák tárolására szolgál (ez az eset több szintű kategóriákat támogat). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Ha igaz, akkor a munkalap a kategóriák tárolására szolgál (ez az eset több szintű kategóriákat támogat). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Visszaadja a használt kategória-csoportosítási szintek számát. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Ha a kategória létezik a gyűjteményben, visszaadja azt. |
| [add(Object value)](#add-java.lang.Object-) | [IChartCategory](../../com.aspose.slides/ichartcategory)-t hoz létre az értékből, és hozzáadja a gyűjteményhez. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Keres a megadott [IChartCategory](../../com.aspose.slides/ichartcategory) után, és a teljes gyűjteményben az első előfordulás nulla alapú indexét adja vissza. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Eltávolítja a megadott értéket. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja az elemet a megadott indexnél. |
| [clear()](#clear--) | Eltávolítja a gyűjtemény összes elemét. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartCategory get_Item(int index)
```

Visszaadja a megadott indexű elemet.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - A megadott indexű elem.
### getUseCells() {#getUseCells--}
```
public abstract boolean getUseCells()
```

Ha igaz, akkor a munkalap a kategóriák tárolására szolgál (ez az eset több szintű kategóriákat támogat). Ha hamis, akkor a munkalap NEM használható az értékek tárolására (és ez az eset nem támogatja a több szintű kategóriákat). Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setUseCells(boolean value) {#setUseCells-boolean-}
```
public abstract void setUseCells(boolean value)
```

Ha igaz, akkor a munkalap a kategóriák tárolására szolgál (ez az eset több szintű kategóriákat támogat). Ha hamis, akkor a munkalap NEM használható az értékek tárolására (és ez az eset nem támogatja a több szintű kategóriákat). Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public abstract int getGroupingLevelCount()
```

Visszaadja a használt kategória-csoportosítási szintek számát. Több mint egy a több szintű kategóriák esetén. Csak olvasható int.

**Visszatérési érték:**
int
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract IChartCategory add(IChartDataCell chartDataCell)
```

Ha a kategória létezik a gyűjteményben, visszaadja azt. Ellenkező esetben új diagramkategóriát hoz létre a [IChartDataCell](../../com.aspose.slides/ichartdatacell) alapján, és hozzáadja a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | A diagramkategória létrehozásához használt cella. |

**Visszatérési érték:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Hozzáadott vagy meglévő kategória.
### add(Object value) {#add-java.lang.Object-}
```
public abstract IChartCategory add(Object value)
```

[IChartCategory](../../com.aspose.slides/ichartcategory)-t hoz létre az értékből, és hozzáadja a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.Object | Az érték.

--------------------

Ez a metódus hozzáad egy AUTO_DATA nevű munkalapot, és oda teszi az összes értéket. Ha a [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)-t használja cellaértékek hozzáadásához vagy szerkesztéséhez, ügyeljen arra, hogy ne használja ezt a munkalapot. Ezzel a módszerrel hozzáadott értékek maximális száma nem haladhatja meg a 16711680-at |
**Visszatérési érték:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Hozzáadott [IChartCategory](../../com.aspose.slides/ichartcategory).
### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public abstract int indexOf(IChartCategory value)
```

Keres a megadott [IChartCategory](../../com.aspose.slides/ichartcategory) után, és a teljes gyűjteményben az első előfordulás nulla alapú indexét adja vissza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Diagramkategória. |

**Visszatérési érték:**
int - A megtalált érték első előfordulásának nulla alapú indexe a teljes CollectionBase-ben, ha megtalálható; egyébként -1.
### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public abstract void remove(IChartCategory value)
```

Eltávolítja a megadott értéket.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Az érték. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolítja az elemet a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A törlendő kategória indexe. |
### clear() {#clear--}
```
public abstract void clear()
```

Eltávolítja a gyűjtemény összes elemét.