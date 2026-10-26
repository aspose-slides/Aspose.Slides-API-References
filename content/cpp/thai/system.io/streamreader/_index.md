---
title: StreamReader
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "เป็นตัวอ่านที่อ่านอักขระจากสตรีมไบต์. ออบเจกต์ของคลาสนี้ควรจัดสรรด้วยฟังก์ชัน System::MakeObject() เท่านั้น. อย่าสร้างอินสแตนซ์ของชนิดนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อหุ้มคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้ส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 378
url: /th/system.io/streamreader/
---
## คลาส StreamReader

Represents a reader that reads characters from a byte stream. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class StreamReader : public System::IO::TextReader
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| void [Close](./close/)() override | ปิดสตรีมปัจจุบันและสตรีมพื้นฐาน |
| virtual void [Dispose](./dispose/)(**bool**) | ปล่อยทรัพยากรทั้งหมดที่ใช้โดยอ็อบเจกต์ปัจจุบันและปิดสตรีมพื้นฐาน |
| void [Dispose](./dispose/)() override | ปล่อยทรัพยากรทั้งหมดที่ใช้โดยอ็อบเจกต์ปัจจุบันและปิดสตรีมพื้นฐาน |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่ในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจริงสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าหรือค่าใด ๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจริงสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าหรือค่าใด ๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น |
| [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() const | ส่งกลับพอยน์เตอร์ shared pointer ไปยังอ็อบเจกต์ที่แสดงสตรีมพื้นฐาน |
| [EncodingPtr](../../system/encodingptr/) [get_CurrentEncoding](./get_currentencoding/)() | ส่งกลับการเข้ารหัสที่ใช้อยู่ในขณะนี้ |
| **bool** [get_EndOfStream](./get_endofstream/)() | ส่งกลับค่าที่บ่งชี้ว่าถึงจุดสิ้นสุดของสตรีมแล้วหรือไม่ |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็น analogue ของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถสร้างแฮชของอ็อบเจกต์แบบกำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์ เป็น analogue ของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เป็น analogue ของโอเปอร์เรเตอร์ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentry [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็น analogue ของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทกำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์มอบหมาย ไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| int [Peek](./peek/)() override | อ่านอักขระเดียวจากสตรีมโดยไม่เปลี่ยนตำแหน่งเคอร์เซอร์การอ่านของสตรีม |
| int [Read](./read/)() override | อ่านอักขระเดียวจากสตรีม |
| int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) override | อ่านจำนวนอักขระที่ระบุจากสตรีม แปลงเป็นการเข้ารหัส UTF-16 แล้วเขียนอักขระ UTF-16 ที่ได้ลงในอาร์เรย์อักขระที่ระบุเริ่มจากตำแหน่งที่กำหนด |
| virtual int [ReadBlock](../textreader/readblock/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | อ่านจำนวนอักขระสูงสุดที่ระบุจากเครื่องอ่านข้อความปัจจุบันและเขียนข้อมูลลงในบัฟเฟอร์ เริ่มจากตำแหน่งที่ระบุ |
| [String](../../system/string/) [ReadLine](./readline/)() override | อ่านอักขระจากสตรีมจนถึงจบบรรทัดปัจจุบัน |
| [String](../../system/string/) [ReadToEnd](./readtoend/)() override | อ่านอักขระจากสตรีมจนถึงจบสตรีม |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจกต์ประเภทค่ากับ nullptr โดยอ้างอิง |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงแบบ shared ลงตามค่าที่ระบุ |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทน shared) ช่วยให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงแบบ shared |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ shared ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงแบบ shared และส่งค่ากลับ ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | สร้างอินสแตนซ์ของอ็อบเจกต์ [StreamReader](./) ที่อ่านอักขระจากสตรีมพื้นฐานที่ระบุโดยใช้การเข้ารหัส UTF-8 และบัฟเฟอร์ขนาดเริ่มต้น 1024 ไบต์ |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **bool**) | สร้างอินสแตนซ์ของอ็อบเจ็กต์ [StreamReader](./) ที่อ่านอักขระจากสตรีมพื้นฐานที่ระบุโดยใช้การเข้ารหัส UTF-8 และบัฟเฟอร์ขนาดเริ่มต้น 1024 ไบต์ พารามิเตอร์กำหนดว่าจะเปิดการตรวจจับ byte order mark หรือไม่ |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | สร้างอินสแตนซ์ของอ็อบเจ็กต์ [StreamReader](./) ที่อ่านอักขระจากสตรีมพื้นฐานที่ระบุโดยใช้การเข้ารหัสที่ระบุและบัฟเฟอร์ขนาดเริ่มต้น 1024 ไบต์ |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | สร้างอินสแตนซ์ของอ็อบเจ็กต์ [StreamReader](./) ที่อ่านอักขระจากสตรีมพื้นฐานที่ระบุโดยใช้การเข้ารหัสที่ระบุและบัฟเฟอร์ขนาดเริ่มต้น 1024 ไบต์ พารามิเตอร์กำหนดว่าจะเปิดการตรวจจับ byte order mark หรือไม่ |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**, int) | สร้างอินสแตนซ์ของอ็อบเจ็กต์ [StreamReader](./) ที่อ่านอักขระจากสตรีมพื้นฐานที่ระบุโดยใช้การเข้ารหัสที่ระบุและบัฟเฟอร์ขนาดตามที่ระบุ พารามิเตอร์กำหนดว่าจะเปิดการตรวจจับ byte order mark หรือไม่ |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&) | สร้างอินสแตนซ์ของอ็อบเจ็กต์ [StreamReader](./) ที่อ่านอักขระจากไฟล์ที่ระบุโดยใช้การเข้ารหัส UTF-8 และบัฟเฟอร์ขนาดเริ่มต้น 4096 ไบต์ |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, **bool**) | สร้างอินสแตนซ์ของอ็อบเจ็กต์ [StreamReader](./) ที่อ่านอักขระจากไฟล์ที่ระบุโดยใช้การเข้ารหัส UTF-8 และบัฟเฟอร์ขนาดเริ่มต้น 4096 ไบต์ พารามิเตอร์กำหนดว่าจะเปิดการตรวจจับ byte order mark หรือไม่ |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | สร้างอินสแตนซ์ของอ็อบเจ็กต์ [StreamReader](./) ที่อ่านอักขระจากไฟล์ที่ระบุโดยใช้การเข้ารหัสที่ระบุและบัฟเฟอร์ขนาดเริ่มต้น 4096 ไบต์ |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | สร้างอินสแตนซ์ของอ็อบเจ็กต์ [StreamReader](./) ที่อ่านอักขระจากสตรีมพื้นฐานที่ระบุโดยใช้การเข้ารหัสที่ระบุและบัฟเฟอร์ขนาดเริ่มต้น 4096 ไบต์ พารามิเตอร์กำหนดว่าจะเปิดการตรวจจับ byte order manifest หรือไม่ |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**, int) | สร้างอินสแตนซ์ของอ็อบเจ็กต์ [StreamReader](./) ที่อ่านอักขระจากไฟล์ที่ระบุโดยใช้การเข้ารหัสที่ระบุและบัฟเฟอร์ขนาดตามที่ระบุ พารามิเตอร์กำหนดว่าจะเปิดการตรวจจับ byte order mark หรือไม่ |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็น analogue ของเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจ็กต์แบบกำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็น construct typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentry [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด |
|  [~StreamReader](./~streamreader/)() | ตัวทำลาย |

## ดูเพิ่มเติม

* คลาส [TextReader](../textreader/)
* เนมสเปซ [System::IO](../)
* ไลบรารี [Aspose.Slides](../../)