---
title: Details_MemberAccessException
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: "MemberAccessException ถูกโยนเมื่อพยายามเข้าถึงสมาชิกของคลาสที่ไม่มีอยู่หรือเมื่อการเข้าถึงสมาชิกไม่ได้รับอนุญาต ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง ใช้คลาส MemberAccessException แทน อย่าใส่ห่ออินสแตนซ์ของคลาส MemberAccessException เข้าไปใน System::SmartPtr."
type: docs
weight: 547
url: /th/system/details_memberaccessexception/
---
## Details_MemberAccessException คลาส

MemberAccessException จะถูกโยนเมื่อมีการพยายามเข้าถึงสมาชิกของคลาสที่ไม่มีอยู่หรือเมื่อการเข้าถึงสมาชิกไม่ถูกอนุญาต ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง ใช้คลาส MemberAccessException แทน อย่าใส่ห่ออินสแตนซ์ของคลาส MemberAccessException ลงใน [System::SmartPtr](../smartptr/).

```cpp
class Details_MemberAccessException : public System::Details_SystemException
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | เปรียบเทียบวัตถุโดยใช้การทำงานของ C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยตามสไตล์ C# ที่ NaN สองค่าได้รับการพิจารณาว่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยตามสไตล์ C# ที่ NaN สองค่าได้รับการพิจารณาว่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | คืนดิกชันนารีที่มีข้อมูลข้อยกเว้นที่กำหนดเอง. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | คืนค่าเต็มจำนวน 32 บิตที่เป็นรหัส HRESULT ที่เชื่อมโยงกับข้อยกเว้นที่แทนด้วยอ็อบเจ็กต์ปัจจุบัน. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | คืนอ้างอิงไปยังอ็อบเจ็กต์ที่แสดงข้อยกเว้นภายใน. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | คืนสตริงที่ประกอบด้วยคำอธิบายข้อผิดพลาด. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | คืนสตริงที่มี stack trace. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | คืนสำเนาของอ็อบเจ็กต์ Exception ที่แสดงข้อยกเว้นที่อยู่ลึกที่สุด. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | เป็นคล้ายกับเมธอด C# [Object.GetHashCode()](../object/gethashcode/). ช่วยให้ทำแฮชสำหรับอ็อบเจ็กต์ที่กำหนดเองได้. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | รับประเภทจริงของอ็อบเจ็กต์. คล้ายกับการเรียก C# [System.Object.GetType()](../object/gettype/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../object/memberwiseclone/). ทำให้สามารถสร้างสำเนาของประเภทที่กำหนดเองได้. |
|  [Object](../object/object/)() | สร้างอ็อบเจ็กต์. กำหนดค่าโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../object/object/)([Object](../object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่กำหนดอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาสำหรับคลาสย่อย. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่กำหนดอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาสำหรับคลาสย่อย. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงวัตถุประเภทค่ากับ nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | ตั้งค่า HRESULT ซึ่งเป็นค่าตัวเลขที่เข้ารหัสและถูกกำหนดให้กับข้อยกเว้นเฉพาะ. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่จะเป็น shared) ทำให้สามารถสลับ pointer ใน containers ไปเป็นโหมด weak ได้. |
| int [SharedCount](../object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | เพิ่มจำนวนอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ลดจำนวนอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | คืนค่าการแสดงผลเป็นสตริงของอ็อบเจ็กต์ปัจจุบัน. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | เพิ่มจำนวน weak reference. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ลดจำนวน weak reference. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| virtual const char * [what](../details_exception/what/)() const | ทำงานตามเมธอด [what()](../details_exception/what/) ซึ่งถูกเรียกโดยคลาส [ExceptionWrapper](../exceptionwrapper/). ถึงแม้ว่าคลาสนี้จะไม่ได้สืบทอดจาก std::exception แต่คลาสที่สืบทอดสามารถใช้สมาชิก protected/private เพื่อดำเนินตรรกะของตนได้ การย้ายการทำงานของเมธอดนี้ไปที่ [ExceptionWrapper](../exceptionwrapper/) อาจทำให้ตรรกะนั้นเสียหาย. |
| virtual  [~Object](../object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [Details_SystemException](../details_systemexception/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)