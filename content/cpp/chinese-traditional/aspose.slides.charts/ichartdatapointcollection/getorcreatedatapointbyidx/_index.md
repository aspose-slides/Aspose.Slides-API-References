---
title: GetOrCreateDataPointByIdx()
second_title: Aspose.Slides C++ API 參考
description: "如果集合已經包含索引為 index 的資料點，則返回該資料點。若集合不包含索引為 index ==N 的資料點（當此集合中的資料點數量小於或等於 N 時），則會新增不足的資料點，並返回最後一個（即具有請求的索引）。例如，集合的索引為 {0, 1, 2}，請求的索引為 5。則方法會新增不足的資料點：{0, 1, 2, 3, 4, 5}，並返回索引為 5 的資料點。"
type: docs
weight: 131
url: /zh-hant/aspose.slides.charts/ichartdatapointcollection/getorcreatedatapointbyidx/
---
## IChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t) 方法


如果集合已經包含索引為 *index* 的資料點，則返回此資料點。若集合不包含索引為 *index* ==N 的資料點（當此集合中的資料點數量小於或等於 N 時），則會新增不足的資料點，並返回最後一個（即具有請求的索引）。例如，集合索引為 {0, 1, 2}，請求的索引為 5。此時方法會新增不足的資料點：{0, 1, 2, 3, 4, 5}。並返回索引為 5 的資料點。

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t index)=0
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | **uint32_t** | 索引。 |

### 回傳值

返回具有請求索引的資料點。

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IChartDataPoint](../../ichartdatapoint/)
* 類別 [IChartDataPointCollection](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)