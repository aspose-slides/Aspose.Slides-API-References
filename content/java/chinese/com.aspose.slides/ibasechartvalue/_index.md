---
title: IBaseChartValue
second_title: Aspose.Slides for Java API 参考
description: 表示图表的值。
type: docs
url: /zh/com.aspose.slides/ibasechartvalue/
---```
public interface IBaseChartValue
```

表示图表的值。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | 指定 AsCell、AsLiteralString 或 AsLiteralDouble 属性是否实际。 |
| [setDataSourceType(int value)](#setDataSourceType-int-) | 指定 AsCell、AsLiteralString 或 AsLiteralDouble 属性是否实际。 |
| [getData()](#getData--) | 读/写 Object。 |
| [setData(Object value)](#setData-java.lang.Object-) | 读/写 Object。 |
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```


指定 AsCell、AsLiteralString 或 AsLiteralDouble 属性是否实际。换句话说，它指定 Data 属性的值类型。此属性为只读。若要更改此属性的值，可使用 ChartDataPointCollection.DataSourceTypeFor<...> 系列属性之一。读/写 [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int))。

**返回：**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public abstract void setDataSourceType(int value)
```


指定 AsCell、AsLiteralString 或 AsLiteralDouble 属性是否实际。换句话说，它指定 Data 属性的值类型。此属性为只读。若要更改此属性的值，可使用 ChartDataPointCollection.DataSourceTypeFor<...> 系列属性之一。读/写 [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int))。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```


读/写 Object。

**返回：**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```


读/写 Object。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Object |  |