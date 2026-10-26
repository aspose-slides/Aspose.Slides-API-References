---
title: RectangleF class
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 儲存四個浮點數，用於表示矩形的位置和大小。
type: docs
url: /zh-hant/aspose.slides/rectanglef/
net_type: System.Drawing.RectangleF
---
## RectangleF 類別

儲存四個浮點數，用於表示矩形的位置和大小。相容於 .NET `System.Drawing.RectangleF`。

**繼承:**[`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef) → [`Rectangle`](/slides/python-net/zh-hant/aspose.slides/rectangle)

RectangleF 類型公開以下成員：

## 建構函式

| 建構函式 | 說明 |
| :- | :- |
| [`__init__(self, x=0.0, y=0.0, width=0.0, height=0.0)`](/slides/python-net/zh-hant/aspose.slides/rectanglef/__init__/#float-float-float-float) | 建立具有指定位置和大小的矩形。 |

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`x`](/slides/python-net/zh-hant/aspose.slides/rectanglef/x/) | 取得此矩形左上角的 x 座標。<br/>            唯讀 **float**。 |
| [`y`](/slides/python-net/zh-hant/aspose.slides/rectanglef/y/) | 取得此矩形左上角的 y 座標。<br/>            唯讀 **float**。 |
| [`width`](/slides/python-net/zh-hant/aspose.slides/rectanglef/width/) | 取得此矩形的寬度。<br/>            唯讀 **float**。 |
| [`height`](/slides/python-net/zh-hant/aspose.slides/rectanglef/height/) | 取得此矩形的高度。<br/>            唯讀 **float**。 |
| [`left`](/slides/python-net/zh-hant/aspose.slides/rectanglef/left/) | 取得此矩形左邊緣的 x 座標。等於 `x`。<br/>            唯讀 **float**。 |
| [`top`](/slides/python-net/zh-hant/aspose.slides/rectanglef/top/) | 取得此矩形上邊緣的 y 座標。等於 `y`。<br/>            唯讀 **float**。 |
| [`right`](/slides/python-net/zh-hant/aspose.slides/rectanglef/right/) | 取得此矩形的 `x` 與 `width` 相加後的 x 座標。<br/>            唯讀 **float**。 |
| [`bottom`](/slides/python-net/zh-hant/aspose.slides/rectanglef/bottom/) | 取得此矩形的 `y` 與 `height` 相加後的 y 座標。<br/>            唯讀 **float**。 |
| [`is_empty`](/slides/python-net/zh-hant/aspose.slides/rectanglef/is_empty/) | 指定此矩形的所有數值屬性是否為零。<br/>            唯讀 **bool**。 |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`contains(self, x, y)`](/slides/python-net/zh-hant/aspose.slides/rectanglef/contains/#float-float) | 判斷指定的點是否位於此矩形內部。 |
| [`contains(self, point)`](/slides/python-net/zh-hant/aspose.slides/rectanglef/contains/#pointf) | 判斷指定的點是否位於此矩形內部。 |
| [`contains(self, rect)`](/slides/python-net/zh-hant/aspose.slides/rectanglef/contains/#rectanglef) | 判斷由 `rect` 表示的矩形區域是否完整地包含在此矩形內。 |

### 備註

矩形可透過 `==` 依其位置與大小進行比較，且可作為字典鍵或集合成員使用。

### 另請參閱
* 類別 [`Rectangle`](/slides/python-net/zh-hant/aspose.slides/rectangle)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)