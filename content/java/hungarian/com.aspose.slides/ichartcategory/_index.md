---
title: IChartCategory
second_title: Aspose.Slides for Java API Reference
description: A diagramkategóriákat képviseli.
type: docs
url: /hu/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

A diagramkategóriákat képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getUseCell()](#getUseCell--) | Ha true akkor az AsCell tulajdonság tényleges. |
| [getAsCell()](#getAsCell--) | Visszaad vagy beállítja az IChartDataCell objektumot. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Visszaad vagy beállítja az IChartDataCell objektumot. |
| [getAsLiteral()](#getAsLiteral--) | Visszaad vagy beállítja az AsLiteral értéket, ha a UseCell false. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Visszaad vagy beállítja az AsLiteral értéket, ha a UseCell false. |
| [getValue()](#getValue--) | Ha a UseCell true, akkor ez a tulajdonság az AsCell.Value tulajdonságot képviseli. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Ha a UseCell true, akkor ez a tulajdonság az AsCell.Value tulajdonságot képviseli. |
| [getGroupingLevels()](#getGroupingLevels--) | Kezelt tárolója a diagramkategória csoportosítási szintek értékeinek. |
| [remove()](#remove--) | Eltávolítja a kategóriát a diagramról. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```

Ha true, akkor az AsCell tulajdonság tényleges. Más szóval, a munkalap a kategória tárolására van használva (ez az eset több szintű kategóriát támogat). Ha false, akkor az AsLiteral tulajdonság tényleges. Más szóval, a munkalap NEM használatos a kategória tárolására (és ez az eset nem támogat több szintű kategóriát). Csak olvasható boolean.

--------------------

A tulajdonság értékének megváltoztatásához (az összes kategória esetén a gyűjteményben) állítsa be az új értéket a [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--) tulajdonsághoz.

**Visszatérési érték:**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```

Visszaad vagy beállítja az IChartDataCell objektumot. Ha a kategória több szintű, akkor az "0" szinthez használt IChartDataCell objektumot. Írás/olvasás [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Visszatérési érték:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```

Visszaad vagy beállítja az IChartDataCell objektumot. Ha a kategória több szintű, akkor az "0" szinthez használt IChartDataCell objektumot. Írás/olvasás [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```

Visszaad vagy beállítja az AsLiteral értéket, ha a UseCell false. Írás/olvasás Object.

**Visszatérési érték:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```

Visszaad vagy beállítja az AsLiteral értéket, ha a UseCell false. Írás/olvasás Object.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.Object |  |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

Ha a UseCell true, akkor ez a tulajdonság az AsCell.Value tulajdonságot képviseli. Ha a UseCell false, akkor ez a tulajdonság az AsLiteral tulajdonságot képviseli. Írás/olvasás Object.

**Visszatérési érték:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Ha a UseCell true, akkor ez a tulajdonság az AsCell.Value tulajdonságot képviseli. Ha a UseCell false, akkor ez a tulajdonság az AsLiteral tulajdonságot képviseli. Írás/olvasás Object.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.Object |  |
### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```

Kezelt konténere a diagramkategória csoportosítási szintek értékeinek. Többszintű kategória több, mint egy csoportosítási szintet tartalmaz. A csoportosítási szintek indexelése nulláról indul. Csak olvasható [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Visszatérési érték:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```

Eltávolítja a kategóriát a diagramról.