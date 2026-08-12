---
title: Details_MethodAccessException
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: "MemberAccessException ถูกโยนออกเมื่อพยายามเข้าถึงเมธอดที่ไม่มีอยู่หรือเมื่อการเข้าถึงเมธอดนั้นไม่ได้รับอนุญาต. ห้ามสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง. ใช้คลาส MethodAccessException แทน. ห้ามห่อหุ้มอินสแตนซ์ของคลาส MethodAccessException ไปยัง System::SmartPtr."
type: docs
weight: 560
url: /th/system/details_methodaccessexception/
---
## Details_MethodAccessException คลาส


MemberAccessException จะถูกโยนออกเมื่อพยายามเข้าถึงเมธอดที่ไม่มีอยู่หรือเมื่อการเข้าถึงเมธอดนั้นไม่ได้รับอนุญาต. ห้ามสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง. ใช้คลาส MethodAccessException แทน. ห้ามห่อหุ้มอินสแตนซ์ของคลาส MethodAccessException ไปยัง [System::SmartPtr](../smartptr/).

```cpp
class Details_MethodAccessException : public System::Details_MemberAccessException
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ semantics ของ C# [Object.Equals](../object/equals/) |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดทศนิยมแบบ C#-style ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดทศนิยมแบบ C#-style ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อวัตถุประสงค์ภายในเท่านั้น |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | ส่งคืนพจนานุกรมที่มีข้อมูลข้อยกเว้นที่กำหนดเอง |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | ส่งคืนค่าเต็ม 32-บิตที่เป็นรหัส HRESULT ที่เชื่อมโยงกับข้อยกเว้นที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | ส่งคืนการอ้างอิงไปยังอ็อบเจ็กต์ที่แสดงข้อยกเว้นภายใน |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | ส่งคืนสตริงที่บรรจุคำอธิบายข้อผิดพลาด |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | ส่งคืนสตริงที่บรรจุข้อมูลสแตกเทรซ |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | ส่งคืนสำเนาของอ็อบเจ็กต์ Exception ที่แสดงข้อยกเว้นระดับในสุด |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | อันตรปของเมธอด C# [Object.GetHashCode()](../object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจ็กต์ที่กำหนดเอง |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | รับประเภทจริงของอ็อบเจ็กต์. อันตรปของการเรียก C# [System.Object.GetType()](../object/gettype/) |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/) |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | อันตรปของเมธอด C# [Object.MemberwiseClone()](../object/memberwiseclone/). เปิดใช้งานการคัดลอกประเภทที่กำหนดเอง |
|  [Object](../object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../object/object/)([Object](../object/) const\&) | คอนสตรักเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสำหรับซับคลาส |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | ตัวดำเนินการมอบหมาย. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสำหรับซับคลาส |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจ็กต์ประเภทค่ากับ nullptr |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | การเจาะจงของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | การเจาะจงของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์โดยค่าที่ระบุ |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | ตั้งค่า HRESULT ซึ่งเป็นค่าตัวเลขที่เข้ารหัสและถูกกำหนดให้กับข้อยกเว้นเฉพาะ |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับ pointer ใน container เป็นโหมด weak |
| int [SharedCount](../object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์ |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | เพิ่มตัวนับการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ลดและส่งคืนค่าตัวนับการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | ส่งคืนการแสดงผลเป็นสตริงของอ็อบเจ็กต์ปัจจุบัน |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | เพิ่มตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ลดตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector |
| virtual const char * [what](../details_exception/what/)() const | ดำเนินการเมธอด [what()](../details_exception/what/) ที่เรียกโดยคลาส [ExceptionWrapper](../exceptionwrapper/). แม้ว่าคลาสนี้จะไม่ได้สืบทอดจาก std::exception, คลาสที่สืบทอดสามารถใช้สมาชิก protected/private เพื่อดำเนินการตรรกะของตนได้. การย้ายการทำงานของเมธอดนี้ไปยัง [ExceptionWrapper](../exceptionwrapper/) อาจทำให้ตรรกะนั้นเสียหาย |
| virtual  [~Object](../object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [Details_MemberAccessException](../details_memberaccessexception/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)