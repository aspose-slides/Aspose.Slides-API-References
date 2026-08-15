---
title: get_Separator()
second_title: Aspose.Slides for C++ API 參考
description: "設定或傳回代表圖表上資料標籤所使用分隔符的 Variant。閱讀 System::String."
type: docs
weight: 326
url: /zh-hant/aspose.slides.charts/idatalabelformat/get_separator/
---
## IDataLabelFormat::get_Separator() 方法

設定或傳回代表圖表上資料標籤所使用分隔符的 Variant。閱讀 [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Charts::IDataLabelFormat::get_Separator()=0
```

## 備註

如果此 [DataLabelFormat](../../datalabelformat/) 物件的父項是 [DataLabelCollection](../../datalabelcollection/) 資料標籤集合，則此屬性會取得或設定 [DataLabelCollection](../../datalabelcollection/) 集合中新資料標籤的 Separator 屬性的預設值。以值設定此屬性同時也會將此值設定給 [DataLabelCollection](../../datalabelcollection/) 集合中所有資料標籤的 Separator 屬性 (例如 "DataLabels.DefaultDataLabelFormat.Separator = val;" 會導致所有 DataLabels[i].Separator 等於 val)。

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [IDataLabelFormat](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)