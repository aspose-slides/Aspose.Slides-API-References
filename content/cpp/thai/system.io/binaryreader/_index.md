---
title: BinaryReader
second_title: การอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "เป็นตัวอ่านที่อ่านประเภทข้อมูลพื้นฐานเป็นข้อมูลไบนารีในรูปแบบการเข้ารหัสที่กำหนด วัตถุของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ ควรหุ้มคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr เสมอและใช้พอยน์เตอร์นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน"
type: docs
weight: 92
url: /th/system.io/binaryreader/
---
## BinaryReader คลาส

เป็นตัวอ่านที่อ่านข้อมูลประเภทพื้นฐานเป็นข้อมูลไบนารีในรูปแบบการเข้ารหัสที่กำหนด วัตถุของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ ควรหุ้มคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) เสมอและใช้พอยน์เตอร์นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน

```cpp
class BinaryReader : public System::IDisposable
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | สร้างอินสแตนซ์ของคลาส [BinaryReader](./) ที่อ่านข้อมูลจากสตรีมที่ระบุโดยใช้การเข้ารหัส UTF-8. |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | สร้างอินสแตนซ์ของคลาส [BinaryReader](./) ที่อ่านข้อมูลจากสตรีมที่ระบุโดยใช้การเข้ารหัสที่ระบุ. |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&, **bool**) | สร้างอินสแตนซ์ของคลาส [BinaryReader](./) ที่อ่านข้อมูลจากสตรีมที่ระบุโดยใช้การเข้ารหัสที่ระบุ. |
| virtual void [Close](./close/)() | ปิดอ็อบเจ็กต์ [BinaryReader](./) ปัจจุบันและสตรีมอินพุตพื้นฐาน |
| void [Dispose](./dispose/)() override | ปล่อยทรัพยากรทั้งหมดที่อ็อบเจ็กต์ปัจจุบันใช้และปิดสตรีมพื้นฐาน |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในรูปแบบ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในรูปแบบ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยตัวแบบ C# ที่ NaN สองค่าถือว่ามีค่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยตัวแบบ C# ที่ NaN สองค่าถือว่ามีค่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() | ส่งคืนสตรีมอินพุต |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลเคาน์เตอร์อ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอะแนโลกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ซึ่งทำให้สามารถแฮชอ็อบเจ็กต์ที่กำหนดเองได้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ เป็นอะแนโลกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เป็นอะแนโลกของโอเปอเรเตอร์ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เป็นการล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอะแนโลกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ซึ่งทำให้สามารถโคลนประเภทที่กำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์และเริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาในคลาสย่อยได้ |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาในคลาสย่อยได้ |
| virtual int [PeekChar](./peekchar/)() | อ่านตัวอักษรเดียวจากสตรีมอินพุตโดยไม่เปลี่ยนตำแหน่งเคอร์เซอร์การอ่านของสตรีม |
| virtual int [Read](./read/)() | อ่านตัวอักษรเดียวจากสตรีมอินพุต |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | อ่านจำนวนไบต์ที่ระบุจากสตรีมอินพุตและเขียนลงในอาเรย์ไบต์ที่ระบุ |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | อ่านจำนวนตัวอักษรที่ระบุจากสตรีมอินพุต แปลงเป็นการเข้ารหัส UTF-16 และเขียนตัวอักษร UTF-16 ที่ได้ลงในอาเรย์ตัวอักษรที่ระบุเริ่มจากตำแหน่งที่ระบุ |
| virtual **bool** [ReadBoolean](./readboolean/)() | อ่านไบต์เดียวจากสตรีมอินพุตและคืนค่าตัวแทนแบบบูลีนของมัน |
| virtual **uint8_t** [ReadByte](./readbyte/)() | อ่านไบต์เดียวจากสตรีมอินพุต |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadBytes](./readbytes/)(int) | อ่านจำนวนไบต์ที่ระบุจากสตรีมอินพุต |
| virtual char_t [ReadChar](./readchar/)() | อ่านตัวอักษรเดียวจากสตรีมอินพุต |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [ReadChars](./readchars/)(int) | อ่านจำนวนตัวอักษรที่ระบุจากสตรีมอินพุตและคืนค่าในรูปแบบการเข้ารหัส UTF-16 |
| virtual [Decimal](../../system/decimal/) [ReadDecimal](./readdecimal/)() | ยังไม่ได้ดำเนินการ. |
| virtual **double** [ReadDouble](./readdouble/)() | อ่าน 8 ไบต์จากสตรีมอินพุตและคืนค่าเป็นค่าจุดลอยแบบ double-precision |
| virtual **int16_t** [ReadInt16](./readint16/)() | อ่าน 2 ไบต์จากสตรีมอินพุตและคืนค่าเป็นจำนวนเต็ม 16 บิต |
| virtual int [ReadInt32](./readint32/)() | อ่าน 4 ไบต์จากสตรีมอินพุตและคืนค่าเป็นจำนวนเต็ม 32 บิต |
| virtual **int64_t** [ReadInt64](./readint64/)() | อ่าน 8 ไบต์จากสตรีมอินพุตและคืนค่าเป็นจำนวนเต็ม 64 บิต |
| virtual **int8_t** [ReadSByte](./readsbyte/)() | อ่านไบต์เดียวจากสตรีมอินพุตและคืนค่าเป็นจำนวนเต็ม 8 บิตมีเครื่องหมาย |
| virtual **float** [ReadSingle](./readsingle/)() | อ่าน 4 ไบต์จากสตรีมอินพุตและคืนค่าเป็นค่าจุดลอยแบบ single-precision |
| virtual [String](../../system/string/) [ReadString](./readstring/)() | อ่านสตริงจากสตรีมปัจจุบัน โดยสตริงจะมีคำนำหน้าความยาวที่เข้ารหัสเป็นจำนวนเต็ม 7 บิตต่อครั้ง |
| virtual **uint16_t** [ReadUInt16](./readuint16/)() | อ่าน 2 ไบต์จากสตรีมอินพุตและคืนค่าเป็นจำนวนเต็มบวก 16 บิต |
| virtual **uint32_t** [ReadUInt32](./readuint32/)() | อ่าน 4 ไบต์จากสตรีมอินพุตและคืนค่าเป็นจำนวนเต็มบวก 32 บิต |
| virtual **uint64_t** [ReadUInt64](./readuint64/)() | อ่าน 8 ไบต์จากสตรีมอินพุตและคืนค่าเป็นจำนวนเต็มบวก 64 บิต |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงของอ็อบเจ็กต์ประเภทค่า กับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายตัว |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่แชร์โดยค่าที่ระบุ |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็นพอยน์เตอร์แบบอ่อน (weak) แทนที่แชร์ ทำให้สามารถสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมดอ่อนได้ |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของเคาน์เตอร์อ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง ให้ใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงที่แชร์และคืนค่า ไม่ควรเรียกโดยตรง ให้ใช้ smart pointers หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอะแนโลกของเมธอด C# [Object.ToString()](../../system/object/tostring/) ที่ทำให้สามารถแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็นการสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบอ่อน ไม่ควรเรียกโดยตรง ให้ใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบอ่อน ไม่ควรเรียกโดยตรง ให้ใช้ smart pointers หรือ ThisProtector |
| virtual  [~BinaryReader](./~binaryreader/)() | ตัวทำลาย |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์และปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [IDisposable](../../system/idisposable/)
* เนมสเปซ [System::IO](../)
* ไลบรารี [Aspose.Slides](../../)