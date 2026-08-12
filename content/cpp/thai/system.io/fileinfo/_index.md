---
title: FileInfo
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "เป็นตัวแทนของเส้นทางไปยังไฟล์และไฟล์ที่อ้างอิงโดยเส้นทางนี้ พร้อมให้วิธีการสำหรับการจัดการไฟล์เหล่านั้น วัตถุของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น อย่าสร้างอินสแตนซ์ของชนิดนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดเวลารันหรือการตรวจสอบล้มเหลว เสมอห่อหุ้มคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้ฟังก์ชัน"
type: docs
weight: 274
url: /th/system.io/fileinfo/
---
## คลาส FileInfo

Represents a path to a file and a file referred to by this path and provides methods for manipulating it. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class FileInfo : public System::IO::FileSystemInfo
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)() | เปิดไฟล์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันเพื่อเขียนข้อความโดยใช้การเข้ารหัส UTF-8 ในโหมด 'Append' โดยไม่มีการแชร์. |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&) | คัดลอกไฟล์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันไปยังตำแหน่งที่ระบุ. หากไฟล์ปลายทางมีอยู่แล้ว การคัดลอกจะล้มเหลว. |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&, **bool**) | คัดลอกไฟล์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันไปยังตำแหน่งที่ระบุ. พารามิเตอร์ระบุว่าควรเขียนทับไฟล์ปลายทางที่มีอยู่หรือไม่. |
| [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)() | สร้างไฟล์ที่ตำแหน่งที่กำหนดโดยเส้นทางที่แสดงโดยอ็อบเจ็กต์ปัจจุบันและเปิดเพื่ออ่านและเขียนในโหมดตัด (truncate) โดยไม่มีการแชร์. |
| [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)() | สร้างไฟล์ที่ตำแหน่งที่กำหนดโดยเส้นทางที่แสดงโดยอ็อบเจ็กต์ปัจจุบันและเปิดเพื่อเขียนข้อความโดยใช้การเข้ารหัส UTF-8 โดยไม่มีการแชร์. |
| void [Decrypt](./decrypt/)() | ยังไม่ได้ทำการใช้งาน. |
| void [Delete](./delete/)() override | ลบไฟล์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [Encrypt](./encrypt/)() | ยังไม่ได้ทำการใช้งาน. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้แนวคิดของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในรูปแบบ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในรูปแบบ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่ถือว่า NaN สองค่ามีค่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าหรือค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่ถือว่า NaN สองค่ามีค่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าหรือค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
|  [FileInfo](./fileinfo/)(const [String](../../system/string/)\&) | สร้างอินสแตนซ์ใหม่ของคลาส [FileInfo](./) ที่แสดงไฟล์ที่ระบุ. |
| virtual void [Finalize](../filesysteminfo/finalize/)() | ไม่ได้ทำอะไร. |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | ส่งคืนแอตทริบิวต์ของเอนทิตีที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | ส่งคืนเวลาในการสร้างของเอนทิตีที่แสดงโดยอ็อบเจ็กต์ปัจจุบันเป็นเวลาท้องถิ่น. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | ส่งคืนเวลาในการสร้างของเอนทิตีที่แสดงโดยอ็อบเจ็กต์ปัจจุบันเป็นเวลา UTC. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Directory](./get_directory/)() | ส่งคืนอ็อบเจ็กต์ [DirectoryInfo](../directoryinfo/) ที่แสดงไดเรกทอรีที่ไฟล์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันตั้งอยู่. |
| [String](../../system/string/) [get_DirectoryName](./get_directoryname/)() | ส่งคืนชื่อเต็มของไดเรกทอรีที่ไฟล์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันตั้งอยู่. |
| **bool** [get_Exists](./get_exists/)() override | ส่งคืนค่าที่บ่งบอกว่าไฟล์มีอยู่หรือไม่. |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | ส่งคืนสกุลไฟล์ของไฟล์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | ส่งคืนชื่อเต็ม (รวมเส้นทาง) ของเอนทิตีที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | ส่งคืนค่าที่บ่งบอกว่าแอตทริบิวต์ ReadOnly ถูกตั้งค่าไว้หรือไม่. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | ส่งคืนเวลาการเข้าถึงครั้งสุดท้ายของเอนทิตีที่แสดงโดยอ็อบเจ็กต์ปัจจุบันเป็นเวลาท้องถิ่น. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | ส่งคืนเวลาการเข้าถึงครั้งสุดท้ายของเอนทิตีที่แสดงโดยอ็อบเจ็กต์ปัจจุบันเป็นเวลา UTC. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | ส่งคืนเวลาเขียนครั้งสุดท้ายของเอนทิตีที่แสดงโดยอ็อบเจ็กต์ปัจจุบันเป็นเวลาท้องถิ่น. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | ส่งคืนเวลาเขียนครั้งสุดท้ายของเอนทิตีที่แสดงโดยอ็อบเจ็กต์ปัจจุบันเป็นเวลา UTC. |
| **int64_t** [get_Length](./get_length/)() | ส่งคืนขนาดของไฟล์เป็นไบต์. |
| [String](../../system/string/) [get_Name](./get_name/)() override | ส่งคืนชื่อของไฟล์. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เทียบเท่ากับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจ็กต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทที่แท้จริงของอ็อบเจ็กต์. เทียบเท่ากับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เทียบเท่ากับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำงานตามการล็อกของคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เทียบเท่ากับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการคัดลอกประเภทที่กำหนดเอง. |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | ย้ายไฟล์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันไปยังตำแหน่งที่ระบุ. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้การคัดลอกคอนสตรัคเตอร์ของคลาสย่อย. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/)) | เปิดไฟล์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันในโหมดที่ระบุเพื่ออ่านและเขียนโดยไม่มีการแชร์. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/)) | เปิดไฟล์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันในโหมดที่ระบุพร้อมประเภทการเข้าถึงที่ระบุและไม่มีการแชร์. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | เปิดไฟล์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันในโหมดที่ระบุพร้อมประเภทการเข้าถึงและตัวเลือกการแชร์ที่ระบุ. |
| [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)() | เปิดไฟล์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันเพื่ออ่านอย่างเดียวในโหมด 'Open' โดยเข้าถึงแบบแชร์สำหรับการอ่าน. |
| [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)() | เปิดไฟล์ที่มีอยู่ที่ตำแหน่งที่ระบุโดยเส้นทางที่แสดงโดยอ็อบเจ็กต์ปัจจุบันเพื่ออ่านข้อความโดยใช้การเข้ารหัส UTF-8 โดยไม่มีการแชร์. |
| [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)() | เปิดไฟล์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันเพื่อเขียนอย่างเดียวในโหมด 'OpenOrCreate' โดยไม่มีการแชร์. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้การคัดลอกคอนสตรัคเตอร์ของคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงของอ็อบเจ็กต์ประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | เชิงพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | เชิงพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| void [Refresh](../filesysteminfo/refresh/)() | รีเฟรชสถานะของอ็อบเจ็กต์ปัจจุบัน. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์โดยค่าที่ระบุ. |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | แทนที่เนื้อหาของไฟล์ปลายทางที่ระบุด้วยไฟล์ที่แสดงโดยอ็อบเจ็กต์ [FileInfo](./) ปัจจุบันและสร้างสำเนาสำรองของไฟล์ที่ถูกแทนที่. |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | แทนที่เนื้อหาของไฟล์ปลายทางที่ระบุด้วยไฟล์ที่แสดงโดยอ็อบเจ็กต์ [FileInfo](./) ปัจจุบันและสร้างสำเนาสำรองของไฟล์ที่ถูกแทนที่. |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | ตั้งค่าแอตทริบิวต์ที่ระบุบนเอนทิตีที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | ตั้งค่าเวลาในการสร้างของเอนทิตีที่แสดงโดยอ็อบเจ็กต์ปัจจุบันเป็นเวลาท้องถิ่น. |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | ตั้งค่าเวลาในการสร้างของเอนทิตีที่แสดงโดยอ็อบเจ็กต์ปัจจุบันเป็นเวลา UTC. |
| void [set_IsReadOnly](./set_isreadonly/)(**bool**) | ตั้งหรือยกเลิกแอตทริบิวต์ ReadOnly ของไฟล์. |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | ตั้งเวลาเข้าถึงครั้งสุดท้ายของเอนทิตีที่แสดงโดยอ็อบเจ็กต์ปัจจุบันเป็นเวลาท้องถิ่น. |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | ตั้งเวลาเข้าถึงครั้งสุดท้ายของเอนทิตีที่แสดงโดยอ็อบเจ็กต์ปัจจุบันเป็นเวลา UTC. |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | ตั้งเวลาเขียนครั้งสุดท้ายของเอนทิตีที่แสดงโดยอ็อบเจ็กต์ปัจจุบันเป็นเวลาท้องถิ่น. |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | ตั้งเวลาเขียนครั้งสุดท้ายของเอนทิตีที่แสดงโดยอ็อบเจ็กต์ปัจจุบันเป็นเวลา UTC. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตลำดับที่ n เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นแบบ weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; แทนที่ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนและส่งคืนตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; แทนที่ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | ส่งคืนเส้นทางที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามการปลดล็อกของคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนที่ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนที่ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [FileSystemInfo](../filesysteminfo/)
* เนมสเปซ [System::IO](../)
* ไลบรารี [Aspose.Slides](../../)