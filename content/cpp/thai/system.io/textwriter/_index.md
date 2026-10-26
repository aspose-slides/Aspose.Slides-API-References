---
title: TextWriter
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: "คลาสพื้นฐานสำหรับคลาสที่แทนผู้เขียนที่เขียนลำดับอักขระไปยังปลายทางต่าง ๆ. วัตถุของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้โอเปอเรเตอร์ new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการอ้างอิง. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 443
url: /th/system.io/textwriter/
---
## คลาส TextWriter

คลาสฐานสำหรับคลาสที่แทนผู้เขียนที่เขียนลำดับอักขระไปยังปลายทางต่าง ๆ. วัตถุของคลาสนี้ควรจะจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/). อย่าสร้างอินสแตนซ์ของชนิดนี้บนสแตกหรือโดยใช้โอเปอเรเตอร์ new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์หรือข้อผิดพลาดการอ้างอิง. ควรห่อหุ้มคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน.

```cpp
class TextWriter : public System::IDisposable
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual void [Close](./close/)() | ปิดสตรีมและปล่อยทรัพยากรที่ได้รับ |
| void [Dispose](./dispose/)() override | ปล่อยทรัพยากรทั้งหมดที่ใช้โดยอ็อบเจกต์ปัจจุบันและปิดสตรีมพื้นฐาน |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าที่เป็นแบบ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยของสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าทใด ๆ รวมถึง NaN |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยของสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าทใด ๆ รวมถึง NaN |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น |
| virtual void [Flush](./flush/)() | ทำการดึงเนื้อหาของบัฟเฟอร์ไปยังสตรีมพื้นฐาน |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | ส่งคืนการเข้ารหัสที่ใช้อยู่ในขณะนี้ |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](./get_formatprovider/)() const | ส่งคืนอ็อบเจกต์ [IFormatProvider](../../system/iformatprovider/) ที่ใช้อยู่ในขณะนี้ |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](./get_formatprovider/)() | ส่งคืนอ็อบเจกต์ [IFormatProvider](../../system/iformatprovider/) ที่ใช้อยู่ในขณะนี้ |
| virtual [System::String](../../system/string/) [get_NewLine](./get_newline/)() const | ส่งคืนสตริงตัวจบบรรทัด |
| [String](../../system/string/) [get_NewLine](./get_newline/)() | ส่งคืนสตริงตัวจบบรรทัด |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอนาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถแฮชอ็อบเจกต์ที่กำหนดเองได้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. เป็นอนาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแทนซ์ของประเภทที่อธิบายโดย targetType. เป็นอนาล็อกของโอเปอเรเตอร์ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอนาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้สามารถโคลนประเภทที่กำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรักเตอร์คัดลอก. จริง ๆ ไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรักเตอร์ของคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ ไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรักเตอร์ของคลาสย่อย |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์ลงตามค่าที่กำหนด |
| virtual void [set_NewLine](./set_newline/)(const [System::String](../../system/string/)\&) | ตั้งค่าสตริงตัวจบบรรทัด |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่จะเป็น shared). อนุญาตให้เปลี่ยนพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนตัวนับอ้างอิงที่แชร์และส่งค่ากลับ. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอนาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/). ทำให้สามารถแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| virtual void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | เขียนการแสดงผลเป็นสตริงของอ็อบเจกต์ที่ระบุไปยังสตรีม |
| virtual void [Write](./write/)(**bool**) | เขียนการแสดงผลเป็นสตริงของค่าบูลีนที่ระบุไปยังสตรีม |
| virtual void [Write](./write/)(char_t) | เขียนอักขระที่ระบุไปยังสตรีม |
| virtual void [Write](./write/)([Decimal](../../system/decimal/)) | เขียนการแสดงผลเป็นสตริงของอ็อบเจกต์ [Decimal](../../system/decimal/) ที่ระบุไปยังสตรีม |
| virtual void [Write](./write/)(**double**) | เขียนการแสดงผลเป็นสตริงของค่าจุดลอยคู่ความแม่นยำที่ระบุไปยังสตรีม |
| virtual void [Write](./write/)(int) | เขียนการแสดงผลเป็นสตริงของค่าจำนวนเต็ม 32-บิตที่ระบุไปยังสตรีม |
| virtual void [Write](./write/)(**int64_t**) | เขียนการแสดงผลเป็นสตริงของค่าจำนวนเต็ม 64-บิตที่ระบุไปยังสตรีม |
| virtual void [Write](./write/)(**float**) | เขียนการแสดงผลเป็นสตริงของค่าจุดลอยเดี่ยวความแม่นยำที่ระบุไปยังสตรีม |
| virtual void [Write](./write/)(const [String](../../system/string/)\&) | เขียนสตริงที่ระบุไปยังสตรีม |
| virtual void [Write](./write/)(**uint32_t**) | เขียนการแสดงผลเป็นสตริงของค่าจำนวนเต็มบวกลบ 32-บิตที่ระบุไปยังสตรีม |
| virtual void [Write](./write/)(**uint64_t**) | เขียนการแสดงผลเป็นสตริงของค่าจำนวนเต็มบวกลบ 64-บิตที่ระบุไปยังสตรีม |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | เขียนอักขระทั้งหมดจากอาเรย์ที่ระบุไปยังสตรีม |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | เขียนช่วงย่อยของอักขระ UTF-16 จากอาเรย์ที่ระบุไปยังสตรีม |
| virtual void [Write](./write/)(const char_t *) | เขียน c-string ที่ระบุไปยังสตรีม |
| virtual void [Write](./write/)(const [TypeInfo](../../system/typeinfo/)\&) | เขียนการแสดงผลเป็นสตริงของอ็อบเจกต์ [TypeInfo](../../system/typeinfo/) ที่ระบุไปยังสตรีม |
| void [Write](./write/)(const [String](../../system/string/)\&, const TArgs\&...) | เขียนค่าที่ระบุโดยจัดรูปตามรูปแบบที่กำหนดไปยังสตรีม |
| virtual void [WriteLine](./writeline/)() | เขียนอักขระตัวจบบรรทัดไปยังสตรีม |
| virtual void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | เขียนการแสดงผลเป็นสตริงของอ็อบเจกต์ที่ระบุแล้วตามด้วยอักขระตัวจบบรรทัดไปยังสตรีม |
| virtual void [WriteLine](./writeline/)(**bool**) | เขียนการแสดงผลเป็นสตริงของค่าบูลีนที่ระบุแล้วตามด้วยอักขระตัวจบบรรทัดไปยังสตรีม |
| virtual void [WriteLine](./writeline/)(char_t) | เขียนอักขระที่ระบุแล้วตามด้วยอักขระตัวจบบรรทัดไปยังสตรีม |
| virtual void [WriteLine](./writeline/)([Decimal](../../system/decimal/)) | เขียนการแสดงผลเป็นสตริงของอ็อบเจกต์ [Decimal](../../system/decimal/) ที่ระบุแล้วตามด้วยอักขระตัวจบบรรทัดไปยังสตรีม |
| virtual void [WriteLine](./writeline/)(**double**) | เขียนการแสดงผลเป็นสตริงของค่าจุดลอยคู่ความแม่นยำที่ระบุแล้วตามด้วยอักขระตัวจบบรรทัดไปยังสตรีม |
| virtual void [WriteLine](./writeline/)(int) | เขียนการแสดงผลเป็นสตริงของค่าจำนวนเต็ม 32-บิตที่ระบุแล้วตามด้วยอักขระตัวจบบรรทัดไปยังสตรีม |
| virtual void [WriteLine](./writeline/)(**int64_t**) | เขียนการแสดงผลเป็นสตริงของค่าจำนวนเต็ม 64-บิตที่ระบุแล้วตามด้วยอักขระตัวจบบรรทัดไปยังสตรีม |
| virtual void [WriteLine](./writeline/)(**float**) | เขียนการแสดงผลเป็นสตริงของค่าจุดลอยเดี่ยวความแม่นยำที่ระบุแล้วตามด้วยอักขระตัวจบบรรทัดไปยังสตรีม |
| virtual void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | เขียนสตริงที่ระบุแล้วตามด้วยอักขระตัวจบบรรทัดไปยังสตรีม |
| virtual void [WriteLine](./writeline/)(**uint32_t**) | เขียนการแสดงผลเป็นสตริงของค่าจำนวนเต็มบวกลบ 32-บิตที่ระบุแล้วตามด้วยอักขระตัวจบบรรทัดไปยังสตรีม |
| virtual void [WriteLine](./writeline/)(**uint64_t**) | เขียนการแสดงผลเป็นสตริงของค่าจำนวนเต็มบวกลบ 64-บิตที่ระบุแล้วตามด้วยอักขระตัวจบบรรทัดไปยังสตรีม |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | เขียนอักขระทั้งหมดจากอาเรย์ที่ระบุแล้วตามด้วยอักขระตัวจบบรรทัดไปยังสตรีม |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | เขียนช่วงย่อยของอักขระ UTF-16 จากอาเรย์ที่ระบุแล้วตามด้วยอักขระตัวจบบรรทัดไปยังสตรีม |
| virtual void [WriteLine](./writeline/)(const char_t *) | เขียน c-string ที่ระบุแล้วตามด้วยอักขระตัวจบบรรทัดไปยังสตรีม |
| virtual void [WriteLine](./writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | เขียนการแสดงผลเป็นสตริงของอ็อบเจกต์ [TypeInfo](../../system/typeinfo/) ที่ระบุแล้วตามด้วยอักขระตัวจบบรรทัดไปยังสตรีม |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | เขียนค่าที่ระบุโดยจัดรูปตามรูปแบบที่กำหนดแล้วตามด้วยอักขระตัวจบบรรทัดไปยังสตรีม |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |
| virtual  [~TextWriter](./~textwriter/)() | ตัวทำลาย |

## ชนิดนิยาม

| ชนิดนิยาม | คำอธิบาย |
| --- | --- |
| [Ptr](./ptr/) | นามแฝงสำหรับพอยน์เตอร์ที่แชร์ไปยังคลาสนี้ |

## ดูเพิ่มเติม

* คลาส [IDisposable](../../system/idisposable/)
* เนมสเปซ [System::IO](../)
* ไลบรารี [Aspose.Slides](../../)