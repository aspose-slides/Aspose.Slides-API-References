---
title: Details_InvalidCastException
second_title: "อ้างอิง API ของ Aspose.Slides สำหรับ C++"
description: "InvalidCastException จะถูกขว้างเมื่อพยายามทำการแคสต์แบบไม่ถูกต้องของการแปลงโดยเจตนาที่ไม่ถูกต้อง. อย่าสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง. ใช้คลาส InvalidCastException แทน. อย่าห่อหุ้มอินสแตนซ์ของคลาส InvalidCastException ด้วย System::SmartPtr."
type: docs
weight: 495
url: /th/system/details_invalidcastexception/
---
## Details_InvalidCastException คลาส

InvalidCastException ถูกโยนเมื่อมีการพยายามทำการแคสต์แบบไม่ถูกต้องของการแปลงโดยเจตนาที่ไม่ถูกต้อง. อย่าสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง. ใช้คลาส InvalidCastException แทน. อย่าห่อหุ้มอินสแตนซ์ของคลาส InvalidCastException ด้วย [System::SmartPtr](../smartptr/).

```cpp
class Details_InvalidCastException : public System::Details_SystemException
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้เซมานติกของ C# [Object.Equals](../object/equals/) |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ของ C# |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C#-style ซึ่ง NaN สองค่าถูกพิจารณาเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าทั้งหมดใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C#-style ซึ่ง NaN สองค่าถูกพิจารณาเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าทั้งหมดใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | คืนพจนานุกรมที่มีข้อมูลข้อยกเว้นที่กำหนดเอง |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | คืนค่าจำนวนเต็ม 32 บิตซึ่งเป็นรหัส HRESULT ที่เชื่อมโยงกับข้อยกเว้นที่แสดงโดยอ็อบเจกต์ปัจจุบัน |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | คืนอ้างอิงไปยังอ็อบเจกต์ที่แสดงข้อยกเว้นภายใน |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | คืนสตริงที่เก็บคำอธิบายข้อผิดพลาด |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | คืนสตริงที่เก็บข้อมูลสแตกเทรซ |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | คืนสำเนาของอ็อบเจกต์ Exception ที่แสดงข้อยกเว้นที่ลึกที่สุด |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์ |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | เป็นการจำลองเมธอด C# [Object.GetHashCode()](../object/gethashcode/). ทำให้สามารถแฮชอ็อบเจกต์ที่กำหนดเองได้ |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | รับประเภทจริงของอ็อบเจกต์. เป็นการจำลองการเรียก C# [System.Object.GetType()](../object/gettype/) |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | ทำการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../lockcontext/) |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | เป็นการจำลองเมธอด C# [Object.MemberwiseClone()](../object/memberwiseclone/). ทำให้สามารถโคลนประเภทที่กำหนดเองได้ |
|  [Object](../object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../object/object/)([Object](../object/) const\&) | คอนสตรัคเตอร์สำเนา. จริง ๆ ไม่ได้คัดลอกอะไรเลย, เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการสร้างสำเนาสำหรับซับคลาส |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | ตัวดำเนินการมอบหมาย. จริง ๆ ไม่ได้คัดลอกอะไรเลย, เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการสร้างสำเนาสำหรับซับคลาส |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริงหลายตัว |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์โดยค่าที่ระบุ |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | ตั้งค่า HRESULT, ค่าตัวเลขที่เข้ารหัสที่กำหนดให้กับข้อยกเว้นเฉพาะ |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับ pointer ใน container ไปเป็นโหมด weak |
| int [SharedCount](../object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์ |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | คืนสตริงที่เป็นการแสดงผลของอ็อบเจกต์ปัจจุบัน |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | ทำการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน |
| virtual const char * [what](../details_exception/what/)() const | ทำการดำเนินเมธอด [what()](../details_exception/what/) ที่ถูกเรียกโดยคลาส [ExceptionWrapper](../exceptionwrapper/). แม้ว่าคลาสนี้จะไม่ได้สืบทอดจาก std::exception, คลาสที่สืบทอดสามารถใช้สมาชิก protected/private เพื่อดำเนินตรรกะของตนได้. การย้ายการดำเนินเมธอดนี้ไปที่ [ExceptionWrapper](../exceptionwrapper/) อาจทำให้ลอจิกนั้นเสีย |
| virtual  [~Object](../object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [Details_SystemException](../details_systemexception/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)