---
title: set_ShowSeriesName()
second_title: Aspose.Slides C++ API 參考
description: 設定一個布林值，以指示圖表上資料標籤的系列名稱顯示行為。True 表示顯示系列名稱。False 表示隱藏。寫入 bool.
type: docs
weight: 183
url: /zh-hant/aspose.slides.charts/idatalabelformat/set_showseriesname/
---
## IDataLabelFormat::set_ShowSeriesName(bool) 方法

設定一個布林值，以指示圖表上資料標籤的系列名稱顯示行為。True 表示顯示系列名稱。False 表示隱藏。寫入 **bool**。

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowSeriesName(bool value)=0
```

## 備註

如果此 [DataLabelFormat](../../datalabelformat/) 物件的父項是 [DataLabelCollection](../../datalabelcollection/) 資料標籤集合，則此屬性會取得或設定 [DataLabelCollection](../../datalabelcollection/) 集合中新資料標籤的 ShowSeriesName 屬性的預設值。將此屬性設為某值時，也會將該值設定到 [DataLabelCollection](../../datalabelcollection/) 集合中所有資料標籤的 ShowSeriesName 屬性 (即 "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" 會導致所有 DataLabels[i].ShowSeriesName 等於 val)。

## 另見

* 類別 [IDataLabelFormat](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)