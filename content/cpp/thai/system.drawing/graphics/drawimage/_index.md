---
title: DrawImage()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ยังไม่ได้ดำเนินการ.
type: docs
weight: 430
url: /th/system.drawing/graphics/drawimage/
---
## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<Point\>\&) เมธอด

ยังไม่ได้ดำเนินการ.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<Point> &destPoints)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ละเว้น |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | ละเว้น |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) เมธอด

วาดส่วนที่ระบุของรูปภาพที่ระบุไว้ที่ตำแหน่งที่ระบุ

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ภาพที่จะวาด |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | อาร์เรย์ที่มีจุดสามจุดซึ่งกำหนดรูปสี่เหลี่ยมขนานบนพื้นผิวการวาดเพื่อวาดรูปภาพ |
| srcRect | const [RectangleF](../../rectanglef/)\& | สี่เหลี่ยมที่กำหนดบริเวณของรูปภาพที่ระบุเพื่อวาด |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | หน่วยวัดที่ใช้โดยพารามิเตอร์ **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | ระบุข้อมูลการจัดสีและแกมมาของรูปภาพ |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::ArrayView\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) เมธอด

วาดส่วนที่ระบุของรูปภาพที่ระบุไว้ที่ตำแหน่งที่ระบุ

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::ArrayView<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ภาพที่จะวาด |
| destPoints | const System::Details::ArrayView\<[PointF](../../pointf/)\>\& | มุมมองอาเรย์ที่มีจุดสามจุดซึ่งกำหนดรูปสี่เหลี่ยมขนานบนพื้นผิวการวาดเพื่อวาดรูปภาพ |
| srcRect | const [RectangleF](../../rectanglef/)\& | สี่เหลี่ยมที่กำหนดบริเวณของรูปภาพที่ระบุเพื่อวาด |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | หน่วยวัดที่ใช้โดยพารามิเตอร์ **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | ระบุข้อมูลการจัดสีและแกมมาของรูปภาพ |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::StackArray\<PointF, N\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) เมธอด

วาดส่วนที่ระบุของรูปภาพที่ระบุไว้ที่ตำแหน่งที่ระบุ

```cpp
template<std::size_t> void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::StackArray<PointF, N> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ภาพที่จะวาด |
| destPoints | const System::Details::StackArray\<[PointF](../../pointf/), N\>\& | สแตกอาเรย์ที่มีจุดสามจุดซึ่งกำหนดรูปสี่เหลี่ยมขนานบนพื้นผิวการวาดเพื่อวาดรูปภาพ |
| srcRect | const [RectangleF](../../rectanglef/)\& | สี่เหลี่ยมที่กำหนดบริเวณของรูปภาพที่ระบุเพื่อวาด |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | หน่วยวัดที่ใช้โดยพารามิเตอร์ **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | ระบุข้อมูลการจัดสีและแกมมาของรูปภาพ |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int) เมธอด

วาดรูปภาพที่ระบุที่ตำแหน่งที่ระบุ

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ภาพที่จะวาด |
| x | int | พิกัด X ของมุมซ้ายบนของรูปภาพที่วาด |
| y | int | พิกัด Y ของมุมซ้ายบนของรูปภาพที่วาด |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float) เมธอด

วาดรูปภาพที่ระบุที่ตำแหน่งที่ระบุ

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ภาพที่จะวาด |
| x | **float** | พิกัด X ของมุมซ้ายบนของรูปภาพที่วาด |
| y | **float** | พิกัด Y ของมุมซ้ายบนของรูปภาพที่วาด |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Point) เมธอด

วาดรูปภาพที่ระบุที่ตำแหน่งที่ระบุ

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Point pt)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ภาพที่จะวาด |
| pt | [Point](../../point/) | ตำแหน่งของมุมซ้ายบนของรูปภาพที่วาด |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, PointF) เมธอด

วาดรูปภาพที่ระบุที่ตำแหน่งที่ระบุ

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, PointF pt)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ภาพที่จะวาด |
| pt | [PointF](../../pointf/) | ตำแหน่งของมุมซ้ายบนของรูปภาพที่วาด |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, int, int) เมธอด

วาดรูปภาพที่ระบุไปยังสี่เหลี่ยมที่ระบุ

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, int width, int height)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ภาพที่จะวาด |
| x | int | พิกัด X ของมุมซ้ายบนของสี่เหลี่ยมที่จะวาดรูปภาพ |
| y | int | พิกัด Y ของมุมซ้ายบนของสี่เหลี่ยมที่จะวาดรูปภาพ |
| width | int | ความกว้างของสี่เหลี่ยมที่จะวาดรูปภาพ |
| height | int | ความสูงของสี่เหลี่ยมที่จะวาดรูปภาพ |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, float, float) เมธอด

วาดรูปภาพที่ระบุไปยังสี่เหลี่ยมที่ระบุ

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, float width, float height)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ภาพที่จะวาด |
| x | **float** | พิกัด X ของมุมซ้ายบนของสี่เหลี่ยมที่จะวาดรูปภาพ |
| y | **float** | พิกัด Y ของมุมซ้ายบนของสี่เหลี่ยมที่จะวาดรูปภาพ |
| width | **float** | ความกว้างของสี่เหลี่ยมที่จะวาดรูปภาพ |
| height | **float** | ความสูงของสี่เหลี่ยมที่จะวาดรูปภาพ |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, RectangleF, RectangleF, GraphicsUnit) เมธอด

วาดส่วนที่ระบุของรูปภาพที่ระบุไว้ที่ตำแหน่งที่ระบุ

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, RectangleF destRect, RectangleF srcRect, GraphicsUnit srcUnit)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ภาพที่จะวาด |
| destRect | [RectangleF](../../rectanglef/) | สี่เหลี่ยมเพื่อวาดรูปภาพ |
| srcRect | [RectangleF](../../rectanglef/) | สี่เหลี่ยมที่กำหนดบริเวณของรูปภาพที่ระบุเพื่อวาด |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | หน่วยวัดที่ใช้โดยพารามิเตอร์ **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, Rectangle, GraphicsUnit) เมธอด

วาดส่วนที่ระบุของรูปภาพที่ระบุไว้ที่ตำแหน่งที่ระบุ

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, Rectangle srcRect, GraphicsUnit srcUnit)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ภาพที่จะวาด |
| destRect | [Rectangle](../../rectangle/) | สี่เหลี่ยมเพื่อวาดรูปภาพ |
| srcRect | [Rectangle](../../rectangle/) | สี่เหลี่ยมที่กำหนดบริเวณของรูปภาพที่ระบุเพื่อวาด |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | หน่วยวัดที่ใช้โดยพารามิเตอร์ **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, Rectangle, GraphicsUnit) เมธอด

วาดส่วนที่ระบุของรูปภาพที่ระบุไว้ที่ตำแหน่งที่ระบุ

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, Rectangle srcRect, GraphicsUnit srcUnit)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ภาพที่จะวาด |
| x | int | พิกัด X ของมุมซ้ายบนของสี่เหลี่ยมที่จะวาดรูปภาพ |
| y | int | พิกัด Y ของมุมซ้ายบนของสี่เหลี่ยมที่จะวาดรูปภาพ |
| srcRect | [Rectangle](../../rectangle/) | สี่เหลี่ยมที่กำหนดบริเวณของรูปภาพที่ระบุเพื่อวาด |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | หน่วยวัดที่ใช้โดยพารามิเตอร์ **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const Rectangle\&) เมธอด

วาดรูปภาพที่ระบุที่ตำแหน่งที่ระบุ

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const Rectangle &rect)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ภาพที่จะวาด |
| rect | const [Rectangle](../../rectangle/)\& | สี่เหลี่ยมเพื่อวาดรูปภาพ |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const RectangleF\&) เมธอด

วาดรูปภาพที่ระบุที่ตำแหน่งที่ระบุ

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const RectangleF &rect)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ภาพที่จะวาด |
| rect | const [RectangleF](../../rectanglef/)\& | สี่เหลี่ยมเพื่อวาดรูปภาพ |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&) เมธอด

วาดส่วนที่ระบุของรูปภาพที่ระบุไปยังสี่เหลี่ยมที่ระบุ

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ภาพที่จะวาด |
| destRect | [Rectangle](../../rectangle/) | สี่เหลี่ยมเพื่อวาดรูปภาพ |
| srcX | int | พิกัด X ของมุมซ้ายบนของสี่เหลี่ยมที่ระบุส่วนของรูปภาพที่จะวาด |
| srcY | int | พิกัด Y ของมุมซ้ายบนของสี่เหลี่ยมที่ระบุส่วนของรูปภาพที่จะวาด |
| srcWidth | int | ความกว้างของสี่เหลี่ยมที่ระบุส่วนของรูปภาพที่จะวาด |
| srcHeight | int | ความสูงของสี่เหลี่ยมที่ระบุส่วนของรูปภาพที่จะวาด |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | หน่วยวัดที่พารามิเตอร์ **srcX**, **srcY**, **srcWidth** และ **srcHeight** ระบุ |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | ระบุข้อมูลการจัดสีและแกมมาของรูปภาพ |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&) เมธอด

วาดส่วนที่ระบุของรูปภาพที่ระบุไปยังสี่เหลี่ยมที่ระบุ

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ภาพที่จะวาด |
| destRect | [Rectangle](../../rectangle/) | สี่เหลี่ยมเพื่อวาดรูปภาพ |
| srcX | **float** | พิกัด X ของมุมซ้ายบนของสี่เหลี่ยมที่ระบุส่วนของรูปภาพที่จะวาด |
| srcY | **float** | พิกัด Y ของมุมซ้ายบนของสี่เหลี่ยมที่ระบุส่วนของรูปภาพที่จะวาด |
| srcWidth | **float** | ความกว้างของสี่เหลี่ยมที่ระบุส่วนของรูปภาพที่จะวาด |
| srcHeight | **float** | ความสูงของสี่เหลี่ยมที่ระบุส่วนของรูปภาพที่จะวาด |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | หน่วยวัดที่พารามิเตอร์ **srcX**, **srcY**, **srcWidth** และ **srcHeight** ระบุ |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | ระบุข้อมูลการจัดสีและแกมมาของรูปภาพ |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit) เมธอด

วาดส่วนที่ระบุของรูปภาพที่ระบุไปยังสี่เหลี่ยมที่ระบุ

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ภาพที่จะวาด |
| destRect | [Rectangle](../../rectangle/) | สี่เหลี่ยมเพื่อวาดรูปภาพ |
| srcX | int | พิกัด X ของมุมซ้ายบนของสี่เหลี่ยมที่ระบุส่วนของรูปภาพที่จะวาด |
| srcY | int | พิกัด Y ของมุมซ้ายบนของสี่เหลี่ยมที่ระบุส่วนของรูปภาพที่จะวาด |
| srcWidth | int | ความกว้างของสี่เหลี่ยมที่ระบุส่วนของรูปภาพที่จะวาด |
| srcHeight | int | ความสูงของสี่เหลี่ยมที่ระบุส่วนของรูปภาพที่จะวาด |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | หน่วยวัดที่พารามิเตอร์ **srcX**, **srcY**, **srcWidth** และ **srcHeight** ระบุ |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit) เมธอด

วาดส่วนที่ระบุของรูปภาพที่ระบุไปยังสี่เหลี่ยมที่ระบุ

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ภาพที่จะวาด |
| destRect | [Rectangle](../../rectangle/) | สี่เหลี่ยมเพื่อวาดรูปภาพ |
| srcX | **float** | พิกัด X ของมุมซ้ายบนของสี่เหลี่ยมที่ระบุส่วนของรูปภาพที่จะวาด |
| srcY | **float** | พิกัด Y ของมุมซ้ายบนของสี่เหลี่ยมที่ระบุส่วนของรูปภาพที่จะวาด |
| srcWidth | **float** | ความกว้างของสี่เหลี่ยมที่ระบุส่วนของรูปภาพที่จะวาด |
| srcHeight | **float** | ความสูงของสี่เหลี่ยมที่ระบุส่วนของรูปภาพที่จะวาด |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | หน่วยวัดที่พารามิเตอร์ **srcX**, **srcY**, **srcWidth** และ **srcHeight** ระบุ |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) เมธอด

ยังไม่ได้ดำเนินการ.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) เมธอด

ยังไม่ได้ดำเนินการ.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) เมธอด

ยังไม่ได้ดำเนินการ.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) เมธอด

ยังไม่ได้ดำเนินการ.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&, RectangleF, GraphicsUnit) เมธอด

ยังไม่ได้ดำเนินการ.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints, RectangleF srcRect, GraphicsUnit srcUnit)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&) เมธอด

ยังไม่ได้ดำเนินการ.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit) เมธอด

ยังไม่ได้ดำเนินการ.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit, const SharedPtr\<Imaging::ImageAttributes\>\&) เมธอด

วาดส่วนที่ระบุของรูปภาพที่ระบุที่ตำแหน่งที่ระบุ

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit, const SharedPtr<Imaging::ImageAttributes> &imageAttr)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ภาพที่จะวาด |
| destPoints | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | อาร์เรย์ที่มีจุดสามจุดซึ่งกำหนดรูปสี่เหลี่ยมขนานบนพื้นผิวการวาดเพื่อวาดรูปภาพ |
| srcRect | [Rectangle](../../rectangle/) | สี่เหลี่ยมที่กำหนดบริเวณของรูปภาพที่ระบุเพื่อวาด |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | หน่วยวัดที่ใช้โดยพารามิเตอร์ **srcRect** |
| imageAttr | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | ระบุข้อมูลการจัดสีและแกมมาของรูปภาพ |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, RectangleF, GraphicsUnit) เมธอด

วาดส่วนที่ระบุของรูปภาพที่ระบุที่ตำแหน่งที่ระบุ

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, RectangleF srcRect, GraphicsUnit srcUnit)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | ภาพที่จะวาด |
| x | **float** | พิกัด X ของมุมซ้ายบนของสี่เหลี่ยมที่จะวาดรูปภาพ |
| y | **float** | พิกัด Y ของมุมซ้ายบนของสี่เหลี่ยมที่จะวาดรูปภาพ |
| srcRect | [RectangleF](../../rectanglef/) | สี่เหลี่ยมที่กำหนดบริเวณของรูปภาพที่ระบุเพื่อวาด |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | หน่วยวัดที่ใช้โดยพารามิเตอร์ **srcRect** |

## ดูเพิ่ม

* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)
* Typedef [DrawImageAbort](../drawimageabort/)
* Class [Image](../../image/)
* Class [Point](../../point/)
* Class [Graphics](../)
* Class [PointF](../../pointf/)
* Class [RectangleF](../../rectanglef/)
* Class [Rectangle](../../rectangle/)
* Class [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)