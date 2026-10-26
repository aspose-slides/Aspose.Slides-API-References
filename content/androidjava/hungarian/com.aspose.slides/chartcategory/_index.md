---
title: ChartCategory
second_title: Aspose.Slides Androidra a Java API hivatkozás
description: Diagramkategóriákat reprezentál.
type: docs
url: /hu/com.aspose.slides/chartcategory/
---
**Öröklés:**  
java.lang.Object

**Minden megvalósított interfész:**  
[com.aspose.slides.IChartCategory](../../com.aspose.slides/ichartcategory), com.aspose.slides.IDOMObject  
```
public class ChartCategory implements IChartCategory, IDOMObject
```

A diagramkategóriákat reprezentálja.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getUseCell()](#getUseCell--) | Ha igaz, akkor az AsCell tulajdonság aktuális. |
| [getAsCell()](#getAsCell--) | Visszaad vagy beállít IChartDataCell objektumot. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Visszaad vagy beállít IChartDataCell objektumot. |
| [getAsLiteral()](#getAsLiteral--) | Visszaad vagy beállít AsLiteral objektumot. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Visszaad vagy beállít AsLiteral objektumot. |
| [getValue()](#getValue--) | Ha a UseCell igaz, akkor ez a tulajdonság az AsCell.Value tulajdonságot képviseli. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Ha a UseCell igaz, akkor ez a tulajdonság az AsCell.Value tulajdonságot képviseli. |
| [getGroupingLevels()](#getGroupingLevels--) | Kezelt tároló a diagramkategória csoportosítási szintek értékeinek. |
| [remove()](#remove--) | Eltávolítja a kategóriát a diagramról. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```

Ha igaz, akkor az AsCell tulajdonság aktuális. Más szóval, a munkalap a kategória tárolására szolgál (ez az eset több szintű kategóriát támogat). Ha hamis, akkor az AsLiteral tulajdonság aktuális. Más szóval, a munkalap NEM használatos a kategória tárolására (és ez az eset nem támogat több szintű kategóriákat). Csak olvasható boolean.

--------------------

Ennek a tulajdonságnak az értékének módosításához (az összes kategória gyűjteményben) állítsa be az új értéket a ChartCategoryCollection.UseCells tulajdonságra.

**Visszatérési érték:**  
boolean
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

Visszaad vagy beállít IChartDataCell objektumot. Ha a kategória több szintű, akkor a szint "0"-hoz használt IChartDataCell objektumot. Olvasás/írás [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Visszatérési érték:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

Visszaad vagy beállít IChartDataCell objektumot. Ha a kategória több szintű, akkor a szint "0"-hoz használt IChartDataCell objektumot. Olvasás/írás [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```

Visszaad vagy beállít AsLiteral objektumot. Olvasás/írás Object.

**Visszatérési érték:**  
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```

Visszaad vagy beállít AsLiteral objektumot. Olvasás/írás Object.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

Ha a UseCell igaz, akkor ez a tulajdonság az AsCell.Value tulajdonságot képviseli. Ha a UseCell hamis, akkor ez a tulajdonság az AsLiteral tulajdonságot képviseli. Olvasás/írás Object.

**Visszatérési érték:**  
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

Ha a UseCell igaz, akkor ez a tulajdonság az AsCell.Value tulajdonságot képviseli. Ha a UseCell hamis, akkor ez a tulajdonság az AsLiteral tulajdonságot képviseli. Olvasás/írás Object.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```

Kezelt tároló a diagramkategória csoportosítási szintek értékeinek. A több szintű kategória több, mint egy csoportosítási szintet tartalmaz. A csoportosítási szintek indexelése nullától kezdődik. Csak olvasható [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Visszatérési érték:**  
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public final void remove()
```

Eltávolítja a kategóriát a diagramról.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszaad Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatérési érték:**  
com.aspose.slides.IDOMObject