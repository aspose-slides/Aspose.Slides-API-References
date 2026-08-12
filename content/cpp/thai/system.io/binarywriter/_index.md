---
title: BinaryWriter
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "เป็นตัวเขียนที่เขียนค่าของชนิดข้อมูลพื้นฐานไปยังสตรีมไบต์. วัตถุของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อหุ้มคลาสนี้ด้วยตัวชี้ System::SmartPtr เสมอและใช้ตัวชี้นี้เพื่อส่งต่อเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 105
url: /th/system.io/binarywriter/
---
## BinaryWriter คลาส


เป็นตัวเขียนที่เขียนค่าของชนิดข้อมูลพื้นฐานไปยังสตรีมไบต์. วัตถุของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อหุ้มคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../../system/smartptr/) เสมอและใช้ตัวชี้นี้เพื่อส่งต่อเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน.

```cpp
class BinaryWriter : public System::IDisposable
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
|  [BinaryWriter](./binarywriter/)(const [StreamPtr](../../system/streamptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | สร้างอินสแตนซ์ของคลาส [BinaryWriter](./) ที่เขียนข้อมูลไปยังสตรีมที่ระบุโดยใช้การเข้ารหัสที่ระบุ |
| void [Close](./close/)() | ปิดออบเจกต์ [BinaryWriter](./) ปัจจุบันและสตรีมเอาต์พุตที่อยู่ใต้ |
| void [Dispose](./dispose/)() override | ปล่อยทรัพยากรทั้งหมดที่ใช้โดยออบเจกต์ปัจจุบันและปิดสตรีมพื้นฐาน |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบออบเจกต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจกต์แบบอ้างอิงในสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจกต์ค่าประเภทในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขจุดลอยแบบ C# ที่ NaN สองค่าถูกพิจารณาเท่ากัน แม้ว่า ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขจุดลอยแบบ C# ที่ NaN สองค่าถูกพิจารณาเท่ากัน แม้ว่า ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| void [Flush](./flush/)() | ทำการ flush สตรีมเอาต์พุต |
| [StreamPtr](../../system/streamptr/) [get_BaseStream](./get_basestream/)() | คืนค่าสตรีมเอาต์พุต |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับออบเจกต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด [Object.GetHashCode()](../../system/object/gethashcode/) ของ C# ทำให้สามารถแฮชออบเจกต์ที่กำหนดเองได้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของออบเจกต์ คล้ายกับการเรียก [System.Object.GetType()](../../system/object/gettype/) ของ C# |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าออบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ คล้ายกับตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ของ C# ทำให้สามารถคล cloning ประเภทที่กำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างออบเจกต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา ไม่ได้คัดลอกอะไรจริงๆ เพียงเริ่มต้นออบเจกต์ใหม่และเปิดใช้งานการสร้างสำเนาสำหรับซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรจริงๆ เพียงเริ่มต้นออบเจกต์ใหม่และเปิดใช้งานการสร้างสำเนาสำหรับซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบออบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบออบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจกต์ค่าประเภทด้วย nullptr โดยอ้างอิง |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายรายการ |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงร่วมโดยค่าที่ระบุ |
| **int64_t** [Seek](./seek/)(int, [System::IO::SeekOrigin](../seekorigin/)) | ตั้งตำแหน่งของสตรีมที่แทนโดยออบเจกต์ปัจจุบัน |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n ให้เป็นตัวชี้แบบ weak (แทนที่ shared) อนุญาตให้เปลี่ยนตัวชี้ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับการอ้างอิงร่วม ไม่ควรเรียกโดยตรง; แทนนั้นให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับการอ้างอิงร่วม ไม่ควรเรียกโดยตรง; แทนนั้นให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด [Object.ToString()](../../system/object/tostring/) ของ C# ทำให้สามารถแปลงออบเจกต์ที่กำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; แทนนั้นให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; แทนนั้นให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| virtual void [Write](./write/)(**uint8_t**) | เขียนค่าจำนวนเต็มบวก 8 บิตที่กำหนดลงในสตรีมเอาต์พุต |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | เขียนช่วงย่อยของไบต์ที่ระบุจากอาเรย์ไบต์ที่กำหนดลงในสตรีมเอาต์พุต |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | เขียนช่วงย่อยของอักขระ UTF-16 ที่ระบุจากอาเรย์อักขระที่กำหนดลงในสตรีมเอาต์พุต |
| virtual void [Write](./write/)(**bool**) | เขียนไบต์เดียวที่มีค่า 0 หาก **value** เป็น 'true' และ 1 หาก **value** เป็น 'false' ลงในสตรีมเอาต์พุต |
| virtual void [Write](./write/)(char16_t) | เขียนค่าตัวอักษรกว้าง 16 บิตที่ระบุลงในสตรีมเอาต์พุต |
| virtual void [Write](./write/)(**int16_t**) | เขียนค่าจำนวนเต็ม 16-bit ที่ระบุลงในสตรีมเอาต์พุต |
| virtual void [Write](./write/)(int) | เขียนค่าจำนวนเต็ม 32-bit ที่ระบุลงในสตรีมเอาต์พุต |
| virtual void [Write](./write/)(**int64_t**) | เขียนค่าจำนวนเต็ม 64-bit ที่ระบุลงในสตรีมเอาต์พุต |
| virtual void [Write](./write/)(**uint16_t**) | เขียนค่าจำนวนเต็มบวก 16-bit ที่ระบุลงในสตรีมเอาต์พุต |
| virtual void [Write](./write/)(**uint32_t**) | เขียนค่าจำนวนเต็มบวก 32-bit ที่ระบุลงในสตรีมเอาต์พุต |
| virtual void [Write](./write/)(**uint64_t**) | เขียนค่าจำนวนเต็มบวก 64-bit ที่ระบุลงในสตรีมเอาต์พุต |
| virtual void [Write](./write/)(**float**) | เขียนค่าจำนวนจริงความละเอียดเดี่ยวที่ระบุลงในสตรีมเอาต์พุต |
| virtual void [Write](./write/)(**double**) | เขียนค่าจำนวนจริงความละเอียดคู่ที่ระบุลงในสตรีมเอาต์พุต |
| virtual void [Write](./write/)(const [Decimal](../../system/decimal/)\&) | เขียนการแทนค่าไบต์ของค่า [Decimal](../../system/decimal/) ที่ระบุลงในสตรีมเอาต์พุต |
| virtual void [Write](./write/)(const [String](../../system/string/)\&) | เขียนสตริงที่มีความยาวเป็น prefix ในการเข้ารหัสปัจจุบันลงในสตรีมเอาต์พุต |
| virtual void [Write](./write/)(const char_t *) | เขียนสตริงที่มีความยาวเป็น prefix ในการเข้ารหัสปัจจุบันลงในสตรีมเอาต์พุต |
|  [~BinaryWriter](./~binarywriter/)() | ตัวทำลาย |
| virtual  [~Object](../../system/object/~object/)() | ทำลายออบเจกต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |
## ดูเพิ่มเติม

* คลาส [IDisposable](../../system/idisposable/)
* เนมสเปซ [System::IO](../)
* ไลบรารี [Aspose.Slides](../../)