---
title: Details_SystemException
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "คลาสฐานสำหรับคลาสที่เป็นตัวแทนข้อยกเว้นระบบ (ไม่ใช่ข้อยกเว้นแอปพลิเคชัน) ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง ใช้คลาส SystemException แทน อย่าห่อหุ้มอินสแตนซ์ของคลาส SystemException เข้าไปใน System::SmartPtr."
type: docs
weight: 703
url: /th/system/details_systemexception/
---
## Details_SystemException คลาส

คลาสฐานสำหรับคลาสที่เป็นตัวแทนข้อยกเว้นระบบ (ไม่ใช่ข้อยกเว้นแอปพลิเคชัน) ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง ใช้คลาส SystemException แทน อย่าห่อหุ้มอินสแตนซ์ของคลาส SystemException เข้าไปใน [System::SmartPtr](../smartptr/).

```cpp
class Details_SystemException : public System::Details_Exception
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้หลักการของ C# [Object.Equals](../object/equals/) |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C# ที่ NaN สองค่าถูกพิจารณาเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C# ที่ NaN สองค่าถูกพิจารณาเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | คืนค่า dictionary ที่มีข้อมูลข้อยกเว้นที่กำหนดเอง |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | คืนค่าจำนวนเต็ม 32 บิตซึ่งเป็นรหัส HRESULT ที่เชื่อมโยงกับข้อยกเว้นที่เป็นตัวแทนโดยอ็อบเจ็กต์ปัจจุบัน |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | คืนค่าการอ้างอิงถึงอ็อบเจ็กต์ที่เป็นตัวแทนของข้อยกเว้นภายใน |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | คืนสตริงที่บรรจุคำอธิบายข้อผิดพลาด |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | คืนสตริงที่บรรจุตราบสแตก |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | คืนสำเนาของอ็อบเจ็กต์ Exception ที่เป็นตัวแทนของข้อยกเว้นที่อยู่ลึกที่สุด |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../object/gethashcode/). ทำให้สามารถแฮชอ็อบเจ็กต์ที่กำหนดเองได้ |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | รับประเภทที่แท้จริงของอ็อบเจ็กต์. คล้ายกับการเรียก C# [System.Object.GetType()](../object/gettype/) |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | ทำหน้าที่ตามคำสั่ง lock() ของ C# เพื่อทำการล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/) |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../object/memberwiseclone/). ทำให้สามารถโคลนประเภทที่กำหนดเองได้ |
|  [Object](../object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../object/object/)([Object](../object/) const\&) | คอนสตรัคเตอร์สำเนา. จริง ๆ แล้วไม่คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริง ๆ แล้วไม่คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงของอ็อบเจ็กต์ประเภทค่า กับ nullptr |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริงหลายค่า |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | ตั้งค่า HRESULT ซึ่งเป็นค่าตัวเลขที่เข้ารหัสและมอบหมายให้กับข้อยกเว้นเฉพาะ |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทนที่จะแชร์). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์ |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | คืนค่าการแสดงผลเป็นสตริงของอ็อบเจ็กต์ปัจจุบัน |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | ทำหน้าที่ตามคำสั่ง lock() ของ C# เพื่อปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | เพิ่มตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ลดตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน |
| virtual const char * [what](../details_exception/what/)() const | ทำหน้าที่ตามเมธอด [what()](../details_exception/what/) ที่ถูกเรียกโดยคลาส [ExceptionWrapper](../exceptionwrapper/) แม้ว่าคลาสนี้จะไม่ได้สืบทอดจาก std::exception แต่คลาสที่สืบทอดสามารถใช้สมาชิก protected/private เพื่อทำตรรกะของตนได้ การย้ายการทำงานของเมธอดนี้ไปยัง [ExceptionWrapper](../exceptionwrapper/) อาจทำให้ตรรกะนั้นเสียหาย |
| virtual  [~Object](../object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [Details_Exception](../details_exception/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)