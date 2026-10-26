---  
title: IChartCategory  
second_title: Aspose.Slides for Android via Java API Reference  
description: A diagram kategóriákat képviseli.  
type: docs  
url: /hu/com.aspose.slides/ichartcategory/  
---```
public interface IChartCategory
```

A diagram kategóriákat képviseli.  
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getUseCell()](#getUseCell--) | If true then AsCell property is actual. |
| [getAsCell()](#getAsCell--) | Returns or sets IChartDataCell object. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Returns or sets IChartDataCell object. |
| [getAsLiteral()](#getAsLiteral--) | Returns or sets AsLiteral if UseCell is false. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Returns or sets AsLiteral if UseCell is false. |
| [getValue()](#getValue--) | If UseCell is true then this property represents AsCell.Value property. |
| [setValue(Object value)](#setValue-java.lang.Object-) | If UseCell is true then this property represents AsCell.Value property. |
| [getGroupingLevels()](#getGroupingLevels--) | Managed container of the values of the chart category grouping levels. |
| [remove()](#remove--) | Removes category from chart. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```

Ha igaz, akkor az AsCell tulajdonság érvényes. Más szóval, a munkalap a kategória tárolására kerül felhasználásra (ez az eset többszintű kategóriát támogat). Ha hamis, akkor az AsLiteral tulajdonság érvényes. Más szóval, a munkalap NEM használatos a kategória tárolására (és ez az eset nem támogat többszintű kategóriákat). Csak olvasható boolean.

--------------------

Ennek a tulajdonságnak az értékének megváltoztatásához (az összes kategória a gyűjteményben) állítsa be az új értéket a [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--) tulajdonságra.

**Visszatér:**  
boolean  
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```

Visszaad vagy beállít egy IChartDataCell objektumot. Ha a kategória többszintű, akkor a szint "0" számára használt IChartDataCell objektumot. Olvasás/írás [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Visszatér:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell)  
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```

Visszaad vagy beállít egy IChartDataCell objektumot. Ha a kategória többszintű, akkor a szint "0" számára használt IChartDataCell objektumot. Olvasás/írás [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```

Visszaad vagy beállít AsLiteral értéket, ha a UseCell hamis. Olvasás/írás Object.

**Visszatér:**  
java.lang.Object  
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```

Visszaad vagy beállít AsLiteral értéket, ha a UseCell hamis. Olvasás/írás Object.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```

Ha UseCell igaz, akkor ez a tulajdonság az AsCell.Value tulajdonságot képviseli. Ha UseCell hamis, akkor ez a tulajdonság az AsLiteral tulajdonságot képviseli. Olvasás/írás Object.

**Visszatér:**  
java.lang.Object  
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Ha UseCell igaz, akkor ez a tulajdonság az AsCell.Value tulajdonságot képviseli. Ha UseCell hamis, akkor ez a tulajdonság az AsLiteral tulajdonságot képviseli. Olvasás/írás Object.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```

Kezelt tároló a diagram kategória csoportosítási szintjeinek értékeinek. A többszintű kategória egynél több csoportosítási szintet tartalmaz. A csoportosítási szintek indexelése nullától indul. Csak olvasható [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Visszatér:**  
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)  
### remove() {#remove--}
```
public abstract void remove()
```

Eltávolítja a kategóriát a diagramról.