---
title: LinearGradientBrush
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: "แทนแปรงไลเนียร์กรเดียนท์. ออบเจ็กต์ของคลาสนี้ควรจะจัดสรรเฉพาะโดยใช้ฟังก์ชัน System::MakeObject() . อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดขณะทำงานและ/หรือการตรวจสอบข้อผิดพลาด. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr เสมอและใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 105
url: /th/system.drawing.drawing2d/lineargradientbrush/
---
## LinearGradientBrush คลาส


แทนแปรงไลเนียร์กรเดียนท์. ออบเจ็กต์ของคลาสนี้ควรจะถูกจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดขณะทำงานและ/หรือการตรวจสอบข้อผิดพลาด. ห่อย่ามคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) เสมอและใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน.

```cpp
class LinearGradientBrush : public System::Drawing::Brush
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | สร้างสำเนาของออบเจ็กต์ปัจจุบัน. |
| virtual void [Dispose](../../system/idisposable/dispose/)() | ไม่ทำอะไร. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบออบเจ็กต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# โดยที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# โดยที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| [SharedPtr](../../system/sharedptr/)\<[Blend](../blend/)\> [get_Blend](./get_blend/)() const | คืนค่า blend ที่ระบุตัวคูณและตำแหน่งของสีฐานสำหรับแปรงนี้. |
| **bool** [get_GammaCorrection](./get_gammacorrection/)() const | คืนค่าที่บ่งชี้ว่าการแก้ไขแกมมาถูกเปิดใช้งานสำหรับแปรงนี้. |
| [SharedPtr](../../system/sharedptr/)\<[ColorBlend](../colorblend/)\> [get_InterpolationColors](./get_interpolationcolors/)() const | คืนออบเจ็กต์ [ColorBlend](../colorblend/) ที่กำหนดไลเนียร์กรเดียนท์หลายสี. |
| [ArrayPtr](../../system/arrayptr/)\<[Color](../../system.drawing/color/)\> [get_LinearColors](./get_linearcolors/)() const | คืนค่าสีเริ่มต้นและสีสุดท้ายของไลเนียร์กรเดียนท์นี้. |
| [RectangleF](../../system.drawing/rectanglef/) [get_Rectangle](./get_rectangle/)() | คืนสี่เหลี่ยมขอบเขต. |
| [SharedPtr](../../system/sharedptr/)\<[Matrix](../matrix/)\> [get_Transform](./get_transform/)() const | คืนสำเนาของออบเจ็กต์ [Matrix](../matrix/) ที่ระบุการแปลงเชิงเรขาคณิตสำหรับแปรงที่แสดงโดยออบเจ็กต์ปัจจุบัน. |
| [WrapMode](../wrapmode/) [get_WrapMode](./get_wrapmode/)() const | คืนโหมดการห่อ. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับข้อมูลโครงสร้างตัวนับอ้างอิงที่เชื่อมโยงกับออบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอนาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถสร้างแฮชของออบเจ็กต์แบบกำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทที่แท้จริงของออบเจ็กต์ เป็นอนาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าออบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เป็นอนาล็อกของตัวดำเนินการ 'is' ของ C#. |
|  [LinearGradientBrush](./lineargradientbrush/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [Color](../../system.drawing/color/)\&, const [Color](../../system.drawing/color/)\&) | สร้างอินสแตนซ์ใหม่ของ [LinearGradientBrush](./). |
|  [LinearGradientBrush](./lineargradientbrush/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Color](../../system.drawing/color/)\&, const [Color](../../system.drawing/color/)\&) | สร้างอินสแตนซ์ใหม่ของ [LinearGradientBrush](./). |
|  [LinearGradientBrush](./lineargradientbrush/)(const [RectangleF](../../system.drawing/rectanglef/)\&, const [Color](../../system.drawing/color/)\&, const [Color](../../system.drawing/color/)\&, [LinearGradientMode](../lineargradientmode/)) | สร้างอินสแตนซ์ใหม่ของ [LinearGradientBrush](./). |
|  [LinearGradientBrush](./lineargradientbrush/)(const [Rectangle](../../system.drawing/rectangle/)\&, const [Color](../../system.drawing/color/)\&, const [Color](../../system.drawing/color/)\&, [LinearGradientMode](../lineargradientmode/)) | สร้างอินสแตนซ์ใหม่ของ [LinearGradientBrush](./). |
|  [LinearGradientBrush](./lineargradientbrush/)(const [RectangleF](../../system.drawing/rectanglef/)\&, const [Color](../../system.drawing/color/)\&, const [Color](../../system.drawing/color/)\&, **float**, **bool**) | สร้างอินสแตนซ์ใหม่ของ [LinearGradientBrush](./). |
|  [LinearGradientBrush](./lineargradientbrush/)(const [Rectangle](../../system.drawing/rectangle/)\&, const [Color](../../system.drawing/color/)\&, const [Color](../../system.drawing/color/)\&, **float**, **bool**) | สร้างอินสแตนซ์ใหม่ของ [LinearGradientBrush](./). |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรืใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอนาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทกำหนดเองได้. |
| void [MultiplyTransform](./multiplytransform/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](../matrix/)\>\&, [MatrixOrder](../matrixorder/)) | คูณเมทริกซ์การแปลงของออบเจ็กต์ปัจจุบันด้วยเมทริกซ์ที่ระบุ. |
|  [Object](../../system/object/object/)() | สร้างออบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา ไม่ได้คัดลอกอะไรจริงๆ เพียงเริ่มต้นออบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์กำหนดค่า ไม่ได้คัดลอกอะไรจริงๆ เพียงเริ่มต้นออบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงออบเจ็กต์ประเภทค่ากับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายตัว. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงร่วมโดยค่าที่ระบุ. |
| void [ResetTransform](./resettransform/)() | รีเซ็ตเมทริกซ์การแปลงของออบเจ็กต์ปัจจุบัน. |
| void [RotateTransform](./rotatetransform/)(**float**, [MatrixOrder](../matrixorder/)) | หมุนเมทริกซ์การแปลงของออบเจ็กต์ปัจจุบัน. |
| void [ScaleTransform](./scaletransform/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | ปรับขนาดเมทริกซ์การแปลงของออบเจ็กต์ปัจจุบัน. |
| void [set_Blend](./set_blend/)(const [SharedPtr](../../system/sharedptr/)\<[Blend](../blend/)\>\&) | ตั้งค่า blend ที่ระบุตัวคูณและตำแหน่งของสีฐานสำหรับแปรงนี้. |
| void [set_GammaCorrection](./set_gammacorrection/)(**bool**) | ตั้งค่าสถานะการแก้ไขแกมมาสำหรับแปรงนี้. |
| void [set_InterpolationColors](./set_interpolationcolors/)(const [SharedPtr](../../system/sharedptr/)\<[ColorBlend](../colorblend/)\>\&) | ตั้งค่าออบเจ็กต์ [ColorBlend](../colorblend/) ที่กำหนดไลเนียร์กรเดียนท์หลายสี. |
| void [set_LinearColors](./set_linearcolors/)(const [ArrayPtr](../../system/arrayptr/)\<[Color](../../system.drawing/color/)\>\&) | ตั้งค่าสีเริ่มต้นและสีสุดท้ายของไลเนียร์กรเดียนท์นี้. |
| void [set_Transform](./set_transform/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](../matrix/)\>\&) | ตั้งค่าออบเจ็กต์ [Matrix](../matrix/) ที่ระบุการแปลงเชิงเรขาคณิตสำหรับแปรงที่แสดงโดยออบเจ็กต์ปัจจุบัน. |
| void [set_WrapMode](./set_wrapmode/)([WrapMode](../wrapmode/)) | ตั้งค่าโหมดการห่อ. |
| void [SetBlendTriangularShape](./setblendtriangularshape/)(**float**, **float**) | ยังไม่ได้ทำงาน. |
| void [SetSigmaBellShape](./setsigmabellshape/)(**float**, **float**) | ยังไม่ได้ทำงาน. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่ shared) อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงร่วม ควรไม่เรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงร่วม ควรไม่เรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอนาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงออบเจ็กต์กำหนดเองเป็นสตริงได้. |
| void [TranslateTransform](./translatetransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../matrixorder/)) | แปลเมทริกซ์การแปลงของออบเจ็กต์ปัจจุบัน. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิง weak ควรไม่เรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิง weak ควรไม่เรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายออบเจ็กต์ ปล่อยทุกโครงสร้างข้อมูลภายใน. |
## ดูเพิ่มเติม

* คลาส [Brush](../../system.drawing/brush/)
* เนมสเปซ [System::Drawing::Drawing2D](../)
* ไลบรารี [Aspose.Slides](../../)