---
title: set_ShowCategoryName()
second_title: Aspose.Slides for C++ API 參考
description: 表示指定圖表的資料標籤類別名稱顯示行為。設定為 true 時，在圖表上顯示資料標籤的類別名稱。設定為 false 時，隱藏。寫入 bool。
type: docs
weight: 157
url: /zh-hant/aspose.slides.charts/idatalabelformat/set_showcategoryname/
---
## IDataLabelFormat::set_ShowCategoryName(bool) method


表示指定圖表的資料標籤類別名稱顯示行為。設定為 true 時，在圖表上顯示資料標籤的類別名稱。設定為 false 時，隱藏。寫入 **bool**。

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowCategoryName(bool value)=0
```

## Remarks


如果此 [DataLabelFormat](../../datalabelformat/) 物件的父項是 [DataLabelCollection](../../datalabelcollection/) 資料標籤集合，則此屬性會取得或設定 [DataLabelCollection](../../datalabelcollection/) 集合中新資料標籤的 ShowCategoryName 屬性的預設值。將此屬性設為某個值時，同時會將該值設定給 [DataLabelCollection](../../datalabelcollection/) 集合中所有資料標籤的 ShowCategoryName 屬性（例如 "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" 會使所有 DataLabels[i].ShowCategoryName 等於 val）。


## See Also

* 類別 [IDataLabelFormat](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)