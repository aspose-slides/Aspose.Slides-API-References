---
title: IBaseChartValue
second_title: Aspose.Slides für Android über Java API Referenz
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
| [getDataSourceType()](#getDataSourceType--) | Gibt an, ob die AsCell- oder AsLiteralString- oder AsLiteralDouble-Eigenschaft tatsächlich ist. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Gibt an, ob die AsCell- oder AsLiteralString- oder AsLiteralDouble-Eigenschaft tatsächlich ist. |
| [getData()](#getData--) | Lesen/Schreiben Object. |
| [setData(Object value)](#setData-java.lang.Object-) | Lesen/Schreiben Object. |
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```


Gibt an, ob die AsCell- oder AsLiteralString- oder AsLiteralDouble-Eigenschaft tatsächlich ist. In anderen Worten gibt es den Typ des Werts der Data-Eigenschaft an. Diese Eigenschaft ist schreibgeschützt. Zum Ändern des Werts dieser Eigenschaft können Sie eine der ChartDataPointCollection.DataSourceTypeFor<...>-Eigenschaften verwenden. Lesen/Schreiben [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Rückgabewert:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public abstract void setDataSourceType(int value)
```


Gibt an, ob die AsCell- oder AsLiteralString- oder AsLiteralDouble-Eigenschaft tatsächlich ist. In anderen Worten gibt es den Typ des Werts der Data-Eigenschaft an. Diese Eigenschaft ist schreibgeschützt. Zum Ändern des Werts dieser Eigenschaft können Sie eine der ChartDataPointCollection.DataSourceTypeFor<...>-Eigenschaften verwenden. Lesen/Schreiben [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```


Lesen/Schreiben Object.

**Rückgabewert:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```


Lesen/Schreiben Object.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.Object |  |