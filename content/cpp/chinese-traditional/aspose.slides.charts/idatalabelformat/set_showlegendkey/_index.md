---
title: set_ShowLegendKey()
second_title: Aspose.Slides for C++ API 參考
description: 表示指定圖表的資料標籤圖例鍵顯示行為。如果資料標籤圖例鍵可見則為 True。寫入 bool。
type: docs
weight: 105
url: /zh-hant/aspose.slides.charts/idatalabelformat/set_showlegendkey/
---
## IDataLabelFormat::set_ShowLegendKey(bool) 方法

表示指定圖表的資料標籤圖例鍵顯示行為。如果資料標籤圖例鍵可見則為 True。寫入 **bool**。

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowLegendKey(bool value)=0
```

## 備註

如果此 [DataLabelFormat](../../datalabelformat/) 物件的父項是 [DataLabelCollection](../../datalabelcollection/) 資料標籤集合，則此屬性取得或設定 [DataLabelCollection](../../datalabelcollection/) 集合中新資料標籤的 ShowLegendKey 屬性的預設值。使用值設定此屬性同時也會將此值設定給 [DataLabelCollection](../../datalabelcollection/) 集合中所有資料標籤的 ShowLegendKey 屬性 (即 "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" 會使所有 DataLabels[i].ShowLegendKey 等於 val)。

## 參見

* 類別 [IDataLabelFormat](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 程式庫 [Aspose.Slides](../../../)