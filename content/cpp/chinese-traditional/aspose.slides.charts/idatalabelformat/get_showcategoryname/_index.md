---
title: get_ShowCategoryName()
second_title: Aspose.Slides for C++ API 參考
description: 表示指定圖表的資料標籤類別名稱顯示行為。True 表示在圖表的資料標籤上顯示類別名稱。False 表示隱藏。唯讀 bool.
type: docs
weight: 144
url: /zh-hant/aspose.slides.charts/idatalabelformat/get_showcategoryname/
---
## IDataLabelFormat::get_ShowCategoryName() 方法

Represents a specified chart's data label category name display behavior. True to display the category name for the data labels on a chart. False to hide. Read **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowCategoryName()=0
```

## 備註

If parent of this [DataLabelFormat](../../datalabelformat/) object is a [DataLabelCollection](../../datalabelcollection/) collection of data labels then this property gets or sets the default value of the ShowCategoryName property for the new data labels in the [DataLabelCollection](../../datalabelcollection/) collection. Set this property with value also sets this value to the ShowCategoryName property for all data labels in the [DataLabelCollection](../../datalabelcollection/) collection (i.e. \"DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;\" cause to all DataLabels[i].ShowCategoryName is equal to val). 

## 參見

* 類別 [IDataLabelFormat](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* 函式庫 [Aspose.Slides](../../../)