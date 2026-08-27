---
title: ChartCategory
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs
url: /zh/aspose.slides/chartcategory/
---
## ChartCategory 类

 表示图表类别。
 
### getAsCell {#getAsCell}}

| 名称 | 描述 |
| --- | --- |
| getAsCell () | 返回或设置 IChartDataCell 对象。如果类别是多级的，则在级别 "0" 使用 IChartDataCell 对象。读/写 IChartDataCell。 |

 **返回：**
[ChartDataCell](../chartdatacell)


---


### getAsLiteral {#getAsLiteral}}

| 名称 | 描述 |
| --- | --- |
| getAsLiteral () | 返回或设置 AsLiteral 对象。读/写 Object。 |

 **返回：**
Object


---


### getGroupingLevels {#getGroupingLevels}}

| 名称 | 描述 |
| --- | --- |
| getGroupingLevels () | 受管理的图表类别分组级别值的容器。多级类别包含多个分组级别。分组级别的索引从零开始。只读 IChartCategoryLevelsManager。 |

 **返回：**
[ChartCategoryLevelsManager](../chartcategorylevelsmanager)


---


### getUseCell {#getUseCell}}

| 名称 | 描述 |
| --- | --- |
| getUseCell () | 如果为 true 则 AsCell 属性有效。换句话说，工作表用于存储类别（此情况支持多级类别）。如果为 false 则 AsLiteral 属性有效。换句话说，工作表不用于存储类别（此情况不支持多级类别）。只读 boolean。要更改此属性的值（针对集合中的所有类别），请将新值设置到 ChartCategoryCollection.UseCells 属性。 |

 **返回：**
boolean


---


### getValue {#getValue}}

| 名称 | 描述 |
| --- | --- |
| getValue () | 如果 UseCell 为 true，则此属性表示 AsCell.Value 属性。如果 UseCell 为 false，则此属性表示 AsLiteral 属性。读/写 Object。 |

 **返回：**
Object


---


### remove {#remove}}

| 名称 | 描述 |
| --- | --- |
| remove () | 从图表中移除类别。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
| PptxEditException | 如果类别已从图表中移除，则抛出。 |


---


### setAsCell {#setAsCell}}

| 名称 | 描述 |
| --- | --- |
| setAsCell ([ChartDataCell](../chartdatacell)) | 返回或设置 IChartDataCell 对象。如果类别是多级的，则在级别 "0" 使用 IChartDataCell 对象。读/写 IChartDataCell。 |

 **返回：**
void


---


### setAsLiteral {#setAsLiteral}}

| 名称 | 描述 |
| --- | --- |
| setAsLiteral (Object) | 返回或设置 AsLiteral 对象。读/写 Object。 |

 **返回：**
void


---


### setValue {#setValue}}

| 名称 | 描述 |
| --- | --- |
| setValue (Object) | 如果 UseCell 为 true，则此属性表示 AsCell.Value 属性。如果 UseCell 为 false，则此属性表示 AsLiteral 属性。读/写 Object。 |

 **返回：**
void


---