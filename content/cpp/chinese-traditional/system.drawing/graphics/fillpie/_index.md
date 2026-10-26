---
title: FillPie()
second_title: Aspose.Slides for C++ API 參考
description: 使用指定的畫筆在當前物件所代表的表面上填滿指定的餅形。
type: docs
weight: 274
url: /zh-hant/system.drawing/graphics/fillpie/
---
## Graphics::FillPie(const SharedPtr\<Brush\>\&, int, int, int, int, int, int) 方法

使用指定的筆刷在當前物件所代表的表面上填滿指定的餅形。

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 用於填充餅形的畫筆 |
| x | int | 定義橢圓的矩形左上角的 X 座標 |
| y | int | 定義橢圓的矩形左上角的 Y 座標 |
| width | int | 定義橢圓的矩形的寬度 |
| height | int | 定義橢圓的矩形的高度 |
| startAngle | int | 角度（以度為單位），自 X 軸順時針測量至餅形的起始點 |
| sweepAngle | int | 角度（以度為單位），自 **startAngle** 順時針測量至餅形的結束點 |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, float, float, float, float, float, float) 方法

使用指定的筆刷在當前物件所代表的表面上填滿指定的餅形。

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 用於填充餅形的畫筆 |
| x | **float** | 定義橢圓的矩形左上角的 X 座標 |
| y | **float** | 定義橢圓的矩形左上角的 Y 座標 |
| width | **float** | 定義橢圓的矩形的寬度 |
| height | **float** | 定義橢圓的矩形的高度 |
| startAngle | **float** | 角度（以度為單位），自 X 軸順時針測量至餅形的起始點 |
| sweepAngle | **float** | 角度（以度為單位），自 **startAngle** 順時針測量至餅形的結束點 |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, Rectangle, float, float) 方法

使用指定的筆刷在當前物件所代表的表面上填滿指定的餅形。

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, Rectangle rect, float startAngle, float sweepAngle)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 用於填充餅形的畫筆 |
| rect | [Rectangle](../../rectangle/) | 定義橢圓的矩形 |
| startAngle | **float** | 角度（以度為單位），自 X 軸順時針測量至餅形的起始點 |
| sweepAngle | **float** | 角度（以度為單位），自 **startAngle** 順時針測量至餅形的結束點 |

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [Brush](../../brush/)
* 類別 [Graphics](../)
* 類別 [Rectangle](../../rectangle/)
* 命名空間 [System::Drawing](../../)
* 函式庫 [Aspose.Slides](../../../)