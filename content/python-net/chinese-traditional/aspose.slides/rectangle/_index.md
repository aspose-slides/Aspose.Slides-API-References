---
title: Rectangle class
second_title: Aspose.Slides for Python via .NET API 參考
description: 儲存一組四個整數，代表矩形的位置與大小。
type: docs
url: /zh-hant/aspose.slides/rectangle/
net_type: System.Drawing.Rectangle
---
## Rectangle 類別

儲存一組四個整數，表示矩形的位置與大小。相容於 .NET `System.Drawing.Rectangle`。

Rectangle 類型公開以下成員：

## 建構式

| 建構式 | 說明 |
| :- | :- |
| [`__init__(self, x=0, y=0, width=0, height=0)`](/slides/python-net/zh-hant/aspose.slides/rectangle/__init__/#int-int-int-int) | 建立具有指定位置與大小的矩形。浮點值會被截斷為整數。 |

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`x`](/slides/python-net/zh-hant/aspose.slides/rectangle/x/) | 取得此矩形左上角的 x 坐標。<br/>            唯讀 **int**. |
| [`y`](/slides/python-net/zh-hant/aspose.slides/rectangle/y/) | 取得此矩形左上角的 y 坐標。<br/>            唯讀 **int**. |
| [`width`](/slides/python-net/zh-hant/aspose.slides/rectangle/width/) | 取得此矩形的寬度。<br/>            唯讀 **int**. |
| [`height`](/slides/python-net/zh-hant/aspose.slides/rectangle/height/) | 取得此矩形的高度。<br/>            唯讀 **int**. |
| [`left`](/slides/python-net/zh-hant/aspose.slides/rectangle/left/) | 取得此矩形左邊緣的 x 坐標。等於 `x`。<br/>            唯讀 **int**. |
| [`top`](/slides/python-net/zh-hant/aspose.slides/rectangle/top/) | 取得此矩形上邊緣的 y 坐標。等於 `y`。<br/>            唯讀 **int**. |
| [`right`](/slides/python-net/zh-hant/aspose.slides/rectangle/right/) | 取得此矩形的 `x` 與 `width` 之和的 x 坐標。<br/>            唯讀 **int**. |
| [`bottom`](/slides/python-net/zh-hant/aspose.slides/rectangle/bottom/) | 取得此矩形的 `y` 與 `height` 之和的 y 坐標。<br/>            唯讀 **int**. |
| [`is_empty`](/slides/python-net/zh-hant/aspose.slides/rectangle/is_empty/) | 指定此矩形的所有數值屬性是否皆為零。<br/>            唯讀 **bool**. |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`contains(self, x, y)`](/slides/python-net/zh-hant/aspose.slides/rectangle/contains/#int-int) | 判斷指定的點是否位於此矩形內。 |
| [`contains(self, point)`](/slides/python-net/zh-hant/aspose.slides/rectangle/contains/#point) | 判斷指定的點是否位於此矩形內。 |
| [`contains(self, rect)`](/slides/python-net/zh-hant/aspose.slides/rectangle/contains/#rectangle) | 判斷由 `rect` 表示的矩形區域是否完全包含於此矩形內。 |

### 備註

矩形會使用 `==` 依其位置與大小進行比較，且可作為字典鍵或集合成員使用。

### 另請參閱
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)