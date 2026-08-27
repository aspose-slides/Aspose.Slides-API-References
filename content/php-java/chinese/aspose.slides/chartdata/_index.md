---
title: ChartData
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs
url: /zh/aspose.slides/chartdata/
---
## ChartData 类

 表示用于图表绘制的数据。

### getCategories {#getCategories}

| 名称 | 描述 |
| --- | --- |
| getCategories () | 获取主要类别（如果 #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) 属性为 false，则获取主类别和次要类别）。只读 IChartCategoryCollection。如果 #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) 属性为 false，则 ( #getSecondaryCategories) 属性返回 null，且此 #getCategories 属性中的数据同时用于主系列和次要系列。如果 #getUseSecondaryCategories/ #setUseSecondaryCategoriesboolean) 属性为 true，则 ( #getSecondaryCategories) 属性中的数据用于次要系列，而此 #getCategories 属性中的数据用于主系列。 |

 **返回：**
[ChartCategoryCollection](../chartcategorycollection)

---

### getChartDataWorkbook {#getChartDataWorkbook}

| 名称 | 描述 |
| --- | --- |
| getChartDataWorkbook () | 获取用于创建图表系列或类别的单元格工厂。只读 IChartDataWorkbook。 |

 **返回：**
[ChartDataWorkbook](../chartdataworkbook)

 **异常**

| 错误 | 条件 |
| --- | --- |
| InvalidOperationException | 当不支持工作簿格式时抛出。 |

---

### getDataSourceType {#getDataSourceType}

| 名称 | 描述 |
| --- | --- |
| getDataSourceType () | 表示外部数据源时的外部工作簿路径，否则为 null。 |

 **返回：**
int

---

### getEmbeddedWorkbookType {#getEmbeddedWorkbookType}

| 名称 | 描述 |
| --- | --- |
| getEmbeddedWorkbookType () | 获取嵌入式工作簿的类型。如果 DataSourceType( #getDataSourceType) 为 ChartDataSourceType#ExternalWorkbook，则返回 WorkbookType#NotDefined。只读 WorkbookType。 |

 **返回：**
int

---

### getExternalWorkbookPath {#getExternalWorkbookPath}

| 名称 | 描述 |
| --- | --- |
| getExternalWorkbookPath () | 表示图表的数据源。 |

 **返回：**
String

---

### getRange {#getRange}

| 名称 | 描述 |
| --- | --- |
| getRange () | 获取图表数据范围。 |

 **返回：**
String

 **异常**

| 错误 | 条件 |
| --- | --- |
| InvalidOperationException | 当图表未使用工作簿作为数据源时抛出。 |

---

### getSecondaryCategories {#getSecondaryCategories}

| 名称 | 描述 |
| --- | --- |
| getSecondaryCategories () | 获取次要类别（如果 #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) 属性为 true）。只读 IChartCategoryCollection。如果 #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) 属性为 false，则此 ( #getSecondaryCategories) 属性返回 null，且 #getCategories 属性中的数据同时用于主系列和次系列。如果 #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) 属性为 true，则此 #getSecondaryCategories 属性中的数据用于次系列，而 #getCategories 属性中的数据用于主系列。 |

 **返回：**
[ChartCategoryCollection](../chartcategorycollection)

---

### getSeries {#getSeries}

| 名称 | 描述 |
| --- | --- |
| getSeries () | 获取系列。只读 IChartSeriesCollection。 |

 **返回：**
[ChartSeriesCollection](../chartseriescollection)

---

### getSeriesGroups {#getSeriesGroups}

| 名称 | 描述 |
| --- | --- |
| getSeriesGroups () | 获取系列组。只读 IChartSeriesGroupCollection。1) 每个系列组包含具有可组合类型的系列。可组合系列类型的组由 CombinableSeriesTypesGroup 枚举定义和描述。此外，每个系列组包含绘制在主坐标轴或次坐标轴上的系列（同一组中不同时包含两者）。因此，系列分组的原则是按上述类型组以及按主/次坐标轴绘制类型进行分组。2) 系列组包含一些对组内每个系列都公共的系列属性（“系列组属性”）。ChartSeriesGroup 类中的“系列组属性”是读写的。每个“系列组属性”在 ChartSeries 类中可以有只读的投影。 |

 **返回：**
ChartSeriesGroupCollection

---

### getUseSecondaryCategories {#getUseSecondaryCategories}

| 名称 | 描述 |
| --- | --- |
| getUseSecondaryCategories () | 如果为 false，则 #getSecondaryCategories 属性返回 null，且 #getCategories 属性中的数据同时用于主系列和次系列。如果为 true，则 #getSecondaryCategories 属性中的数据用于次系列，而 #getCategories 属性中的数据用于主系列。读写 boolean。 |

 **返回：**
boolean

---

### readWorkbookStream {#readWorkbookStream}

| 名称 | 描述 |
| --- | --- |
| readWorkbookStream () | 将内部包含的 Excel 工作簿写入内存流。 |

 **返回：**
byte

---

### setExternalWorkbook {#setExternalWorkbook}

| 名称 | 描述 |
| --- | --- |
| setExternalWorkbook (String) | 设置外部工作簿作为图表的数据源。图表数据将从目标工作簿更新。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| workbookPath | String | 目标工作簿的路径 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
| InvalidOperationException | 外部工作簿不可用或无法加载。 |

---

### setExternalWorkbook {#setExternalWorkbook}

| 名称 | 描述 |
| --- | --- |
| setExternalWorkbook (String, boolean) | 设置外部工作簿作为图表的数据源。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| workbookPath | String | 目标工作簿的路径 |
| updateChartData | boolean | 如果值为 false，则仅更新工作簿路径。图表数据不会从目标工作簿加载和更新。当目标工作簿不存在或不可用时可使用此方式。如果值为 true，则图表数据将从目标工作簿更新。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
| InvalidOperationException | 外部工作簿不可用或无法加载。 |

---

### setRange {#setRange}

| 名称 | 描述 |
| --- | --- |
| setRange (String) | 设置图表数据范围。系列和类别将依据新的数据范围进行更新。如果数据范围内的系列数量大于图表数据中的系列数量，则会在集合末尾添加与当前集合中最后一个系列相同类型的额外系列。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| formula | String | 单元格数据范围公式。例如：“Sheet1!$A$1:$C$4”, “SomeSheetName!A1:B100”, “Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5”。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | formula 格式不正确。 |

---

### setUseSecondaryCategories {#setUseSecondaryCategories}

| 名称 | 描述 |
| --- | --- |
| setUseSecondaryCategories (boolean) | 如果为 false，则 #getSecondaryCategories 属性返回 null，且 #getCategories 属性中的数据同时用于主系列和次系列。如果为 true，则 #getSecondaryCategories 属性中的数据用于次系列，而 #getCategories 属性中的数据用于主系列。读写 boolean。 |

 **返回：**
void

---

### switchRowColumn {#switchRowColumn}

| 名称 | 描述 |
| --- | --- |
| switchRowColumn () | 交换轴向上的数据。绘制在 X 轴上的数据将移动到 Y 轴，反之亦然。 |

 **返回：**
void

---

### writeWorkbookStream {#writeWorkbookStream}

| 名称 | 描述 |
| --- | --- |
| writeWorkbookStream (byte[]) | 使用用户指定的值初始化内部包含的 Excel 工作簿。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| ms | byte[] | 用户提供的包含整个 Excel 工作簿的流。 |

 **返回：**
void

---