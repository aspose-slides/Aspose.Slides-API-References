---
title: DrawImageUnscaled()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: วาดรูปภาพที่ระบุโดยใช้ขนาดจริงตามกายภาพที่ตำแหน่งที่กำหนด
type: docs
weight: 443
url: /th/system.drawing/graphics/drawimageunscaled/
---
## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int) method

วาดรูปภาพที่กำหนดโดยใช้ขนาดจริงตามกายภาพที่ตำแหน่งที่ระบุ

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | รูปภาพที่ต้องวาด |
| x | int | พิกัด X ของมุมซ้ายบนของรูปภาพที่วาด |
| y | int | พิกัด Y ของมุมซ้ายบนของรูปภาพที่วาด |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int, int, int) method

วาดรูปภาพที่กำหนดโดยใช้ขนาดจริงตามกายภาพที่ตำแหน่งที่ระบุ

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y, int width, int height)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | รูปภาพที่ต้องวาด |
| x | int | พิกัด X ของมุมซ้ายบนของรูปภาพที่วาด |
| y | int | พิกัด Y ของมุมซ้ายบนของรูปภาพที่วาด |
| width | int | ไม่ได้ใช้ |
| height | int | ไม่ได้ใช้ |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Rectangle\&) method

วาดรูปภาพที่กำหนดโดยใช้ขนาดจริงตามกายภาพที่ตำแหน่งที่ระบุ

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Rectangle &rect)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | รูปภาพที่ต้องวาด |
| rect | const [Rectangle](../../rectangle/)\& | สี่เหลี่ยมที่ระบุมุมซ้ายบนของรูปภาพที่วาด. คุณสมบัติ X และ Y ของสี่เหลี่ยมกำหนดมุมซ้ายบน. ค่าความกว้างและความสูงจะถูกละเว้น. |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Point\&) method

วาดรูปภาพที่กำหนดโดยใช้ขนาดจริงตามกายภาพที่ตำแหน่งที่ระบุ

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Point &point)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | รูปภาพที่ต้องวาด |
| point | const [Point](../../point/)\& | โครงสร้าง [Point](../../point/) ที่ระบุมุมซ้ายบนของรูปภาพที่วาด. |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Image](../../image/)
* คลาส [Graphics](../)
* คลาส [Rectangle](../../rectangle/)
* คลาส [Point](../../point/)
* เนมสเปซ [System::Drawing](../../)
* ไลบรารี [Aspose.Slides](../../../)