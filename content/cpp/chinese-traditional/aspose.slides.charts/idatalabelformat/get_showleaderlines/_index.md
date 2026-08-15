---
title: get_ShowLeaderLines()
second_title: Aspose.Slides for C++ API 參考文件
description: 表示指定圖表的資料標籤引導線顯示行為。True 表示顯示引導線，False 表示隱藏。讀取 bool。
type: docs
weight: 248
url: /zh-hant/aspose.slides.charts/idatalabelformat/get_showleaderlines/
---
## IDataLabelFormat::get_ShowLeaderLines() 方法


表示指定圖表的資料標籤引導線顯示行為。True 表示顯示引導線，False 表示隱藏。讀取 **bool**。

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowLeaderLines()=0
```

## 備註


如果此 [DataLabelFormat](../../datalabelformat/) 物件的父級是 [DataLabelCollection](../../datalabelcollection/) 資料標籤集合，則此屬性會取得或設定 [DataLabelCollection](../../datalabelcollection/) 集合中新資料標籤的 ShowLeaderLines 屬性的預設值。將此屬性設定為指定值，同時也會將該值設定給 [DataLabelCollection](../../datalabelcollection/) 集合中所有資料標籤的 ShowLeaderLines 屬性（例如 \"DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;\" 會使所有 DataLabels[i].ShowLeaderLines 等於 val）。 
## 另見

* 類別 [IDataLabelFormat](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)