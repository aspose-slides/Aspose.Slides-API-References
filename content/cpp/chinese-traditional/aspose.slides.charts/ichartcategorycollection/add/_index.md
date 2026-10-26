---
title: Add()
second_title: Aspose.Slides for C++ API 參考
description: 如果集合中已存在此類別，則返回它。否則從 IChartDataCell 建立新圖表類別並將其加入集合。
type: docs
weight: 53
url: /zh-hant/aspose.slides.charts/ichartcategorycollection/add/
---
## IChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) 方法

如果集合中已存在此類別，則返回它。否則從 [IChartDataCell](../../ichartdatacell/) 建立新的圖表類別並將其加入集合。

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) 用於建立圖表類別。 |

### 返回值

已新增或現有的類別。

## IChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) 方法

從值建立新的 [IChartCategory](../../ichartcategory/) 並將其加入集合。

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<System::Object> value)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 該值。 |

### 返回值

已新增 [IChartCategory](../../ichartcategory/)。

## 備註

此方法會新增名稱為 AUTO_DATA 的工作表，並將所有值加入其中。如果您使用 [IChartDataWorkbook](../../ichartdataworkbook/) 來新增或編輯儲存格值，請確保不要使用此工作表。使用此方法新增的值的最大數量不得超過 16711680

## 另見

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IChartCategory](../../ichartcategory/)
* 類別 [IChartDataCell](../../ichartdatacell/)
* 類別 [IChartCategoryCollection](../)
* 類別 [Object](../../../system/object/)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)