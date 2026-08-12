---
title: IBulletFormat
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แสดงคุณสมบัติการจัดรูปแบบสัญลักษณ์หัวข้อในย่อหน้า.
type: docs
weight: 1561
url: /th/aspose.slides/ibulletformat/
---
## IBulletFormat คลาส


แสดงคุณสมบัติการจัดรูปแบบสัญลักษณ์หัวข้อในย่อหน้า.

```cpp
class IBulletFormat : public virtual System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual void [ApplyDefaultParagraphIndentsShifts](./applydefaultparagraphindentsshifts/)() | ตั้งค่าการขยับที่ไม่เป็นศูนย์เริ่มต้นสำหรับ Indent และ MarginLeft ของย่อหน้าที่มีผลเมื่อเปิดใช้สัญลักษณ์หัวข้อ (เช่นเดียวกับที่ PowerPoint ทำเมื่อเปิดใช้สัญลักษณ์หัวข้อ/การนับเลขในย่อหน้า) หากสัญลักษณ์หัวข้อถูกปิดใช้งานก็จะรีเซ็ต Indent และ MarginLeft ของย่อหน้า (เช่นเดียวกับที่ PowerPoint ทำเมื่อปิดใช้งานสัญลักษณ์หัวข้อ/การนับเลข) การขยับ Indent จะถูกประยุกต์ตามบริบทสัญลักษณ์หัวข้อปัจจุบัน - IBulletFormat::get(set)_Type, .NumberedBulletStyle และ FontHeight ของส่วนแรก การขยับที่ไม่เป็นศูนย์จะถูกประยุกต์กับ Indent และ MarginLeft ที่มีผลของย่อหน้าในปัจจุบัน (ทำให้ค่าที่ได้เป็นค่าท้องถิ่น) |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในรูปแบบ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในรูปแบบ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่า float แบบ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่า double แบบ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| virtual char16_t [get_Char](./get_char/)() | คืนค่าตัวอักษรสัญลักษณ์หัวข้อของย่อหน้าโดยไม่มีการสืบทอด อ่านเป็น **wchar_t** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_Color](./get_color/)() | คืนค่าแบบฟอร์แมตสีของสัญลักษณ์หัวข้อของย่อหน้าโดยไม่มีการสืบทอด อ่านอย่างเดียว [IColorFormat](../icolorformat/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_Font](./get_font/)() | คืนค่าแบบอักษรของสัญลักษณ์หัวข้อของย่อหน้าโดยไม่มีการสืบทอด อ่าน [IFontData](../ifontdata/) |
| virtual **float** [get_Height](./get_height/)() | คืนค่าสูงของสัญลักษณ์หัวข้อของย่อหน้าโดยไม่มีการสืบทอด ค่า std::numeric_limits<float>::quiet_NaN() ระบุว่าสัญลักษณ์หัวข้อสืบทอดความสูงจากส่วนแรกของย่อหน้า อ่าน **float** |
| virtual [NullableBool](../nullablebool/) [get_IsBulletHardColor](./get_isbullethardcolor/)() | กำหนดว่าสัญลักษณ์หัวข้อมีสีของตนเองหรือสืบทอดจากส่วนแรกของย่อหน้า **[NullableBool::True](../nullablebool/)** หากสัญลักษณ์หัวข้อมีสีของตนเองและ **[NullableBool::False](../nullablebool/)** หากสัญลักษณ์หัวข้อสืบทอดสีจากส่วนแรกของย่อหน้า อ่าน [NullableBool](../nullablebool/) |
| virtual [NullableBool](../nullablebool/) [get_IsBulletHardFont](./get_isbullethardfont/)() | กำหนดว่าสัญลักษณ์หัวข้อมีแบบอักษรของตนเองหรือสืบทอดจากส่วนแรกของย่อหน้า **[NullableBool::True](../nullablebool/)** หากสัญลักษณ์หัวข้อมีแบบอักษรของตนเองและ **[NullableBool::False](../nullablebool/)** หากสัญลักษณ์หัวข้อสืบทอดแบบอักษรจากส่วนแรกของย่อหน้า อ่าน [NullableBool](../nullablebool/) |
| virtual **int16_t** [get_NumberedBulletStartWith](./get_numberedbulletstartwith/)() | คืนค่าตัวเลขแรกที่ใช้สำหรับกลุ่มสัญลักษณ์หัวข้อแบบลำดับโดยไม่มีการสืบทอด อ่าน **int16_t** |
| virtual [Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/) [get_NumberedBulletStyle](./get_numberedbulletstyle/)() | คืนค่าสไตล์ของสัญลักษณ์หัวข้อแบบลำดับโดยไม่มีการสืบทอด อ่าน [NumberedBulletStyle](../numberedbulletstyle/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() | คืนค่าภาพที่ใช้เป็นสัญลักษณ์หัวข้อในย่อหน้าโดยไม่มีการสืบทอด อ่านอย่างเดียว [ISlidesPicture](../islidespicture/) |
| virtual [BulletType](../bullettype/) [get_Type](./get_type/)() | คืนค่าประเภทสัญลักษณ์หัวข้อของย่อหน้าโดยไม่มีการสืบทอด อ่าน [BulletType](../bullettype/) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับออบเจ็กต์ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [GetEffective](./geteffective/)() | รับข้อมูลการจัดรูปแบบสัญลักษณ์หัวข้อที่มีผลพร้อมการสืบทอดที่นำมาใช้ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นฟังก์ชันเทียบเท่าของ C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชออบเจ็กต์ที่กำหนดเองได้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของออบเจ็กต์ เป็นฟังก์ชันเทียบเท่าของ C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าออบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType เป็นฟังก์ชันเทียบเท่าของตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุสังเกต [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นฟังก์ชันเทียบเท่าของ C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทที่กำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างออบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นออบเจ็กต์ใหม่และเปิดใช้การสร้างสำเนาสำหรับคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมาย ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นออบเจ็กต์ใหม่และเปิดใช้การสร้างสำเนาสำหรับคลาสย่อย |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบออบเจ็กต์ตามอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบออบเจ็กต์ตามอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงของออบเจ็กต์ประเภทค่า กับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| virtual void [set_Char](./set_char/)(char16_t) | ตั้งค่าตัวอักษรสัญลักษณ์หัวข้อของย่อหน้าโดยไม่มีการสืบทอด เขียนเป็น **wchar_t** |
| virtual void [set_Font](./set_font/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | ตั้งค่าแบบอักษรของสัญลักษณ์หัวข้อในย่อหน้าโดยไม่มีการสืบทอด เขียน [IFontData](../ifontdata/) |
| virtual void [set_Height](./set_height/)(**float**) | ตั้งค่าสูงของสัญลักษณ์หัวข้อในย่อหน้าโดยไม่มีการสืบทอด ค่า std::numeric_limits<float>::quiet_NaN() ระบุว่าสัญลักษณ์หัวข้อสืบทอดความสูงจากส่วนแรกของย่อหน้า เขียน **float** |
| virtual void [set_IsBulletHardColor](./set_isbullethardcolor/)([NullableBool](../nullablebool/)) | กำหนดว่าสัญลักษณ์หัวข้อมีสีของตนเองหรือสืบทอดจากส่วนแรกของย่อหน้า **[NullableBool::True](../nullablebool/)** หากสัญลักษณ์หัวข้อมีสีของตนเองและ **[NullableBool::False](../nullablebool/)** หากสัญลักษณ์หัวข้อสืบทอดสีจากส่วนแรกของย่อหน้า เขียน [NullableBool](../nullablebool/) |
| virtual void [set_IsBulletHardFont](./set_isbullethardfont/)([NullableBool](../nullablebool/)) | กำหนดว่าสัญลักษณ์หัวข้อมีแบบอักษรของตนเองหรือสืบทอดจากส่วนแรกของย่อหน้า **[NullableBool::True](../nullablebool/)** หากสัญลักษณ์หัวข้อความอักษรของตนเองและ **[NullableBool::False](../nullablebool/)** หากสัญลักษณ์หัวข้อสืบทอดแบบอักษรจากส่วนแรกของย่อหน้า เขียน [NullableBool](../nullablebool/) |
| virtual void [set_NumberedBulletStartWith](./set_numberedbulletstartwith/)(**int16_t**) | ตั้งค่าตัวเลขแรกที่ใช้สำหรับกลุ่มสัญลักษณ์หัวข้อแบบลำดับโดยไม่มีการสืบทอด เขียน **int16_t** |
| virtual void [set_NumberedBulletStyle](./set_numberedbulletstyle/)([Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/)) | ตั้งค่าสไตล์ของสัญลักษณ์หัวข้อแบบลำดับโดยไม่มีการสืบทอด เขียน [NumberedBulletStyle](../numberedbulletstyle/) |
| virtual void [set_Type](./set_type/)([BulletType](../bullettype/)) | ตั้งค่าประเภทสัญลักษณ์หัวข้อของย่อหน้าโดยไม่มีการสืบทอด เขียน [BulletType](../bullettype/) |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าพารามิเตอร์เทมเพลตที่ n ให้เป็น weak pointer (แทน shared) ทำให้สามารถสลับ pointer ในคอนเทนเนอร์เป็นโหมด weak ได้ |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; แทนที่ควรใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงที่แชร์และคืนค่าตัวนับ ไม่ควรเรียกโดยตรง; แทนที่ควรใช้ smart pointers หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นฟังก์ชันเทียบเท่าของ C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงออบเจ็กต์ที่กำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เหมือน construct typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุสังเกต [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; แทนที่ควรใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; แทนที่ควรใช้ smart pointers หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายออบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [Aspose::Slides](../)
* Library [Aspose.Slides](../../)