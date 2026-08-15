---
title: Add()
second_title: Aspose.Slides for C++ API 參考
description: 新增儲存格至集合。
type: docs
weight: 53
url: /zh-hant/aspose.slides.charts/ichartcellcollection/add/
---
## IChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) 方法

新增儲存格至集合。

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 要新增的儲存格。 |

## IChartCellCollection::Add(System::SharedPtr\<System::Object\>) 方法

從指定的值建立 [IChartDataCell](../../ichartdatacell/) 並將其加入集合。

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<System::Object> value)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 值。 |

## 備註

此方法會新增名稱為 AUTO_DATA 的工作表，並將所有值加入該工作表。若使用 [IChartDataWorkbook](../../ichartdataworkbook/) 來新增或編輯 [Cell](../../../aspose.slides/cell/) 值，請確保不要使用此工作表。使用此方法加入的值的最大數量不得超過 16711680。

## 參見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IChartDataCell](../../ichartdatacell/)
* 類別 [IChartCellCollection](../)
* 類別 [Object](../../../system/object/)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)