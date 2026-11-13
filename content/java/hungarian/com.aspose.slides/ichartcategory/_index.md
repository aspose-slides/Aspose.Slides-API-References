---
title: IChartCategory
second_title: Aspose.Slides Java API-referencia
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
| [getUseCell()](#getUseCell--) | Ha igaz, akkor az AsCell tulajdonság az aktuális. |
| [getAsCell()](#getAsCell--) | Visszaad vagy beállítja az IChartDataCell objektumot. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Visszaad vagy beállítja az IChartDataCell objektumot. |
| [getAsLiteral()](#getAsLiteral--) | Visszaad vagy beállítja az AsLiteral értéket, ha a UseCell hamis. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Visszaad vagy beállítja az AsLiteral értéket, ha a UseCell hamis. |
| [getValue()](#getValue--) | Ha a UseCell igaz, akkor ez a tulajdonság az AsCell.Value tulajdonságot képviseli. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Ha a UseCell igaz, akkor ez a tulajdonság az AsCell.Value tulajdonságot képviseli. |
| [getCachedValue()](#getCachedValue--) | Lekéri egy diagramkategória gyorsítótárazott értékét. |
| [getGroupingLevels()](#getGroupingLevels--) | Kezelt tároló a diagramkategória csoportosítási szintjeinek értékeinek. |
| [remove()](#remove--) | Eltávolítja a kategóriát a diagramról. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```


Ha igaz, akkor az AsCell tulajdonság az aktuális. Más szóval, a munkalap a kategória tárolására szolgál (ez az eset több szintű kategóriát támogat). Ha hamis, akkor az AsLiteral tulajdonság az aktuális. Más szóval, a munkalap NEM szolgál a kategória tárolására (és ez az eset nem támogat több szintű kategóriákat). Csak olvasható boolean.

--------------------

A tulajdonság értékének módosításához (az összes kategória esetén a gyűjteményben) állítsa be az új értéket a [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--) tulajdonságra.

**Visszaad:**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```


Visszaad vagy beállítja az IChartDataCell objektumot. Ha a kategória több szintű, akkor a "0" szinthez használt IChartDataCell objektumot. Olvasható/írható [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Visszaad:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```


Visszaad vagy beállítja az IChartDataCell objektumot. Ha a kategória több szintű, akkor a "0" szinthez használt IChartDataCell objektumot. Olvasható/írható [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```


Visszaad vagy beállítja az AsLiteral értéket, ha a UseCell hamis. Olvasható/írható Object.

**Visszaad:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```


Visszaad vagy beállítja az AsLiteral értéket, ha a UseCell hamis. Olvasható/írható Object.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```


Ha a UseCell igaz, akkor ez a tulajdonság az AsCell.Value tulajdonságot képviseli. Ha a UseCell hamis, akkor ez a tulajdonság az AsLiteral tulajdonságot képviseli. Olvasható/írható Object.

**Visszaad:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Ha a UseCell igaz, akkor ez a tulajdonság az AsCell.Value tulajdonságot képviseli. Ha a UseCell hamis, akkor ez a tulajdonság az AsLiteral tulajdonságot képviseli. Olvasható/írható Object.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.Object |  |

### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
```


Lekéri egy diagramkategória gyorsítótárazott értékét. Csak olvasható [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
> 
>      // Kiírja az összes gyorsítótárazott diagramkategória értéket.
>      for (IChartCategory category : chart.getChartData().getCategories())
>          System.out.println(category.getCachedValue().toString());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszaad:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```


Kezelt tároló a diagramkategória csoportosítási szintjeinek értékeinek. A több szintű kategória több, mint egy csoportosítási szintet tartalmaz. A csoportosítási szintek indexelése nullától induló. Csak olvasható [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Visszaad:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```


Eltávolítja a kategóriát a diagramról.