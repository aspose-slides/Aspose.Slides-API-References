---
title: Add()
second_title: Aspose.Slides for C++ API 參考文件
description: 將新儲存格新增至集合。
type: docs
weight: 53
url: /zh-hant/aspose.slides.charts/chartcellcollection/add/
---
## ChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) 方法

將新儲存格新增至集合。

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<IChartDataCell> cell) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| cell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 要新增的新儲存格。 |

## ChartCellCollection::Add(System::SharedPtr\<System::Object\>) 方法

從指定的值建立 [ChartDataCell](../../chartdatacell/)，並將其新增至集合。

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<System::Object> value) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 該值。 |
## 備註

此方法會新增名稱為 AUTO_DATA 的工作表，並將所有值新增至該工作表。如果您使用 [ChartDataWorkbook](../../chartdataworkbook/) 來新增或編輯 [Cell](../../../aspose.slides/cell/) 值，請確保不要使用此工作表。使用此方法新增的值的最大數量不得超過 16711680

## 另請參閱

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IChartDataCell](../../ichartdatacell/)
* 類別 [ChartCellCollection](../)
* 類別 [Object](../../../system/object/)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)