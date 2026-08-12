---
title: Details_InvalidTimeZoneException
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: "InvalidTimeZoneException จะถูกขว้างเมื่อข้อมูลเขตเวลาไม่ถูกต้อง ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง ใช้คลาส InvalidTimeZoneException แทน ไม่ควรห่อหุ้มอินสแตนซ์ของคลาส InvalidTimeZoneException เข้าไปใน System::SmartPtr."
type: docs
weight: 534
url: /th/system/details_invalidtimezoneexception/
---
## Details_InvalidTimeZoneException คลาส

InvalidTimeZoneException จะถูกขว้างเมื่อข้อมูลเขตเวลาไม่ถูกต้อง ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง ใช้คลาส InvalidTimeZoneException แทน ไม่ควรห่อหุ้มอินสแตนซ์ของคลาส InvalidTimeZoneException เข้าไปใน [System::SmartPtr](../smartptr/).

```cpp
class Details_InvalidTimeZoneException : public System::Details_Exception
```

## เมธอด

| เมธอด | รายละเอียด |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้แนวคิดของ C# [Object.Equals](../object/equals/) |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในรูปแบบ C# |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในรูปแบบ C# |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดทศนิยมแบบ C# ที่สองค่า NaN ถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดทศนิยมแบบ C# ที่สองค่า NaN ถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อวัตถุประสงค์ภายในเท่านั้น |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | คืนพจนานุกรมที่มีข้อมูลข้อยกเว้นแบบกำหนดเอง |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | คืนค่าจำนวนเต็ม 32 บิตที่เป็นรหัส HRESULT ที่เชื่อมโยงกับข้อยกเว้นที่แสดงโดยอ็อบเจกต์ปัจจุบัน |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | คืนการอ้างอิงถึงอ็อบเจกต์ที่แสดงข้อยกเว้นภายใน |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | คืนสตริงที่มีคำอธิบายข้อผิดพลาด |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | คืนสตริงที่มีสแต็กทริส |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | คืนสำเนาของอ็อบเจกต์ Exception ที่แสดงข้อยกเว้นที่อยู่ภายในที่สุด |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์ |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | เป็นคล้ายกับเมธอด C# [Object.GetHashCode()](../object/gethashcode/) ทำให้สามารถแฮชอ็อบเจกต์แบบกำหนดเองได้ |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | รับชนิดจริงของอ็อบเจกต์ เป็นคล้ายกับการเรียก C# [System.Object.GetType()](../object/gettype/) |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | ทำหน้าที่เชื่อมล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/) |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | เป็นคล้ายกับเมธอด C# [Object.MemberwiseClone()](../object/memberwiseclone/) ทำให้สามารถโคลนนิ่งประเภทแบบกำหนดเองได้ |
|  [Object](../object/object/)() | สร้างอ็อบเจกต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../object/object/)([Object](../object/) const\&) | คอนสตรัคเตอร์สำเนา ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างคลาสย่อย |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างคลาสย่อย |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบการอ้างอิงอ็อบเจกต์ประเภทค่ากับ nullptr |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | การกำหนดเฉพาะของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | การกำหนดเฉพาะของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริงหลายตัว |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | ลดค่าตัวนับการอ้างอิงแบบแชร์ลงตามค่าที่ระบุ |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | ตั้งค่า HRESULT ค่าตัวเลขที่เข้ารหัสซึ่งกำหนดให้กับข้อยกเว้นเฉพาะ |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่ shared) อนุญาตให้สลับพอยนเตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงแบบแชร์ |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | เพิ่มค่าตัวนับการอ้างอิงแบบแชร์ ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยนเตอร์หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ลดค่าตัวนับการอ้างอิงแบบแชร์และคืนค่า ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยนเตอร์หรือ ThisProtector แทน |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | คืนสตริงที่แสดงตัวอ็อบเจกต์ปัจจุบัน |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | เพิ่มค่าตัวนับ weak pointer ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยนเตอร์หรือ ThisProtector แทน |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ลดค่าตัวนับ weak pointer ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยนเตอร์หรือ ThisProtector แทน |
| virtual const char * [what](../details_exception/what/)() const | ทำหน้าที่เมธอด [what()](../details_exception/what/) ที่ถูกเรียกโดยคลาส [ExceptionWrapper](../exceptionwrapper/) แม้ว่าคลาสนี้จะไม่ได้สืบทอดจาก std::exception แต่คลาสที่สืบทอดสามารถใช้สมาชิก protected/private เพื่อทำตรรกะของตน การย้ายการทำงานของเมธอดนี้ไปยัง [ExceptionWrapper](../exceptionwrapper/) อาจทำให้ตรรกะนั้นขัดข้อง |
| virtual  [~Object](../object/~object/)() | ทำลายอ็อบเจกต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [Details_Exception](../details_exception/)
* เนมส페ซ [System](../)
* ไลบรารี [Aspose.Slides](../../)