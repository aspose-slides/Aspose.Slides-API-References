---
title: ContentDispositionHeaderValue
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "แทนค่าของหัวข้อ 'Content-Disposition' . ออบเจ็กต์ของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแต็คหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะทำงานและ/หรือการตรวจสอบ. เสมอห่อคลาสนี้เป็นพอยน์เตอร์ System::SmartPtr แล้วใช้พอยน์เตอร์นี้ส่งเป็นอาร์กิวเมนต์ให้ฟังก์ชัน."
type: docs
weight: 27
url: /th/system.net.http.headers/contentdispositionheadervalue/
---
## ContentDispositionHeaderValue คลาส


แทนค่าของหัวข้อ 'Content-Disposition' . ออบเจ็กต์ของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแต็คหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือการตรวจสอบข้อผิดพลาด. เสมอห่อคลาสนี้เป็นพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) แล้วใช้พอยน์เตอร์นี้ส่งเป็นอาร์กิวเมนต์ให้ฟังก์ชัน.

```cpp
class ContentDispositionHeaderValue : public System::ICloneable
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
|  [ContentDispositionHeaderValue](./contentdispositionheadervalue/)() | สร้างอินสแตนซ์ใหม่. |
|  [ContentDispositionHeaderValue](./contentdispositionheadervalue/)([String](../../system/string/)) | สร้างอินสแตนซ์ใหม่. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | เปรียบเทียบออบเจ็กต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบออบเจ็กต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจ็กต์แบบอ้างอิงในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขจำนวนจริงแบบ C# ที่ NaN สองค่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขจำนวนจริงแบบ C# ที่ NaN สองค่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น. |
| [Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\> [get_CreationDate](./get_creationdate/)() | ดึงวันที่สร้างไฟล์. |
| [String](../../system/string/) [get_DispositionType](./get_dispositiontype/)() | ดึงประเภทการจัดวาง. |
| [String](../../system/string/) [get_FileName](./get_filename/)() | ดึงค่าที่กำหนดวิธีการสร้างชื่อไฟล์สำหรับจัดเก็บ payload ของข้อความ ซึ่งใช้เมื่อเอนทิตี้ถูกตัดแยกและจัดเก็บในไฟล์แยก. |
| [String](../../system/string/) [get_FileNameStar](./get_filenamestar/)() | ดึงค่าที่กำหนดวิธีการสร้างชื่อไฟล์สำหรับจัดเก็บ payload ของข้อความ ซึ่งใช้เมื่อหลายเอนทิตี้ถูกตัดแยกและจัดเก็บในไฟล์แยก. |
| [Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\> [get_ModificationDate](./get_modificationdate/)() | ดึงวันที่แก้ไขไฟล์. |
| [String](../../system/string/) [get_Name](./get_name/)() | ดึงชื่อของส่วนเนื้อหา. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Parameters](./get_parameters/)() | คืนคอลเลกชันของพารามิเตอร์ของหัวข้อ 'Content-Disposition'. |
| [Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\> [get_ReadDate](./get_readdate/)() | ดึงวันที่ที่ไฟล์ถูกอ่านเป็นครั้งสุดท้าย. |
| [Nullable](../../system/nullable/)\<**int64_t**\> [get_Size](./get_size/)() | ดึงขนาดไฟล์โดยประมาณ. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ดึงโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมกับออบเจ็กต์. |
| static **int32_t** [GetDispositionTypeLength](./getdispositiontypelength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | แปลงสตริงที่ส่งจากตำแหน่งที่กำหนดเป็นอินสแตนซ์ของคลาส [ContentDispositionHeaderValue](./). |
| **int32_t** [GetHashCode](./gethashcode/)() const override | เป็นคล้ายเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชออบเจ็กต์ที่กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ดึงประเภทจริงของออบเจ็กต์ เป็นคล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าออบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType เป็นคล้ายออปเรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นคล้ายเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถคัดลอกประเภทที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างออบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรักเตอร์คัดลอก. จริงๆ แล้วไม่ได้คัดลอกอะไร เพียงทำการเริ่มต้นออบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรักเตอร์ของซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอร์เรเตอร์การกำหนดค่า. จริงๆ แล้วไม่ได้คัดลอกอะไร เพียงทำการเริ่มต้นออบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรักเตอร์ของซับคลาส. |
| static [System::SharedPtr](../../system/sharedptr/)\<[ContentDispositionHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | แปลงสตริงที่ส่งเป็นอินสแตนซ์ของคลาส [ContentDispositionHeaderValue](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การประยุกต์ของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การประยุกต์ของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงร่วมโดยค่าที่ระบุ. |
| void [set_CreationDate](./set_creationdate/)([Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\>) | ตั้งค่าวันที่สร้างไฟล์. |
| void [set_DispositionType](./set_dispositiontype/)([String](../../system/string/)) | ตั้งค่าประเภทการจัดวาง. |
| void [set_FileName](./set_filename/)([String](../../system/string/)) | ตั้งค่าที่กำหนดวิธีการสร้างชื่อไฟล์สำหรับจัดเก็บ payload ของข้อความ ซึ่งใช้เมื่อเอนทิตี้ถูกตัดแยกและจัดเก็บในไฟล์แยก. |
| void [set_FileNameStar](./set_filenamestar/)([String](../../system/string/)) | ตั้งค่าที่กำหนดวิธีการสร้างชื่อไฟล์สำหรับจัดเก็บ payload ของข้อความ ซึ่งใช้เมื่อหลายเอนทิตี้ถูกตัดแยกและจัดเก็บในไฟล์แยก. |
| void [set_ModificationDate](./set_modificationdate/)([Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\>) | ตั้งค่าวันที่แก้ไขไฟล์. |
| void [set_Name](./set_name/)([String](../../system/string/)) | ตั้งชื่อตำแหน่งของส่วนเนื้อหา. |
| void [set_ReadDate](./set_readdate/)([Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\>) | ตั้งค่าวันที่ที่ไฟล์ถูกอ่านเป็นครั้งสุดท้าย. |
| void [set_Size](./set_size/)([Nullable](../../system/nullable/)\<**int64_t**\>) | ตั้งค่าขนาดไฟล์โดยประมาณ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | กำหนดเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทน shared) ทำให้สามารถสลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | ดึงค่าปัจจุบันของตัวนับอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงร่วม ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงร่วมและคืนค่า ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | เป็นคล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงออบเจ็กต์ที่กำหนดเองเป็นสตริง. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[ContentDispositionHeaderValue](./)\>\&) | พยายามแปลงสตริงที่ส่งเป็นอินสแตนซ์ของคลาส [ContentDispositionHeaderValue](./). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามการปลดล็อกของคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิง weak ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิง weak ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายออบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [ICloneable](../../system/icloneable/)
* เนมสเปซ [System::Net::Http::Headers](../)
* ไลบรารี [Aspose.Slides](../../)