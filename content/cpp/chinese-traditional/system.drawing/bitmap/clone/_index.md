---
title: Clone()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立目前物件的副本。
type: docs
weight: 183
url: /zh-hant/system.drawing/bitmap/clone/
---
## Bitmap::Clone() 方法

建立目前物件的副本。

```cpp
virtual SharedPtr<Image> System::Drawing::Bitmap::Clone() override
```

### 傳回值

目前物件的副本。

## Bitmap::Clone(Rectangle, Imaging::PixelFormat) 方法

建立一個 [Bitmap](../) 物件，代表目前物件所表示之點陣圖影像的某區域的副本。

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(Rectangle rect, Imaging::PixelFormat format)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | 指定要複製之區域的矩形 |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | 新 [Bitmap](../) 的像素格式 |

### 傳回值

已建立的 [Bitmap](../) 物件

## Bitmap::Clone(RectangleF, Imaging::PixelFormat) 方法

建立一個 [Bitmap](../) 物件，代表目前物件所表示之點陣圖影像的某區域的副本。

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(RectangleF rect, Imaging::PixelFormat format)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | 指定要複製之區域的矩形 |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | 新 [Bitmap](../) 的像素格式 |

### 傳回值

已建立的 [Bitmap](../) 物件

## 另見

* 列舉 [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [Image](../../image/)
* 類別 [Bitmap](../)
* 類別 [Rectangle](../../rectangle/)
* 類別 [RectangleF](../../rectanglef/)
* 命名空間 [System::Drawing](../../)
* 函式庫 [Aspose.Slides](../../../)