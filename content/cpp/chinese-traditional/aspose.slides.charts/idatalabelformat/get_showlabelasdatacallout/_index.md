---
title: get_ShowLabelAsDataCallout()
second_title: Aspose.Slides for C++ API 參考文件
description: 確定指定圖表的資料標籤是顯示為資料標註還是顯示為資料標籤。
type: docs
weight: 274
url: /zh-hant/aspose.slides.charts/idatalabelformat/get_showlabelasdatacallout/
---
## IDataLabelFormat::get_ShowLabelAsDataCallout() 方法

確定指定圖表的資料標籤是顯示為資料標註還是顯示為資料標籤。

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowLabelAsDataCallout()=0
```

## 備註

如果此 [DataLabelFormat](../../datalabelformat/) 物件的父項是 [DataLabelCollection](../../datalabelcollection/) 資料標籤集合，則此屬性取得或設定 [DataLabelCollection](../../datalabelcollection/) 集合中新資料標籤的 ShowLabelAsDataCallout 屬性的預設值。以此值設定此屬性亦會將此值設定為 [DataLabelCollection](../../datalabelcollection/) 集合中所有資料標籤的 ShowLabelAsDataCallout 屬性 (即 "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" 會導致所有 DataLabels[i].ShowLabelAsDataCallout 等於 val)。

## 另見

* 類別 [IDataLabelFormat](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)