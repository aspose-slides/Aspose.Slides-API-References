---
title: show_category_name property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/datalabelformat/show_category_name/
weight: 130
---
## show_category_name 屬性
表示指定圖表的資料標籤類別名稱顯示行為。
            True 以在圖表的資料標籤上顯示類別名稱。False 以隱藏。
            讀/寫 **bool**.


### 備註

如果此 DataLabelFormat 物件的父項是 DataLabelCollection（資料標籤集合），則此屬性會取得或設定 DataLabelCollection 中新資料標籤的 ShowCategoryName 屬性的預設值。
            將此屬性設為某個值時，也會將該值設定給 DataLabelCollection 中所有資料標籤的 ShowCategoryName 屬性
            （例如 "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" 會導致所有 DataLabels[i].ShowCategoryName 等於 val）。

### 定義:
```python
@property
def show_category_name(self):
    ...

@show_category_name.setter
def show_category_name(self, value):
    ...
```


### 另請參閱
* 類別 [`DataLabelFormat`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelformat)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)