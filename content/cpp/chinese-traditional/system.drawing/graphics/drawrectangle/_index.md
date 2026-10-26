---
title: DrawRectangle()
second_title: Aspose.Slides for C++ API 參考
description: 使用指定的筆在由當前物件所代表的表面上繪製指定的矩形。
type: docs
weight: 287
url: /zh-hant/system.drawing/graphics/drawrectangle/
---
## Graphics::DrawRectangle(const SharedPtr\<Pen\>\&, int, int, int, int) 方法

使用指定的筆在由目前物件所代表的表面上繪製指定的矩形。

```cpp
void System::Drawing::Graphics::DrawRectangle(const SharedPtr<Pen> &pen, int x, int y, int width, int height)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 用於繪製矩形的筆 |
| x | int | 要繪製之矩形左上角的 X 座標 |
| y | int | 要繪製之矩形左上角的 Y 座標 |
| width | int | 要繪製之矩形的寬度 |
| height | int | 要繪製之矩形的高度 |

## Graphics::DrawRectangle(const SharedPtr\<Pen\>\&, float, float, float, float) 方法

使用指定的筆在由目前物件所代表的表面上繪製指定的矩形。

```cpp
void System::Drawing::Graphics::DrawRectangle(const SharedPtr<Pen> &pen, float x, float y, float width, float height)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 用於繪製矩形的筆 |
| x | **float** | 要繪製之矩形左上角的 X 座標 |
| y | **float** | 要繪製之矩形左上角的 Y 座標 |
| width | **float** | 要繪製之矩形的寬度 |
| height | **float** | 要繪製之矩形的高度 |

## Graphics::DrawRectangle(const SharedPtr\<Pen\>\&, Rectangle) 方法

使用指定的筆在由目前物件所代表的表面上繪製指定的矩形。

```cpp
void System::Drawing::Graphics::DrawRectangle(const SharedPtr<Pen> &pen, Rectangle rect)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 用於繪製矩形的筆 |
| rect | [Rectangle](../../rectangle/) | 一個 [Rectangle](../../rectangle/) 物件，指定要繪製之矩形的位置與大小 |

## 另請參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [Pen](../../pen/)
* 類別 [Graphics](../)
* 類別 [Rectangle](../../rectangle/)
* 命名空間 [System::Drawing](../../)
* Library [Aspose.Slides](../../../)