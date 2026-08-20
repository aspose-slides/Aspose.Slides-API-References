---
title: IBaseChartValue
second_title: Aspose.Slides for Java API Reference
description: एक चार्ट मान का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ibasechartvalue/
---```
public interface IBaseChartValue
```

एक चार्ट मान का प्रतिनिधित्व करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual. |
| [getData()](#getData--) | Read/write Object. |
| [setData(Object value)](#setData-java.lang.Object-) | Read/write Object. |
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```


Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual. In other words it specifies the type of value of the Data property. This property is read-only. For changing value of this property you can use one of the ChartDataPointCollection.DataSourceTypeFor<...> properties. पढ़ें/लिखें [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**रिटर्न:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public abstract void setDataSourceType(int value)
```


Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual. In other words it specifies the type of value of the Data property. This property is read-only. For changing value of this property you can use one of the ChartDataPointCollection.DataSourceTypeFor<...> properties. पढ़ें/लिखें [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```


पढ़ें/लिखें Object.

**रिटर्न:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```


पढ़ें/लिखें Object.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.Object |  |