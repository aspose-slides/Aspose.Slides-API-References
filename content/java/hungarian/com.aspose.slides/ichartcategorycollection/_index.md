---
title: IChartCategoryCollection
second_title: Aspose.Slides Java API referencia
description: Gyűjteményt képvisel
type: docs
url: /hu/com.aspose.slides/ichartcategorycollection/
---
**Minden megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface IChartCategoryCollection extends IGenericCollection<IChartCategory>
```

A [IChartCategory](../../com.aspose.slides/ichartcategory) gyűjteményét reprezentálja
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lekéri a megadott indexű elemet. |
| [getUseCells()](#getUseCells--) | Ha igaz, akkor a munkalapot a kategóriák tárolására használják (ez az eset több szintű kategóriákat támogat). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Ha igaz, akkor a munkalapot a kategóriák tárolására használják (ez az eset több szintű kategóriákat támogat). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Visszaadja a használt kategória-csoportosítási szintek számát. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Ha a kategória létezik a gyűjteményben, visszaadja. |
| [add(Object value)](#add-java.lang.Object-) | Új [IChartCategory](../../com.aspose.slides/ichartcategory) objektumot hoz létre az értékből, és hozzáadja a gyűjteményhez. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Megkeresi a megadott [IChartCategory](../../com.aspose.slides/ichartcategory) elemet, és visszaadja a nullától indexelt első előfordulásának indexét az egész gyűjteményben. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Eltávolítja a megadott értéket. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a megadott indexű elemet. |
| [clear()](#clear--) | Eltávolítja az összes elemet a gyűjteményből. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartCategory get_Item(int index)
```


Lekéri a megadott indexű elemet.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatér:**  
[IChartCategory](../../com.aspose.slides/ichartcategory) - A megadott indexű elem.

### getUseCells() {#getUseCells--}
```
public abstract boolean getUseCells()
```


Ha igaz, akkor a munkalapot a kategóriák tárolására használják (ez az eset több szintű kategóriákat támogat). Ha hamis, akkor a munkalap NEM használható az értékek tárolására (és ez az eset nem támogatja a több szintű kategóriákat). Olvasás/írás boolean.

**Visszatér:**  
boolean

### setUseCells(boolean value) {#setUseCells-boolean-}
```
public abstract void setUseCells(boolean value)
```


Ha igaz, akkor a munkalapot a kategóriák tárolására használják (ez az eset több szintű kategóriákat támogat). Ha hamis, akkor a munkalap NEM használható az értékek tárolására (és ez az eset nem támogatja a több szintű kategóriákat). Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public abstract int getGroupingLevelCount()
```


Visszaadja a használt kategória-csoportosítási szintek számát. Több mint egy, ha több szintű kategóriák vannak. Csak olvasható int.

**Visszatér:**  
int

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract IChartCategory add(IChartDataCell chartDataCell)
```


Ha a kategória létezik a gyűjteményben, visszaadja. Ellenkező esetben új diagramkategóriát hoz létre a [IChartDataCell](../../com.aspose.slides/ichartdatacell) alapján, és hozzáadja a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | A diagramkategória létrehozásához használt cella. |

**Visszatér:**  
[IChartCategory](../../com.aspose.slides/ichartcategory) - Hozzáadott vagy meglévő kategória.

### add(Object value) {#add-java.lang.Object-}
```
public abstract IChartCategory add(Object value)
```


Új [IChartCategory](../../com.aspose.slides/ichartcategory) objektumot hoz létre az értékből, és hozzáadja a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.Object | Az érték.

--------------------

Ez a metódus hozzáad egy AUTO_DATA nevű munkalapot, és oda helyezi az összes értéket. Ha a [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)-t használja cellaértékek hozzáadására vagy szerkesztésére, ügyeljen arra, hogy ezt a munkalapot ne használja. A módszerrel hozzáadott értékek maximális száma nem haladhatja meg a 16711680-at |

**Visszatér:**  
[IChartCategory](../../com.aspose.slides/ichartcategory) - Hozzáadott [IChartCategory](../../com.aspose.slides/ichartcategory).

### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public abstract int indexOf(IChartCategory value)
```


Megkeresi a megadott [IChartCategory](../../com.aspose.slides/ichartcategory) elemet, és visszaadja a nullától indexelt első előfordulásának indexét az egész gyűjteményben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Diagramkategória. |

**Visszatér:**  
int - A nullától indexelt első előfordulás indexe az egész CollectionBase-ben, ha megtalálta; egyébként -1.

### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public abstract void remove(IChartCategory value)
```


Eltávolítja a megadott értéket.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Az érték.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Eltávolítja a megadott indexű elemet.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A törlendő kategória indexe.

### clear() {#clear--}
```
public abstract void clear()
```


Eltávolítja az összes elemet a gyűjteményből.