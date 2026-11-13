---
title: ChartCategory
second_title: Aspose.Slides für Java API-Referenz
description: Stellt Diagrammkategorien dar.
type: docs
url: /de/com.aspose.slides/chartcategory/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IChartCategory](../../com.aspose.slides/ichartcategory), com.aspose.slides.IDOMObject
```
public class ChartCategory implements IChartCategory, IDOMObject
```

Stellt Diagrammkategorien dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getUseCell()](#getUseCell--) | Ist true, dann ist die AsCell-Eigenschaft gültig. |
| [getAsCell()](#getAsCell--) | Gibt ein IChartDataCell-Objekt zurück oder setzt es. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Gibt ein IChartDataCell-Objekt zurück oder setzt es. |
| [getAsLiteral()](#getAsLiteral--) | Gibt ein AsLiteral-Objekt zurück oder setzt es. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Gibt ein AsLiteral-Objekt zurück oder setzt es. |
| [getValue()](#getValue--) | Ist UseCell true, dann stellt diese Eigenschaft die AsCell.Value-Eigenschaft dar. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Ist UseCell true, dann stellt diese Eigenschaft die AsCell.Value-Eigenschaft dar. |
| [getGroupingLevels()](#getGroupingLevels--) | Verwalteter Container der Werte der Gruppierungsebenen der Diagrammkategorie. |
| [getCachedValue()](#getCachedValue--) | Liefert den zwischengespeicherten Wert einer Diagrammkategorie. |
| [remove()](#remove--) | Entfernt die Kategorie aus dem Diagramm. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```


Ist true, dann ist die AsCell-Eigenschaft gültig. Mit anderen Worten, das Arbeitsblatt wird zum Speichern der Kategorie verwendet (dieser Fall unterstützt eine mehrstufige Kategorie). Ist false, dann ist die AsLiteral-Eigenschaft gültig. Mit anderen Worten, das Arbeitsblatt wird NICHT zum Speichern der Kategorie verwendet (und dieser Fall unterstützt keine mehrstufigen Kategorien). Nur lesend Boolean.

--------------------

Um den Wert dieser Eigenschaft zu ändern (für alle Kategorien in der Sammlung), setzen Sie den neuen Wert auf die Eigenschaft ChartCategoryCollection.UseCells.

**Rückgabe:**
boolean
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```


Gibt ein IChartDataCell-Objekt zurück oder setzt es. Wenn die Kategorie mehrstufig ist, wird das IChartDataCell-Objekt für Ebene „0“ verwendet. Lese/Schreib [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Rückgabe:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```


Gibt ein IChartDataCell-Objekt zurück oder setzt es. Wenn die Kategorie mehrstufig ist, wird das IChartDataCell-Objekt für Ebene „0“ verwendet. Lese/Schreib [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```


Gibt ein AsLiteral-Objekt zurück oder setzt es. Lese/Schreib Object.

**Rückgabe:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```


Gibt ein AsLiteral-Objekt zurück oder setzt es. Lese/Schreib Object.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


Ist UseCell true, dann stellt diese Eigenschaft die AsCell.Value-Eigenschaft dar. Ist UseCell false, dann stellt diese Eigenschaft die AsLiteral-Eigenschaft dar. Lese/Schreib Object.

**Rückgabe:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Ist UseCell true, dann stellt diese Eigenschaft die AsCell.Value-Eigenschaft dar. Ist UseCell false, dann stellt diese Eigenschaft die AsLiteral-Eigenschaft dar. Lese/Schreib Object.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```


Verwalteter Container der Werte der Gruppierungsebenen der Diagrammkategorie. Mehrstufige Kategorien enthalten mehr als eine Gruppierungsebene. Die Indizierung der Gruppierungsebenen beginnt bei 0. Nur lesend [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Rückgabe:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### getCachedValue() {#getCachedValue--}
```
public final ICachedChartValue getCachedValue()
```


Liefert den zwischengespeicherten Wert einer Diagrammkategorie. Nur lesend [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx")
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
> 
>      // Gibt alle zwischengespeicherten Diagrammkategoriewerte aus.
>      for (IChartCategory category : chart.getChartData().getCategories())
>          System.out.println(category.getCachedValue().toString());
>  } finally {
>      pres.dispose();
>  }
> ```


**Rückgabe:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### remove() {#remove--}
```
public final void remove()
```


Entfernt die Kategorie aus dem Diagramm.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Gibt das Objekt Parent_Immediate zurück. Nur lesend IDOMObject.

**Rückgabe:**
com.aspose.slides.IDOMObject