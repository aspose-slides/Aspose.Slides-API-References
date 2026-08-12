---
title: Details_SynchronizationLockException
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: 
type: docs
weight: 66
url: /th/system.threading/details_synchronizationlockexception/
---
## Details_SynchronizationLockException คลาส




```cpp
class Details_SynchronizationLockException : public System::Details_SystemException
```

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบออบเจกต์โดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจกต์ประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจกต์ประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมสไตล์ C# ที่โดยที่ NaN สองค่าได้รับการพิจารณาว่าเท่ากัน ถึงแม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าทั้งหมดใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมสไตล์ C# ที่โดยที่ NaN สองค่าได้รับการพิจารณาว่าเท่ากัน ถึงแม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าทั้งหมดใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เฉพาะเพื่อการใช้งานภายในเท่านั้น. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | ส่งคืนพจนานุกรมที่มีข้อมูลข้อยกเว้นแบบกำหนดเอง. |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | ส่งคืนค่าจำนวนเต็ม 32 บิตซึ่งเป็นรหัส HRESULT ที่เชื่อมโยงกับข้อยกเว้นที่ออบเจกต์ปัจจุบันแสดง. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | ส่งคืนอ้างอิงไปยังออบเจกต์ที่แทนข้อยกเว้นภายใน. |
| virtual [String](../../system/string/) [get_Message](../../system/details_exception/get_message/)() const | ส่งคืนสตริงที่มีคำอธิบายข้อผิดพลาด. |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | ส่งคืนสตริงที่มีข้อมูลสแตกเทรซ. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | ส่งคืนสำเนาของออบเจกต์ Exception ที่แทนข้อยกเว้นที่อยู่ระดับลึกที่สุด. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับออบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นแบบจำลองของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถแฮชออบเจกต์แบบกำหนดเองได้. |
| const [System::TypeInfo](../../system/typeinfo/)\& [GetType](./gettype/)() const override | รับประเภทจริงของออบเจกต์. เป็นแบบจำลองของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const override |  |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentinel. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นแบบจำลองของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้สามารถโคลนประเภทที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างออบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. จริง ๆ ไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นออบเจกต์ใหม่และทำให้สามารถสร้างสำเนาของคลาสย่อยได้. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การมอบหมาย. จริง ๆ ไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นออบเจกต์ใหม่และทำให้สามารถสร้างสำเนาของคลาสย่อยได้. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบออบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบออบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจกต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายตัว. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงแบบแชร์ลงตามค่าที่ระบุ. |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | ตั้งค่า HRESULT, ค่าตัวเลขที่เข้ารหัสซึ่งกำหนดให้กับข้อยกเว้นเฉพาะ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงแบบแชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบแชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงแบบแชร์และส่งค่ากลับ. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | ส่งคืนการแสดงผลสตริงของออบเจกต์ปัจจุบัน. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentinel. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual const char * [what](../../system/details_exception/what/)() const | ทำเมธอด [what()](../../system/details_exception/what/) ซึ่งถูกเรียกโดยคลาส [ExceptionWrapper](../../system/exceptionwrapper/). แม้ว่าคลาสนี้จะไม่ได้สืบทอดจาก std::exception, คลาสที่สืบทอดสามารถใช้สมาชิกแบบ protected/private เพื่อดำเนินตรรกะของตนได้. การย้ายการดำเนินการเมธอดนี้ไปยัง [ExceptionWrapper](../../system/exceptionwrapper/) อาจทำให้ตรรกะนั้นเสียหาย. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายออบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
## ดูเพิ่มเติม

* คลาส [Details_SystemException](../../system/details_systemexception/)
* เนมสเปซ [System::Threading](../)
* ไลบรารี [Aspose.Slides](../../)