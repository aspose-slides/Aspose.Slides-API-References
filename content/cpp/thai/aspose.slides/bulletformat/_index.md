---
title: BulletFormat
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงคุณสมบัติการจัดรูปแบบ bullet ของย่อหน้า.
type: docs
weight: 248
url: /th/aspose.slides/bulletformat/
---
## BulletFormat คลาส

Represents paragraph bullet formatting properties.

```cpp
class BulletFormat : public Aspose::Slides::PVIObject,
                     public Aspose::Slides::IBulletFormat
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| void [ApplyDefaultParagraphIndentsShifts](./applydefaultparagraphindentsshifts/)() override | กำหนดการเปลี่ยนแปลงค่าเริ่มต้นที่ไม่เป็นศูนย์สำหรับ Indent และ MarginLeft ที่มีผลของย่อหน้าเมื่อเปิดใช้งาน bullets (เช่นเดียวกับที่ PowerPoint ทำเมื่อเปิดใช้งานหัวข้อย่อย/การจัดลำดับในย่อหน้า). หาก bullets ถูกปิดใช้งานจะรีเซ็ต Indent และ MarginLeft ของย่อหน้า (เช่นเดียวกับที่ PowerPoint ทำเมื่อปิดใช้งานหัวข้อย่อย/การจัดลำดับในย่อหน้า). การเปลี่ยนแปลง Indent จะถูกนำไปใช้โดยอ้างอิงบริบทของ bullet ปัจจุบัน - IBulletFormat::get(set)_Type, .NumberedBulletStyle และ FontHeight ของส่วนแรก. การเปลี่ยนแปลง Indent ที่ไม่เป็นศูนย์จะถูกนำไปใช้กับ Indent และ MarginLeft ที่มีผลของย่อหน้า ณ ปัจจุบัน (ทำให้ค่าผลลัพธ์เป็นค่าท้องถิ่น). |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | เปรียบเทียบกับอ็อบเจ็กต์ที่ระบุ. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่า floating point แบบ C# ซึ่ง NaN สองค่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่า floating point แบบ C# ซึ่ง NaN สองค่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| char16_t [get_Char](./get_char/)() override | คืนค่าตัวอักขระ bullet ของย่อหน้าโดยไม่มีการสืบทอด. อ่าน **wchar_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_Color](./get_color/)() override | คืนค่ารูปแบบสีของ bullet ของย่อหน้าโดยไม่มีการสืบทอด. อ่านอย่างเดียว [IColorFormat](../icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_Font](./get_font/)() override | คืนค่าแบบอักษรของ bullet ของย่อหน้าโดยไม่มีการสืบทอด. อ่าน [IFontData](../ifontdata/). |
| **float** [get_Height](./get_height/)() override | คืนความสูงของ bullet ของย่อหน้าโดยไม่มีการสืบทอด. ค่าที่ std::numeric_limits<float>::quiet_NaN() ระบุว่า bullet สืบทอดความสูงจากส่วนแรกในย่อหน้า. อ่าน **float**. |
| [NullableBool](../nullablebool/) [get_IsBulletHardColor](./get_isbullethardcolor/)() override | กำหนดว่า bullet มีสีของตัวเองหรือสืบทอดจากส่วนแรกในย่อหน้า. **[NullableBool::True](../nullablebool/)** หาก bullet มีสีของตัวเองและ **[NullableBool::False](../nullablebool/)** หาก bullet สืบทอดสีจากส่วนแรกในย่อหน้า. อ่าน [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsBulletHardFont](./get_isbullethardfont/)() override | กำหนดว่า bullet มีแบบอักษรของตัวเองหรือสืบทอดจากส่วนแรกในย่อหน้า. **[NullableBool::True](../nullablebool/)** หาก bullet มีแบบอักษรของตัวเองและ **[NullableBool::False](../nullablebool/)** หาก bullet สืบทอดแบบอักษรจากส่วนแรกในย่อหน้า. อ่าน [NullableBool](../nullablebool/). |
| **int16_t** [get_NumberedBulletStartWith](./get_numberedbulletstartwith/)() override | คืนหมายเลขแรกที่ใช้สำหรับกลุ่ม bullet ที่มีหมายเลขโดยไม่มีการสืบทอด. อ่าน **int16_t**. |
| [Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/) [get_NumberedBulletStyle](./get_numberedbulletstyle/)() override | คืนสไตล์ของ bullet ที่มีหมายเลขโดยไม่มีการสืบทอด. อ่าน [Slides::NumberedBulletStyle](../numberedbulletstyle/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | คืนอ็อบเจ็กต์ Parent_Immediate. อ่านอย่างเดียว [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | คืน parent [IPresentationComponent](../ipresentationcomponent/). อ่านอย่างเดียว [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | คืนรูปภาพที่ใช้เป็น bullet ในย่อหน้าโดยไม่มีการสืบทอด. อ่านอย่างเดียว [ISlidesPicture](../islidespicture/). |
| [BulletType](../bullettype/) [get_Type](./get_type/)() override | คืนประเภทของ bullet ของย่อหน้าโดยไม่มีการสืบทอด. อ่าน [BulletType](../bullettype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [GetEffective](./geteffective/)() override | รับข้อมูลการจัดรูปแบบ bullet ที่มีผลโดยมีการสืบทอดที่ใช้. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | คืนค่า hash code. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับชนิดจริงของอ็อบเจ็กต์. เป็นเทียบเคียงกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. เป็นเทียบเคียงกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เป็นการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นเทียบเคียงกับเมธอด [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ของ C#. เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. ไม่ได้คัดลอกอะไรเลย จริงๆ แล้วเพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. ไม่ได้คัดลอกอะไรเลย จริงๆ แล้วเพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณี string และ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| void [set_Char](./set_char/)(char16_t) override | ตั้งค่าตัวอักขระ bullet ของย่อหน้าโดยไม่มีการสืบทอด. เขียน **wchar_t**. |
| void [set_Font](./set_font/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | ตั้งค่าแบบอักษร bullet ของย่อหน้าโดยไม่มีการสืบทอด. เขียน [IFontData](../ifontdata/). |
| void [set_Height](./set_height/)(**float**) override | ตั้งค่าความสูงของ bullet ของย่อหน้าโดยไม่มีการสืบทอด. ค่า std::numeric_limits<float>::quiet_NaN() ระบุว่า bullet สืบทอดความสูงจากส่วนแรกในย่อหน้า. เขียน **float**. |
| void [set_IsBulletHardColor](./set_isbullethardcolor/)([NullableBool](../nullablebool/)) override | กำหนดว่า bullet มีสีของตัวเองหรือสืบทอดจากส่วนแรกในย่อหน้า. **[NullableBool::True](../nullablebool/)** หาก bullet มีสีของตัวเองและ **[NullableBool::False](../nullablebool/)** หาก bullet สืบทอดสีจากส่วนแรกในย่อหน้า. เขียน [NullableBool](../nullablebool/). |
| void [set_IsBulletHardFont](./set_isbullethardfont/)([NullableBool](../nullablebool/)) override | กำหนดว่า bullet มีแบบอักษรของตัวเองหรือสืบทอดจากส่วนแรกในย่อหน้า. **[NullableBool::True](../nullablebool/)** หาก bullet มีแบบอักษรของตัวเองและ **[NullableBool::False](../nullablebool/)** หาก bullet สืบทอดแบบอักษรจากส่วนแรกในย่อหน้า. เขียน [NullableBool](../nullablebool/). |
| void [set_NumberedBulletStartWith](./set_numberedbulletstartwith/)(**int16_t**) override | ตั้งค่าหมายเลขแรกที่ใช้สำหรับกลุ่ม bullet ที่มีหมายเลขโดยไม่มีการสืบทอด. เขียน **int16_t**. |
| void [set_NumberedBulletStyle](./set_numberedbulletstyle/)([Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/)) override | ตั้งค่าสไตล์ของ bullet ที่มีหมายเลขโดยไม่มีการสืบทอด. เขียน [Slides::NumberedBulletStyle](../numberedbulletstyle/). |
| void [set_Type](./set_type/)([BulletType](../bullettype/)) override | ตั้งค่าประเภทของ bullet ของย่อหน้าโดยไม่มีการสืบทอด. เขียน [BulletType](../bullettype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; แทนที่จะใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; แทนที่จะใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นเทียบเคียงกับเมธอด [Object.ToString()](../../system/object/tostring/) ของ C#. เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็นการสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่เป็นการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนที่จะใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนที่จะใช้ smart pointers หรือ ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [PVIObject](../pviobject/)
* คลาส [IBulletFormat](../ibulletformat/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)