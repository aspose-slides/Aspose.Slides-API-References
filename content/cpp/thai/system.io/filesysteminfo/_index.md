---
title: FileSystemInfo
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "คลาสฐานสำหรับ FileInfo และ DirectoryInfo. อ็อบเจกต์ของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr เสมอและใช้พอยน์เตอร์นี้เพื่อส่งผ่านไปยังฟังก์ชันเป็นอาร์กิวเมนต์."
type: docs
weight: 300
url: /th/system.io/filesysteminfo/
---
## FileSystemInfo คลาส


คลาสฐานสำหรับ [FileInfo](../fileinfo/) และ [DirectoryInfo](../directoryinfo/). อ็อบเจกต์ของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../../system/smartptr/) เสมอและใช้ตัวชี้นี้เพื่อส่งผ่านไปยังฟังก์ชันเป็นอาร์กิวเมนต์.

```cpp
class FileSystemInfo : public System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual void [Delete](./delete/)() | ลบเอนทิตีที่เป็นตัวแทนของอ็อบเจกต์ปัจจุบัน |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้รูปแบบของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ชนิดอ้างอิงในสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ชนิดค่าในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยตัวแบบ C#-style ที่ NaN สองค่าถูกพิจารณาเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยตัวแบบ C#-style ที่ NaN สองค่าถูกพิจารณาเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น |
| virtual void [Finalize](./finalize/)() | ไม่มีการทำอะไร |
| [FileAttributes](../fileattributes/) [get_Attributes](./get_attributes/)() | คืนคุณลักษณะของเอนทิตีที่เป็นตัวแทนของอ็อบเจกต์ปัจจุบัน |
| [DateTime](../../system/datetime/) [get_CreationTime](./get_creationtime/)() | คืนเวลาการสร้างของเอนทิตีที่เป็นตัวแทนของอ็อบเจกต์ปัจจุบันเป็นเวลาท้องถิ่น |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](./get_creationtimeutc/)() | คืนเวลาการสร้างของเอนทิตีที่เป็นตัวแทนของอ็อบเจกต์ปัจจุบันเป็นเวลา UTC |
| virtual **bool** [get_Exists](./get_exists/)() | กำหนดว่ามีเอนทิตีที่อ้างอิงโดยเส้นทางที่เป็นตัวแทนของอ็อบเจกต์ปัจจุบันหรือไม่ |
| [String](../../system/string/) [get_Extension](./get_extension/)() | คืนส่วนขยายของไฟล์ที่เป็นตัวแทนของอ็อบเจกต์ปัจจุบัน |
| virtual [String](../../system/string/) [get_FullName](./get_fullname/)() | คืนชื่อเต็ม (รวมเส้นทาง) ของเอนทิตีที่เป็นตัวแทนของอ็อบเจกต์ปัจจุบัน |
| [DateTime](../../system/datetime/) [get_LastAccessTime](./get_lastaccesstime/)() | คืนเวลาการเข้าถึงครั้งสุดท้ายของเอนทิตีที่เป็นตัวแทนของอ็อบเจกต์ปัจจุบันเป็นเวลาท้องถิ่น |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](./get_lastaccesstimeutc/)() | คืนเวลาการเข้าถึงครั้งสุดท้ายของเอนทิตีที่เป็นตัวแทนของอ็อบเจกต์ปัจจุบันเป็นเวลา UTC |
| [DateTime](../../system/datetime/) [get_LastWriteTime](./get_lastwritetime/)() | คืนเวลาการเขียนครั้งสุดท้ายของเอนทิตีที่เป็นตัวแทนของอ็อบเจกต์ปัจจุบันเป็นเวลาท้องถิ่น |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](./get_lastwritetimeutc/)() | คืนเวลาการเขียนครั้งสุดท้ายของเอนทิตีที่เป็นตัวแทนของอ็อบเจกต์ปัจจุบันเป็นเวลา UTC |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | คืนชื่อของเอนทิตีที่เป็นตัวแทนของอ็อบเจกต์ปัจจุบัน |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอนาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการทำแฮชของอ็อบเจกต์ที่กำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทที่แท้จริงของอ็อบเจกต์. เป็นอนาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นอนาล็อกของตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอนาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนของชนิดที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรักเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงของอ็อบเจกต์ชนิดค่ากับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| void [Refresh](./refresh/)() | รีเฟรชสถานะของอ็อบเจกต์ปัจจุบัน |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| void [set_Attributes](./set_attributes/)([FileAttributes](../fileattributes/)) | ตั้งค่าแอตทริบิวต์ที่ระบุบนเอนทิตีที่เป็นตัวแทนของอ็อบเจกต์ปัจจุบัน |
| void [set_CreationTime](./set_creationtime/)([DateTime](../../system/datetime/)) | ตั้งค่าเวลาการสร้างของเอนทิตีที่เป็นตัวแทนของอ็อบเจกต์ปัจจุบันเป็นเวลาท้องถิ่น |
| void [set_CreationTimeUtc](./set_creationtimeutc/)([DateTime](../../system/datetime/)) | ตั้งค่าเวลาการสร้างของเอนทิตีที่เป็นตัวแทนของอ็อบเจกต์ปัจจุบันเป็นเวลา UTC |
| void [set_LastAccessTime](./set_lastaccesstime/)([DateTime](../../system/datetime/)) | ตั้งค่าเวลาการเข้าถึงครั้งสุดท้ายของเอนทิตีที่เป็นตัวแทนของอ็อบเจกต์ปัจจุบันเป็นเวลาท้องถิ่น |
| void [set_LastAccessTimeUtc](./set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | ตั้งค่าเวลาการเข้าถึงครั้งสุดท้ายของเอนทิตีที่เป็นตัวแทนของอ็อบเจกต์ปัจจุบันเป็นเวลา UTC |
| void [set_LastWriteTime](./set_lastwritetime/)([DateTime](../../system/datetime/)) | ตั้งค่าเวลาการเขียนครั้งสุดท้ายของเอนทิตีที่เป็นตัวแทนของอ็อบเจกต์ปัจจุบันเป็นเวลาท้องถิ่น |
| void [set_LastWriteTimeUtc](./set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | ตั้งค่าเวลาการเขียนครั้งสุดท้ายของเอนทิตีที่เป็นตัวแทนของอ็อบเจกต์ปัจจุบันเป็นเวลา UTC |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับตัวชี้ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอนาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็น typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [System::IO](../)
* ไลบรารี [Aspose.Slides](../../)