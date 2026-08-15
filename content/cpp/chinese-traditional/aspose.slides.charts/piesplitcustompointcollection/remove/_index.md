---
title: Remove()
second_title: Aspose.Slides for C++ API 參考
description: 從集合中移除項目。
type: docs
weight: 79
url: /zh-hant/aspose.slides.charts/piesplitcustompointcollection/remove/
---
## PieSplitCustomPointCollection::Remove(const System::SharedPtr\<IChartDataPoint\>\&) 方法


從集合中移除項目。

```cpp
bool Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(const System::SharedPtr<IChartDataPoint> &dataPoint) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| dataPoint | const [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataPoint](../../ichartdatapoint/)\>\& | 要移除的資料點。 |

### 傳回值

若項目成功移除則返回 true；否則返回 false。如果在 [System::Collections::Generic::List](../../../system.collections.generic/list/){T} 中未找到項目，則此方法也返回 false。

## PieSplitCustomPointCollection::Remove(int32_t) 方法


根據父系列點集合中的索引從集合中移除項目。

```cpp
void Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(int32_t dataPointIndex) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| dataPointIndex | **int32_t** | 父系列點集合中資料點的索引。 |

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IChartDataPoint](../../ichartdatapoint/)
* 類別 [PieSplitCustomPointCollection](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)