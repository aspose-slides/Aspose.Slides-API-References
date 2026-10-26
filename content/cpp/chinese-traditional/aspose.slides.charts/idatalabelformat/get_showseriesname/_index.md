---
title: get_ShowSeriesName()
second_title: Aspose.Slides for C++ API 參考文件
description: 傳回布林值以指示圖表上資料標籤的系列名稱顯示行為。True 表示顯示系列名稱。False 表示隱藏。讀取 bool.
type: docs
weight: 170
url: /zh-hant/aspose.slides.charts/idatalabelformat/get_showseriesname/
---
## IDataLabelFormat::get_ShowSeriesName() 方法

傳回布林值以指示圖表上資料標籤的系列名稱顯示行為。True 表示顯示系列名稱。False 表示隱藏。讀取 **bool**。

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowSeriesName()=0
```

## 備註

如果此 [DataLabelFormat](../../datalabelformat/) 物件的父物件是 [DataLabelCollection](../../datalabelcollection/) 資料標籤集合，則此屬性會取得或設定 [DataLabelCollection](../../datalabelcollection/) 集合中新資料標籤的 ShowSeriesName 屬性的預設值。將此屬性設定為某個值時，也會將該值設定到 [DataLabelCollection](../../datalabelcollection/) 集合中所有資料標籤的 ShowSeriesName 屬性 (例如 "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" 會導致所有 DataLabels[i].ShowSeriesName 等於 val)。

## 另見

* 類別 [IDataLabelFormat](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)