---
title: StreamWriter
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "แสดงถึงผู้เขียนที่เขียนอักขระไปยังสตรีมไบต์. อ็อบเจ็กต์ของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแต็กหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือการตรวจสอบความถูกต้องล้มเหลว. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr เสมอและใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน"
type: docs
weight: 391
url: /th/system.io/streamwriter/
---
## StreamWriter คลาส


แสดงถึงผู้เขียนที่เขียนอักขระไปยังสตรีมไบต์. อ็อบเจ็กต์ของคลาสนี้ควรจัดสรรด้วยฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือการตรวจสอบความถูกต้องล้มเหลว. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) เสมอและใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน

```cpp
class StreamWriter : public System::IO::TextWriter
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| void [Close](./close/)() override | ปิดสตรีมและปล่อยทรัพยากรที่ได้รับ |
| void [Dispose](./dispose/)() override | ปล่อยทรัพยากรทั้งหมดที่ออบเจ็กต์ปัจจุบันใช้และปิดสตรีมพื้นฐาน |
| virtual void [Dispose](./dispose/)(**bool**) | ปล่อยทรัพยากรทั้งหมดที่ออบเจ็กต์ปัจจุบันใช้และปิดสตรีมพื้นฐาน |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบออบเจ็กต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจ็กต์แบบอ้างอิงในรูปแบบ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจ็กต์แบบค่าในรูปแบบ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขลอยแบบ C# ซึ่ง NaN สองตัวจะถือว่าเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขลอยแบบ C# ซึ่ง NaN สองตัวจะถือว่าเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับวัตถุประสงค์ภายในเท่านั้น |
| void [Flush](./flush/)() override | ล้างเนื้อหาของบัฟเฟอร์ไปยังสตรีมพื้นฐานและจากนั้นล้างสตรีมพื้นฐาน |
| **bool** [get_AutoFlush](./get_autoflush/)() const | คืนค่าที่บ่งชี้ว่า [StreamWriter](./) จะล้างข้อมูลไปยังสตรีมพื้นฐานทุกครั้งที่เรียกเมธอด [StreamWriter::Write](./write/) |
| [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() const | คืนค่า shared pointer ไปยังออบเจ็กต์ที่แสดงถึงสตรีมพื้นฐาน |
| [EncodingPtr](../../system/encodingptr/) [get_Encoding](./get_encoding/)() override | คืนค่า encoding ที่กำลังใช้ในขณะนี้ |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | คืนค่าออบเจ็กต์ [IFormatProvider](../../system/iformatprovider/) ที่กำลังใช้ในขณะนี้ |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | คืนค่าออบเจ็กต์ [IFormatProvider](../../system/iformatprovider/) ที่กำลังใช้ในขณะนี้ |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | คืนสตริงตัวจบบรรทัด |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | คืนสตริงตัวจบบรรทัด |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับออบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ที่ทำให้สามารถแฮชออบเจ็กต์ที่กำหนดเองได้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของออบเจ็กต์ เป็นอเนกประสงค์ของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าออบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType เป็นอเนกประสงค์ของโอเปอร์เรเตอร์ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เป็นการล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้ออบเจ็กต์ [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ที่ทำให้สามารถโคลนประเภทที่กำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างออบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นออบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอร์เรเตอร์การกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นออบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจ็กต์แบบค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงแบบ shared ลงตามค่าที่ระบุ |
| void [set_AutoFlush](./set_autoflush/)(**bool**) | คืนค่าที่ระบุว่า [StreamWriter](./) ควรล้างข้อมูลไปยังสตรีมพื้นฐานทุกครั้งที่เรียกเมธอด [StreamWriter::Write](./write/) |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | ตั้งค่าสตริงตัวจบบรรทัด |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กูเมนต์ที่ n ให้เป็น weak pointer (แทนที่จะเป็น shared) ทำให้สามารถสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงแบบ shared |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ shared ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงแบบ shared แล้วคืนค่า ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | สร้างอินสแตนซ์ของออบเจ็กต์ [StreamWriter](./) ที่เขียนอักขระไปยังสตรีมพื้นฐานที่ระบุโดยใช้การเข้ารหัส UTF-8 และบัฟเฟอร์ขนาดเริ่มต้น 1024 ไบต์ |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | สร้างอินสแตนซ์ของออบเจ็กต์ [StreamWriter](./) ที่เขียนอักขระไปยังสตรีมพื้นฐานที่ระบุโดยใช้การเข้ารหัสที่กำหนดและบัฟเฟอร์ขนาดเริ่มต้น 1024 ไบต์ |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, int, **bool**) | สร้างอินสแตนซ์ของออบเจ็กต์ [StreamWriter](./) ที่เขียนอักขระไปยังสตรีมพื้นฐานที่ระบุโดยใช้การเข้ารหัสที่กำหนดและบัฟเฟอร์ขนาดที่กำหนด พารามิเตอร์ระบุว่าควรปิดสตรีมพื้นฐานเมื่อออบเจ็กต์ [StreamWriter](./) ถูกทำลาย |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&) | สร้างอินสแตนซ์ของออบเจ็กต์ [StreamWriter](./) ที่เขียนอักขระไปยังไฟล์ที่ระบุโดยใช้การเข้ารหัส UTF-8 และบัฟเฟอร์ขนาดเริ่มต้น 1024 ไบต์ |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&) | สร้างอินสแตนซ์ของออบเจ็กต์ [StreamWriter](./) ที่เขียนอักขระไปยังไฟล์ที่ระบุโดยใช้การเข้ารหัสที่กำหนดและบัฟเฟอร์ขนาดเริ่มต้น 1024 ไบต์ พารามิเตอร์ระบุว่าข้อมูลควรต่อเติมไฟล์หรือเขียนทับไฟล์ |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&, int) | สร้างอินสแตนซ์ของออบเจ็กต์ [StreamWriter](./) ที่เขียนอักขระไปยังไฟล์ที่ระบุโดยใช้การเข้ารหัสและขนาดบัฟเฟอร์ที่กำหนด พารามิเตอร์ระบุว่าข้อมูลควรต่อเติมไฟล์หรือเขียนทับไฟล์ |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.ToString()](../../system/object/tostring/) ที่ทำให้สามารถแปลงออบเจ็กต์ที่กำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็นโครงสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้ออบเจ็กต์ [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน |
| void [Write](./write/)(char_t) override | เขียนอักขระที่ระบุไปยังสตรีม |
| void [Write](./write/)(const [String](../../system/string/)\&) override | เขียนสตริงที่ระบุไปยังสตรีม |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | เขียนการแสดงผลเป็นสตริงของออบเจ็กต์ที่ระบุไปยังสตรีม |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | เขียนอักขระทั้งหมดจากอาเรย์ที่ระบุไปยังสตรีม |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | เขียนช่วงย่อยของอักขระ UTF-16 ที่ระบุจากอาเรย์อักขระที่ระบุไปยังสตรีม |
| void [Write](./write/)(const char_t *) override | เขียน c-string ที่ระบุไปยังสตรีม |
| void [Write](./write/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | เขียนการแสดงผลเป็นสตริงของออบเจ็กต์ที่ระบุไปยังสตรีม |
| virtual void [Write](../textwriter/write/)(**bool**) | เขียนการแสดงผลเป็นสตริงของค่า boolean ที่ระบุไปยังสตรีม |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | เขียนการแสดงผลเป็นสตริงของออบเจ็กต์ [Decimal](../../system/decimal/) ที่ระบุไปยังสตรีม |
| virtual void [Write](../textwriter/write/)(**double**) | เขียนการแสดงผลเป็นสตริงของค่า double-precision floating point ที่ระบุไปยังสตรีม |
| virtual void [Write](../textwriter/write/)(int) | เขียนการแสดงผลเป็นสตริงของค่า integer 32 บิตที่ระบุไปยังสตรีม |
| virtual void [Write](../textwriter/write/)(**int64_t**) | เขียนการแสดงผลเป็นสตริงของค่า integer 64 บิตที่ระบุไปยังสตรีม |
| virtual void [Write](../textwriter/write/)(**float**) | เขียนการแสดงผลเป็นสตริงของค่า single-precision floating point ที่ระบุไปยังสตรีม |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | เขียนการแสดงผลเป็นสตริงของค่า unsigned integer 32 บิตที่ระบุไปยังสตรีม |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | เขียนการแสดงผลเป็นสตริงของค่า unsigned integer 64 บิตที่ระบุไปยังสตรีม |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | เขียนการแสดงผลเป็นสตริงของออบเจ็กต์ [TypeInfo](../../system/typeinfo/) ที่ระบุไปยังสตรีม |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | เขียนค่าที่ระบุโดยจัดรูปตามรูปแบบที่ระบุไปยังสตรีม |
| void [WriteLine](./writeline/)() override | เขียนอักขระจบบรรทัดไปยังสตรีม |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&) override | เขียนสตริงที่ระบุตามด้วยอักขระจบบรรทัดไปยังสตรีม |
| void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | เขียนการแสดงผลเป็นสตริงของออบเจ็กต์ที่ระบุตามด้วยอักขระจบบรรทัดไปยังสตรีม |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | เขียนอักขระทั้งหมดจากอาเรย์ที่ระบุตามด้วยอักขระจบบรรทัดไปยังสตรีม |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | เขียนช่วงย่อยของอักขระ UTF-16 จากอาเรย์อักขระที่ระบุตามด้วยอักขระจบบรรทัดไปยังสตรีม |
| void [WriteLine](./writeline/)(const char_t *) override | เขียน c-string ที่ระบุตามด้วยอักขระจบบรรทัดไปยังสตรีม |
| void [WriteLine](./writeline/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | เขียนการแสดงผลเป็นสตริงของออบเจ็กต์ที่ระบุตามด้วยอักขระจบบรรทัดไปยังสตรีม |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | เขียนการแสดงผลเป็นสตริงของค่า boolean ที่ระบุตามด้วยอักขระจบบรรทัดไปยังสตรีม |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | เขียนอักขระที่ระบุตามด้วยอักขระจบบรรทัดไปยังสตรีม |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | เขียนการแสดงผลเป็นสตริงของออบเจ็กต์ [Decimal](../../system/decimal/) ที่ระบุตามด้วยอักขระจบบรรทัดไปยังสตรีม |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | เขียนการแสดงผลเป็นสตริงของค่า double-precision floating point ที่ระบุตามด้วยอักขระจบบรรทัดไปยังสตรีม |
| virtual void [WriteLine](../textwriter/writeline/)(int) | เขียนการแสดงผลเป็นสตริงของค่า integer 32 บิตที่ระบุตามด้วยอักขระจบบรรทัดไปยังสตรีม |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | เขียนการแสดงผลเป็นสตริงของค่า integer 64 บิตที่ระบุตามด้วยอักขระจบบรรทัดไปยังสตรีม |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | เขียนการแสดงผลเป็นสตริงของค่า single-precision floating point ที่ระบุตามด้วยอักขระจบบรรทัดไปยังสตรีม |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | เขียนการแสดงผลเป็นสตริงของค่า unsigned integer 32 บิตที่ระบุตามด้วยอักขระจบบรรทัดไปยังสตรีม |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | เขียนการแสดงผลเป็นสตริงของค่า unsigned integer 64 บิตที่ระบุตามด้วยอักขระจบบรรทัดไปยังสตรีม |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | เขียนการแสดงผลเป็นสตริงของออบเจ็กต์ [TypeInfo](../../system/typeinfo/) ที่ระบุตามด้วยอักขระจบบรรทัดไปยังสตรีม |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | เขียนค่าที่ระบุโดยจัดรูปตามรูปแบบที่ระบุตามด้วยอักขระจบบรรทัดไปยังสตรีม |
| virtual  [~Object](../../system/object/~object/)() | ทำลายออบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |
|  [~StreamWriter](./~streamwriter/)() | ตัวทำลาย |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | ตัวทำลาย |

## ดูเพิ่มเติม

* คลาส [TextWriter](../textwriter/)
* เนมสเปซ [System::IO](../)
* ไลบรารี [Aspose.Slides](../../)