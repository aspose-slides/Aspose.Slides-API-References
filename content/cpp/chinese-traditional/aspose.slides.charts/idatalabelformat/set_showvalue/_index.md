---
title: set_ShowValue()
second_title: Aspose.Slides for C++ API 參考文件
description: 表示指定圖表的資料標籤百分比值顯示行為。True 會顯示百分比值。False 會隱藏。寫入 bool。
type: docs
weight: 131
url: /zh-hant/aspose.slides.charts/idatalabelformat/set_showvalue/
---
## IDataLabelFormat::set_ShowValue(bool) 方法


表示指定圖表的資料標籤百分比值顯示行為。True 會顯示百分比值。False 會隱藏。寫入 **bool**。

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowValue(bool value)=0
```

## 備註


如果此 [DataLabelFormat](../../datalabelformat/) 物件的父項是 [DataLabelCollection](../../datalabelcollection/) 資料標籤集合，則此屬性會取得或設定 [DataLabelCollection](../../datalabelcollection/) 集合中新資料標籤的 ShowValue 屬性的預設值。以值設定此屬性時，也會將此值設定給 [DataLabelCollection](../../datalabelcollection/) 集合中所有資料標籤的 ShowValue 屬性（即 \"DataLabels.DefaultDataLabelFormat.ShowValue = val;\" 會導致所有 DataLabels[i].ShowValue 等於 val）。

## 另見

* 類別 [IDataLabelFormat](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)