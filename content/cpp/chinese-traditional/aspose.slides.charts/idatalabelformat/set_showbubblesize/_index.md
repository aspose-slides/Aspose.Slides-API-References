---
title: set_ShowBubbleSize()
second_title: Aspose.Slides for C++ API 參考文件
description: 表示指定圖表的資料標籤氣泡大小值顯示行為。True 顯示氣泡大小值。False 隱藏。寫入 bool.
type: docs
weight: 235
url: /zh-hant/aspose.slides.charts/idatalabelformat/set_showbubblesize/
---
## IDataLabelFormat::set_ShowBubbleSize(bool) 方法

表示指定圖表的資料標籤氣泡大小值顯示行為。True 顯示氣泡大小值。False 隱藏。寫入 **bool**。

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowBubbleSize(bool value)=0
```

## 備註

如果此 [DataLabelFormat](../../datalabelformat/) 物件的父項是 [DataLabelCollection](../../datalabelcollection/) 資料標籤集合，則此屬性會取得或設定 [DataLabelCollection](../../datalabelcollection/) 集合中新資料標籤的 ShowBubbleSize 屬性的預設值。將此屬性設定為某個值時，同時會將此值設定給 [DataLabelCollection](../../datalabelcollection/) 集合中所有資料標籤的 ShowBubbleSize 屬性（例如 "DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;" 會導致所有 DataLabels[i].ShowBubbleSize 等於 val）。

## 另見

* 類別 [IDataLabelFormat](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 程式庫 [Aspose.Slides](../../../)