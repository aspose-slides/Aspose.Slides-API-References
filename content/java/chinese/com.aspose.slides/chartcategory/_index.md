---
title: ChartCategory
second_title: Aspose.Slides Java API 参考
description: 表示图表类别。
type: docs
url: /zh/com.aspose.slides/chartcategory/
---
**继承:**  
java.lang.Object

**所有实现的接口:**  
[com.aspose.slides.IChartCategory](../../com.aspose.slides/ichartcategory), com.aspose.slides.IDOMObject  
```
public class ChartCategory implements IChartCategory, IDOMObject
```

表示图表类别。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getUseCell()](#getUseCell--) | 如果为 true，则 AsCell 属性为实际值。 |
| [getAsCell()](#getAsCell--) | 返回或设置 IChartDataCell 对象。 |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | 返回或设置 IChartDataCell 对象。 |
| [getAsLiteral()](#getAsLiteral--) | 返回或设置 AsLiteral 对象。 |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | 返回或设置 AsLiteral 对象。 |
| [getValue()](#getValue--) | 如果 UseCell 为 true，则此属性表示 AsCell.Value 属性。 |
| [setValue(Object value)](#setValue-java.lang.Object-) | 如果 UseCell 为 true，则此属性表示 AsCell.Value 属性。 |
| [getGroupingLevels()](#getGroupingLevels--) | 图表类别分组级别值的受管容器。 |
| [getCachedValue()](#getCachedValue--) | 获取图表类别的缓存值。 |
| [remove()](#remove--) | 从图表中删除类别。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```

如果为 true，则 AsCell 属性为实际值。换句话说，工作表用于存储类别（此情况支持多层级类别）。如果为 false，则 AsLiteral 属性为实际值。换句话说，工作表不用于存储类别（此情况不支持多层级类别）。只读布尔值。

要更改此属性的值（对集合中的所有类别），请将新值设置到 ChartCategoryCollection.UseCells 属性。

**返回：**  
boolean

### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

返回或设置 IChartDataCell 对象。如果类别是多层级的，则使用层级 “0” 的 IChartDataCell 对象。读/写 [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**返回：**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

返回或设置 IChartDataCell 对象。如果类别是多层级的，则使用层级 “0” 的 IChartDataCell 对象。读/写 [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```

返回或设置 AsLiteral 对象。读/写 Object。

**返回：**  
java.lang.Object

### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```

返回或设置 AsLiteral 对象。读/写 Object。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

如果 UseCell 为 true，则此属性表示 AsCell.Value 属性。如果 UseCell 为 false，则此属性表示 AsLiteral 属性。读/写 Object。

**返回：**  
java.lang.Object

### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

如果 UseCell 为 true，则此属性表示 AsCell.Value 属性。如果 UseCell 为 false，则此属性表示 AsLiteral 属性。读/写 Object。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```

图表类别分组级别值的受管容器。多层级类别包含多个分组级别。分组级别索引从零开始。只读 [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)。

**返回：**  
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)

### getCachedValue() {#getCachedValue--}
```
public final ICachedChartValue getCachedValue()
```

获取图表类别的缓存值。只读 [ICachedChartValue](../../com.aspose.slides/icachedchartvalue)。

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx")
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
> 
>      // 打印所有缓存的图表类别值。
>      for (IChartCategory category : chart.getChartData().getCategories())
>          System.out.println(category.getCachedValue().toString());
>  } finally {
>      pres.dispose();
>  }
> ```

**返回：**  
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### remove() {#remove--}
```
public final void remove()
```

从图表中删除类别。

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。只读 IDOMObject。

**返回：**  
com.aspose.slides.IDOMObject