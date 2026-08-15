---
title: AddArc()
second_title: Aspose.Slides for C++ API 參考
description: 將指定的橢圓弧新增至目前物件所代表的路徑。
type: docs
weight: 183
url: /zh-hant/system.drawing.drawing2d/graphicspath/addarc/
---
## GraphicsPath::AddArc(float, float, float, float, float, float) 方法

將指定的橢圓弧新增至目前物件所代表的路徑。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddArc(float x, float y, float width, float height, float startAngle, float sweepAngle)
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | **float** | 橢圓所屬矩形左上角的 X 座標 |
| y | **float** | 橢圓所屬矩形左上角的 Y 座標 |
| width | **float** | 橢圓所屬矩形的寬度 |
| height | **float** | 橢圓所屬矩形的高度 |
| startAngle | **float** | 指定弧線的起始角度（度），以 X 軸順時針方向測量 |
| sweepAngle | **float** | 指定起始角度與弧線結束角之間的角度 |

## GraphicsPath::AddArc(int, int, int, int, float, float) 方法

將指定的橢圓弧新增至目前物件所代表的路徑。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddArc(int x, int y, int width, int height, float startAngle, float sweepAngle)
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | int | 橢圓所屬矩形左上角的 X 座標 |
| y | int | 橢圓所屬矩形左上角的 Y 座標 |
| width | int | 橢圓所屬矩形的寬度 |
| height | int | 橢圓所屬矩形的高度 |
| startAngle | **float** | 指定弧線的起始角度（度），以 X 軸順時針方向測量 |
| sweepAngle | **float** | 指定起始角度與弧線結束角之間的角度 |

## GraphicsPath::AddArc(const RectangleF\&, float, float) 方法

將指定的橢圓弧新增至目前物件所代表的路徑。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddArc(const RectangleF &rect, float startAngle, float sweepAngle)
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| rect | const [RectangleF](../../../system.drawing/rectanglef/)\& | 橢圓所屬的矩形 |
| startAngle | **float** | 指定弧線的起始角度（度），以 X 軸順時針方向測量 |
| sweepAngle | **float** | 指定起始角度與弧線結束角之間的角度 |

## GraphicsPath::AddArc(const Rectangle\&, float, float) 方法

將指定的橢圓弧新增至目前物件所代表的路徑。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddArc(const Rectangle &rect, float startAngle, float sweepAngle)
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| rect | const [Rectangle](../../../system.drawing/rectangle/)\& | 橢圓所屬的矩形 |
| startAngle | **float** | 指定弧線的起始角度（度），以 X 軸順時針方向測量 |
| sweepAngle | **float** | 指定起始角度與弧線結束角之間的角度 |

## 另請參見

* 類別 [GraphicsPath](../)
* 類別 [RectangleF](../../../system.drawing/rectanglef/)
* 類別 [Rectangle](../../../system.drawing/rectangle/)
* 命名空間 [System::Drawing::Drawing2D](../../)
* 函式庫 [Aspose.Slides](../../../)