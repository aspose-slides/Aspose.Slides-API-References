---
title: get_NumberFormat()
second_title: Aspose.Slides for C++ API 參考文件
description: "表示 DataLabels 物件的格式字串。請閱讀 System::String."
type: docs
weight: 27
url: /zh-hant/aspose.slides.charts/datalabelformat/get_numberformat/
---
## DataLabelFormat::get_NumberFormat() 方法


表示 DataLabels 物件的格式字串。請閱讀 [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Charts::DataLabelFormat::get_NumberFormat() override
```

## 備註



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```





如果此 [DataLabelFormat](../) 物件的父項是 [DataLabelCollection](../../datalabelcollection/) 資料標籤集合，則此屬性取得或設定 [DataLabelCollection](../../datalabelcollection/) 集合中新資料標籤的 NumberFormat 屬性的預設值。當此屬性以某個值設定時，該值也會設定 [DataLabelCollection](../../datalabelcollection/) 集合中所有資料標籤的 NumberFormat 屬性 (即 "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" 會使所有 DataLabels[i].NumberFormat 等於 val)。 



## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [DataLabelFormat](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)