---
title: BaseChartValue
second_title: Aspose.Slides for Android 通过 Java API 参考
description: 表示图表的一个值。
type: docs
url: /zh/com.aspose.slides/basechartvalue/
---
**继承:**
java.lang.Object

**所有实现的接口:**
[com.aspose.slides.IBaseChartValue](../../com.aspose.slides/ibasechartvalue), com.aspose.slides.IDOMObject
```
public abstract class BaseChartValue implements IBaseChartValue, IDOMObject
```

表示图表的一个值。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | 指定在子类中 AsCell、AsCells、AsLiteralString 或 AsLiteralDouble 属性是否有效。 |
| [setDataSourceType(int value)](#setDataSourceType-int-) | 指定在子类中 AsCell、AsCells、AsLiteralString 或 AsLiteralDouble 属性是否有效。 |
| [getData()](#getData--) | 数据。 |
| [setData(Object value)](#setData-java.lang.Object-) | 数据。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

指定在子类中 AsCell、AsCells、AsLiteralString 或 AsLiteralDouble 属性是否有效。换句话说，它指定 Data 属性的值类型。可读写 [DataSourceType](../../com.aspose.slides/datasourcetype)。

--------------------

对于 ChartDataPointCollection 中的点，此属性是只读的。在这种情况下，要更改此属性的值，可使用 ChartDataPointCollection.DataSourceTypeFor<...> 属性之一。

**返回:**
int

### setDataSourceType(int value) {#setDataSourceType-int-}
```
public final void setDataSourceType(int value)
```

指定在子类中 AsCell、AsCells、AsLiteralString 或 AsLiteralDouble 属性是否有效。换句话说，它指定 Data 属性的值类型。可读写 [DataSourceType](../../com.aspose.slides/datasourcetype)。

--------------------

对于 ChartDataPointCollection 中的点，此属性是只读的。在这种情况下，要更改此属性的值，可使用 ChartDataPointCollection.DataSourceTypeFor<...> 属性之一。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```

数据。可读写 Object。

**返回:**
java.lang.Object

### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

数据。可读写 Object。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Object |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。只读 IDOMObject。

**返回:**
com.aspose.slides.IDOMObject