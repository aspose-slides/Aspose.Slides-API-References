---
title: IBaseChartValue
second_title: Aspose.Slides for Java API Reference
description: Stellt einen Wert eines Diagramms dar.
type: docs
url: /de/com.aspose.slides/ibasechartvalue/
---```
public interface IBaseChartValue
```

Stellt einen Wert eines Diagramms dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Gibt an, ob die AsCell- oder AsLiteralString- oder AsLiteralDouble-Eigenschaft aktuell ist. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Gibt an, ob die AsCell- oder AsLiteralString- oder AsLiteralDouble-Eigenschaft aktuell ist. |
| [getData()](#getData--) | Lese/Schreib-Objekt. |
| [setData(Object value)](#setData-java.lang.Object-) | Lese/Schreib-Objekt. |
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

Gibt an, ob die AsCell- oder AsLiteralString- oder AsLiteralDouble-Eigenschaft aktuell ist. Mit anderen Worten gibt es den Typ des Werts der Data-Eigenschaft an. Diese Eigenschaft ist nur lesbar. Um den Wert dieser Eigenschaft zu ändern, können Sie eine der ChartDataPointCollection.DataSourceTypeFor<...>-Eigenschaften verwenden. Lese/Schreib [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Rückgabewert:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public abstract void setDataSourceType(int value)
```

Gibt an, ob die AsCell- oder AsLiteralString- oder AsLiteralDouble-Eigenschaft aktuell ist. Mit anderen Worten gibt es den Typ des Werts der Data-Eigenschaft an. Diese Eigenschaft ist nur lesbar. Um den Wert dieser Eigenschaft zu ändern, können Sie eine der ChartDataPointCollection.DataSourceTypeFor<...>-Eigenschaften verwenden. Lese/Schreib [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```

Lese/Schreib-Objekt.

**Rückgabewert:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

Lese/Schreib-Objekt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.Object |  |