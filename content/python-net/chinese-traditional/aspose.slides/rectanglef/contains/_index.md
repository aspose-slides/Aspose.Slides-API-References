---
title: contains method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/rectanglef/contains/
weight: 20
---
## contains(self, point) {#pointf}
判斷指定的點是否位於此矩形內。

### 回傳值

`True` if the point is contained within this rectangle; otherwise, `False`.



```python
def contains(self, point):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/zh-hant/aspose.slides/pointf) | 要測試的點。接受具有 `x` 和 `y` 屬性的任何物件。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **TypeError** | 參數數量錯誤。 |


## contains(self, rect) {#rectanglef}
判斷由 `rect` 所表示的矩形區域是否完全位於此矩形內。

### 回傳值

`True` if the rectangular region represented by `rect` is entirely contained within this rectangle; otherwise, `False`.



```python
def contains(self, rect):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| rect | [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef) | 要測試的矩形。接受具有 `x`、`y`、`width` 和 `height` 屬性的任何物件。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **TypeError** | 參數數量錯誤。 |


## contains(self, x, y) {#float-float}
判斷指定的點是否位於此矩形內。

### 回傳值

`True` if the point defined by `x` and `y` is contained within this rectangle; otherwise, `False`.



```python
def contains(self, x, y):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| x | **float** | 要測試之點的 x 座標。 |
| y | **float** | 要測試之點的 y 座標。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **TypeError** | 參數數量錯誤。 |



### 另請參閱
* 類別 [`PointF`](/slides/python-net/zh-hant/aspose.slides/pointf)
* 類別 [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)