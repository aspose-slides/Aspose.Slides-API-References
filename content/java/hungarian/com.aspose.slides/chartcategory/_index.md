---
title: ChartCategory
second_title: Aspose.Slides Java API referenciája
description: A diagramkategóriákat képviseli.
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

A diagram kategóriákat képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getUseCell()](#getUseCell--) | Ha igaz, akkor az AsCell tulajdonság a tényleges. |
| [getAsCell()](#getAsCell--) | Visszaadja vagy beállítja az IChartDataCell objektumot. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Visszaadja vagy beállítja az IChartDataCell objektumot. |
| [getAsLiteral()](#getAsLiteral--) | Visszaadja vagy beállítja az AsLiteral objektumot. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Visszaadja vagy beállítja az AsLiteral objektumot. |
| [getValue()](#getValue--) | Ha a UseCell igaz, akkor ez a tulajdonság az AsCell.Value tulajdonságot képviseli. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Ha a UseCell igaz, akkor ez a tulajdonság az AsCell.Value tulajdonságot képviseli. |
| [getGroupingLevels()](#getGroupingLevels--) | Kezelt konténer a diagramkategória csoportosítási szintek értékeinek. |
| [getCachedValue()](#getCachedValue--) | A diagramkategória gyorsítótárazott értékét adja vissza. |
| [remove()](#remove--) | Eltávolítja a kategóriát a diagramról. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```


Ha igaz, akkor az AsCell tulajdonság a tényleges. Más szóval, a munkalap a kategória tárolására szolgál (ez az eset több szintű kategóriát támogat). Ha hamis, akkor az AsLiteral tulajdonság a tényleges. Más szóval, a munkalap NEM használatos a kategória tárolására (és ez az eset nem támogat több szintű kategóriákat). Csak olvasható boolean.

--------------------

Az ezzel a tulajdonsággal kapcsolatos érték módosításához (az összes kategória gyűjteményben) állítsa be az új értéket a ChartCategoryCollection.UseCells tulajdonságra.

**Visszatér:**
boolean
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```


Visszaadja vagy beállítja az IChartDataCell objektumot. Ha a kategória több szintű, akkor az "0" szinthez használt IChartDataCell objektumot. Olvasás/írás [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Visszatér:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```


Visszaadja vagy beállítja az IChartDataCell objektumot. Ha a kategória több szintű, akkor az "0" szinthez használt IChartDataCell objektumot. Olvasás/írás [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```


Visszaadja vagy beállítja az AsLiteral objektumot. Olvasás/írás Object.

**Visszatér:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```


Visszaadja vagy beállítja az AsLiteral objektumot. Olvasás/írás Object.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


Ha a UseCell igaz, akkor ez a tulajdonság az AsCell.Value tulajdonságot képviseli. Ha a UseCell hamis, akkor ez a tulajdonság az AsLiteral tulajdonságot képviseli. Olvasás/írás Object.

**Visszatér:**
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


Kezelt konténer a diagramkategória csoportosítási szintek értékeinek. A több szintű kategória egynél több csoportosítási szintet tartalmaz. A csoportosítási szintek indexelése nullától indul. Csak olvasható [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Visszatér:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### getCachedValue() {#getCachedValue--}
```
public final ICachedChartValue getCachedValue()
```


A diagramkategória gyorsítótárazott értékét adja vissza. Csak olvasható [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx")
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
> 
>      // Írja ki az összes gyorsítótárazott diagramkategória értéket.
>      for (IChartCategory category : chart.getChartData().getCategories())
>          System.out.println(category.getCachedValue().toString());
>  } finally {
>      pres.dispose();
>  }
> ```

**Visszatér:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### remove() {#remove--}
```
public final void remove()
```


Eltávolítja a kategóriát a diagramról.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Visszaadja a Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatér:**
com.aspose.slides.IDOMObject