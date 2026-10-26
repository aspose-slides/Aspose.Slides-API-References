---
title: ChartCategory
second_title: Aspose.Slides für Android über Java API-Referenz
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
| [getUseCell()](#getUseCell--) | Wenn true, dann ist die AsCell-Eigenschaft tatsächlich. |
| [getAsCell()](#getAsCell--) | Gibt ein IChartDataCell-Objekt zurück oder setzt es. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Gibt ein IChartDataCell-Objekt zurück oder setzt es. |
| [getAsLiteral()](#getAsLiteral--) | Gibt ein AsLiteral-Objekt zurück oder setzt es. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Gibt ein AsLiteral-Objekt zurück oder setzt es. |
| [getValue()](#getValue--) | Wenn UseCell true ist, stellt diese Eigenschaft die AsCell.Value-Eigenschaft dar. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Wenn UseCell true ist, stellt diese Eigenschaft die AsCell.Value-Eigenschaft dar. |
| [getGroupingLevels()](#getGroupingLevels--) | Verwalteter Container der Werte der Diagrammkategorie-Gruppierungsebenen. |
| [remove()](#remove--) | Entfernt die Kategorie aus dem Diagramm. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```

Wenn true, dann ist die AsCell-Eigenschaft tatsächlich. Mit anderen Worten, das Arbeitsblatt wird zum Speichern der Kategorie verwendet (dieser Fall unterstützt eine mehrstufige Kategorie). Wenn false, dann ist die AsLiteral-Eigenschaft tatsächlich. Mit anderen Worten, das Arbeitsblatt wird NICHT zum Speichern der Kategorie verwendet (und dieser Fall unterstützt keine mehrstufigen Kategorien). Nur lesbarer boolescher Wert.

--------------------

Um den Wert dieser Eigenschaft zu ändern (für alle Kategorien in der Sammlung), setzen Sie den neuen Wert auf die ChartCategoryCollection.UseCells-Eigenschaft.

**Rückgabe:**
boolean

### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

Gibt ein IChartDataCell-Objekt zurück oder setzt es. Wenn die Kategorie mehrstufig ist, wird das IChartDataCell-Objekt für Ebene "0" verwendet. Lesen/Schreiben [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Rückgabe:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

Gibt ein IChartDataCell-Objekt zurück oder setzt es. Wenn die Kategorie mehrstufig ist, wird das IChartDataCell-Objekt für Ebene "0" verwendet. Lesen/Schreiben [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```

Gibt ein AsLiteral-Objekt zurück oder setzt es. Lesen/Schreiben Objekt.

**Rückgabe:**
java.lang.Object

### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```

Gibt ein AsLiteral-Objekt zurück oder setzt es. Lesen/Schreiben Objekt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

Wenn UseCell true ist, stellt diese Eigenschaft die AsCell.Value-Eigenschaft dar. Wenn UseCell false ist, stellt diese Eigenschaft die AsLiteral-Eigenschaft dar. Lesen/Schreiben Objekt.

**Rückgabe:**
java.lang.Object

### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

Wenn UseCell true ist, stellt diese Eigenschaft die AsCell.Value-Eigenschaft dar. Wenn UseCell false ist, stellt diese Eigenschaft die AsLiteral-Eigenschaft dar. Lesen/Schreiben Objekt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```

Verwalteter Container der Werte der Diagrammkategorie-Gruppierungsebenen. Mehrstufige Kategorien enthalten mehr als eine Gruppierungsebene. Die Indizierung der Gruppierungsebenen ist nullbasiert. Nur lesbar [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Rückgabe:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)

### remove() {#remove--}
```
public final void remove()
```

Entfernt die Kategorie aus dem Diagramm.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Gibt ein Parent_Immediate-Objekt zurück. Nur lesbar IDOMObject.

**Rückgabe:**
com.aspose.slides.IDOMObject