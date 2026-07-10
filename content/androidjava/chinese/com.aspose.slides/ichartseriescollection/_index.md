---
title: IChartSeriesCollection
second_title: Aspose.Slides Android 版 Java API 参考
description: 表示...的集合
type: docs
url: /zh/com.aspose.slides/ichartseriescollection/
---
**所有实现的接口：**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesCollection extends IGenericCollection<IChartSeries>
```

表示 [IChartSeries](../../com.aspose.slides/ichartseries) 的集合
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [add(int type)](#add-int-) | 创建新的图表系列并将其添加到集合中。 |
| [insert(int index, int type)](#insert-int-int-) | 创建新的图表系列并将其插入到集合中。 |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | 从 [IChartDataCell](../../com.aspose.slides/ichartdatacell) 创建新的图表系列并将其添加到集合中。 |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | 从 [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) 创建新的图表系列并将其添加到集合中。 |
| [add(String name, int type)](#add-java.lang.String-int-) | 从值创建新的图表系列并将其添加到集合中。 |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | 搜索指定的 [IChartSeries](../../com.aspose.slides/ichartseries)，并返回整个集合中首次出现的零基索引。 |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | 移除指定的值。 |
| [removeAt(int index)](#removeAt-int-) | 移除指定索引处的元素 |
| [clear()](#clear--) | 从集合中删除所有元素（包括图表样式）。 |

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

获取指定索引处的元素。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回：**
[IChartSeries](../../com.aspose.slides/ichartseries) - 指定索引处的元素。

### add(int type) {#add-int-}
```
public abstract IChartSeries add(int type)
```

创建新的图表系列并将其添加到集合中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | int | 系列的类型 |

**返回：**
[IChartSeries](../../com.aspose.slides/ichartseries) - 新的图表系列。

### insert(int index, int type) {#insert-int-int-}
```
public abstract IChartSeries insert(int index, int type)
```

创建新的图表系列并将其插入到集合中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入的索引 |
| type | int | 图表类型 [ChartType](../../com.aspose.slides/charttype) |

**返回：**
[IChartSeries](../../com.aspose.slides/ichartseries) - 新的图表系列 [IChartSeries](../../com.aspose.slides/ichartseries)

### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public abstract IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

从 [IChartDataCell](../../com.aspose.slides/ichartdatacell) 创建新的图表系列并将其添加到集合中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 包含系列名称的 Cell。 |
| type | int | 系列的类型 |

--------------------

如果该图表系列已经由同一 Cell 创建并已在集合中，则方法不执行任何操作并返回其索引。 |

**返回：**
[IChartSeries](../../com.aspose.slides/ichartseries) - 已添加的图表系列，或已在集合中的系列。

### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public abstract IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

从 [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) 创建新的图表系列并将其添加到集合中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | 包含系列名称的 Cell。 |
| type | int | 系列的类型 |

--------------------

如果该图表系列已经由同一 Cell 创建并已在集合中，则方法不执行任何操作并返回其索引。 |

**返回：**
[IChartSeries](../../com.aspose.slides/ichartseries) - 已添加的图表系列，或已在集合中的系列。

### add(String name, int type) {#add-java.lang.String-int-}
```
public abstract IChartSeries add(String name, int type)
```

从值创建新的图表系列并将其添加到集合中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 系列名称。 |
| type | int | 系列的类型 |

**返回：**
[IChartSeries](../../com.aspose.slides/ichartseries) - 已添加的图表系列。

### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public abstract int indexOf(IChartSeries value)
```

搜索指定的 [IChartSeries](../../com.aspose.slides/ichartseries)，并返回整个集合中首次出现的零基索引。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | 图表系列的值。 |

**返回：**
int - 如果找到，则返回整个 CollectionBase 中值首次出现的零基索引；否则返回 -1。

### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public abstract void remove(IChartSeries value)
```

移除指定的值。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | 该值。 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

删除指定索引处的元素

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 索引 |

### clear() {#clear--}
```
public abstract void clear()
```

从集合中删除所有元素（包括图表样式）。