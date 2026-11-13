---
title: IChartCategory
second_title: Aspose.Slides for Java API Reference
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
| [getUseCell()](#getUseCell--) | 如果为 true，则 AsCell 属性有效。 |
| [getAsCell()](#getAsCell--) | 返回或设置 IChartDataCell 对象。 |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | 返回或设置 IChartDataCell 对象。 |
| [getAsLiteral()](#getAsLiteral--) | 如果 UseCell 为 false，则返回或设置 AsLiteral。 |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | 如果 UseCell 为 false，则返回或设置 AsLiteral。 |
| [getValue()](#getValue--) | 如果 UseCell 为 true，则此属性表示 AsCell.Value 属性。 |
| [setValue(Object value)](#setValue-java.lang.Object-) | 如果 UseCell 为 true，则此属性表示 AsCell.Value 属性。 |
| [getCachedValue()](#getCachedValue--) | 获取图表类别的缓存值。 |
| [getGroupingLevels()](#getGroupingLevels--) | 受管理的图表类别分组级别值的容器。 |
| [remove()](#remove--) | 从图表中删除类别。 |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```

如果为 true，则 AsCell 属性有效。换句话说，工作表用于存储类别（此情况支持多层级类别）。如果为 false，则 AsLiteral 属性有效。换句话说，工作表不用于存储类别（此情况不支持多层级类别）。只读布尔。

--------------------

要更改此属性的值（针对集合中的所有类别），请将新值设置到 [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--) 属性。

**返回：**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```

返回或设置 IChartDataCell 对象。如果类别是多层级的，则使用第 “0” 级的 IChartDataCell 对象。读/写 [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**返回：**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```

返回或设置 IChartDataCell 对象。如果类别是多层级的，则使用第 “0” 级的 IChartDataCell 对象。读/写 [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```

如果 UseCell 为 false，则返回或设置 AsLiteral。读/写 Object。

**返回：**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```

如果 UseCell 为 false，则返回或设置 AsLiteral。读/写 Object。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Object |  |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

如果 UseCell 为 true，则此属性表示 AsCell.Value 属性。如果 UseCell 为 false，则此属性表示 AsLiteral 属性。读/写 Object。

**返回：**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

如果 UseCell 为 true，则此属性表示 AsCell.Value 属性。如果 UseCell 为 false，则此属性表示 AsLiteral 属性。读/写 Object。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Object |  |
### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
```

获取图表类别的缓存值。只读 [ICachedChartValue](../../com.aspose.slides/icachedchartvalue)。

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
> 
>      // 打印所有缓存的图表类别值。
>      for (IChartCategory category : chart.getChartData().getCategories())
>          System.out.println(category.getCachedValue().toString());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回：**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```

受管理的图表类别分组级别值的容器。多层级类别包含多个分组级别。分组级别索引从零开始。只读 [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)。

**返回：**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```

从图表中删除类别。