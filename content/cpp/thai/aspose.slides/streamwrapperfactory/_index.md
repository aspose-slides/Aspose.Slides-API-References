---
title: StreamWrapperFactory
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: โรงงานของ StreamWrappers สำหรับอินเทอร์เฟซ COM.
type: docs
weight: 5292
url: /th/aspose.slides/streamwrapperfactory/
---
## StreamWrapperFactory class


Factory ของ StreamWrappers สำหรับอินเทอร์เฟซ COM.

```cpp
class StreamWrapperFactory : public Aspose::Slides::IStreamWrapperFactory
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IStreamWrapper](../istreamwrapper/)\> [CreateFileStreamWrapper](./createfilestreamwrapper/)([System::String](../../system/string/), [System::IO::FileMode](../../system.io/filemode/)) override | สร้าง FileStream ด้วยเส้นทางที่ระบุและโหมดการสร้าง. |
| [System::SharedPtr](../../system/sharedptr/)\<[IStreamWrapper](../istreamwrapper/)\> [CreateFileStreamWrapper](./createfilestreamwrapper/)([System::String](../../system/string/), [System::IO::FileMode](../../system.io/filemode/), [System::IO::FileAccess](../../system.io/fileaccess/)) override | สร้าง FileStream ด้วยเส้นทางที่ระบุ, โหมดการสร้าง, และสิทธิ์การอ่าน/เขียน. |
| [System::SharedPtr](../../system/sharedptr/)\<[IStreamWrapper](../istreamwrapper/)\> [CreateMemoryStreamWrapper](./creatememorystreamwrapper/)() override | สร้างตัวหุ้ม MemoryStream. |
| [System::SharedPtr](../../system/sharedptr/)\<[IStreamWrapper](../istreamwrapper/)\> [CreateMemoryStreamWrapper](./creatememorystreamwrapper/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | สร้างตัวหุ้ม MemoryStream ตามอาร์เรย์ไบต์ที่ระบุ. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบออบเจ็กต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจ็กต์ประเภทอ้างอิงสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่า floating point สไตล์ C# ที่สองค่า NaN ถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่า floating point สไตล์ C# ที่สองค่า NaN ถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ดึงโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมกับออบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เทียบเคียงกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชออบเจ็กต์ที่กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ดึงประเภทจริงของออบเจ็กต์ เทียบเคียงกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าออบเจ็กต์เป็นอินสแทนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เทียบเคียงกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เทียบเคียงกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างออบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกรายการใดๆ จริงๆ เพียงเริ่มต้นออบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกในซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกรายการใดๆ จริงๆ เพียงเริ่มต้นออบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกในซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การแสดงเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การแสดงเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดตัวนับอ้างอิงที่แชร์โดยค่าที่ระบุ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทนที่จะแชร์) อนุญาตให้เปลี่ยนพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | ดึงค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์ ควรไม่เรียกโดยตรง; แทนให้ใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์ ควรไม่เรียกโดยตรง; แทนให้ใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบเคียงกับเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงออบเจ็กต์ที่กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เหมือนการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับ weak reference ควรไม่เรียกโดยตรง; แทนให้ใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับ weak reference ควรไม่เรียกโดยตรง; แทนให้ใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายออบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
## ดูเพิ่มเติม

* คลาส [IStreamWrapperFactory](../istreamwrapperfactory/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)