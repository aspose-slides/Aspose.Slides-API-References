---
title: contains method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/rectangle/contains/
weight: 20
---
## contains(self, point) {#point}
判斷指定的點是否位於此矩形內。

### Returns
如果點位於此矩形內則返回 `True`；否則返回 `False`。

```python
def contains(self, point):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| point | [`Point`](/slides/python-net/zh-hant/aspose.slides/point) | 要測試的點。接受任何具有 `x` 和 `y` 屬性的物件。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **TypeError** | 參數個數錯誤。 |

## contains(self, rect) {#rectangle}
判斷由 `rect` 表示的矩形區域是否完全位於此矩形內。

### Returns
如果由 `rect` 表示的矩形區域完全位於此矩形內則返回 `True`；否則返回 `False`。

```python
def contains(self, rect):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| rect | [`Rectangle`](/slides/python-net/zh-hant/aspose.slides/rectangle) | 要測試的矩形。接受任何具有 `x`、`y`、`width` 和 `height` 屬性的物件。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **TypeError** | 參數個數錯誤。 |

## contains(self, x, y) {#int-int}
判斷指定的點是否位於此矩形內。

### Returns
如果由 `x` 和 `y` 定義的點位於此矩形內則返回 `True`；否則返回 `False`。

```python
def contains(self, x, y):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| x | **int** | 要測試的點的 X 座標。 |
| y | **int** | 要測試的點的 Y 座標。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **TypeError** | 參數個數錯誤。 |

### See Also
* 類別 [`Point`](/slides/python-net/zh-hant/aspose.slides/point)
* 類別 [`Rectangle`](/slides/python-net/zh-hant/aspose.slides/rectangle)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)