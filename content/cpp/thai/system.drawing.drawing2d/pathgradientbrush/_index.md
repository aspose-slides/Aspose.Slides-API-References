---
title: PathGradientBrush
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "แทนสัดส่วนของแปรงที่เติมภายในของวัตถุ GraphicsPath ด้วยการไล่ระดับสี. วัตถุของคลาสนี้ควรได้รับการจัดสรรเฉพาะโดยใช้ฟังก์ชัน System::MakeObject(). ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new, เพราะจะทำให้เกิดข้อผิดพลาดระหว่างรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ. ควรหุ้มคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้ฟังก์ชัน."
type: docs
weight: 144
url: /th/system.drawing.drawing2d/pathgradientbrush/
---
## PathGradientBrush คลาส

แทนสัดส่วนของแปรงที่เติมภายในของวัตถุ [GraphicsPath](../graphicspath/) ด้วยการไล่ระดับสี. วัตถุของคลาสนี้ควรได้รับการจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/). ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดระหว่างรันไทม์และ/หรือข้อผิดพลาดการยืนยัน. ควรหุ้มคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้ฟังก์ชัน.

```cpp
class PathGradientBrush : public System::Drawing::Brush
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | สร้างสำเนาของวัตถุปัจจุบัน |
| virtual void [Dispose](../../system/idisposable/dispose/)() | ไม่ทำอะไร |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่า floating point แบบ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่า floating point แบบ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้ภายในเท่านั้น |
| [SharedPtr](../../system/sharedptr/)\<[Blend](../blend/)\> [get_Blend](./get_blend/)() const | ยังไม่ได้ดำเนินการ |
| [Color](../../system.drawing/color/) [get_CenterColor](./get_centercolor/)() const | ส่งคืนสีที่อยู่ที่จุดศูนย์กลางของเส้นทางที่วัตถุปัจจุบันเติม |
| [PointF](../../system.drawing/pointf/) [get_CenterPoint](./get_centerpoint/)() const | รับจุดศูนย์กลางของการไล่ระดับสี |
| [PointF](../../system.drawing/pointf/) [get_FocusScales](./get_focusscales/)() const | รับจุดโฟกัสสำหรับการลดระดับสี |
| [SharedPtr](../../system/sharedptr/)\<[ColorBlend](../colorblend/)\> [get_InterpolationColors](./get_interpolationcolors/)() const | ส่งคืนค่าที่กำหนดการไล่ระดับสีเชิงเส้นหลายสี |
| [RectangleF](../../system.drawing/rectanglef/) [get_Rectangle](./get_rectangle/)() | ยังไม่ได้ดำเนินการ |
| [ArrayPtr](../../system/arrayptr/)\<[Color](../../system.drawing/color/)\> [get_SurroundColors](./get_surroundcolors/)() const | ส่งคืนสีที่สอดคล้องกับจุดในเส้นทางที่ [PathGradientBrush](./) นี้เติม |
| [SharedPtr](../../system/sharedptr/)\<[Matrix](../matrix/)\> [get_Transform](./get_transform/)() const | ส่งคืนสำเนาของวัตถุ [Matrix](../matrix/) ที่ระบุการเปลี่ยนรูปเรขาคณิตสำหรับแปรงที่วัตถุปัจจุบันแสดง |
| [WrapMode](../wrapmode/) [get_WrapMode](./get_wrapmode/)() const | ส่งคืนโหมดการห่อ |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เกี่ยวข้องกับวัตถุ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชวัตถุแบบกำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับชนิดจริงของวัตถุ. คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. คล้ายกับตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการคัดลอกประเภทกำหนดเอง |
| void [MultiplyTransform](./multiplytransform/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](../matrix/)\>\&, [MatrixOrder](../matrixorder/)) | คูณเมทริกซ์การแปลงของวัตถุปัจจุบันด้วยเมทริกซ์ที่ระบุ |
|  [Object](../../system/object/object/)() | สร้างวัตถุ. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. จริงๆ แล้วไม่ได้คัดลอ้วนอะไร เพียงแค่เริ่มต้นวัตถุใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมาย. จริงๆ แล้วไม่ได้คัดลอ้วนอะไร เพียงแค่เริ่มต้นวัตถุใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
|  [PathGradientBrush](./pathgradientbrush/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, [WrapMode](../wrapmode/)) | สร้างอินสแตนซ์ใหม่ของคลาส [PathGradientBrush](./) |
|  [PathGradientBrush](./pathgradientbrush/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, [WrapMode](../wrapmode/)) | สร้างอินสแตนซ์ใหม่ของคลาส [PathGradientBrush](./) |
|  [PathGradientBrush](./pathgradientbrush/)(const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](../graphicspath/)\>\&) | สร้างอินสแตนซ์ใหม่ของคลาส [PathGradientBrush](./) |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงวัตถุประเภทค่ากับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| void [ResetTransform](./resettransform/)() | รีเซ็ตเมทริกซ์การแปลงของวัตถุปัจจุบันให้เป็นเมทริกซ์เอกลักษณ์ |
| void [RotateTransform](./rotatetransform/)(**float**, [Drawing2D::MatrixOrder](../matrixorder/)) | หมุนการแปลงเรขาคณิตท้องถิ่นโดยมุมที่ระบุในลำดับที่กำหนด |
| void [ScaleTransform](./scaletransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../matrixorder/)) | ปรับขนาดการแปลงเรขาคณิตท้องถิ่นโดยปัจจัยที่ระบุในลำดับที่กำหนด |
| void [set_Blend](./set_blend/)(const [SharedPtr](../../system/sharedptr/)\<[Blend](../blend/)\>\&) | ตั้งค่าการผสมที่กำหนดปัจจัยและตำแหน่งของสีพื้นฐานสำหรับแปรงนี้ |
| void [set_CenterColor](./set_centercolor/)([Color](../../system.drawing/color/)) | ตั้งค่าสีที่อยู่ที่ศูนย์กลางของเส้นทางที่วัตถุปัจจุบันเติม |
| void [set_CenterPoint](./set_centerpoint/)(const [PointF](../../system.drawing/pointf/)\&) | ตั้งค่าจุดศูนย์กลางของการไล่ระดับสี |
| void [set_FocusScales](./set_focusscales/)(const [PointF](../../system.drawing/pointf/)\&) | ตั้งค่าจุดโฟกัสสำหรับการลดระดับสี |
| void [set_InterpolationColors](./set_interpolationcolors/)(const [SharedPtr](../../system/sharedptr/)\<[ColorBlend](../colorblend/)\>\&) | ตั้งค่าค่าที่กำหนดการไล่ระดับสีเชิงเส้นหลายสี |
| void [set_SurroundColors](./set_surroundcolors/)(const [ArrayPtr](../../system/arrayptr/)\<[Color](../../system.drawing/color/)\>\&) | ตั้งค่าสีที่สอดคล้องกับจุดในเส้นทางที่ [PathGradientBrush](./) นี้เติม |
| void [set_Transform](./set_transform/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](../matrix/)\>\&) | ตั้งค่าวัตถุ [Matrix](../matrix/) ที่ระบุการเปลี่ยนรูปเรขาคณิตสำหรับแปรงที่วัตถุปัจจุบันแสดง |
| void [set_WrapMode](./set_wrapmode/)([WrapMode](../wrapmode/)) | ตั้งค่าโหมดการห่อ |
| void [SetBlendTriangularShape](./setblendtriangularshape/)(**float**, **float**) | ยังไม่ได้ดำเนินการ |
| void [SetSigmaBellShape](./setsigmabellshape/)(**float**, **float**) | ยังไม่ได้ดำเนินการ |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็นพอยน์เตอร์อ่อน (แทนการแชร์). อนุญาตให้เปลี่ยนพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมดอ่อน |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและส่งคืนตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงวัตถุกำหนดเองเป็นสตริง |
| void [TranslateTransform](./translatetransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../matrixorder/)) | แปลการแปลงเรขาคณิตท้องถิ่นโดยตามขนาดที่ระบุในลำดับที่กำหนด |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงอ่อน. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงอ่อน. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายวัตถุ. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [Brush](../../system.drawing/brush/)
* เนมสเปซ [System::Drawing::Drawing2D](../)
* ไลบรารี [Aspose.Slides](../../)