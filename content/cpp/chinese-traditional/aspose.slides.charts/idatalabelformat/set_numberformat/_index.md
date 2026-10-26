---
title: set_NumberFormat()
second_title: Aspose.Slides for C++ API 參考文件
description: "表示 DataLabels 物件的格式字串。寫入 System::String。"
type: docs
weight: 40
url: /zh-hant/aspose.slides.charts/idatalabelformat/set_numberformat/
---
## IDataLabelFormat::set_NumberFormat(System::String) 方法

表示 DataLabels 物件的格式字串。寫入 [System::String](../../../system/string/)。

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_NumberFormat(System::String value)=0
```

## 備註

```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```

如果此 [DataLabelFormat](../../datalabelformat/) 物件的父項是 [DataLabelCollection](../../datalabelcollection/) 資料標籤集合，則此屬性取得或設定 [DataLabelCollection](../../datalabelcollection/) 集合中新資料標籤的 NumberFormat 屬性的預設值。當此屬性以某個值設定時，該值亦會設定於 [DataLabelCollection](../../datalabelcollection/) 集合中所有資料標籤的 NumberFormat 屬性 (例如 "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" 會使所有 DataLabels[i].NumberFormat 等於 val)。

## 參見

* 類別 [String](../../../system/string/)
* 類別 [IDataLabelFormat](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)