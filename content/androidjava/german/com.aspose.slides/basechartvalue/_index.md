---
title: BaseChartValue
second_title: Aspose.Slides für Android über die Java API-Referenz
description: Stellt einen Wert eines Diagramms dar.
type: docs
url: /de/com.aspose.slides/basechartvalue/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IBaseChartValue](../../com.aspose.slides/ibasechartvalue), com.aspose.slides.IDOMObject
```
public abstract class BaseChartValue implements IBaseChartValue, IDOMObject
```

Stellt einen Wert eines Diagramms dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Gibt an, ob die Eigenschaft AsCell, AsCells, AsLiteralString oder AsLiteralDouble in abgeleiteten Klassen vorhanden ist. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Gibt an, ob die Eigenschaft AsCell, AsCells, AsLiteralString oder AsLiteralDouble in abgeleiteten Klassen vorhanden ist. |
| [getData()](#getData--) | Daten. |
| [setData(Object value)](#setData-java.lang.Object-) | Daten. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

Gibt an, ob die Eigenschaft AsCell, AsCells, AsLiteralString oder AsLiteralDouble in abgeleiteten Klassen vorhanden ist. Mit anderen Worten gibt sie den Typ des Werts der Eigenschaft Data an. Lesen/Schreiben [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

Für Punkte in ChartDataPointCollection ist diese Eigenschaft nur lesbar. In diesem Fall können Sie zum Ändern des Werts dieser Eigenschaft eine der Eigenschaften ChartDataPointCollection.DataSourceTypeFor<...> verwenden.

**Rückgabe:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public final void setDataSourceType(int value)
```

Gibt an, ob die Eigenschaft AsCell, AsCells, AsLiteralString oder AsLiteralDouble in abgeleiteten Klassen vorhanden ist. Mit anderen Worten gibt sie den Typ des Werts der Eigenschaft Data an. Lesen/Schreiben [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

Für Punkte in ChartDataPointCollection ist diese Eigenschaft nur lesbar. In diesem Fall können Sie zum Ändern des Werts dieser Eigenschaft eine der Eigenschaften ChartDataPointCollection.DataSourceTypeFor<...> verwenden.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getData() {#getData--}
```
public abstract Object getData()
```

Daten. Lesen/Schreiben Object.

**Rückgabe:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

Daten. Lesen/Schreiben Object.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.Object |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Gibt das Objekt Parent_Immediate zurück. Nur lesbar IDOMObject.

**Rückgabe:**
com.aspose.slides.IDOMObject