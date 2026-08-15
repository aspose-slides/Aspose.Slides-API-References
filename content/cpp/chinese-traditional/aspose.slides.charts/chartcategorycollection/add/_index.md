---
title: Add()
second_title: Aspose.Slides for C++ API 參考
description: 如果集合中已存在類別，則返回它。否則從 IChartDataCell 建立新的圖表類別並將其加入集合。
type: docs
weight: 92
url: /zh-hant/aspose.slides.charts/chartcategorycollection/add/
---
## ChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) method

如果集合中已存在類別，則返回該類別。否則從 [IChartDataCell](../../ichartdatacell/) 建立新的圖表類別並將其加入集合。

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) 用於建立圖表類別。 |

### 回傳值

已新增或已存在的類別。

## ChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) method

從值建立新的 [ChartCategory](../../chartcategory/) 並將其加入集合。

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<System::Object> value) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 此值。 |

### 回傳值

已新增 [IChartCategory](../../ichartcategory/)。

## 備註

此方法會新增名稱為 AUTO_DATA 的工作表，並將所有值添加至其中。若使用 [ChartDataWorkbook](../../chartdataworkbook/) 來新增或編輯儲存格值，請確保不要使用此工作表。使用此方法新增的值的最大數量不得超過 16711680

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IChartCategory](../../ichartcategory/)
* 類別 [IChartDataCell](../../ichartdatacell/)
* 類別 [ChartCategoryCollection](../)
* 類別 [Object](../../../system/object/)
* 命名空間 [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)