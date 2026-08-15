---
title: set_ShowLabelValueFromCell()
second_title: Aspose.Slides for C++ API 參考
description: 表示指定圖表的資料標籤儲存格值顯示行為。True 會顯示儲存格值。False 會隱藏。寫入 bool。
type: docs
weight: 313
url: /zh-hant/aspose.slides.charts/idatalabelformat/set_showlabelvaluefromcell/
---
## IDataLabelFormat::set_ShowLabelValueFromCell(bool) 方法

表示指定圖表的資料標籤儲存格值顯示行為。True 會顯示儲存格值。False 會隱藏。寫入 **bool**。

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowLabelValueFromCell(bool value)=0
```
## 備註

如果此 [DataLabelFormat](../../datalabelformat/) 物件的父項是 [DataLabelCollection](../../datalabelcollection/) 資料標籤集合，則此屬性會取得或設定 [DataLabelCollection](../../datalabelcollection/) 集合中新資料標籤的 ShowLabelValueFromCell 屬性的預設值。將此屬性設定為某個值時，也會將該值設定給 [DataLabelCollection](../../datalabelcollection/) 集合中所有資料標籤的 ShowLabelValueFromCell 屬性（即 "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" 會導致所有 DataLabels[i].ShowLabelValueFromCell 等於 val）。

## 另見

* 類別 [IDataLabelFormat](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)