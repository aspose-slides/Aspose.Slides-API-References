---
title: set_Separator()
second_title: Aspose.Slides for C++ API 參考
description: "設定或返回一個代表圖表中資料標籤所使用分隔符的 Variant。寫入 System::String."
type: docs
weight: 339
url: /zh-hant/aspose.slides.charts/idatalabelformat/set_separator/
---
## IDataLabelFormat::set_Separator(System::String) 方法

設定或返回一個代表圖表中資料標籤所使用分隔符的 Variant。寫入 [System::String](../../../system/string/)。

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_Separator(System::String value)=0
```

## 備註

如果此 [DataLabelFormat](../../datalabelformat/) 物件的父項是 [DataLabelCollection](../../datalabelcollection/) 資料標籤集合，則此屬性會取得或設定 [DataLabelCollection](../../datalabelcollection/) 集合中新資料標籤的 Separator 屬性的預設值。以值設定此屬性也會將此值設定為 [DataLabelCollection](../../datalabelcollection/) 集合中所有資料標籤的 Separator 屬性（即 "DataLabels.DefaultDataLabelFormat.Separator = val;" 會使所有 DataLabels[i].Separator 等於 val）。

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [IDataLabelFormat](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)