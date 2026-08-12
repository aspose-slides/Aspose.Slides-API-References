---
title: Details_UriFormatException
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "UriFormatException จะถูกโยนเมื่อรูปแบบของ URI ไม่ถูกต้อง. ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง. ใช้คลาส UriFormatException แทน. ไม่ควรห่อหุ้มอินสแตนซ์ของคลาส UriFormatException ไว้ใน System::SmartPtr."
type: docs
weight: 768
url: /th/system/details_uriformatexception/
---
## Details_UriFormatException คลาส

UriFormatException ถูกโยนเมื่อรูปแบบของ URI ไม่ถูกต้อง. อย่าสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง. ใช้คลาส UriFormatException แทน. อย่าห่อหุ้มอินสแตนซ์ของคลาส UriFormatException เข้าไปใน [System::SmartPtr](../smartptr/).

```cpp
class Details_UriFormatException : public System::Details_FormatException
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้แนวคิดของ C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดทศนิยมแบบ C#-style ที่สองค่า NaN ถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดทศนิยมแบบ C#-style ที่สองค่า NaN ถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | คืนพจนานุกรมที่มีข้อมูลข้อยกเว้นแบบกำหนดเอง. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | คืนค่าจำนวนเต็ม 32-bit ที่เป็นรหัส HRESULT ที่เกี่ยวข้องกับข้อยกเว้นที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | คืนการอ้างอิงไปยังอ็อบเจ็กต์ที่แสดงข้อยกเว้นภายใน. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | คืนสตริงที่บรรจุคำอธิบายข้อผิดพลาด. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | คืนสตริงที่บรรจุข้อมูล stack trace. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | คืนสำเนาของอ็อบเจ็กต์ Exception ที่แสดงข้อยกเว้นที่อยู่ด้านในที่สุด. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | คล้ายเมธอด C# [Object.GetHashCode()](../object/gethashcode/). ทำให้สามารถทำแฮชอ็อบเจ็กต์แบบกำหนดเองได้. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | รับประเภทจริงของอ็อบเจ็กต์. คล้ายการเรียก C# [System.Object.GetType()](../object/gettype/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | ทำการล็อกโดยใช้คำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentry [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | คล้ายเมธอด C# [Object.MemberwiseClone()](../object/memberwiseclone/). ทำให้สามารถโคลนประเภทที่กำหนดเองได้. |
|  [Object](../object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../object/object/)([Object](../object/) const\&) | คอนสตรักเตอร์คัดลอก. จริงๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | ตัวดำเนินการมอบหมาย. จริงๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบการอ้างอิงของอ็อบเจ็กต์ประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | ลดตัวนับอ้างอิงที่แชร์โดยค่าที่ระบุ. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | ตั้งค่า HRESULT, ซึ่งเป็นค่าตัวเลขที่เข้ารหัสและถูกกำหนดให้กับข้อยกเว้นเฉพาะ. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n'th เป็น weak pointer (แทนที่การแชร์). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | เพิ่มตัวนับการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | คืนการแสดงผลเป็นสตริงของอ็อบเจ็กต์ปัจจุบัน. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | ทำการปลดล็อกโดยใช้คำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentry [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | เพิ่มตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ลดตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน. |
| virtual const char * [what](../details_exception/what/)() const | ทำการประมวลผลเมธอด [what()](../details_exception/what/) ที่ถูกเรียกโดยคลาส [ExceptionWrapper](../exceptionwrapper/). แม้ว่าคลาสนี้จะไม่สืบทอดจาก std::exception แต่คลาสที่สืบทอดสามารถใช้สมาชิก protected/private เพื่อดำเนินการตรรกะของตนได้ การย้ายการทำงานของเมธอดนี้ไปที่ [ExceptionWrapper](../exceptionwrapper/) อาจทำให้ตรรกะนั้นเสียหาย. |
| virtual  [~Object](../object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
## ดูเพิ่มเติม

* คลาส [Details_FormatException](../details_formatexception/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)