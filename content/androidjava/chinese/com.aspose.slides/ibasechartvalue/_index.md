---
title: IBaseChartValue
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a value of a chart.
type: docs
url: /zh/com.aspose.slides/ibasechartvalue/
---```
public interface IBaseChartValue
```

表示图表的一个值。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | 指定 AsCell、AsLiteralString 或 AsLiteralDouble 属性哪个是实际使用的。 |
| [setDataSourceType(int value)](#setDataSourceType-int-) | 指定 AsCell、AsLiteralString 或 AsLiteralDouble 属性哪个是实际使用的。 |
| [getData()](#getData--) | 读/写 对象。 |
| [setData(Object value)](#setData-java.lang.Object-) | 读/写 对象。 |
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

指定 AsCell、AsLiteralString 或 AsLiteralDouble 属性哪个是实际使用的。换句话说，它指定 Data 属性的值类型。此属性为只读。要更改此属性的值，可使用 ChartDataPointCollection.DataSourceTypeFor<...> 系列属性。读/写 [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int))。

**返回：**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public abstract void setDataSourceType(int value)
```

指定 AsCell、AsLiteralString 或 AsLiteralDouble 属性哪个是实际使用的。换句话说，它指定 Data 属性的值类型。此属性为只读。要更改此属性的值，可使用 ChartDataPointCollection.DataSourceTypeFor<...> 系列属性。读/写 [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int))。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```

读/写 对象。

**返回：**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

读/写 对象。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Object |  |