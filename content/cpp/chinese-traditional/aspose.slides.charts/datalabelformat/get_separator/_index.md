---
title: get_Separator()
second_title: Aspose.Slides for C++ API 參考文件
description: "設定或傳回一個 Variant，表示圖表上資料標籤所使用的分隔符號。請閱讀 System::String."
type: docs
weight: 326
url: /zh-hant/aspose.slides.charts/datalabelformat/get_separator/
---
## DataLabelFormat::get_Separator() 方法


設定或傳回一個 Variant，表示用於圖表上資料標籤的分隔符號。請閱讀 [System::String](../../../system/string/)。

```cpp
System::String Aspose::Slides::Charts::DataLabelFormat::get_Separator() override
```

## 備註


如果此 [DataLabelFormat](../) 物件的父項是 [DataLabelCollection](../../datalabelcollection/) 資料標籤集合，則此屬性會取得或設定 [DataLabelCollection](../../datalabelcollection/) 集合中新資料標籤的 Separator 屬性之預設值。將此屬性設定為某個值同時會將該值設定給 [DataLabelCollection](../../datalabelcollection/) 集合中所有資料標籤的 Separator 屬性 (例如 "DataLabels.DefaultDataLabelFormat.Separator = val;" 會使所有 DataLabels[i].Separator 等於 val)。 


## 參見

* 類別 [String](../../../system/string/)
* 類別 [DataLabelFormat](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)