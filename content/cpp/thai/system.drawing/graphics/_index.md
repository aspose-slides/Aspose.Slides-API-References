---
title: Graphics
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "เป็นตัวแทนของพื้นผิวการวาด วัตถุของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดเวลาเรียกใช้งานและ/หรือข้อบกพร่องของการยืนยันค่า ควรหุ้มคลาสนี้ด้วยตัวชี้ System::SmartPtr เสมอและใช้ตัวชี้นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้ฟังก์ชันต่างๆ"
type: docs
weight: 118
url: /th/system.drawing/graphics/
---
## Graphics คลาส

แสดงพื้นผิวการวาด. อ็อบเจ็กต์ของคลาสนี้ควรได้รับการจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new, เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการตรวจสอบความถูกต้อง. เสมอห่อคลาสนี้เข้าในพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งผ่านไปยังฟังก์ชันเป็นอาร์กิวเมนต์.

```cpp
class Graphics : public virtual System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| void [AddMetafileComment](./addmetafilecomment/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | ยังไม่ได้ดำเนินการ. |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsContainer](../../system.drawing.drawing2d/graphicscontainer/)\> [BeginContainer](./begincontainer/)() | บันทึกคอนเทนเนอร์ที่มีสถานะปัจจุบันของอ็อบเจ็กต์นี้, เปิดและใช้คอนเทนเนอร์ใหม่แล้วคืนค่าคอนเทนเนอร์ที่บันทึกไว้. |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsContainer](../../system.drawing.drawing2d/graphicscontainer/)\> [BeginContainer](./begincontainer/)([Rectangle](../rectangle/), [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/)) | บันทึกคอนเทนเนอร์ที่มีสถานะปัจจุบันของอ็อบเจ็กต์นี้, เปิดและใช้คอนเทนเนอร์ใหม่แล้วคืนค่าคอนเทนเนอร์ที่บันทึกไว้. |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsContainer](../../system.drawing.drawing2d/graphicscontainer/)\> [BeginContainer](./begincontainer/)([RectangleF](../rectanglef/), [RectangleF](../rectanglef/), [GraphicsUnit](../graphicsunit/)) | บันทึกคอนเทนเนอร์ที่มีสถานะปัจจุบันของอ็อบเจ็กต์นี้, เปิดและใช้คอนเทนเนอร์ใหม่แล้วคืนค่าคอนเทนเนอร์ที่บันทึกไว้. |
| void [Clear](./clear/)([Color](../color/)) | ลบพื้นผิวการวาดที่แสดงโดยอ็อบเจ็กต์ปัจจุบันและเติมด้วยสีที่ระบุ. |
| void [CopyFromScreen](./copyfromscreen/)([Point](../point/), [Point](../point/), [Size](../size/), [CopyPixelOperation](../copypixeloperation/)) | ยังไม่ได้ดำเนินการ. |
| void [CopyFromScreen](./copyfromscreen/)(**int32_t**, **int32_t**, **int32_t**, **int32_t**, [Size](../size/), [CopyPixelOperation](../copypixeloperation/)) | ยังไม่ได้ดำเนินการ. |
| void [Dispose](./dispose/)() | ปล่อยทรัพยากรระบบปฏิบัติการทั้งหมดที่อ็อบเจ็กต์ปัจจุบันได้ครอบครอง. |
| void [DrawArc](./drawarc/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **int32_t**, **int32_t**, **int32_t**, **int32_t**, **int32_t**, **int32_t**) | วาดส่วนโค้งที่ระบุโดยใช้ปากกาที่ระบุบนพื้นผิวที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [DrawArc](./drawarc/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **float**, **float**, **float**, **float**, **float**, **float**) | วาดส่วนโค้งที่ระบุโดยใช้ปากกาที่ระบุบนพื้นผิวที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [DrawArc](./drawarc/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [Rectangle](../rectangle/), **float**, **float**) | วาดส่วนโค้งที่ระบุโดยใช้ปากกาที่ระบุบนพื้นผิวที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [DrawArc](./drawarc/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [RectangleF](../rectanglef/), **float**, **float**) | วาดส่วนโค้งที่ระบุโดยใช้ปากกาที่ระบุบนพื้นผิวที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [DrawBezier](./drawbezier/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [Point](../point/)\&, const [Point](../point/)\&, const [Point](../point/)\&, const [Point](../point/)\&) | ยังไม่ได้ดำเนินการ. |
| void [DrawBezier](./drawbezier/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [PointF](../pointf/)\&, const [PointF](../pointf/)\&, const [PointF](../pointf/)\&, const [PointF](../pointf/)\&) | ยังไม่ได้ดำเนินการ. |
| void [DrawBezier](./drawbezier/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **float**, **float**, **float**, **float**, **float**, **float**, **float**, **float**) | ยังไม่ได้ดำเนินการ. |
| void [DrawBeziers](./drawbeziers/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&) | วาดชุดของเส้นเบเซียร์โดยใช้ปากกาที่ระบุ. |
| void [DrawBeziers](./drawbeziers/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&) | วาดชุดของเส้นเบเซียร์โดยใช้ปากกาที่ระบุ. |
| void [DrawClosedCurve](./drawclosedcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, **float**, [Drawing2D::FillMode](../../system.drawing.drawing2d/fillmode/)) | วาดเส้น spline ปิดโดยใช้ปากกาที่ระบุ. |
| void [DrawClosedCurve](./drawclosedcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, **float**, [Drawing2D::FillMode](../../system.drawing.drawing2d/fillmode/)) | วาดเส้น spline ปิดโดยใช้ปากกาที่ระบุ. |
| void [DrawCurve](./drawcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, **float**) | วาดเส้น spline โดยใช้ปากกาที่ระบุ. |
| void [DrawCurve](./drawcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, **float**) | วาดเส้น spline โดยใช้ปากกาที่ระบุ. |
| void [DrawCurve](./drawcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, **int32_t**, **int32_t**, **float**) | วาดเส้น spline โดยใช้ปากกาที่ระบุ. |
| void [DrawCurve](./drawcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, **int32_t**, **int32_t**, **float**) | วาดเส้น spline โดยใช้ปากกาที่ระบุ. |
| void [DrawEllipse](./drawellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [Rectangle](../rectangle/)) | วาดรูปวงรีที่ระบุโดยใช้ปากกาที่ระบุบนพื้นผิวที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [DrawEllipse](./drawellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [RectangleF](../rectanglef/)) | วาดรูปวงรีที่ระบุโดยใช้ปากกาที่ระบุบนพื้นผิวที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [DrawEllipse](./drawellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, int, int, int, int) | วาดรูปวงรีที่ระบุโดยใช้ปากกาที่ระบุบนพื้นผิวที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [DrawEllipse](./drawellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **float**, **float**, **float**, **float**) | วาดรูปวงรีที่ระบุโดยใช้ปากกาที่ระบุบนพื้นผิวที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [DrawIcon](./drawicon/)(const [SharedPtr](../../system/sharedptr/)\<[Icon](../icon/)\>\&, [Rectangle](../rectangle/)) | ยังไม่ได้ดำเนินการ. |
| void [DrawIcon](./drawicon/)(const [SharedPtr](../../system/sharedptr/)\<[Icon](../icon/)\>\&, **int32_t**, **int32_t**) | ยังไม่ได้ดำเนินการ. |
| void [DrawIconUnstretched](./drawiconunstretched/)(const [SharedPtr](../../system/sharedptr/)\<[Icon](../icon/)\>\&, [Rectangle](../rectangle/)) | ยังไม่ได้ดำเนินการ. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [System::ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&) | ยังไม่ได้ดำเนินการ. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [System::ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, const [RectangleF](../rectanglef/)\&, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&) | วาดส่วนที่ระบุของภาพที่ระบุในตำแหน่งที่ระบุ. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const System::Details::ArrayView\<[PointF](../pointf/)\>\&, const [RectangleF](../rectanglef/)\&, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&) | วาดส่วนที่ระบุของภาพที่ระบุในตำแหน่งที่ระบุ. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const System::Details::StackArray\<[PointF](../pointf/), N\>\&, const [RectangleF](../rectanglef/)\&, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&) | วาดส่วนที่ระบุของภาพที่ระบุในตำแหน่งที่ระบุ. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int) | วาดภาพที่ระบุในตำแหน่งที่ระบุ. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, **float**, **float**) | วาดภาพที่ระบุในตำแหน่งที่ระบุ. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Point](../point/)) | วาดภาพที่ระบุในตำแหน่งที่ระบุ. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [PointF](../pointf/)) | วาดภาพที่ระบุในตำแหน่งที่ระบุ. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int, int, int) | วาดภาพที่ระบุไปยังสี่เหลี่ยมที่ระบุ. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, **float**, **float**, **float**, **float**) | วาดภาพที่ระบุไปยังสี่เหลี่ยมที่ระบุ. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [RectangleF](../rectanglef/), [RectangleF](../rectanglef/), [GraphicsUnit](../graphicsunit/)) | วาดส่วนที่ระบุของภาพที่ระบุในตำแหน่งที่ระบุ. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/)) | วาดส่วนที่ระบุของภาพที่ระบุในตำแหน่งที่ระบุ. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int, [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/)) | วาดส่วนที่ระบุของภาพที่ระบุในตำแหน่งที่ระบุ. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Rectangle](../rectangle/)\&) | วาดภาพที่ระบุในตำแหน่งที่ระบุ. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [RectangleF](../rectanglef/)\&) | วาดภาพที่ระบุในตำแหน่งที่ระบุ. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), int, int, int, int, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&) | วาดส่วนที่ระบุของภาพที่ระบุไปยังสี่เหลี่ยมที่ระบุ. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), **float**, **float**, **float**, **float**, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&) | วาดส่วนที่ระบุของภาพที่ระบุไปยังสี่เหลี่ยมที่ระบุ. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), int, int, int, int, [GraphicsUnit](../graphicsunit/)) | วาดส่วนที่ระบุของภาพที่ระบุไปยังสี่เหลี่ยมที่ระบุ. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), **float**, **float**, **float**, **float**, [GraphicsUnit](../graphicsunit/)) | วาดส่วนที่ระบุของภาพที่ระบุไปยังสี่เหลี่ยมที่ระบุ. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), int, int, int, int, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&, [Graphics::DrawImageAbort](./drawimageabort/)) | ยังไม่ได้ดำเนินการ. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), **float**, **float**, **float**, **float**, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&, [Graphics::DrawImageAbort](./drawimageabort/)) | ยังไม่ได้ดำเนินการ. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), int, int, int, int, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&, [Graphics::DrawImageAbort](./drawimageabort/), IntPtr) | ยังไม่ได้ดำเนินการ. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), **float**, **float**, **float**, **float**, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&, [Graphics::DrawImageAbort](./drawimageabort/), IntPtr) | ยังไม่ได้ดำเนินการ. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, [RectangleF](../rectanglef/), [GraphicsUnit](../graphicsunit/)) | ยังไม่ได้ดำเนินการ. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&) | ยังไม่ได้ดำเนินการ. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/)) | ยังไม่ได้ดำเนินการ. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/), const [SharedPtr](../../system/sharedptr/)\<[Imaging::ImageAttributes](../../system.drawing.imaging/imageattributes/)\>\&) | วาดส่วนที่ระบุของภาพที่ระบุในตำแหน่งที่ระบุ. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, **float**, **float**, [RectangleF](../rectanglef/), [GraphicsUnit](../graphicsunit/)) | วาดส่วนที่ระบุของภาพที่ระบุในตำแหน่งที่ระบุ. |
| void [DrawImageUnscaled](./drawimageunscaled/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int) | วาดภาพที่ระบุโดยใช้ขนาดจริงของมันที่ตำแหน่งที่ระบุ. |
| void [DrawImageUnscaled](./drawimageunscaled/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int, int, int) | วาดภาพที่ระบุโดยใช้ขนาดจริงของมันในตำแหน่งที่ระบุ. |
| void [DrawImageUnscaled](./drawimageunscaled/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Rectangle](../rectangle/)\&) | วาดภาพที่ระบุโดยใช้ขนาดจริงของมันในตำแหน่งที่ระบุ. |
| void [DrawImageUnscaled](./drawimageunscaled/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Point](../point/)\&) | วาดภาพที่ระบุโดยใช้ขนาดจริงของมันในตำแหน่งที่ระบุ. |
| void [DrawImageUnscaledAndClipped](./drawimageunscaledandclipped/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/)) | ยังไม่ได้ดำเนินการ. |
| void [DrawLine](./drawline/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [Point](../point/), [Point](../point/)) | วาดเส้นที่ระบุโดยใช้ปากกาที่ระบุ. |
| void [DrawLine](./drawline/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [PointF](../pointf/), [PointF](../pointf/)) | วาดเส้นที่ระบุโดยใช้ปากกาที่ระบุ. |
| void [DrawLine](./drawline/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, int, int, int, int) | วาดเส้นที่ระบุโดยใช้ปากกาที่ระบุ. |
| void [DrawLine](./drawline/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **float**, **float**, **float**, **float**) | วาดเส้นที่ระบุโดยใช้ปากกาที่ระบุ. |
| void [DrawLines](./drawlines/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [System::ArrayPtr](../../system/arrayptr/)\<[System::Drawing::Point](../point/)\>\&) | วาดชุดของส่วนเส้นโดยใช้ปากกาที่ระบุ. |
| void [DrawLines](./drawlines/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [System::ArrayPtr](../../system/arrayptr/)\<[System::Drawing::PointF](../pointf/)\>\&) | วาดชุดของส่วนเส้นโดยใช้ปากกาที่ระบุ. |
| void [DrawPath](./drawpath/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | วาดเส้นทางที่ระบุโดยใช้ปากกาที่ระบุ. |
| void [DrawPie](./drawpie/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **int32_t**, **int32_t**, **int32_t**, **int32_t**, **int32_t**, **int32_t**) | วาดพายที่ระบุโดยใช้ปากกาที่ระบุบนพื้นผิวที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [DrawPie](./drawpie/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **float**, **float**, **float**, **float**, **float**, **float**) | วาดพายที่ระบุโดยใช้ปากกาที่ระบุบนพื้นผิวที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [DrawPie](./drawpie/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [Rectangle](../rectangle/), **float**, **float**) | วาดพายที่ระบุโดยใช้ปากกาที่ระบุบนพื้นผิวที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [DrawPie](./drawpie/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [RectangleF](../rectanglef/), **float**, **float**) | วาดพายที่ระบุโดยใช้ปากกาที่ระบุบนพื้นผิวที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [DrawPolygon](./drawpolygon/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&) | วาดรูปหลายเหลี่ยมโดยใช้ปากกาที่ระบุ. |
| void [DrawPolygon](./drawpolygon/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&) | วาดรูปหลายเหลี่ยมโดยใช้ปากกาที่ระบุ |
| void [DrawRectangle](./drawrectangle/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, int, int, int, int) | วาดสี่เหลี่ยมที่ระบุโดยใช้ปากกาที่ระบุบนพื้นผิวที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน |
| void [DrawRectangle](./drawrectangle/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **float**, **float**, **float**, **float**) | วาดสี่เหลี่ยมที่ระบุโดยใช้ปากกาที่ระบุบนพื้นผิวที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน |
| void [DrawRectangle](./drawrectangle/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [Rectangle](../rectangle/)) | วาดสี่เหลี่ยมที่ระบุโดยใช้ปากกาที่ระบุบนพื้นผิวที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน |
| void [DrawRectangles](./drawrectangles/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Rectangle](../rectangle/)\>\&) | วาดชุดของสี่เหลี่ยมโดยใช้ปากกาที่ระบุ |
| void [DrawRectangles](./drawrectangles/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../rectanglef/)\>\&) | วาดชุดของสี่เหลี่ยมโดยใช้ปากกาที่ระบุ |
| void [DrawString](./drawstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Font](../font/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, [PointF](../pointf/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Drawing::StringFormat](../stringformat/)\>\&) | วาดข้อความที่ระบุในตำแหน่งที่ระบุโดยใช้ฟอนต์และแปรงที่ระบุ |
| void [DrawString](./drawstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Font](../font/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, [RectangleF](../rectanglef/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Drawing::StringFormat](../stringformat/)\>\&) | วาดข้อความที่ระบุในสี่เหลี่ยมที่ระบุโดยใช้ฟอนต์และแปรงที่ระบุ |
| void [DrawString](./drawstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Font](../font/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, **float**, **float**, const [System::SharedPtr](../../system/sharedptr/)\<[System::Drawing::StringFormat](../stringformat/)\>\&) | วาดข้อความที่ระบุในตำแหน่งที่ระบุโดยใช้ฟอนต์และแปรงที่ระบุ |
| void [EndContainer](./endcontainer/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsContainer](../../system.drawing.drawing2d/graphicscontainer/)\>\&) | ปิดคอนเทนเนอร์ปัจจุบันและกู้คืนสถานะของอ็อบเจ็กต์นี้จากสถานะของคอนเทนเนอร์ที่บันทึกไว้ |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | ยังไม่ได้ดำเนินการ |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | ยังไม่ได้ดำเนินการ |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [Point](../point/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | ยังไม่ได้ดำเนินการ |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [PointF](../pointf/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | ยังไม่ได้ดำเนินการ |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [Rectangle](../rectangle/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | ยังไม่ได้ดำเนินการ |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [RectangleF](../rectanglef/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | ยังไม่ได้ดำเนินการ |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [Point](../point/), [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | ยังไม่ได้ดำเนินการ |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [PointF](../pointf/), [RectangleF](../rectanglef/), [GraphicsUnit](../graphicsunit/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | ยังไม่ได้ดำเนินการ |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | ยังไม่ได้ดำเนินการ |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, [RectangleF](../rectanglef/), [GraphicsUnit](../graphicsunit/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | ยังไม่ได้ดำเนินการ |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [Rectangle](../rectangle/), [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | ยังไม่ได้ดำเนินการ |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [RectangleF](../rectanglef/), [RectangleF](../rectanglef/), [GraphicsUnit](../graphicsunit/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | ยังไม่ได้ดำเนินการ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าตามสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบตัวเลขทศนิยมแบบ C# ที่สองค่า NaN ถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบตัวเลขทศนิยมแบบ C# ที่สองค่า NaN ถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย |
| void [ExcludeClip](./excludeclip/)([Rectangle](../rectangle/)) | ยังไม่ได้ดำเนินการ |
| void [ExcludeClip](./excludeclip/)(const [SharedPtr](../../system/sharedptr/)\<[Region](../region/)\>\&) | ยังไม่ได้ดำเนินการ |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| void [FillClosedCurve](./fillclosedcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, [Drawing2D::FillMode](../../system.drawing.drawing2d/fillmode/), **float**) | วาดเส้นโค้งแบบปิดโดยใช้แปรงที่ระบุ |
| void [FillClosedCurve](./fillclosedcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, [Drawing2D::FillMode](../../system.drawing.drawing2d/fillmode/), **float**) | วาดเส้นโค้งแบบปิดโดยใช้แปรงที่ระบุ |
| void [FillEllipse](./fillellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, [Rectangle](../rectangle/)) | เติมส่วนภายในของวงรีที่ระบุโดยสี่เหลี่ยมขอบเขตโดยใช้แปรงที่ระบุ |
| void [FillEllipse](./fillellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, [RectangleF](../rectanglef/)) | เติมส่วนภายในของวงร

ที่ระบุโดยสี่เหลี่ยมขอบเขตโดยใช้แปรงที่ระบุ |
| void [FillEllipse](./fillellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, int, int, int, int) | เติมส่วนภายในของวงรีที่ระบุโดยสี่เหลี่ยมขอบเขตโดยใช้แปรงที่ระบุ |
| void [FillEllipse](./fillellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, **float**, **float**, **float**, **float**) | เติมส่วนภายในของวงรีที่ระบุโดยสี่เหลี่ยมขอบเขตโดยใช้แปรงที่ระบุ |
| void [FillPath](./fillpath/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | เติมส่วนภายในของเส้นทางที่ระบุโดยใช้แปรงที่ระบุ |
| void [FillPie](./fillpie/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, int, int, int, int, int, int) | เติมส่วนพายที่ระบุโดยใช้แปรงที่ระบุบนพื้นผิวที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน |
| void [FillPie](./fillpie/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, **float**, **float**, **float**, **float**, **float**, **float**) | เติมส่วนพายที่ระบุโดยใช้แปรงที่ระบุบนพื้นผิวที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน |
| void [FillPie](./fillpie/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, [Rectangle](../rectangle/), **float**, **float**) | เติมส่วนพายที่ระบุโดยใช้แปรงที่ระบุบนพื้นผิวที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน |
| void [FillPolygon](./fillpolygon/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, [Drawing2D::FillMode](../../system.drawing.drawing2d/fillmode/)) | เติมส่วนภายในของรูปหลายเหลี่ยมที่ระบุโดยใช้แปรงที่ระบุ |
| void [FillPolygon](./fillpolygon/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, [Drawing2D::FillMode](../../system.drawing.drawing2d/fillmode/)) | เติมส่วนภายในของรูปหลายเหลี่ยมที่ระบุโดยใช้แปรงที่ระบุ |
| void [FillRectangle](./fillrectangle/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, **float**, **float**, **float**, **float**) | เติมสี่เหลี่ยมที่ระบุด้วยแปรงที่ระบุ |
| void [FillRectangle](./fillrectangle/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, int, int, int, int) | เติมสี่เหลี่ยมที่ระบุด้วยแปรงที่ระบุ |
| void [FillRectangle](./fillrectangle/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, [Rectangle](../rectangle/)) | เติมสี่เหลี่ยมที่ระบุด้วยแปรงที่ระบุ |
| void [FillRectangle](./fillrectangle/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, [RectangleF](../rectanglef/)) | เติมสี่เหลี่ยมที่ระบุด้วยแปรงที่ระบุ |
| void [FillRectangles](./fillrectangles/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Rectangle](../rectangle/)\>\&) | เติมสี่เหลี่ยมที่ระบุด้วยแปรงที่ระบุ |
| void [FillRectangles](./fillrectangles/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../rectanglef/)\>\&) | เติมสี่เหลี่ยมที่ระบุด้วยแปรงที่ระบุ |
| void [FillRegion](./fillregion/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Region](../region/)\>\&) | เติมส่วนภายในของพื้นที่ที่ระบุโดยใช้แปรงที่ระบุ |
| void [Flush](./flush/)([Drawing2D::FlushIntention](../../system.drawing.drawing2d/flushintention/)) | เรียกทำงานทันทีของการวาดทั้งหมดที่ค้างอยู่ |
| static [SharedPtr](../../system/sharedptr/)\<[Graphics](./)\> [FromHwnd](./fromhwnd/)(IntPtr) | ยังไม่ได้ดำเนินการ |
| static [SharedPtr](../../system/sharedptr/)\<[Graphics](./)\> [FromHwndInternal](./fromhwndinternal/)(IntPtr) | ยังไม่ได้ดำเนินการ |
| static [SharedPtr](../../system/sharedptr/)\<[Graphics](./)\> [FromImage](./fromimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&) | สร้างอ็อบเจ็กต์ [Graphics](./) ใหม่จากภาพที่ระบุ |
| [SharedPtr](../../system/sharedptr/)\<[Region](../region/)\> [get_Clip](./get_clip/)() | คืนค่าอ็อบเจ็กต์ [Region](../region/) ที่แสดงถึงบริเวณที่จำกัดพื้นที่การวาดของพื้นผิวการวาดที่แสดงโดยอ็อบเจ็กต์ [Graphics](./) ปัจจุบัน |
| [RectangleF](../rectanglef/) [get_ClipBounds](./get_clipbounds/)() const | คืนสี่เหลี่ยมที่ล้อมรอบพื้นที่คลิปของพื้นผิวที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน |
| [Drawing2D::CompositingMode](../../system.drawing.drawing2d/compositingmode/) [get_CompositingMode](./get_compositingmode/)() | คืนค่าที่บ่งชี้ว่าภาพที่ผสมกันถูกวาดอย่างไรบนพื้นผิวที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน |
| [Drawing2D::CompositingQuality](../../system.drawing.drawing2d/compositingquality/) [get_CompositingQuality](./get_compositingquality/)() | คืนค่าที่บ่งชี้ระดับคุณภาพที่ใช้เมื่อผสมภาพ |
| **float** [get_DpiX](./get_dpix/)() | คืนความละเอียดในแนวนอน |
| **float** [get_DpiY](./get_dpiy/)() | คืนความละเอียดในแนวตั้ง |
| [Drawing2D::InterpolationMode](../../system.drawing.drawing2d/interpolationmode/) [get_InterpolationMode](./get_interpolationmode/)() | คืนค่าที่บ่งชี้โหมดการใส่ค่ากลางที่เชื่อมโยงกับอ็อบเจ็กต์ปัจจุบัน |
| **bool** [get_IsClipEmpty](./get_isclipempty/)() const | ยังไม่ได้ดำเนินการ |
| **bool** [get_IsVisibleClipEmpty](./get_isvisibleclipempty/)() const | ยังไม่ได้ดำเนินการ |
| **float** [get_PageScale](./get_pagescale/)() const | คืนค่าการสเกลระหว่างหน่วยโลกและหน่วยหน้า สำหรับอ็อบเจ็กต์ [Graphics](./) ปัจจุบัน |
| [GraphicsUnit](../graphicsunit/) [get_PageUnit](./get_pageunit/)() const | คืนหน่วยการวัดที่ใช้สำหรับพิกัดหน้าในพื้นผิวที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน |
| [Drawing2D::PixelOffsetMode](../../system.drawing.drawing2d/pixeloffsetmode/) [get_PixelOffsetMode](./get_pixeloffsetmode/)() | คืนค่าที่บ่งชี้ว่าพิกเซลถูกเคลื่อนย้ายอย่างไรระหว่างการเรนเดอร์บนพื้นผิวที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน |
| [Point](../point/) [get_RenderingOrigin](./get_renderingorigin/)() const | คืนค่าอ็อบเจ็กต์ [Point](../point/) ที่แสดงต้นกำเนิดการเรนเดอร์ของอ็อบเจ็กต์ [Graphics](./) ปัจจุบันสำหรับการไดโธริ่งและแปรง Hatch |
| [Drawing2D::SmoothingMode](../../system.drawing.drawing2d/smoothingmode/) [get_SmoothingMode](./get_smoothingmode/)() | คืนค่าที่บ่งชี้โหมดการผ่อนคลายที่ใช้ระหว่างการเรนเดอร์บนพื้นผิวที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน |
| **int32_t** [get_TextContrast](./get_textcontrast/)() const | ยังไม่ได้ดำเนินการ |
| [Text::TextRenderingHint](../../system.drawing.text/textrenderinghint/) [get_TextRenderingHint](./get_textrenderinghint/)() | คืนค่าที่บ่งชี้คุณภาพของการเรนเดอร์ข้อความ |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\> [get_Transform](./get_transform/)() | คืนการแปลงเชิงเรขษาโลกสำหรับอ็อบเจ็กต์ [Graphics](./) ปัจจุบัน |
| [RectangleF](../rectanglef/) [get_VisibleClipBounds](./get_visibleclipbounds/)() const | คืนค่าอ็อบเจ็กต์ [RectangleF](../rectanglef/) ที่แสดงสี่เหลี่ยมล้อมรอบของพื้นที่คลิปที่มองเห็นได้ของอ็อบเจ็กต์ [Graphics](./) ปัจจุบัน |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นเทียบเคียงของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ช่วยให้แฮชอ็อบเจ็กต์ที่กำหนดเองได้ |
| IntPtr [GetHdc](./gethdc/)() | ยังไม่ได้ดำเนินการ |
| [Color](../color/) [GetNearestColor](./getnearestcolor/)([Color](../color/)) | ยังไม่ได้ดำเนินการ |
| SkCanvas * [GetSkCanvas](./getskcanvas/)() const |  |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ เทียบเคียงกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| void [IntersectClip](./intersectclip/)(const [System::SharedPtr](../../system/sharedptr/)\<[Region](../region/)\>\&) | อัปเดตพื้นที่คลิปของอ็อบเจ็กต์นี้ให้เป็นส่วนตัดของคลิปปัจจุบันและคลิปที่ระบุ |
| void [IntersectClip](./intersectclip/)([System::Drawing::RectangleF](../rectanglef/)) | อัปเดตพื้นที่คลิปของอ็อบเจ็กต์นี้ให้เป็นส่วนตัดของคลิปปัจจุบันและคลิปที่ระบุ |
| void [IntersectClip](./intersectclip/)([System::Drawing::Rectangle](../rectangle/)) | อัปเดตพื้นที่คลิปของอ็อบเจ็กต์นี้ให้เป็นส่วนตัดของคลิปปัจจุบันและคลิปที่ระบุ |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เทียบเคียงกับตัวดำเนินการ 'is' ของ C# |
| **bool** [IsVisible](./isvisible/)([Point](../point/)) | กำหนดว่าจุดที่ระบุอยู่ภายในพื้นที่คลิปที่มองเห็นได้ของอ็อบเจ็กต์ [Graphics](./) ปัจจุบันหรือไม่ |
| **bool** [IsVisible](./isvisible/)([PointF](../pointf/)) | ยังไม่ได้ดำเนินการ |
| **bool** [IsVisible](./isvisible/)([Rectangle](../rectangle/)) | ยังไม่ได้ดำเนินการ |
| **bool** [IsVisible](./isvisible/)([RectangleF](../rectanglef/)) | ยังไม่ได้ดำเนินการ |
| **bool** [IsVisible](./isvisible/)(**int32_t**, **int32_t**) | ยังไม่ได้ดำเนินการ |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) | ยังไม่ได้ดำเนินการ |
| **bool** [IsVisible](./isvisible/)(**float**, **float**, **float**, **float**) | ยังไม่ได้ดำเนินการ |
| **bool** [IsVisible](./isvisible/)(**int32_t**, **int32_t**, **int32_t**, **int32_t**) | ยังไม่ได้ดำเนินการ |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Region](../region/)\>\> [MeasureCharacterRanges](./measurecharacterranges/)(const [System::String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Font](../font/)\>\&, [RectangleF](../rectanglef/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../stringformat/)\>\&) | คืนอาร์เรย์ของพื้นที่ที่แต่ละอันล้อมรอบตำแหน่งอักขระในข้อความที่ระบุ |
| [SizeF](../sizef/) [MeasureString](./measurestring/)([String](../../system/string/) const\&, [System::SharedPtr](../../system/sharedptr/)\<[Font](../font/)\> const\&, [PointF](../pointf/) const\&, [System::SharedPtr](../../system/sharedptr/)\<[StringFormat](../stringformat/)\> const\&) const | คืนขนาดของข้อความที่ระบุเมื่อวาดด้วยฟอนต์ที่ระบุในรูปแบบที่ระบุ |
| [SizeF](../sizef/) [MeasureString](./measurestring/)([String](../../system/string/) const\&, [System::SharedPtr](../../system/sharedptr/)\<[Font](../font/)\> const\&, int, [System::SharedPtr](../../system/sharedptr/)\<[StringFormat](../stringformat/)\> const\&) const | คืนขนาดของสตริงที่ระบุเมื่อวาดด้วยฟอนต์ที่ระบุในรูปแบบที่ระบุ |
| [SizeF](../sizef/) [MeasureString](./measurestring/)([String](../../system/string/) const\&, [System::SharedPtr](../../system/sharedptr/)\<[Font](../font/)\> const\&, [SizeF](../sizef/) const\&, [System::SharedPtr](../../system/sharedptr/)\<[StringFormat](../stringformat/)\> const\&, int\&, int\&) const | ยังไม่ได้ทำ |
| [SizeF](../sizef/) [MeasureString](./measurestring/)([String](../../system/string/) const\&, [System::SharedPtr](../../system/sharedptr/)\<[Font](../font/)\> const\&, [SizeF](../sizef/) const\&, [System::SharedPtr](../../system/sharedptr/)\<[StringFormat](../stringformat/)\> const\&) const | คืนขนาดของสตริงที่ระบุเมื่อวาดด้วยฟอนต์ที่ระบุในรูปแบบที่ระบุ |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | อ้างอิงของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง |
| void [MultiplyTransform](./multiplytransform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | คูณเมตริกซ์การแปลงโลกของอ็อบเจกต์ [Graphics](./) ปัจจุบันด้วยเมตริกซ์ที่ระบุ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอร์เรเตอร์มอบหมายค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่าด้วยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| void [ReleaseHdc](./releasehdc/)() | ยังไม่ได้ทำ |
| void [ReleaseHdc](./releasehdc/)(IntPtr) | ยังไม่ได้ทำ |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| void [ResetClip](./resetclip/)() | รีเซ็ตพื้นที่คลิปสำหรับกราฟิกนี้เป็นพื้นที่ไม่จำกัด |
| void [ResetTransform](./resettransform/)() | รีเซ็ตเมตริกซ์การแปลงโลกของอ็อบเจกต์ปัจจุบันให้เป็นเมตริกซ์หน่วย |
| void [Restore](./restore/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsState](../../system.drawing.drawing2d/graphicsstate/)\>\&) | กู้สภาพของอ็อบเจกต์นี้จากสภาพที่บันทึกไว้ |
| void [RotateTransform](./rotatetransform/)(**float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | ใช้การหมุนที่ระบุกับเมตริกซ์การแปลงโลกของอ็อบเจกต์ [Graphics](./) ปัจจุบันตามลำดับที่ระบุ |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsState](../../system.drawing.drawing2d/graphicsstate/)\> [Save](./save/)() | บันทึกสภาพปัจจุบันของอ็อบเจกต์นี้และคืนค่าสภาพที่บันทึกไว้ |
| void [ScaleTransform](./scaletransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | ใช้เวกเตอร์สเกลที่ระบุกับเมตริกซ์การแปลงโลกของอ็อบเจกต์ปัจจุบัน |
| void [set_Clip](./set_clip/)(const [SharedPtr](../../system/sharedptr/)\<[Region](../region/)\>\&) | กำหนดพื้นที่ที่จำกัดพื้นที่วาดของพื้นผิวการวาดที่แสดงโดยอ็อบเจกต์ปัจจุบัน |
| void [set_CompositingMode](./set_compositingmode/)([Drawing2D::CompositingMode](../../system.drawing.drawing2d/compositingmode/)) | กำหนดค่าที่ระบุวิธีการวาดภาพที่รวมกันบนพื้นผิวที่แสดงโดยอ็อบเจกต์ปัจจุบัน |
| void [set_CompositingQuality](./set_compositingquality/)([Drawing2D::CompositingQuality](../../system.drawing.drawing2d/compositingquality/)) | กำหนดค่าที่ระบุระดับคุณภาพที่จะใช้เมื่อทำการรวมภาพ |
| void [set_InterpolationMode](./set_interpolationmode/)([Drawing2D::InterpolationMode](../../system.drawing.drawing2d/interpolationmode/)) | กำหนดค่าที่บ่งบอกโหมดการทำอินเทอร์โพเลชันที่เชื่อมโยงกับอ็อบเจกต์ปัจจุบัน |
| void [set_PageScale](./set_pagescale/)(**float**) | กำหนดสเกลระหว่างหน่วยโลกและหน่วยหน้าสำหรับอ็อบเจกต์ [Graphics](./) ปัจจุบัน |
| void [set_PageUnit](./set_pageunit/)([GraphicsUnit](../graphicsunit/)) | กำหนดหน่วยการวัดที่ใช้สำหรับพิกัดหน้าในพื้นผิวที่แสดงโดยอ็อบเจกต์ปัจจุบัน |
| void [set_PixelOffsetMode](./set_pixeloffsetmode/)([Drawing2D::PixelOffsetMode](../../system.drawing.drawing2d/pixeloffsetmode/)) | กำหนดค่าที่ระบุว่าพิกเซลควรชิดออฟเซตอย่างไรระหว่างการเรนเดอร์บนพื้นผิวที่แสดงโดยอ็อบเจกต์ปัจจุบัน |
| void [set_RenderingOrigin](./set_renderingorigin/)([Point](../point/)) | กำหนดอ็อบเจกต์ [Point](../point/) ที่ระบุจุดเริ่มต้นการเรนเดอร์ของอ็อบเจกต์ [Graphics](./) ปัจจุบันสำหรับการทำดีธี่งและแปรง hatch |
| void [set_SmoothingMode](./set_smoothingmode/)([Drawing2D::SmoothingMode](../../system.drawing.drawing2d/smoothingmode/)) | กำหนดค่าที่ระบุโหมดบรรเทาที่ใช้ระหว่างการเรนเดอร์บนพื้นผิวที่แสดงโดยอ็อบเจกต์ปัจจุบัน |
| void [set_TextContrast](./set_textcontrast/)(**int32_t**) | ยังไม่ได้ทำ |
| void [set_TextRenderingHint](./set_textrenderinghint/)([Text::TextRenderingHint](../../system.drawing.text/textrenderinghint/)) | กำหนดค่าที่ระบุคุณภาพการเรนเดอร์ข้อความ |
| void [set_Transform](./set_transform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | กำหนดการแปลงโลกเชิงเรขาคณิตสำหรับอ็อบเจกต์ [Graphics](./) ปัจจุบัน |
| void [SetClip](./setclip/)(const [SharedPtr](../../system/sharedptr/)\<[Region](../region/)\>\&, [Drawing2D::CombineMode](../../system.drawing.drawing2d/combinemode/)) | กำหนดพื้นที่คลิปของพื้นผิวการวาดที่แสดงโดยอ็อบเจกต์ [Graphics](./) ปัจจุบันให้เป็นผลลัพธ์ของการดำเนินการที่ระบุซึ่งรวมพื้นที่คลิปปัจจุบันและพื้นที่ที่ระบุ |
| void [SetClip](./setclip/)([Rectangle](../rectangle/), [Drawing2D::CombineMode](../../system.drawing.drawing2d/combinemode/)) | กำหนดพื้นที่คลิปของพื้นผิวการวาดที่แสดงโดยอ็อบเจกต์ [Graphics](./) ปัจจุบันให้เป็นผลลัพธ์ของการดำเนินการที่ระบุซึ่งรวมพื้นที่คลิปปัจจุบันและพื้นที่ที่ระบุ |
| void [SetClip](./setclip/)([RectangleF](../rectanglef/), [Drawing2D::CombineMode](../../system.drawing.drawing2d/combinemode/)) | กำหนดพื้นที่คลิปของพื้นผิวการวาดที่แสดงโดยอ็อบเจกต์ [Graphics](./) ปัจจุบันให้เป็นผลลัพธ์ของการดำเนินการที่ระบุซึ่งรวมพื้นที่คลิปปัจจุบันและพื้นที่ที่ระบุ |
| void [SetClip](./setclip/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](./)\>\&, [Drawing2D::CombineMode](../../system.drawing.drawing2d/combinemode/)) | ยังไม่ได้ทำ |
| void [SetClip](./setclip/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&, [Drawing2D::CombineMode](../../system.drawing.drawing2d/combinemode/)) | กำหนดพื้นที่คลิปของพื้นผิวการวาดที่แสดงโดยอ็อบเจกต์ [Graphics](./) ปัจจุบันให้เป็นผลลัพธ์ของการดำเนินการที่ระบุซึ่งรวมพื้นที่คลิปปัจจุบันกับพื้นที่ที่ระบุโดยเส้นทางกราฟิก |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทน shared) . อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของเคาน์เตอร์อ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; แทนนั้นให้ใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; แทนนั้นให้ใช้ smart pointers หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | อ้างอิงของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริง |
| void [TransformPoints](./transformpoints/)([Drawing2D::CoordinateSpace](../../system.drawing.drawing2d/coordinatespace/), [Drawing2D::CoordinateSpace](../../system.drawing.drawing2d/coordinatespace/), const [ArrayPtr](../../system/arrayptr/)\<[System::Drawing::Point](../point/)\>\&) | ยังไม่ได้ทำ |
| void [TransformPoints](./transformpoints/)([Drawing2D::CoordinateSpace](../../system.drawing.drawing2d/coordinatespace/), [Drawing2D::CoordinateSpace](../../system.drawing.drawing2d/coordinatespace/), const [ArrayPtr](../../system/arrayptr/)\<[System::Drawing::PointF](../pointf/)\>\&) | ยังไม่ได้ทำ |
| void [TranslateClip](./translateclip/)(int, int) | ยังไม่ได้ทำ |
| void [TranslateClip](./translateclip/)(**float**, **float**) | ยังไม่ได้ทำ |
| void [TranslateTransform](./translatetransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | ใช้เวกเตอร์การแปลที่ระบุกับเมตริกซ์การแปลงโลกของอ็อบเจกต์ [Graphics](./) ปัจจุบัน |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการโครงสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกคำสั่ง C# lock(). เรียกโดยตรงหรือใช้อ็อบเจ็กต์ sentry [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนนั้นให้ใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนนั้นให้ใช้ smart pointers หรือ ThisProtector |
|  [~Graphics](./~graphics/)() |  |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |
## ชนิดนิยาม

| ชนิดนิยาม | คำอธิบาย |
| --- | --- |
| [EnumerateMetafileProc](./enumeratemetafileproc/) | ประเภทของอ็อบเจกต์ฟังก์ชัน callback ที่ใช้เป็นอาร์กิวเมนต์สำหรับเมธอด EnumerateMetafile |
| [DrawImageAbort](./drawimageabort/) | ประเภทของอ็อบเจกต์ฟังก์ชัน callback ที่ใช้เป็นอาร์กิวเมนต์สำหรับเมธอด DrawImage |
## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [System::Drawing](../)
* ไลบรารี [Aspose.Slides](../../)