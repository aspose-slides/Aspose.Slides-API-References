---
title: Details_TimeZoneNotFoundException
second_title: Aspose.Slides สำหรับอ้างอิง API C++
description: "TimeZoneNotFoundException จะถูกโยนเมื่อไม่พบข้อมูลโซนเวลา. ห้ามสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง. ให้ใช้คลาส TimeZoneNotFoundException แทน. ห้ามห่อหุ้มอินสแตนซ์ของคลาส TimeZoneNotFoundException ด้วย System::SmartPtr."
type: docs
weight: 729
url: /th/system/details_timezonenotfoundexception/
---
## Details_TimeZoneNotFoundException คลาส

TimeZoneNotFoundException จะถูกโยนเมื่อไม่พบข้อมูลโซนเวลา. ห้ามสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง. ให้ใช้คลาส TimeZoneNotFoundException แทน. ห้ามห่อหุ้มอินสแตนซ์ของคลาส TimeZoneNotFoundException ด้วย [System::SmartPtr](../smartptr/).

```cpp
class Details_TimeZoneNotFoundException : public System::Details_Exception
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | เปรียบเทียบวัตถุโดยใช้เซมานติกของ C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าจุดลอยแบบ C# ที่ในกรณีของ NaN สองค่า ถือว่าเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าจุดลอยแบบ C# ที่ในกรณีของ NaN สองค่า ถือว่าเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | ส่งคืนพจนานุกรมที่มีข้อมูลข้อยกเว้นแบบกำหนดเอง. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | ส่งคืนค่าเต็ม 32-bit ซึ่งเป็นรหัส HRESULT ที่เชื่อมโยงกับข้อยกเว้นที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | ส่งคืนการอ้างอิงไปยังอ็อบเจ็กต์ที่แสดงถึงข้อยกเว้นภายใน. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | ส่งคืนสตริงที่บรรจุคำอธิบายข้อผิดพลาด. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | ส่งคืนสตริงที่บรรจุสแต็กเทรซ. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | ส่งคืนสำเนาของอ็อบเจ็กต์ Exception ที่แสดงถึงข้อยกเว้นระดับในที่สุด. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | เป็นเมธอดที่คล้ายกับ C# [Object.GetHashCode()](../object/gethashcode/). ทำให้สามารถแฮชอ็อบเจ็กต์ที่กำหนดเอง. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | รับประเภทจริงของอ็อบเจ็กต์. เป็นอเนกประสงค์ของการเรียก C# [System.Object.GetType()](../object/gettype/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | ทำการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้อ็อบเจ็กต์ sentinel [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.MemberwiseClone()](../object/memberwiseclone/). ทำให้สามารถโคลนประเภทที่กำหนดเอง. |
|  [Object](../object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../object/object/)([Object](../object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้ซับคลาสสามารถคัดลอกได้. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้ซับคลาสสามารถคัดลอกได้. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจ็กต์ประเภทค่ากับ nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | การพิเศษของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | การพิเศษของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | ลดตัวนับอ้างอิงที่แชร์ด้วยค่าที่ระบุ. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | ตั้งค่า HRESULT ซึ่งเป็นค่าตัวเลขที่เข้ารหัสและถูกกำหนดให้กับข้อยกเว้นเฉพาะ. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | กำหนดเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทนที่เป็น shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ลดตัวนับอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | ส่งคืนการแสดงผลสตริงของอ็อบเจ็กต์ปัจจุบัน. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | ทำการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้อ็อบเจ็กต์ sentinel [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
| virtual const char * [what](../details_exception/what/)() const | ทำเมธอด [what()](../details_exception/what/) ซึ่งถูกเรียกโดยคลาส [ExceptionWrapper](../exceptionwrapper/). แม้ว่าคลาสนี้จะไม่ได้สืบทอดจาก std::exception, คลาสที่สืบทอดสามารถใช้สมาชิก protected/private เพื่อทำตรรกะของตนได้. การย้ายการทำงานของเมธอดนี้ไปยัง [ExceptionWrapper](../exceptionwrapper/) อาจทำให้ตรรกะเสียหาย. |
| virtual  [~Object](../object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [Details_Exception](../details_exception/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)