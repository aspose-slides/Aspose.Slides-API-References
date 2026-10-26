---
title: add_group_shape method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/ishapecollection/add_group_shape/
weight: 80
---
## add_group_shape(self) {#}
建立一個新的空白群組圖形，並將其新增至圖形集合的末端。群組的框架會自動調整以容納加入的任何圖形。

### Returns

新建立的 [`IGroupShape`](/slides/python-net/zh-hant/aspose.slides/igroupshape)。

```python
def add_group_shape(self):
    ...
```

## add_group_shape(self, svg_image, x, y, width, height) {#isvgimage-float-float-float-float}
建立一個新的群組圖形，將指定的 SVG 圖像轉換為個別圖形，並將產生的群組新增至圖形集合的末端。

### Returns

新建立的 [`IGroupShape`](/slides/python-net/zh-hant/aspose.slides/igroupshape)。

```python
def add_group_shape(self, svg_image, x, y, width, height):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/zh-hant/aspose.slides/isvgimage) | 包含向量內容以轉換為圖形的 [`ISvgImage`](/slides/python-net/zh-hant/aspose.slides/isvgimage)。 |
| x | **float** | 群組框架的 x 座標，單位為點。 |
| y | **float** | 群組框架的 y 座標，單位為點。 |
| width | **float** | 群組框架的寬度，單位為點。 |
| height | **float** | 群組框架的高度，單位為點。 |

### See Also
* 類別 [`IGroupShape`](/slides/python-net/zh-hant/aspose.slides/igroupshape)
* 類別 [`IShapeCollection`](/slides/python-net/zh-hant/aspose.slides/ishapecollection)
* 類別 [`ISvgImage`](/slides/python-net/zh-hant/aspose.slides/isvgimage)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)