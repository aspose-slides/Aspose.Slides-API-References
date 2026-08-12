---
title: Details_FormatException
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: "FormatException ถูกโยนเมื่อรูปแบบของอาร์กิวเมนต์ของเมธอดไม่ถูกต้อง. อย่าสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง. ใช้คลาส FormatException แทน. อย่าห่อหุ้มอินสแตนซ์ของคลาส FormatException ไปยัง System::SmartPtr."
type: docs
weight: 469
url: /th/system/details_formatexception/
---
## Details_FormatException คลาส

FormatException ถูกโยนเมื่อรูปแบบของอาร์กิวเมนต์ของเมธอดไม่ถูกต้อง. อย่าสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง. ใช้คลาส FormatException แทน. อย่าห่อหุ้มอินสแตนซ์ของคลาส FormatException ไปยัง [System::SmartPtr](../smartptr/).

```cpp
class Details_FormatException : public System::Details_SystemException
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | เปรียบเทียบออบเจ็กต์โดยใช้เชิงปฏิบัติของ C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าตัวเลขแบบ floating point สไตล์ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าตัวเลขแบบ floating point สไตล์ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับวัตถุประสงค์ภายในเท่านั้น. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | คืนพจนานุกรมที่มีข้อมูลข้อยกเว้นที่กำหนดเอง. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | คืนค่าจำนวนเต็ม 32 บิตที่เป็นรหัส HRESULT ที่สัมพันธ์กับข้อยกเว้นที่แทนโดยออบเจ็กต์ปัจจุบัน. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | คืนการอ้างอิงไปยังออบเจ็กต์ที่เป็นตัวแทนข้อยกเว้นภายใน. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | คืนสตริงที่มีรายละเอียดข้อผิดพลาด. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | คืนสตริงที่มีข้อมูลสแตคเทรซ. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | คืนสำเนาของออบเจ็กต์ Exception ที่เป็นตัวแทนข้อยกเว้นที่อยู่ในระดับที่ลึกที่สุด. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่สัมพันธ์กับออบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | เป็นอันตรของเมธอด C# [Object.GetHashCode()](../object/gethashcode/). ทำให้สามารถแฮชออบเจ็กต์ที่กำหนดเองได้. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | รับประเภทจริงของออบเจ็กต์. เป็นอันตรของการเรียก C# [System.Object.GetType()](../object/gettype/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | เป็นอันตรของเมธอด C# [Object.MemberwiseClone()](../object/memberwiseclone/). ทำให้สามารถโคลนประเภทที่กำหนดเองได้. |
|  [Object](../object/object/)() | สร้างออบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../object/object/)([Object](../object/) const\&) | คอนสตรัคเตอร์สำเนา. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นออบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | ตัวดำเนินการมอบหมายค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นออบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจ็กต์ประเภทค่ากับ nullptr โดยอ้างอิง. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | ตั้งค่า HRESULT, ค่าตัวเลขที่เข้ารหัสซึ่งกำหนดให้กับข้อยกเว้นเฉพาะ. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | กำหนดอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ลดจำนวนตัวนับอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | คืนสตริงที่เป็นตัวแทนของออบเจ็กต์ปัจจุบัน. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | เพิ่มจำนวนตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ลดจำนวนตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| virtual const char * [what](../details_exception/what/)() const | ทำหน้าที่เมธอด [what()](../details_exception/what/) ที่ถูกเรียกโดยคลาส [ExceptionWrapper](../exceptionwrapper/). แม้ว่าคลาสนี้จะไม่ได้สืบทอดจาก std::exception, คลาสที่สืบทอดสามารถใช้สมาชิก protected/private เพื่อดำเนินตรรกะของตนได้. การย้ายการทำงานของเมธอดนี้ไปยัง [ExceptionWrapper](../exceptionwrapper/) อาจทำให้ตรรกะดังกล่าวเสียหาย. |
| virtual  [~Object](../object/~object/)() | ทำลายออบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* Class [Details_SystemException](../details_systemexception/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)