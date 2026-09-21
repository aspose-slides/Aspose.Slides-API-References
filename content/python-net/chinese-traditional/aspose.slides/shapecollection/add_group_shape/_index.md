---
title: add_group_shape method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/shapecollection/add_group_shape/
weight: 80
---
## add_group_shape(self) {#}
建立一個新的空白群組形狀，並將其加入形狀集合的末端。  
群組的框架會自動調整，以容納加入的任何形狀。

### 回傳值

新建立的 [`IGroupShape`](/slides/python-net/zh-hant/aspose.slides/igroupshape)。



```python
def add_group_shape(self):
    ...
```



## add_group_shape(self, svg_image, x, y, width, height) {#isvgimage-float-float-float-float}
建立一個新的群組形狀，將指定的 SVG 圖像轉換為個別形狀，  
並將產生的群組加入形狀集合的末端。

### 回傳值

新建立的 [`IGroupShape`](/slides/python-net/zh-hant/aspose.slides/igroupshape)。



```python
def add_group_shape(self, svg_image, x, y, width, height):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/zh-hant/aspose.slides/isvgimage) | 包含向量內容以轉換為形狀的 [`ISvgImage`](/slides/python-net/zh-hant/aspose.slides/isvgimage)。 |
| x | **float** | 群組框架的 x 座標，以點為單位。 |
| y | **float** | 群組框架的 y 座標，以點為單位。 |
| width | **float** | 群組框架的寬度，以點為單位。 |
| height | **float** | 群組框架的高度，以點為單位。 |



### 參見
* 類別 [`IGroupShape`](/slides/python-net/zh-hant/aspose.slides/igroupshape)
* 類別 [`ISvgImage`](/slides/python-net/zh-hant/aspose.slides/isvgimage)
* 類別 [`ShapeCollection`](/slides/python-net/zh-hant/aspose.slides/shapecollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)