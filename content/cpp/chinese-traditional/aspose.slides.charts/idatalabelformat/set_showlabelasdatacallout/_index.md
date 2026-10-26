---
title: set_ShowLabelAsDataCallout()
second_title: Aspose.Slides C++ API 參考
description: 判斷指定圖表的資料標籤是顯示為資料標註還是顯示為資料標籤。
type: docs
weight: 287
url: /zh-hant/aspose.slides.charts/idatalabelformat/set_showlabelasdatacallout/
---
## IDataLabelFormat::set_ShowLabelAsDataCallout(bool) 方法

確定指定圖表的資料標籤將顯示為資料標注或作為資料標籤。

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowLabelAsDataCallout(bool value)=0
```

## 備註

如果此 [DataLabelFormat](../../datalabelformat/) 物件的父項是 [DataLabelCollection](../../datalabelcollection/) 資料標籤集合，則此屬性取得或設定 [DataLabelCollection](../../datalabelcollection/) 集合中新資料標籤的 ShowLabelAsDataCallout 屬性的預設值。將此屬性設為某值時，也會將此值設定給 [DataLabelCollection](../../datalabelcollection/) 集合中所有資料標籤的 ShowLabelAsDataCallout 屬性（例如 "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" 會使所有 DataLabels[i].ShowLabelAsDataCallout 等於 val）。

## 另請參閱

* 類別 [IDataLabelFormat](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)