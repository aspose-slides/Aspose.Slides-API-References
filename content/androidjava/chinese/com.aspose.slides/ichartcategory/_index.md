---
title: IChartCategory
second_title: Aspose.Slides for Android via Java API Reference
description: 表示图表类别。
type: docs
url: /zh/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

表示图表类别。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getUseCell()](#getUseCell--) | 如果为 true，则 AsCell 属性为实际值。 |
| [getAsCell()](#getAsCell--) | 返回或设置 IChartDataCell 对象。 |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | 返回或设置 IChartDataCell 对象。 |
| [getAsLiteral()](#getAsLiteral--) | 如果 UseCell 为 false，则返回或设置 AsLiteral。 |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | 如果 UseCell 为 false，则返回或设置 AsLiteral。 |
| [getValue()](#getValue--) | 如果 UseCell 为 true，则此属性表示 AsCell.Value 属性。 |
| [setValue(Object value)](#setValue-java.lang.Object-) | 如果 UseCell 为 true，则此属性表示 AsCell.Value 属性。 |
| [getGroupingLevels()](#getGroupingLevels--) | 图表类别分组级别值的托管容器。 |
| [remove()](#remove--) | 从图表中删除类别。 |

### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```

如果为 true，则 AsCell 属性为实际值。换句话说，工作表用于存储类别（此情况下支持多层级类别）。如果为 false，则 AsLiteral 属性为实际值。换句话说，工作表不用于存储类别（此情况下不支持多层级类别）。只读布尔值。

--------------------

要更改此属性的值（针对集合中的所有类别），请将新值设置到 [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--) 属性。

**返回:**  
boolean

### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```

返回或设置 IChartDataCell 对象。如果类别是多层级的，则在级别 "0" 使用 IChartDataCell 对象。可读写 [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**返回:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```

返回或设置 IChartDataCell 对象。如果类别是多层级的，则在级别 "0" 使用 IChartDataCell 对象。可读写 [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```

如果 UseCell 为 false，则返回或设置 AsLiteral。可读写 Object。

**返回:**  
java.lang.Object

### setAsLiteral(java.lang.Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```

如果 UseCell 为 false，则返回或设置 AsLiteral。可读写 Object。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```

如果 UseCell 为 true，则此属性表示 AsCell.Value 属性。如果 UseCell 为 false，则此属性表示 AsLiteral 属性。可读写 Object。

**返回:**  
java.lang.Object

### setValue(java.lang.Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

如果 UseCell 为 true，则此属性表示 AsCell.Value 属性。如果 UseCell 为 false，则此属性表示 AsLiteral 属性。可读写 Object。

**参数:**  
| 参数 | 类型 | 描述 |
| --- ... | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```

图表类别分组级别值的托管容器。多层级类别包含多个分组级别。分组级别的索引从零开始。只读 [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)。

**返回:**  
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)

### remove() {#remove--}
```
public abstract void remove()
```

从图表中删除类别。