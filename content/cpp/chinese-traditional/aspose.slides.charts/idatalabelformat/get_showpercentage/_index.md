---
title: get_ShowPercentage()
second_title: Aspose.Slides C++ API 參考
description: 表示指定圖表的資料標籤百分比值顯示行為。True 表示顯示百分比值。False 表示隱藏。讀取 bool.
type: docs
weight: 196
url: /zh-hant/aspose.slides.charts/idatalabelformat/get_showpercentage/
---
## IDataLabelFormat::get_ShowPercentage() 方法


表示指定圖表的資料標籤百分比值顯示行為。True 表示顯示百分比值。False 表示隱藏。讀取 **bool**。

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowPercentage()=0
```

## 備註


如果此 [DataLabelFormat](../../datalabelformat/) 物件的父項是 [DataLabelCollection](../../datalabelcollection/) 資料標籤集合，則此屬性取得或設定在 [DataLabelCollection](../../datalabelcollection/) 集合中新資料標籤的 ShowPercentage 屬性的預設值。將此屬性設定為某值時，也會將此值設定給 [DataLabelCollection](../../datalabelcollection/) 集合中所有資料標籤的 ShowPercentage 屬性（即 "DataLabels.DefaultDataLabelFormat.ShowPercentage = val;" 會導致所有 DataLabels[i].ShowPercentage 等於 val）。 



## 另請參閱

* 類別 [IDataLabelFormat](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 程式庫 [Aspose.Slides](../../../)