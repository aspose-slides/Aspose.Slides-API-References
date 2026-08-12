---
title: IHtmlGenerator
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ตัวสร้าง HTML.
type: docs
weight: 209
url: /th/aspose.slides.export/ihtmlgenerator/
---
## IHtmlGenerator คลาส

ตัวสร้าง HTML.

```cpp
class IHtmlGenerator : public virtual System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual void [AddAttributeValue](./addattributevalue/)([System::String](../../system/string/)) | อ้างอิงค่าแอตทริบิวต์และเพิ่มลงในไฟล์ html. |
| virtual void [AddAttributeValue](./addattributevalue/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>) | อ้างอิงค่าแอตทริบิวต์และเพิ่มลงในไฟล์ html. |
| virtual void [AddAttributeValue](./addattributevalue/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | อ้างอิงค่าแอตทริบิวต์และเพิ่มลงในไฟล์ html. |
| virtual void [AddHtml](./addhtml/)([System::String](../../system/string/)) | เพิ่มข้อความ HTML ที่จัดรูปแบบแล้ว. |
| virtual void [AddHtml](./addhtml/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>) | เพิ่มข้อความ HTML ที่จัดรูปแบบแล้ว. |
| virtual void [AddHtml](./addhtml/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | เพิ่มข้อความ HTML ที่จัดรูปแบบแล้ว. |
| virtual void [AddText](./addtext/)([System::String](../../system/string/)) | เพิ่มข้อความธรรมดาไปยังไฟล์ html โดยแทนที่อักขระพิเศษด้วยเอนทิตี HTML. การขึ้นบรรทัดใหม่และช่องว่างจะไม่ถูกแทนที่. |
| virtual void [AddText](./addtext/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>) | เพิ่มข้อความธรรมดาไปยังไฟล์ html โดยแทนที่อักขระพิเศษด้วยเอนทิตี HTML. การขึ้นบรรทัดใหม่และช่องว่างจะไม่ถูกแทนที่. |
| virtual void [AddText](./addtext/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | เพิ่มข้อความธรรมดาไปยังไฟล์ htmlโดยแทนที่อักขระพิเศษด้วยเอนทิตี HTML. การขึ้นบรรทัดใหม่และช่องว่างจะไม่ถูกแทนที่. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| virtual **int32_t** [get_NextSlideIndex](./get_nextslideindex/)() | คืนค่าดัชนีของสไลด์ที่จะเรนเดอร์หลังสไลด์ปัจจุบัน หรือ -1 หากกำลังเรนเดอร์สไลด์สุดท้าย. อ่านอย่างเดียว **int32_t**. |
| virtual **int32_t** [get_PreviousSlideIndex](./get_previousslideindex/)() | คืนค่าดัชนีของสไลด์ที่เรนเดรก่อนหน้า หรือ -1 หากกำลังเรนเดอร์สไลด์แรก. อ่านอย่างเดียว **int32_t**. |
| virtual [System::Drawing::SizeF](../../system.drawing/sizef/) [get_SlideImageSize](./get_slideimagesize/)() | คืนขนาดภาพสไลด์. อ่านอย่างเดียว [System::Drawing::SizeF](../../system.drawing/sizef/). |
| virtual [SvgCoordinateUnit](../svgcoordinateunit/) [get_SlideImageSizeUnit](./get_slideimagesizeunit/)() | คืนหน่วยที่ใช้ระบุขนาดภาพสไลด์. อ่านอย่างเดียว [SvgCoordinateUnit](../svgcoordinateunit/). |
| virtual [System::String](../../system/string/) [get_SlideImageSizeUnitCode](./get_slideimagesizeunitcode/)() | คืนรหัส CSS ของหน่วยที่ใช้ระบุขนาดภาพสไลด์. อ่านอย่างเดียว [System::String](../../system/string/). |
| virtual **int32_t** [get_SlideIndex](./get_slideindex/)() | คืนค่าดัชนีของสไลด์ที่กำลังเรนเดอร์อยู่. อ่านอย่างเดียว **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถสร้างแฮชของอ็อบเจกต์ที่กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. คล้ายกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้สามารถโคลนนิ่งประเภทที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงที่แชร์โดยค่าที่ระบุ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนอ้างอิงที่แชร์. ควรไม่เรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนอ้างอิงที่แชร์และคืนค่า. ควรไม่เรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/). ทำให้สามารถแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวน weak reference. ควรไม่เรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวน weak reference. ควรไม่เรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [Aspose::Slides::Export](../)
* ไลบรารี [Aspose.Slides](../../)