---
title: DataLabelCollection
second_title: Aspose.Sildes for PHP 通过 Java API 参考
description: 
type: docs
url: /zh/aspose.slides/datalabelcollection/
---
## DataLabelCollection 类

 表示系列标签。

### getChart {#getChart}

| 名称 | 描述 |
| --- | --- |
| getChart () | 返回父图表。只读 IChart。 |

**返回:**
[Chart](../chart)


---


### getCount {#getCount}

| 名称 | 描述 |
| --- | --- |
| getCount () | 获取集合中所有数据标签的数量。只读 int。 |

**返回:**
int


---


### getCountOfVisibleDataLabels {#getCountOfVisibleDataLabels}

| 名称 | 描述 |
| --- | --- |
| getCountOfVisibleDataLabels () | 获取集合中可见数据标签的数量。只读 int。 |

**返回:**
int


---


### getDefaultDataLabelFormat {#getDefaultDataLabelFormat}

| 名称 | 描述 |
| --- | --- |
| getDefaultDataLabelFormat () | 获取默认数据标签格式。只读 IDataLabelFormat。 |

**返回:**
[DataLabelFormat](../datalabelformat)


---


### getLeaderLinesFormat {#getLeaderLinesFormat}

| 名称 | 描述 |
| --- | --- |
| getLeaderLinesFormat () | 表示数据标签引导线格式。只读 IChartLinesFormat。 |

**返回:**
[ChartLinesFormat](../chartlinesformat)


---


### getParentSeries {#getParentSeries}

| 名称 | 描述 |
| --- | --- |
| getParentSeries () | 获取父系列。只读 IChartSeries。 |

**返回:**
[ChartSeries](../chartseries)


---


### getPresentation {#getPresentation}

| 名称 | 描述 |
| --- | --- |
| getPresentation () | 返回 FillFormat 的父演示文稿。只读 IPresentation。 |

**返回:**
[Presentation](../presentation)


---


### getSlide {#getSlide}

| 名称 | 描述 |
| --- | --- |
| getSlide () | 返回 FillFormat 的父幻灯片。只读 BaseSlide。 |

**返回:**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### get_Item {#get_Item}

| 名称 | 描述 |
| --- | --- |
| get_Item (int) | 获取具有指定索引的数据点的数据标签。访问数据标签的另一种方式是：- series.getDataPoints().get_Item(i).getLabel() - 管理标签属性。 |

**返回:**
[DataLabel](../datalabel)


---


### hide {#hide}

| 名称 | 描述 |
| --- | --- |
| hide () | 通过将 DefaultDataLabelFormat 属性的所有 Show* 标志（如 ShowValue 等）设为 false，使数据标签默认隐藏。执行后 IsVisible 为 false。如果默认情况下数据标签不可见（IsVisible 为 false），可以通过将 DefaultDataLabelFormat 属性的 Show* 标志设为 true，使数据标签“默认可见”。 |

**返回:**
void


---


### indexOf {#indexOf}

| 名称 | 描述 |
| --- | --- |
| indexOf ([DataLabel](../datalabel)) | 返回集合中指定 DataLabel 的索引。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| value | [DataLabel](../datalabel) | 要查找的 DataLabel。 |

**返回:**
int


---


### isVisible {#isVisible}

| 名称 | 描述 |
| --- | --- |
| isVisible () | False 表示数据标签默认不可见（因此 DefaultDataLabelFormat 属性的所有 Show* 标志（ShowValue 等）均为 false）。只读 boolean。如果数据标签默认可见，您可以使用 Hide() 方法使其默认隐藏。但是，如果数据标签默认不可见（IsVisible 为 false），可以通过将 DefaultDataLabelFormat 属性的 Show* 标志设为 true，使数据标签“默认可见”。 |

**返回:**
boolean


---


### iterator {#iterator}

| 名称 | 描述 |
| --- | --- |
| iterator () | 返回遍历集合的枚举器。 |

**返回:**



---


### iteratorJava {#iteratorJava}

| 名称 | 描述 |
| --- | --- |
| iteratorJava () | 返回整个集合的 java 迭代器。 |

**返回:**



---