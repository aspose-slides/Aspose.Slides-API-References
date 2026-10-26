---
title: IChartCategory
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt Diagrammkategorien dar.
type: docs
url: /de/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

Stellt Diagrammkategorien dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getUseCell()](#getUseCell--) | Wenn true, dann ist die AsCell-Eigenschaft gültig. |
| [getAsCell()](#getAsCell--) | Gibt ein IChartDataCell-Objekt zurück oder setzt es. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Gibt ein IChartDataCell-Objekt zurück oder setzt es. |
| [getAsLiteral()](#getAsLiteral--) | Gibt AsLiteral zurück oder setzt es, wenn UseCell false ist. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Gibt AsLiteral zurück oder setzt es, wenn UseCell false ist. |
| [getValue()](#getValue--) | Wenn UseCell true ist, dann stellt diese Eigenschaft die AsCell.Value-Eigenschaft dar. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Wenn UseCell true ist, dann stellt diese Eigenschaft die AsCell.Value-Eigenschaft dar. |
| [getGroupingLevels()](#getGroupingLevels--) | Verwalteter Container der Werte der Gruppierungsebenen der Diagrammkategorie. |
| [remove()](#remove--) | Entfernt die Kategorie aus dem Diagramm. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```


Wenn true, dann ist die AsCell-Eigenschaft gültig. Mit anderen Worten, das Arbeitsblatt wird zum Speichern der Kategorie verwendet (dieser Fall unterstützt eine mehrstufige Kategorie). Wenn false, dann ist die AsLiteral-Eigenschaft gültig. Mit anderen Worten, das Arbeitsblatt wird NICHT zum Speichern der Kategorie verwendet (und dieser Fall unterstützt keine mehrstufigen Kategorien). Nur-Lese Boolean.

Um den Wert dieser Eigenschaft zu ändern (für alle Kategorien in der Sammlung), setzen Sie den neuen Wert in die [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--)-Eigenschaft.

**Rückgabe:**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```


Gibt ein IChartDataCell-Objekt zurück oder setzt es. Ist die Kategorie mehrstufig, wird das IChartDataCell-Objekt für Ebene "0" verwendet. Lese/Schreiben [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Rückgabe:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```


Gibt ein IChartDataCell-Objekt zurück oder setzt es. Ist die Kategorie mehrstufig, wird das IChartDataCell-Objekt für Ebene "0" verwendet. Lese/Schreiben [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```


Gibt AsLiteral zurück oder setzt es, wenn UseCell false ist. Lese/Schreiben Object.

**Rückgabe:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```


Gibt AsLiteral zurück oder setzt es, wenn UseCell false ist. Lese/Schreiben Object.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.Object |  |
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Wenn UseCell true ist, dann stellt diese Eigenschaft die AsCell.Value-Eigenschaft dar. Wenn UseCell false ist, dann stellt diese Eigenschaft die AsLiteral-Eigenschaft dar. Lese/Schreiben Object.

**Rückgabe:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Wenn UseCell true ist, dann stellt diese Eigenschaft die AsCell.Value-Eigenschaft dar. Wenn UseCell false ist, dann stellt diese Eigenschaft die AsLiteral-Eigenschaft dar. Lese/Schreiben Object.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.Object |  |
### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```


Verwalteter Container der Werte der Gruppierungsebenen der Diagrammkategorie. Mehrstufige Kategorien enthalten mehr als eine Gruppierungsebene. Die Indexierung der Gruppierungsebenen ist nullbasiert. Nur-Lese [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Rückgabe:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```


Entfernt die Kategorie aus dem Diagramm.