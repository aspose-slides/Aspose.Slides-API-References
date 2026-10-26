---
title: get_ShowLabelValueFromCell()
second_title: Aspose.Slides C++ API 參考
description: 表示指定圖表的資料標籤儲存格值顯示行為。True 表示顯示儲存格值。False 表示隱藏。讀取 bool.
type: docs
weight: 274
url: /zh-hant/aspose.slides.charts/datalabelformat/get_showlabelvaluefromcell/
---
## DataLabelFormat::get_ShowLabelValueFromCell() method

表示指定圖表的資料標籤儲存格值顯示行為。True 表示顯示儲存格值。False 表示隱藏。讀取 **bool**。

```cpp
bool Aspose::Slides::Charts::DataLabelFormat::get_ShowLabelValueFromCell() override
```

## 備註

如果此 [DataLabelFormat](../) 物件的父項是 [DataLabelCollection](../../datalabelcollection/) 資料標籤集合，則此屬性取得或設定 [DataLabelCollection](../../datalabelcollection/) 集合中新資料標籤的 ShowLabelValueFromCell 屬性的預設值。將此屬性設定為某個值時，同時也會將此值設定給 [DataLabelCollection](../../datalabelcollection/) 集合中所有資料標籤的 ShowLabelValueFromCell 屬性（例如 \"DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;\" 會導致所有 DataLabels[i].ShowLabelValueFromCell 等於 val）。

## 另見

* 類別 [DataLabelFormat](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)