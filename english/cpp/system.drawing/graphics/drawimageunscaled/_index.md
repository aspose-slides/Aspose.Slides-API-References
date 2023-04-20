---
title: DrawImageUnscaled()
second_title: Aspose.Slides for C++ API Reference
description: Draws the specified image using its original physical size at the specified location.
type: docs
weight: 443
url: /cpp/system.drawing/graphics/drawimageunscaled/
---
## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int) method


Draws the specified image using its original physical size at the specified location.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | The image to draw |
| x | int | The X coordinate of the upper left corner of the drawn image |
| y | int | The Y coordinate of the upper left corner of the drawn image |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int, int, int) method


Draws a specified image using its original physical size at a specified location.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y, int width, int height)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | The image to draw |
| x | int | The X coordinate of the upper left corner of the drawn image |
| y | int | The Y coordinate of the upper left corner of the drawn image |
| width | int | Not used |
| height | int | Not used |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Rectangle\&) method


Draws a specified image using its original physical size at a specified location.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Rectangle &rect)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | The image to draw |
| rect | const [Rectangle](../../rectangle/)\& | The rectangle that specifies the upper-left corner of the drawn image. The X and Y properties of the rectangle specify the upper-left corner. The width and height values are ignored. |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Point\&) method


Draws a specified image using its original physical size at a specified location.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Point &point)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | The image to draw |
| point | const [Point](../../point/)\& | The [Point](../../point/) structure that specifies the upper-left corner of the drawn image. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Class [Point](../../point/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)