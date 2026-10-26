---
title: AdjustableArrowCap
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "แสดงถึงหัวเส้นรูปลูกศรที่ปรับได้. วัตถุของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือใช้ตัวดำเนินการ new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือข้อผิดพลาดการยืนยัน. ควรห่อหุ้มคลาสนี้ด้วยตัวชี้ System::SmartPtr และใช้ตัวชี้นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 1
url: /th/system.drawing.drawing2d/adjustablearrowcap/
---
## AdjustableArrowCap คลาส

แสดงถึงหัวเส้นรูปลูกศรที่ปรับได้. วัตถุของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดเวลารันและ/หรือข้อผิดพลาดการยืนยัน. ควรห่อหุ้มคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน.

```cpp
class AdjustableArrowCap : public System::Drawing::Drawing2D::CustomLineCap
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
|  [AdjustableArrowCap](./adjustablearrowcap/)(**float**, **float**, **bool**) | สร้างอินสแตนซ์ใหม่ของ [AdjustableArrowCap](./) ด้วยความกว้างและความสูงที่ระบุ. |
| virtual [SharedPtr](../../system/sharedptr/)\<[CustomLineCap](../customlinecap/)\> [Clone](../customlinecap/clone/)() | ส่งกลับสำเนาของอ็อบเจ็กต์ปัจจุบัน. |
|  [CustomLineCap](../customlinecap/customlinecap/)(const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](../graphicspath/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](../graphicspath/)\>\&, [LineCap](../linecap/), **float**) | สร้างอินสแตนซ์ใหม่ของคลาส [CustomLineCap](../customlinecap/) ที่แสดงถึงหัวเส้นที่กำหนดโดยผู้ใช้ด้วยคุณสมบัติที่ระบุ. |
| void [Dispose](../customlinecap/dispose/)() | ปล่อยทรัพยากรของระบบปฏิบัติการทั้งหมดที่อ็อบเจ็กต์ปัจจุบันได้รับ. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงแบบสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าแบบสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่ NaN สองค่าได้รับการพิจารณาเท่ากันแม้ว่า ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าที่ใด รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่ NaN สองค่าถูกถือว่าเท่ากัน แม้ว่า ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| [LineCap](../linecap/) [get_BaseCap](../customlinecap/get_basecap/)() const | ส่งกลับหัวเส้นฐานที่สร้างจากหัวแบบกำหนดเองนี้. |
| **float** [get_BaseInset](../customlinecap/get_baseinset/)() const | ส่งกลับระยะห่างระหว่างเส้นและหัว. |
| **bool** [get_Filled](./get_filled/)() const | ส่งกลับค่าที่บ่งบอกว่าลูกศรที่อ็อบเจ็กต์ปัจจุบันแทนมีการเติมสีหรือไม่. |
| **float** [get_Height](./get_height/)() const | ส่งกลับความสูงของลูกศรที่อ็อบเจ็กต์ปัจจุบันแทน. |
| **float** [get_MiddleInset](./get_middleinset/)() const | ตั้งค่าระยะห่างระหว่างเส้นและหัวที่อ็อบเจ็กต์ปัจจุบันแทน. |
| [LineJoin](../linejoin/) [get_StrokeJoin](../customlinecap/get_strokejoin/)() const | ส่งกลับค่า LineJoin ที่กำหนดว่าตัวเส้นของหัวแบบกำหนดเองนี้ถูกเชื่อมต่ออย่างไร. |
| **float** [get_Width](./get_width/)() const | ส่งกลับความกว้างของลูกศรที่อ็อบเจ็กต์ปัจจุบันแทน. |
| **float** [get_WidthScale](../customlinecap/get_widthscale/)() const | ส่งกลับสเกลของหัวแบบกำหนดเองนี้. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชอ็อบเจ็กต์แบบกำหนดเอง. |
| void [GetStrokeCaps](../customlinecap/getstrokecaps/)([LineCap](../linecap/)\&, [LineCap](../linecap/)\&) | รับหัวเส้นเริ่มต้นและสิ้นสุดของหัวแบบกำหนดเองที่อ็อบเจ็กต์ปัจจุบันแทน. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. คล้ายกับตัวดำเนินการ C# 'is'. |
| void [Lock](../../system/object/lock/)() | ทำงานตามการล็อกของคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทแบบกำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมาย. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงของอ็อบเจ็กต์ประเภทค่ากับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายตัว. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงที่ใช้ร่วมกันโดยค่าที่ระบุ. |
| void [set_BaseCap](../customlinecap/set_basecap/)([LineCap](../linecap/)) | ตั้งค่าหัวเส้นฐานสำหรับหัวแบบกำหนดเองนี้. |
| void [set_BaseInset](../customlinecap/set_baseinset/)(**float**) | ตั้งค่าระยะห่างระหว่างเส้นและหัว. |
| void [set_Filled](./set_filled/)(**bool**) | ตั้งค่าที่ระบุว่าลูกศรที่อ็อบเจ็กต์ปัจจุบันแทนมีการเติมสีหรือไม่. |
| void [set_Height](./set_height/)(**float**) | ตั้งค่าความสูงของลูกศรที่อ็อบเจ็กต์ปัจจุบันแทน. |
| void [set_MiddleInset](./set_middleinset/)(**float**) | ตั้งค่าระยะห่างระหว่างเส้นและหัวที่อ็อบเจ็กต์ปัจจุบันแทน. |
| void [set_StrokeJoin](../customlinecap/set_strokejoin/)([LineJoin](../linejoin/)) | ตั้งค่า LineJoin ที่กำหนดว่าตัวเส้นของหัวแบบกำหนดเองนี้ถูกเชื่อมต่ออย่างไร. |
| void [set_Width](./set_width/)(**float**) | ตั้งค่าความกว้างของลูกศรที่อ็อบเจ็กต์ปัจจุบันแทน. |
| void [set_WidthScale](../customlinecap/set_widthscale/)(**float**) | ตั้งค่าค่าสเกลของหัวแบบกำหนดเองนี้. |
| void [SetStrokeCaps](../customlinecap/setstrokecaps/)([LineCap](../linecap/), [LineCap](../linecap/)) | ตั้งค่าหัวเส้นเริ่มต้นและสิ้นสุดของหัวแบบกำหนดเองที่อ็อบเจ็กต์ปัจจุบันแทน. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทนที่จะเป็น shared). อนุญาตให้เปลี่ยนพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่ใช้ร่วมกัน. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่ใช้ร่วมกัน. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงที่ใช้ร่วมกันและส่งกลับค่า. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์แบบกำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามการปลดล็อกของคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [CustomLineCap](../customlinecap/)
* เนมสเปซ [System::Drawing::Drawing2D](../)
* ไลบรารี [Aspose.Slides](../../)