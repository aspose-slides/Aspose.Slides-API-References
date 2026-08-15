---
title: AddPie()
second_title: Aspose.Slides for C++ API 參考文件
description: 會將指定的餡餅形狀輪廓加入到目前物件所代表的路徑中。
type: docs
weight: 209
url: /zh-hant/system.drawing.drawing2d/graphicspath/addpie/
---
## GraphicsPath::AddPie(float, float, float, float, float, float) 方法

將指定的餡餅形狀輪廓添加到目前物件所表示的路徑中。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPie(float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | 餡餅所繪製橢圓所圍繞之矩形左上角的 X 座標 |
| y | **float** | 餡餅所繪製橢圓所圍繞之矩形左上角的 Y 座標 |
| width | **float** | 餡餅所繪製橢圓所圍繞之矩形的寬度 |
| height | **float** | 餡餅所繪製橢圓所圍繞之矩形的高度 |
| startAngle | **float** | 指定餡餅的起始角度（以度為單位），從 X 軸順時針測量 |
| sweepAngle | **float** | 指定起始角度與餡餅結束角度之間的角度 |

## GraphicsPath::AddPie(int, int, int, int, float, float) 方法

將指定的餡餅形狀輪廓添加到目前物件所表示的路徑中。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPie(int x, int y, int width, int height, float startAngle, float sweepAngle)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| x | int | 餡餅所繪製橢圓所圍繞之矩形左上角的 X 座標 |
| y | int | 餡餅所繪製橢圓所圍繞之矩形左上角的 Y 座標 |
| width | int | 餡餅所繪製橢圓所圍繞之矩形的寬度 |
| height | int | 餡餅所繪製橢圓所圍繞之矩形的高度 |
| startAngle | **float** | 指定餡餅的起始角度（以度為單位），從 X 軸順時針測量 |
| sweepAngle | **float** | 指定起始角度與餡餅結束角度之間的角度 |

## GraphicsPath::AddPie(const Rectangle\&, float, float) 方法

將指定的餡餅形狀輪廓添加到目前物件所表示的路徑中。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPie(const Rectangle &rect, float startAngle, float sweepAngle)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [Rectangle](../../../system.drawing/rectangle/)\& | 圍繞餡餅所繪製橢圓的矩形 |
| startAngle | **float** | 指定餡餅的起始角度（以度為單位），從 X 軸順時針測量 |
| sweepAngle | **float** | 指定起始角度與餡餅結束角度之間的角度 |

## 另見

* 類別 [GraphicsPath](../)
* 類別 [Rectangle](../../../system.drawing/rectangle/)
* 命名空間 [System::Drawing::Drawing2D](../../)
* 函式庫 [Aspose.Slides](../../../)