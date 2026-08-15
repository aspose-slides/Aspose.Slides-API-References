---
title: DrawImageUnscaled()
second_title: Aspose.Slides for C++ API 參考文件
description: 在指定位置以原始實體大小繪製指定的影像。
type: docs
weight: 443
url: /zh-hant/system.drawing/graphics/drawimageunscaled/
---
## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int) 方法

在指定位置以原始實體大小繪製指定的影像。

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要繪製的影像 |
| x | int | 繪製影像左上角的 X 座標 |
| y | int | 繪製影像左上角的 Y 座標 |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int, int, int) 方法

在指定位置以原始實體大小繪製指定的影像。

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y, int width, int height)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要繪製的影像 |
| x | int | 繪製影像左上角的 X 座標 |
| y | int | 繪製影像左上角的 Y 座標 |
| width | int | 未使用 |
| height | int | 未使用 |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Rectangle\&) 方法

在指定位置以原始實體大小繪製指定的影像。

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Rectangle &rect)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要繪製的影像 |
| rect | const [Rectangle](../../rectangle/)\& | 指定要繪製影像左上角的矩形。矩形的 X 與 Y 屬性指定左上角。寬度與高度值會被忽略。 |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Point\&) 方法

在指定位置以原始實體大小繪製指定的影像。

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Point &point)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 要繪製的影像 |
| point | const [Point](../../point/)\& | 指定繪製影像左上角的 [Point](../../point/) 結構。 |

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [Image](../../image/)
* 類別 [Graphics](../)
* 類別 [Rectangle](../../rectangle/)
* 類別 [Point](../../point/)
* 命名空間 [System::Drawing](../../)
* Library [Aspose.Slides](../../../)