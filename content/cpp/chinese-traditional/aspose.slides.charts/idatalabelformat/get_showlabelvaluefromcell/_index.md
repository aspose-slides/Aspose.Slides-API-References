---
title: get_ShowLabelValueFromCell()
second_title: Aspose.Slides for C++ API 參考文件
description: 代表指定圖表的資料標籤儲存格值顯示行為。True 會顯示儲存格值。False 會隱藏。讀取 bool。
type: docs
weight: 300
url: /zh-hant/aspose.slides.charts/idatalabelformat/get_showlabelvaluefromcell/
---
## IDataLabelFormat::get_ShowLabelValueFromCell() 方法

表示指定圖表的資料標籤儲存格值顯示行為。True 會顯示儲存格值。False 會隱藏。讀取 **bool**。

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowLabelValueFromCell()=0
```

## 備註

如果此 [DataLabelFormat](../../datalabelformat/) 物件的父項是 [DataLabelCollection](../../datalabelcollection/) 資料標籤集合，則此屬性會取得或設定 [DataLabelCollection](../../datalabelcollection/) 集合中新資料標籤的 ShowLabelValueFromCell 屬性的預設值。以值設定此屬性同時會將此值設定給 [DataLabelCollection](../../datalabelcollection/) 集合中所有資料標籤的 ShowLabelValueFromCell 屬性 (例如\"DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;\" 會使所有 DataLabels[i].ShowLabelValueFromCell 等於 val)。

## 另請參閱

* 類別 [IDataLabelFormat](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)