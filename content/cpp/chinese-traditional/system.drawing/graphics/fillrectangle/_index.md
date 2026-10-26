---
title: FillRectangle()
second_title: Aspose.Slides for C++ API 參考
description: 使用指定的 brush 填充指定的 rectangle。
type: docs
weight: 326
url: /zh-hant/system.drawing/graphics/fillrectangle/
---
## Graphics::FillRectangle(const SharedPtr\<Brush\>\&, float, float, float, float) 方法

使用指定的 brush 填充指定的 rectangle。

```cpp
void System::Drawing::Graphics::FillRectangle(const SharedPtr<Brush> &brush, float x, float y, float width, float height)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 用於填充的 [Brush](../../brush/) 物件 |
| x | **float** | 要填充的 rectangle 左上角的 X 坐標 |
| y | **float** | 要填充的 rectangle 左上角的 Y 坐標 |
| width | **float** | 要填充的 rectangle 的寬度 |
| height | **float** | 要填充的 rectangle 的高度 |

## Graphics::FillRectangle(const SharedPtr\<Brush\>\&, int, int, int, int) 方法

使用指定的 brush 填充指定的 rectangle。

```cpp
void System::Drawing::Graphics::FillRectangle(const SharedPtr<Brush> &brush, int x, int y, int width, int height)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 用於填充的 [Brush](../../brush/) 物件 |
| x | int | 要填充的 rectangle 左上角的 X 坐標 |
| y | int | 要填充的 rectangle 左上角的 Y 坐標 |
| width | int | 要填充的 rectangle 的寬度 |
| height | int | 要填充的 rectangle 的高度 |

## Graphics::FillRectangle(const SharedPtr\<Brush\>\&, Rectangle) 方法

使用指定的 brush 填充指定的 rectangle。

```cpp
void System::Drawing::Graphics::FillRectangle(const SharedPtr<Brush> &brush, Rectangle rect)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 用於填充的 [Brush](../../brush/) 物件 |
| rect | [Rectangle](../../rectangle/) | 用於指定要填充的 rectangle 位置與大小的 [Rectangle](../../rectangle/) 物件 |

## Graphics::FillRectangle(const SharedPtr\<Brush\>\&, RectangleF) 方法

使用指定的 brush 填充指定的 rectangle。

```cpp
void System::Drawing::Graphics::FillRectangle(const SharedPtr<Brush> &brush, RectangleF rect)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 用於填充的 [Brush](../../brush/) 物件 |
| rect | [RectangleF](../../rectanglef/) | 用於指定要填充的 rectangle 位置與大小的 [RectangleF](../../rectanglef/) 物件 |

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [Brush](../../brush/)
* 類別 [Graphics](../)
* 類別 [Rectangle](../../rectangle/)
* 類別 [RectangleF](../../rectanglef/)
* 命名空間 [System::Drawing](../../)
* Library [Aspose.Slides](../../../)