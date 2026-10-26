---
title: ConsoleOutput
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: "แสดงถึงสตรีมเอาต์พุตมาตรฐาน. อ็อบเจ็กต์ของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อหุ้มคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 209
url: /th/system/consoleoutput/
---
## ConsoleOutput คลาส

Represents the standard output stream. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ConsoleOutput : public System::IO::TextWriter
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual void [Close](../../system.io/textwriter/close/)() | ปิดสตรีมและปล่อยทรัพยากรที่ได้. |
| void [Dispose](../../system.io/textwriter/dispose/)() override | ปล่อยทรัพยากรทั้งหมดที่ใช้โดยอ็อบเจ็กต์ปัจจุบันและปิดสตรีมพื้นฐาน. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้แนวคิดของ C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่ NaN สองค่าถูกพิจารณาเท่ากันแม้ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าตัวใดๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่ NaN สองค่าถูกพิจารณาเท่ากันแม้ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าตัวใดๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับวัตถุภายในเท่านั้น. |
| virtual void [Flush](../../system.io/textwriter/flush/)() | ทำการเคลียร์เนื้อหาในบัฟเฟอร์ไปยังสตรีมพื้นฐาน. |
| [SharedPtr](../sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | ส่งกลับการเข้ารหัส ASCII เสมอ. |
| virtual [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\> [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() const | ส่งคืนอ็อบเจ็กต์ [IFormatProvider](../iformatprovider/) ที่ใช้งานอยู่ในขณะนี้. |
| [IFormatProviderPtr](../iformatproviderptr/) [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() | ส่งคืนอ็อบเจ็กต์ [IFormatProvider](../iformatprovider/) ที่ใช้งานอยู่ในขณะนี้. |
| virtual [System::String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() const | ส่งคืนสตริงตัวกำหนดจบบรรทัด. |
| [String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() | ส่งคืนสตริงตัวกำหนดจบบรรทัด. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | รับข้อมูลโครงสร้างตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | ฟังก์ชันที่คล้ายกับเมธอด C# [Object.GetHashCode()](../object/gethashcode/). เปิดใช้งานการแฮชอ็อบเจ็กต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. ฟังก์ชันที่คล้ายกับการเรียก C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. คล้ายกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | ฟังก์ชันที่คล้ายกับเมธอด C# [Object.MemberwiseClone()](../object/memberwiseclone/). เปิดใช้งานการคัดลอกประเภทที่กำหนดเอง. |
|  [Object](../object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../object/object/)([Object](../object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกก่อสร้างซับคลาส. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไร เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกก่อสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าด้วยการอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงแบบแชร์โดยค่าที่ระบุ. |
| virtual void [set_NewLine](../../system.io/textwriter/set_newline/)(const [System::String](../string/)\&) | ตั้งค่าสตริงตัวกำหนดจบบรรทัด. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | กำหนดอาร์กิวเมนต์เทมเพลตที่ n เป็นพอยน์เตอร์อ่อน (แทนที่แชร์). อนุญาตให้เปลี่ยนพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมดอ่อน. |
| int [SharedCount](../object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงแบบแชร์. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงแบบแชร์. ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงแบบแชร์. ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | ฟังก์ชันที่คล้ายกับเมธอด C# [Object.ToString()](../object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเป็นสตริง. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | ทำหน้าที่เหมือนคำสั่ง typeof([System.Object](../object/)) ของ C#. |
| void [Unlock](../object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงอ่อน. ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ลดตัวนับอ้างอิงอ่อน. ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| void [Write](./write/)(**bool**) override | แสดงผลสตริงของค่าบูลีนที่ระบุไปยังสตรีม output ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [Write](./write/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | แสดงผลสตริงของอ็อบเจ็กต์ที่ระบุไปยังสตรีม output ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [Write](./write/)(char_t) override | แสดงผลค่าตัวอักษรที่ระบุไปยังสตรีม output ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [Write](./write/)([Decimal](../decimal/)) override | แสดงผลสตริงของค่าที่ [Decimal](../decimal/) ไปยังสตรีม output ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [Write](./write/)(**double**) override | แสดงผลสตริงของค่าจุดลอยแบบ double-precision ไปยังสตรีม output ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [Write](./write/)(**int32_t**) override | แสดงผลสตริงของค่าจำนวนเต็ม 32 บิตไปยังสตรีม output ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [Write](./write/)(**int64_t**) override | แสดงผลสตริงของค่าจำนวนเต็ม 64 บิตไปยังสตรีม output ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [Write](./write/)(**float**) override | แสดงผลสตริงของค่าจุดลอยแบบ single-precision ไปยังสตรีม output ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [Write](./write/)(const [String](../string/)\&) override | แสดงผลอ็อบเจ็กต์สตริงที่ระบุไปยังสตรีม output ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [Write](./write/)(**uint32_t**) override | แสดงผลสตริงของค่าจำนวนเต็มไม่เป็นลบ 32 บิตไปยังสตรีม output ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [Write](./write/)(**uint64_t**) override | แสดงผลสตริงของค่าจำนวนเต็มไม่เป็นลบ 64 บิตไปยังสตรีม output ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | แสดงผลสตริงของอาร์เรย์อักขระที่ระบุไปยังสตรีม output ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | แสดงผลสตริงของช่วงค่าของอาร์เรย์อักขระที่ระบุไปยังสตรีม output ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [Write](./write/)(const char_t *) override | แสดงผล c-string ที่ระบุไปยังสตรีม output ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) override | แสดงผลสตริงของอ็อบเจ็กต์ [TypeInfo](../typeinfo/) ที่ระบุไปยังสตรีม output ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [Write](./write/)(const char *) |  |
| virtual void [Write](../../system.io/textwriter/write/)(int) | เขียนสตริงของค่าจำนวนเต็ม 32 บิตที่ระบุลงสตรีม. |
| void [Write](../../system.io/textwriter/write/)(const [String](../string/)\&, const TArgs\&...) | เขียนค่าที่ระบุโดยจัดรูปตามฟอร์แมตที่กำหนดลงสตรีม. |
| void [WriteLine](./writeline/)() override | แสดงผลตัวกำหนดจบบรรทัดปัจจุบันไปยังสตรีม output ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | แสดงผลสตริงของอ็อบเจ็กต์ที่ระบุและตามด้วยตัวกำหนดจบบรรทัดปัจจุบันไปยังสตรีม output ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [WriteLine](./writeline/)(**bool**) override | แสดงผลสตริงของค่าบูลีนที่ระบุและตามด้วยตัวกำหนดจบบรรทัดปัจจุบันไปยังสตรีม output ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [WriteLine](./writeline/)(char_t) override | แสดงผลค่าตัวอักษรที่ระบุและตามด้วยตัวกำหนดจบบรรทัดปัจจุบันไปยังสตรีม output ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [WriteLine](./writeline/)([Decimal](../decimal/)) override | แสดงผลสตริงของค่าที่ [Decimal](../decimal/) และตามด้วยตัวกำหนดจบบรรทัดปัจจุบันไปยังสตรีม output ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [WriteLine](./writeline/)(**double**) override | แสดงผลสตริงของค่าจุดลอยแบบ double-precision และตามด้วยตัวกำหนดจบบรรทัดปัจจุบันไปยังสตรีม output ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [WriteLine](./writeline/)(int) override | แสดงผลสตริงของค่าจำนวนเต็ม 32 บิตและตามด้วยตัวกำหนดจบบรรทัดปัจจุบันไปยังสตรีม output ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [WriteLine](./writeline/)(**int64_t**) override | แสดงผลสตริงของค่าจำนวนเต็ม 64 บิตและตามด้วยตัวกำหนดจบบรรทัดปัจจุบันไปยังสตรีม output ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [WriteLine](./writeline/)(**float**) override | แสดงผลสตริงของค่าจุดลอยแบบ single-precision และตามด้วยตัวกำหนดจบบรรทัดปัจจุบันไปยังสตรีม output ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [WriteLine](./writeline/)(const [String](../string/)\&) override | แสดงผลอ็อบเจ็กต์สตริงที่ระบุและตามด้วยตัวกำหนดจบบรรทัดปัจจุบันไปยังสตรีม output ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [WriteLine](./writeline/)(**uint32_t**) override | แสดงผลสตริงของค่าจำนวนเต็มไม่เป็นลบ 32 บิตและตามด้วยตัวกำหนดจบบรรทัดปัจจุบันไปยังสตรีม output ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [WriteLine](./writeline/)(**uint64_t**) override | แสดงผลสตริงของค่าจำนวนเต็มไม่เป็นลบ 64 บิตและตามด้วยตัวกำหนดจบบรรทัดปัจจุบันไปยังสตรีม output ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | แสดงผลสตริงของอาร์เรย์อักขระที่ระบุและตามด้วยตัวกำหนดจบบรรทัดปัจจุบันไปยังสตรีม output ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | แสดงผลสตริงของช่วงค่าของอาร์เรย์อักขระที่ระบุและตามด้วยตัวกำหนดจบบรรทัดปัจจุบันไปยังสตรีม output ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [WriteLine](./writeline/)(const char_t *) override | แสดงผล c-string ที่ระบุและตามด้วยตัวกำหนดจบบรรทัดปัจจุบันไปยังสตรีม output ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) override | แสดงผลสตริงของอ็อบเจ็กต์ [TypeInfo](../typeinfo/) ที่ระบุและตามด้วยตัวกำหนดจบบรรทัดปัจจุบันไปยังสตรีม output ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [WriteLine](./writeline/)(const char *) |  |
| void [WriteLine](../../system.io/textwriter/writeline/)(const [String](../string/)\&, const TArgs\&...) | เขียนค่าที่ระบุโดยจัดรูปตามฟอร์แมตที่กำหนดและตามด้วยอักขระสิ้นบรรทัดไปยังสตรีม. |
| virtual  [~Object](../object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
| virtual  [~TextWriter](../../system.io/textwriter/~textwriter/)() | ตัวทำลาย. |

## ดูเพิ่มเติม

* คลาส [TextWriter](../../system.io/textwriter/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)