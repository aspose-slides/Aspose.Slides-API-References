---
title: DrawArc()
second_title: Aspose.Slides for C++ API 參考
description: 使用指定的筆在當前物件所代表的表面上繪製指定的弧形。
type: docs
weight: 248
url: /zh-hant/system.drawing/graphics/drawarc/
---
## Graphics::DrawArc(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) 方法


使用指定的筆在當前物件所代表的表面上繪製指定的弧形。

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, int32_t x, int32_t y, int32_t width, int32_t height, int32_t startAngle, int32_t sweepAngle)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 繪製弧形時使用的筆 |
| x | **int32_t** | 定義橢圓的矩形左上角的 X 座標 |
| y | **int32_t** | 定義橢圓的矩形左上角的 Y 座標 |
| width | **int32_t** | 定義橢圓的矩形的寬度 |
| height | **int32_t** | 定義橢圓的矩形的高度 |
| startAngle | **int32_t** | 從 X 軸順時針測量到弧形起點的角度（度） |
| sweepAngle | **int32_t** | 從 **startAngle** 順時針測量到弧形終點的角度（度） |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) 方法


使用指定的筆在當前物件所代表的表面上繪製指定的弧形。

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 繪製弧形時使用的筆 |
| x | **float** | 定義橢圓的矩形左上角的 X 座標 |
| y | **float** | 定義橢圓的矩形左上角的 Y 座標 |
| width | **float** | 定義橢圓的矩形的寬度 |
| height | **float** | 定義橢圓的矩形的高度 |
| startAngle | **float** | 從 X 軸順時針測量到弧形起點的角度（度） |
| sweepAngle | **float** | 從 **startAngle** 順時針測量到弧形終點的角度（度） |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, Rectangle, float, float) 方法


使用指定的筆在當前物件所代表的表面上繪製指定的弧形。

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, Rectangle rect, float startAngle, float sweepAngle)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 繪製弧形時使用的筆 |
| rect | [Rectangle](../../rectangle/) | 定義橢圓的矩形 |
| startAngle | **float** | 從 X 軸順時針測量到弧形起點的角度（度） |
| sweepAngle | **float** | 從 **startAngle** 順時針測量到弧形終點的角度（度） |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, RectangleF, float, float) 方法


使用指定的筆在當前物件所代表的表面上繪製指定的弧形。

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, RectangleF rect, float startAngle, float sweepAngle)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 繪製弧形時使用的筆 |
| rect | [RectangleF](../../rectanglef/) | 定義橢圓的矩形 |
| startAngle | **float** | 從 X 軸順時針測量到弧形起點的角度（度） |
| sweepAngle | **float** | 從 **startAngle** 順時針測量到弧形終點的角度（度） |

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [Pen](../../pen/)
* 類別 [Graphics](../)
* 類別 [Rectangle](../../rectangle/)
* 類別 [RectangleF](../../rectanglef/)
* 命名空間 [System::Drawing](../../)
* Library [Aspose.Slides](../../../)