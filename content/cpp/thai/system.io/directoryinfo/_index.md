---
title: DirectoryInfo
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "แทนเส้นทางของระบบไฟล์, ไดเรกทอรีที่อ้างถึงโดยเส้นทางนี้และให้เมธอดอินสแตนซ์สำหรับการจัดการไดเรกทอรี. อ็อบเจ็กต์ของคลาสนี้ควรสร้างด้วยฟังก์ชัน System::MakeObject() เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้โอเปอเรเตอร์ new, เพราะจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือการอ้างอิงที่ล้มเหลว. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 248
url: /th/system.io/directoryinfo/
---
## DirectoryInfo คลาส

Represents a file system path, a directory referred to by this path and provides instance methods for manipulating directories. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DirectoryInfo : public System::IO::FileSystemInfo
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| void [Create](./create/)() | สร้างไดเรกทอรีที่เส้นทางที่อ้างอิงโดยอ็อบเจ็กต์ปัจจุบัน. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [CreateSubdirectory](./createsubdirectory/)(const [String](../../system/string/)\&) | สร้างไดเรกทอรีย่อยในเส้นทางที่ระบุ. |
| void [Delete](./delete/)() override | ลบไดเรกทอรีที่อ้างอิงโดยเส้นทางที่อ็อบเจ็กต์ปัจจุบันถ้าไดเรกทอรีว่าง. |
| void [Delete](./delete/)(**bool**) | ลบไดเรกทอรีที่อ้างอิงโดยเส้นทางที่อ็อบเจ็กต์ปัจจุบัน. พารามิเตอร์ระบุว่าหากไดเรกทอรีไม่ว่าง ควรลบเนื้อหาแบบเรียกซ้ำหรือไม่. |
|  [DirectoryInfo](./directoryinfo/)(const [String](../../system/string/)\&) | สร้างอินสแตนซ์ของคลาส [DirectoryInfo](./) ในเส้นทางที่ระบุ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)() | ส่งกลับคอลเลกชันที่สามารถวนซ้ำได้ซึ่งประกอบด้วยไดเรกทอรีทั้งหมดที่อยู่ในไดเรกทอรีที่อ็อบเจ็กต์ปัจจุบันอ้างอิง. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&) | ค้นหาไดเรกทอรีที่ตรงตามเกณฑ์การค้นหาที่ระบุในไดเรกทอรีที่อ็อบเจ็กต์ปัจจุบันอ้างอิง. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | ค้นหาไดเรกทอรีที่ตรงตามเกณฑ์การค้นหาที่ระบุ ไม่ว่าจะในไดเรกทอรีที่อ็อบเจ็กต์ปัจจุบันอ้างอิง หรือในต้นไม้ไดเรกทอรีทั้งหมดที่เริ่มจากไดเรกทอรีนั้น. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)() | ส่งกลับคอลเลกชันที่สามารถวนซ้ำได้ซึ่งประกอบด้วยไฟล์ทั้งหมดที่อยู่ในไดเรกทอรีที่อ็อบเจ็กต์ปัจจุบันอ้างอิง. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&) | ค้นหาไฟล์ที่ตรงตามเกณฑ์การค้นหาที่ระบุในไดเรกทอรีที่อ็อบเจ็กต์ปัจจุบันอ้างอิง. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | ค้นหาไฟล์ที่ตรงตามเกณฑ์การค้นหาที่ระบุ ไม่ว่าจะในไดเรกทอรีที่อ็อบเจ็กต์ปัจจุบันอ้างอิง หรือในต้นไม้ไดเรกทอรีทั้งหมดที่เริ่มจากไดเรกทอรีนั้น. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)() | ส่งกลับคอลเลกชันที่สามารถวนซ้ำได้ซึ่งประกอบด้วยไฟล์และไดเรกทอรีทั้งหมดที่อยู่ในไดเรกทอรีที่อ็อบเจ็กต์ปัจจุบันอ้างอิง. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const [String](../../system/string/)\&) | ค้นหาไฟล์และไดเรกทอรีที่ตรงตามเกณฑ์การค้นหาที่ระบุในไดเรกทอรีที่อ็อบเจ็กต์ปัจจุบันอ้างอิง. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | ค้นหาไฟล์และไดเรกทอรีที่ตรงตามเกณฑ์การค้นหาที่ระบุ ไม่ว่าจะในไดเรกทอรีที่อ็อบเจ็กต์ปัจจุบันอ้างอิง หรือในต้นไม้ไดเรกทอรีทั้งหมดที่เริ่มจากไดเรกทอรีนั้น. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้แนวคิดของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับวัตถุประสงค์ภายในเท่านั้น. |
| virtual void [Finalize](../filesysteminfo/finalize/)() | ไม่ทำอะไร. |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | ส่งกลับแอตทริบิวต์ของเอนทิตีที่อ็อบเจ็กต์ปัจจุบันอ้างอิง. |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | ส่งกลับเวลาสร้างของเอนทิตีที่อ็อบเจ็กต์ปัจจุบันอ้างอิงในรูปแบบเวลาท้องถิ่น. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | ส่งกลับเวลาสร้างของเอนทิตีที่อ็อบเจ็กต์ปัจจุบันอ้างอิงในรูปแบบเวลา UTC. |
| **bool** [get_Exists](./get_exists/)() override | กำหนดว่าเส้นทางที่อ็อบเจ็กต์ปัจจุบันอ้างอิงอ้างถึงไดเรกทอรีที่มีอยู่หรือไม่. |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | ส่งกลับส่วนขยายของไฟล์ที่อ็อบเจ็กต์ปัจจุบันอ้างอิง. |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | ส่งกลับชื่อเต็ม (รวมเส้นทาง) ของเอนทิตีที่อ็อบเจ็กต์ปัจจุบันอ้างอิง. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | ส่งกลับเวลาการเข้าถึงล่าสุดของเอนทิตีที่อ็อบเจ็กต์ปัจจุบันอ้างอิงในรูปแบบเวลาท้องถิ่น. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | ส่งกลับเวลาการเข้าถึงล่าสุดของเอนทิตีที่อ็อบเจ็กต์ปัจจุบันอ้างอิงในรูปแบบเวลา UTC. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | ส่งกลับเวลาการเขียนล่าสุดของเอนทิตีที่อ็อบเจ็กต์ปัจจุบันอ้างอิงในรูปแบบเวลาท้องถิ่น. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | ส่งกลับเวลาการเขียนล่าสุดของเอนทิตีที่อ็อบเจ็กต์ปัจจุบันอ้างอิงในรูปแบบเวลา UTC. |
| [String](../../system/string/) [get_Name](./get_name/)() override | ส่งกลับชื่อของเอนทิตีที่เส้นทางที่อ็อบเจ็กต์ปัจจุบันอ้างอิงอ้างถึง. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Parent](./get_parent/)() | ส่งกลับ shared pointer ไปยังออบเจ็กต์ [DirectoryInfo](./) ที่แสดงเส้นทางอ้างถึงไดเรกทอรีแม่ของไดเรกทอรีที่อ็อบเจ็กต์ปัจจุบันอ้างอิง. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Root](./get_root/)() | ส่งกลับ shared pointer ไปยังออบเจ็กต์ [DirectoryInfo](./) ที่แสดงเส้นทางอ้างถึงไดเรกทอรีรากของไดเรกทอรีที่อ็อบเจ็กต์ปัจจุบันอ้างอิง. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)() | ส่งกลับอาร์เรย์ที่มี shared pointer ไปยังออบเจ็กต์ [DirectoryInfo](./) ซึ่งแสดงไดเรกทอรีทั้งหมดที่อยู่ในไดเรกทอรีที่อ็อบเจ็กต์ปัจจุบันอ้างอิง. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&) | ค้นหาไดเรกทอรีที่ตรงตามเกณฑ์การค้นหาที่ระบุในไดเรกทอรีที่อ็อบเจ็กต์ปัจจุบันอ้างอิง. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | ค้นหาไดเรกทอรีที่ตรงตามเกณฑ์การค้นหาที่ระบุ ไม่ว่าจะในไดเรกทอรีที่อ็อบเจ็กต์ปัจจุบันอ้างอิง หรือในต้นไม้ไดเรกทอรีทั้งหมดที่เริ่มจากไดเรกทอรีนั้น. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)() | ส่งกลับอาร์เรย์ที่มี shared pointer ไปยังออบเจ็กต์ [FileInfo](../fileinfo/) ซึ่งแสดงไดเรกทอรีทั้งหมดที่อยู่ในไดเรกทอรีที่อ็อบเจ็กต์ปัจจุบันอ้างอิง. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&) | ค้นหาไฟล์ที่ตรงตามเกณฑ์การค้นหาที่ระบุในไดเรกทอรีที่อ็อบเจ็กต์ปัจจุบันอ้างอิง. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | ค้นหาไฟล์ที่ตรงตามเกณฑ์การค้นหาที่ระบุ ไม่ว่าจะในไดเรกทอรีที่อ็อบเจ็กต์ปัจจุบันอ้างอิง หรือในต้นไม้ไดเรกทอรีทั้งหมดที่เริ่มจากไดเรกทอรีนั้น. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)() | ส่งกลับอาร์เรย์ที่มี shared pointer ไปยังออบเจ็กต์ [FileSystemInfo](../filesysteminfo/) ซึ่งแสดงไฟล์และไดเรกทอรีทั้งหมดที่อยู่ในไดเรกทอรีที่อ็อบเจ็กต์ปัจจุบันอ้างอิง. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)(const [String](../../system/string/)\&) | ค้นหาไฟล์และไดเรกทอรีที่ตรงตามเกณฑ์การค้นหาที่ระบุในไดเรกทอรีที่อ็อบเจ็กต์ปัจจุบันอ้างอิง. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | ค้นหาไฟล์และไดเรกทอรีที่ตรงตามเกณฑ์การค้นหาที่ระบุ ไม่ว่าจะในไดเรกทอรีที่อ็อบเจ็กต์ปัจจุบันอ้างอิง หรือในต้นไม้ไดเรกทอรีทั้งหมดที่เริ่มจากไดเรกทอรีนั้น. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นเวอร์ชันของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจ็กต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เป็นอเนกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. เป็นอเนกของโอเปอเรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอเนกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการทำสำเนาประเภทที่กำหนดเอง. |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | ย้ายไดเรกทอรีที่อ็อบเจ็กต์ปัจจุบันอ้างอิงและเนื้อหาทั้งหมดไปยังตำแหน่งที่ระบุ. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. ไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจ็กต์ประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| void [Refresh](../filesysteminfo/refresh/)() | รีเฟรชสถานะของอ็อบเจ็กต์ปัจจุบัน. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | ตั้งค่าแอตทริบิวต์ที่ระบุบนเอนทิตีที่อ็อบเจ็กต์ปัจจุบันอ้างอิง. |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | ตั้งค่าเวลาสร้างของเอนทิตีที่อ็อบเจ็กต์ปัจจุบันอ้างอิงเป็นเวลาท้องถิ่น. |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | ตั้งค่าเวลาสร้างของเอนทิตีที่อ็อบเจ็กต์ปัจจุบันอ้างอิงเป็นเวลา UTC. |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | ตั้งค่าเวลาการเข้าถึงล่าสุดของเอนทิตีที่อ็อบเจ็กต์ปัจจุบันอ้างอิงเป็นเวลาท้องถิ่น. |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | ตั้งค่าเวลาการเข้าถึงล่าสุดของเอนทิตีที่อ็อบเจ็กต์ปัจจุบันอ้างอิงเป็นเวลา UTC. |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | ตั้งค่าเวลาการเขียนล่าสุดของเอนทิตีที่อ็อบเจ็กต์ปัจจุบันอ้างอิงเป็นเวลาท้องถิ่น. |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | ตั้งค่าเวลาการเขียนล่าสุดของเอนทิตีที่อ็อบเจ็กต์ปัจจุบันอ้างอิงเป็นเวลา UTC. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตพารามิเตอร์ที่ n ให้เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นแบบ weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | ส่งกลับสตริงที่มีเส้นทางที่อ็อบเจ็กต์ปัจจุบันอ้างอิง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำการสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [FileSystemInfo](../filesysteminfo/)
* เนมสเปซ [System::IO](../)
* ไลบรารี [Aspose.Slides](../../)