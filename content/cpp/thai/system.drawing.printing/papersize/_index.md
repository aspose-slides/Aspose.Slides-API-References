---
title: PaperSize
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ระบุขนาดของกระดาษแผ่นหนึ่ง.
type: docs
weight: 27
url: /th/system.drawing.printing/papersize/
---
## PaperSize คลาส

ระบุขนาดของกระดาษแผ่นหนึ่ง.

```cpp
class PaperSize : public System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่า floating point แบบ C# ที่สองค่า NaN ถือว่าเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 ค่า NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่า floating point แบบ C# ที่สองค่า NaN ถือว่าเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 ค่า NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| **int32_t** [get_Height](./get_height/)() const | ได้ความสูงของกระดาษ หน่วยเป็นร้อยส่วนของนิ้ว |
| [PaperKind](../paperkind/) [get_Kind](./get_kind/)() const | ได้ประเภทของกระดาษ |
| [System::String](../../system/string/) [get_PaperName](./get_papername/)() const | ได้ชื่อของประเภทกระดาษ |
| **int32_t** [get_RawKind](./get_rawkind/)() const | ได้จำนวนเต็มที่แทนค่าหนึ่งในค่า [System::Drawing::Printing::PaperSize](./) หรือค่าที่กำหนดเอง |
| **int32_t** [get_Width](./get_width/)() const | ได้ความกว้างของกระดาษ หน่วยเป็นร้อยส่วนของนิ้ว |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ได้โครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | ฟังก์ชันที่คล้ายกับ C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชอ็อบเจ็กต์ที่กำหนดเองได้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ได้ประเภทจริงของอ็อบเจ็กต์ ฟังก์ชันที่คล้ายกับ C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType ฟังก์ชันที่คล้ายกับตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | ฟังก์ชันที่คล้ายกับ C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถคล cloning ประเภทที่กำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | ตัวสร้างสำเนา ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาของคลาสตย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาของคลาสตย่อย |
|  [PaperSize](./papersize/)() | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [System::Drawing::Printing::PaperSize](./) |
|  [PaperSize](./papersize/)([PaperKind](../paperkind/), [System::String](../../system/string/), **int32_t**, **int32_t**) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [System::Drawing::Printing::PaperSize](./) |
|  [PaperSize](./papersize/)([System::String](../../system/string/), **int32_t**, **int32_t**) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [System::Drawing::Printing::PaperSize](./) |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่แชร์โดยค่าที่กำหนด |
| void [set_Height](./set_height/)(**int32_t**) | ตั้งความสูงของกระดาษ หน่วยเป็นร้อยส่วนของนิ้ว |
| void [set_PaperName](./set_papername/)([System::String](../../system/string/)) | ตั้งชื่อของประเภทกระดาษ |
| void [set_RawKind](./set_rawkind/)(**int32_t**) | ตั้งจำนวนเต็มที่แทนค่าหนึ่งในค่า [System::Drawing::Printing::PaperSize](./) หรือค่าที่กำหนดเอง |
| void [set_Width](./set_width/)(**int32_t**) | ตั้งความกว้างของกระดาษ หน่วยเป็นร้อยส่วนของนิ้ว |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทนที่จะเป็น shared) อนุญาตให้เปลี่ยน pointer ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | ได้ค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector |
| [System::String](../../system/string/) [ToString](./tostring/)() const override | ให้ข้อมูลเกี่ยวกับ [System::Drawing::Printing::PaperSize](./) ในรูปแบบสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Printing](../)
* Library [Aspose.Slides](../../)