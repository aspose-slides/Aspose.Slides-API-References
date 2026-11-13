---
title: IChartCategory
second_title: Aspose.Slides for Java API Reference
description: Represents chart categories.
type: docs
url: /de/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

Stellt Diagrammkategorien dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getUseCell()](#getUseCell--) | Wenn true, ist die AsCell-Eigenschaft aktuell. |
| [getAsCell()](#getAsCell--) | Gibt ein IChartDataCell-Objekt zurück oder legt es fest. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Gibt ein IChartDataCell-Objekt zurück oder legt es fest. |
| [getAsLiteral()](#getAsLiteral--) | Gibt AsLiteral zurück oder legt es fest, wenn UseCell false ist. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Gibt AsLiteral zurück oder legt es fest, wenn UseCell false ist. |
| [getValue()](#getValue--) | Wenn UseCell true ist, stellt diese Eigenschaft die AsCell.Value-Eigenschaft dar. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Wenn UseCell true ist, stellt diese Eigenschaft die AsCell.Value-Eigenschaft dar. |
| [getCachedValue()](#getCachedValue--) | Liest den zwischengespeicherten Wert einer Diagrammkategorie. |
| [getGroupingLevels()](#getGroupingLevels--) | Verwalteter Container der Werte der Gruppierungsebenen einer Diagrammkategorie. |
| [remove()](#remove--) | Entfernt die Kategorie aus dem Diagramm. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```

Wenn true, ist die AsCell-Eigenschaft aktuell. Anders gesagt, das Arbeitsblatt wird zum Speichern der Kategorie verwendet (dieser Fall unterstützt eine mehrstufige Kategorie). Wenn false, ist die AsLiteral-Eigenschaft aktuell. Anders gesagt, das Arbeitsblatt wird NICHT zum Speichern der Kategorie verwendet (und dieser Fall unterstützt keine mehrstufigen Kategorien). Nur lesbarer Boolean.

--------------------

Um den Wert dieser Eigenschaft (für alle Kategorien in der Sammlung) zu ändern, setzen Sie den neuen Wert auf die Eigenschaft [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--).

**Rückgabe:**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```

Gibt ein IChartDataCell-Objekt zurück oder legt es fest. Wenn die Kategorie mehrstufig ist, wird das IChartDataCell-Objekt für Ebene "0" verwendet. Lese/Schreib [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Rückgabe:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```

Gibt ein IChartDataCell-Objekt zurück oder legt es fest. Wenn die Kategorie mehrstufig ist, wird das IChartDataCell-Objekt für Ebene "0" verwendet. Lese/Schreib [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```

Gibt AsLiteral zurück oder legt es fest, wenn UseCell false ist. Lese/Schreib Object.

**Rückgabe:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```

Gibt AsLiteral zurück oder legt es fest, wenn UseCell false ist. Lese/Schreib Object.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.Object |  |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

Wenn UseCell true ist, stellt diese Eigenschaft die AsCell.Value-Eigenschaft dar. Wenn UseCell false ist, stellt diese Eigenschaft die AsLiteral-Eigenschaft dar. Lese/Schreib Object.

**Rückgabe:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Wenn UseCell true ist, stellt diese Eigenschaft die AsCell.Value-Eigenschaft dar. Wenn UseCell false ist, stellt diese Eigenschaft die AsLiteral-Eigenschaft dar. Lese/Schreib Object.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.Object |  |
### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
```

Liest den zwischengespeicherten Wert einer Diagrammkategorie. Nur lesbar [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
> 
>      // Gibt alle zwischengespeicherten Diagrammkategorie Werte aus.
>      for (IChartCategory category : chart.getChartData().getCategories())
>          System.out.println(category.getCachedValue().toString());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabe:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```

Verwalteter Container der Werte der Gruppierungsebenen einer Diagrammkategorie. Mehrstufige Kategorien enthalten mehr als eine Gruppierungsebene. Die Indexierung der Gruppierungsebenen ist nullbasiert. Nur lesbar [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Rückgabe:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```

Entfernt die Kategorie aus dem Diagramm.