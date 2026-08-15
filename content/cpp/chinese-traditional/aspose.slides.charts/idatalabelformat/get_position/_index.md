---
title: get_Position()
second_title: Aspose.Slides for C++ API 參考文件
description: 代表資料標籤的位置。閱讀 LegendDataLabelPosition.
type: docs
weight: 66
url: /zh-hant/aspose.slides.charts/idatalabelformat/get_position/
---
## IDataLabelFormat::get_Position() 方法


代表資料標籤的位置。閱讀 [LegendDataLabelPosition](../../legenddatalabelposition/)。

```cpp
virtual LegendDataLabelPosition Aspose::Slides::Charts::IDataLabelFormat::get_Position()=0
```

## 備註


如果此 [DataLabelFormat](../../datalabelformat/) 物件的父項是 [DataLabelCollection](../../datalabelcollection/) 資料標籤集合，則此屬性會取得或設定新資料標籤在 [DataLabelCollection](../../datalabelcollection/) 集合中的 Position 屬性之預設值。代表 [DataLabel](../../datalabel/) 物件的 Position。將此屬性設定為某個值時，也會將此值設定給 [DataLabelCollection](../../datalabelcollection/) 集合中所有資料標籤的 Position 屬性 (即 \"DataLabels.DefaultDataLabelFormat.Position = val;\" 導致所有 DataLabels[i].Position 等於 val)。 



## 參見

* 列舉 [LegendDataLabelPosition](../../legenddatalabelposition/)
* 類別 [IDataLabelFormat](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)