---
title: StringWriter
second_title: เอกสารอ้างอิง API ของ Aspose.Slides for C++
description: "ทำงานเป็น TextWriter ที่เขียนข้อมูลลงในสตริง. วัตถุของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน System::MakeObject() . ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อหุ้มคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 417
url: /th/system.io/stringwriter/
---
## StringWriter คลาส

ทำงานเป็น [TextWriter](../textwriter/) ที่เขียนข้อมูลลงในสตริง. วัตถุของคลาสนี้ควรจัดสรรเฉพาะด้วยฟังก์ชัน [System::MakeObject()](../../system/makeobject/). ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแต็กหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดระหว่างทำงานและ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อหุ้มคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน.

```cpp
class StringWriter : public System::IO::TextWriter
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual void [Close](../textwriter/close/)() | ปิดสตรีมและปล่อยทรัพยากรที่ได้เรียกใช้. |
| void [Dispose](../textwriter/dispose/)() override | ปล่อยทรัพยากรทั้งหมดที่วัตถุปัจจุบันใช้และปิดสตรีมพื้นฐาน. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่ NaN สองค่าถูกถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่ NaN สองค่าถูกถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับการทำงานภายในเท่านั้น. |
| virtual void [Flush](../textwriter/flush/)() | ทำการล้างเนื้อหาของบัฟเฟอร์ไปยังสตรีมพื้นฐาน. |
| [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | ส่งคืน encoding ที่กำลังใช้อยู่. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | ส่งคืนอ็อบเจ็กต์ [IFormatProvider](../../system/iformatprovider/) ที่กำลังใช้อยู่. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | ส่งคืนอ็อบเจ็กต์ [IFormatProvider](../../system/iformatprovider/) ที่กำลังใช้อยู่. |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | ส่งคืนสตริงตัวกำหนดจบบรรทัด. |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | ส่งคืนสตริงตัวกำหนดจบบรรทัด. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นเชิงเทียบของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ช่วยให้สามารถทำแฮชอ็อบเจ็กต์แบบกำหนดเอง. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\> [GetStringBuilder](./getstringbuilder/)() | ส่งคืน StringBuilder ที่กำลังใช้อยู่. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เป็นเชิงเทียบของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นเชิงเทียบของตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นเชิงเทียบของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ช่วยให้สามารถทำสำเนาประเภทแบบกำหนดเอง. |
| [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่คัดลอกข้อมูลใด ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกของซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ แล้วไม่คัดลอกข้อมูลใด ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกของซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจ็กต์ประเภทค่ากับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | ตั้งค่าสตริงตัวกำหนดจบบรรทัด. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าตัวเทมเพลตที่ n ให้เป็นพอยน์เตอร์แบบ weak (แทนที่ shared). อนุญาตให้เปลี่ยนพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | สร้างอินสแตนซ์ใหม่ของ [StringWriter](./) ด้วย StringBuilder ที่ระบุและ [IFormatProvider](../../system/iformatprovider/). |
| [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | สร้างอินสแตนซ์ใหม่ของ [StringWriter](./) ด้วย StringBuilder ที่ระบุและ [IFormatProvider](../../system/iformatprovider/) จากวัฒนธรรมปัจจุบัน. |
| [StringWriter](./stringwriter/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | สร้างอินสแตนซ์ใหม่ของ [StringWriter](./) ด้วย [IFormatProvider](../../system/iformatprovider/) ที่ระบุ. |
| [StringWriter](./stringwriter/)() | สร้างอินสแตนซ์ใหม่ของ [StringWriter](./) ด้วย [IFormatProvider](../../system/iformatprovider/) จากวัฒนธรรมปัจจุบัน. |
| [String](../../system/string/) [ToString](./tostring/)() const override | ส่งคืนสตริงพื้นฐาน. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | จำลองโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| void [Write](./write/)(char_t) override | เขียนอักษรที่ระบุลงในสตรีม. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | เขียนช่วงย่อยของอักษรที่ระบุจากอาเรย์อักษรที่ระบุไปยังสตรีม. |
| void [Write](./write/)(const [String](../../system/string/)\&) override | เขียนสตริงที่ระบุลงในสตรีม. |
| virtual void [Write](../textwriter/write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | เขียนการแสดงผลเป็นสตริงของอ็อบเจ็กต์ที่ระบุไปยังสตรีม. |
| virtual void [Write](../textwriter/write/)(**bool**) | เขียนการแสดงผลเป็นสตริงของค่า boolean ที่ระบุไปยังสตรีม. |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | เขียนการแสดงผลเป็นสตริงของอ็อบเจ็กต์ [Decimal](../../system/decimal/) ที่ระบุไปยังสตรีม. |
| virtual void [Write](../textwriter/write/)(**double**) | เขียนการแสดงผลเป็นสตริงของค่าจุดลอยแบบ double precision ที่ระบุไปยังสตรีม. |
| virtual void [Write](../textwriter/write/)(int) | เขียนการแสดงผลเป็นสตริงของค่าจำนวนเต็ม 32-bit ที่ระบุไปยังสตรีม. |
| virtual void [Write](../textwriter/write/)(**int64_t**) | เขียนการแสดงผลเป็นสตริงของค่าจำนวนเต็ม 64-bit ที่ระบุไปยังสตรีม. |
| virtual void [Write](../textwriter/write/)(**float**) | เขียนการแสดงผลเป็นสตริงของค่าจุดลอยแบบ single precision ที่ระบุไปยังสตรีม. |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | เขียนการแสดงผลเป็นสตริงของค่าจำนวนเต็มบวก 32-bit ที่ระบุไปยังสตรีม. |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | เขียนการแสดงผลเป็นสตริงของค่าจำนวนเต็มบวก 64-bit ที่ระบุไปยังสตรีม. |
| virtual void [Write](../textwriter/write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | เขียนอักขระทั้งหมดจากอาเรย์ที่ระบุไปยังสตรีม. |
| virtual void [Write](../textwriter/write/)(const char_t *) | เขียน c-string ที่ระบุไปยังสตรีม. |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | เขียนการแสดงผลเป็นสตริงของอ็อบเจ็กต์ [TypeInfo](../../system/typeinfo/) ที่ระบุไปยังสตรีม. |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | เขียนค่าที่ระบุโดยจัดรูปตามรูปแบบที่ระบุไปยังสตรีม. |
| virtual void [WriteLine](../textwriter/writeline/)() | เขียนอักขระตัวกำหนดจบบรรทัดไปยังสตรีม. |
| virtual void [WriteLine](../textwriter/writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | เขียนการแสดงผลเป็นสตริงของอ็อบเจ็กต์ที่ระบุ ตามด้วยอักขระจบบรรทัดไปยังสตรีม. |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | เขียนการแสดงผลเป็นสตริงของค่า boolean ที่ระบุ ตามด้วยอักขระจบบรรทัดไปยังสตรีม. |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | เขียนอักษรที่ระบุ ตามด้วยอักขระจบบรรทัดไปยังสตรีม. |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | เขียนการแสดงผลเป็นสตริงของอ็อบเจ็กต์ [Decimal](../../system/decimal/) ที่ระบุ ตามด้วยอักขระจบบรรทัดไปยังสตรีม. |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | เขียนการแสดงผลเป็นสตริงของค่าจุดลอยแบบ double precision ที่ระบุ ตามด้วยอักขระจบบรรทัดไปยังสตรีม. |
| virtual void [WriteLine](../textwriter/writeline/)(int) | เขียนการแสดงผลเป็นสตริงของค่าจำนวนเต็ม 32-bit ที่ระบุ ตามด้วยอักขระจบบรรทัดไปยังสตรีม. |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | เขียนการแสดงผลเป็นสตริงของค่าจำนวนเต็ม 64-bit ที่ระบุ ตามด้วยอักขระจบบรรทัดไปยังสตรีม. |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | เขียนการแสดงผลเป็นสตริงของค่าจุดลอยแบบ single precision ที่ระบุ ตามด้วยอักขระจบบรรทัดไปยังสตรีม. |
| virtual void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&) | เขียนสตริงที่ระบุ ตามด้วยอักขระจบบรรทัดไปยังสตรีม. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | เขียนการแสดงผลเป็นสตริงของค่าจำนวนเต็มบวก 32-bit ที่ระบุ ตามด้วยอักขระจบบรรทัดไปยังสตรีม. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | เขียนการแสดงผลเป็นสตริงของค่าจำนวนเต็มบวก 64-bit ที่ระบุ ตามด้วยอักขระจบบรรทัดไปยังสตรีม. |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | เขียนอักขระทั้งหมดจากอาเรย์ที่ระบุ ตามด้วยอักขระจบบรรทัดไปยังสตรีม. |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | เขียนช่วงย่อยของอักขระ UTF-16 ที่ระบุจากอาเรย์อักขระที่ระบุ ตามด้วยอักขระจบบรรทัดไปยังสตรีม. |
| virtual void [WriteLine](../textwriter/writeline/)(const char_t *) | เขียน c-string ที่ระบุ ตามด้วยอักขระจบบรรทัดไปยังสตรีม. |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | เขียนการแสดงผลเป็นสตริงของอ็อบเจ็กต์ [TypeInfo](../../system/typeinfo/) ที่ระบุ ตามด้วยอักขระจบบรรทัดไปยังสตรีม. |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | เขียนค่าที่ระบุโดยจัดรูปตามรูปแบบที่ระบุ ตามด้วยอักขระจบบรรทัดไปยังสตรีม. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | ตัวทำลาย. |

## ดูเพิ่มเติม

* คลาส [TextWriter](../textwriter/)
* เนมสเปซ [System::IO](../)
* ไลบรารี [Aspose.Slides](../../)