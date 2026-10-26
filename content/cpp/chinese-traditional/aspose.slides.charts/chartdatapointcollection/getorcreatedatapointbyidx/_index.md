---
title: GetOrCreateDataPointByIdx()
second_title: Aspose.Slides for C++ API 參考
description: "如果集合已經包含索引 index 的資料點，則返回該資料點。如果集合不包含索引 index ==N 的資料點（當此集合中的資料點數量小於或等於 N 時），則會新增缺少的資料點，並返回最後一個（具有請求的索引）。例如，集合的索引為 {0, 1, 2}，請求的索引為 5。此時方法會新增缺少的資料點：{0, 1, 2, 3, 4, 5}。並返回索引為 5 的資料點。"
type: docs
weight: 170
url: /zh-hant/aspose.slides.charts/chartdatapointcollection/getorcreatedatapointbyidx/
---
## ChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t) 方法

如果集合已經包含索引為 *index* 的資料點，則返回此資料點。如果集合不包含索引為 *index* ==N（當此集合中的資料點數量小於或等於 N 時），則會新增缺少的資料點，並返回最後一個（即具有請求索引的資料點）。例如，集合的索引為 {0, 1, 2}，請求的索引為 5。此時方法會新增缺少的資料點：{0, 1, 2, 3, 4, 5}，並返回索引為 5 的資料點。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t index) override
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | **uint32_t** | 索引。 |

### 返回值

返回具有請求索引的資料點。

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IChartDataPoint](../../ichartdatapoint/)
* 類別 [ChartDataPointCollection](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)