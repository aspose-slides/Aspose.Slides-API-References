---
title: Details_ObjectDisposedException
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: "ObjectDisposedException จะถูกโยนเมื่อมีการเรียกเมธอดบนอ็อบเจ็กต์ที่ถูกทำลายแล้ว. ห้ามสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง. ใช้คลาส ObjectDisposedException แทน. ห้ามใส่อินสแตนซ์ของคลาส ObjectDisposedException ลงใน System::SmartPtr."
type: docs
weight: 612
url: /th/system/details_objectdisposedexception/
---
## Details_ObjectDisposedException คลาส

ObjectDisposedException ถูกโยนเมื่อมีการเรียกเมธอดบนอ็อบเจ็กต์ที่ถูกทำลายแล้ว. อย่าสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง. ใช้คลาส ObjectDisposedException แทน. อย่าใส่อินสแตนซ์ของคลาส ObjectDisposedException ลงใน [System::SmartPtr](../smartptr/).

```cpp
class Details_ObjectDisposedException : public System::Details_InvalidOperationException
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้หลักการของ C# [Object.Equals](../object/equals/) |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C# |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยตามสไตล์ C# ซึ่ง NaN สสองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยตามสไตล์ C# ซึ่ง NaN สสองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | คืนพจนานุกรมที่มีข้อมูลข้อยกเว้นแบบกำหนดเอง |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | คืนค่าจำนวนเต็ม 32 บิตที่เป็นรหัส HRESULT ที่เชื่อมโยงกับข้อยกเว้นที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | คืนการอ้างอิงไปยังอ็อบเจ็กต์ที่เป็นตัวแทนของข้อยกเว้นภายใน |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | คืนสตริงที่บรรจุรายละเอียดข้อผิดพลาด |
| [String](../string/) [get_ObjectName](./get_objectname/)() |  |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | คืนสตริงที่บรรจุ stack trace |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | คืนสำเนาของอ็อบเจ็กต์ Exception ที่เป็นตัวแทนของข้อยกเว้นที่อยู่ในระดับลึกที่สุด |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | เป็นอเนกแบบของเมธอด C# [Object.GetHashCode()](../object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจ็กต์แบบกำหนดเอง |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | รับประเภทจริงของอ็อบเจ็กต์. เป็นอเนกแบบของการเรียก C# [System.Object.GetType()](../object/gettype/) |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentry [LockContext](../lockcontext/) |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | เป็นอเนกแบบของเมธอด C# [Object.MemberwiseClone()](../object/memberwiseclone/). เปิดใช้งานการโคลนของประเภทที่กำหนดเอง |
|  [Object](../object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../object/object/)([Object](../object/) const\&) | คอนสตรัคเตอร์สำเนา. ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | กำหนดค่า HRESULT ซึ่งเป็นค่าตัวเลขที่เข้ารหัสที่กำหนดให้ข้อยกเว้นเฉพาะ |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทน shared). อนุญาตให้สลับพอยเตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์ |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยเตอร์หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยเตอร์หรือ ThisProtector แทน |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | คืนสตริงที่เป็นการแสดงผลของอ็อบเจ็กต์ปัจจุบัน |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | ดำเนินการปลดล็อกจากคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentry [LockContext](../lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยเตอร์หรือ ThisProtector แทน |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยเตอร์หรือ ThisProtector แทน |
| virtual const char * [what](../details_exception/what/)() const | ดำเนินการเมธอด [what()](../details_exception/what/) ที่ถูกเรียกโดยคลาส [ExceptionWrapper](../exceptionwrapper/). แม้ว่าคลาสนี้จะไม่ได้สืบทอดจาก std::exception คลาสที่สืบทอดสามารถใช้สมาชิก protected/private เพื่อดำเนินตรรกะของตน. การย้ายการประมวลผลเมธอดนี้ไปยัง [ExceptionWrapper](../exceptionwrapper/) อาจทำให้ตรรกะนั้นเสียหาย |
| virtual  [~Object](../object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |
## ดูเพิ่มเติม

* คลาส [Details_InvalidOperationException](../details_invalidoperationexception/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)