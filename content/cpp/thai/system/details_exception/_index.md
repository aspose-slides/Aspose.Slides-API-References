---
title: Details_Exception
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "เป็นตัวแทนของข้อยกเว้น. ห้ามสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง. ใช้คลาส Exception แทน. ห้ามห่ออินสแตนซ์ของคลาส Exception เข้าไปใน System::SmartPtr."
type: docs
weight: 417
url: /th/system/details_exception/
---
## Details_Exception คลาส

เป็นตัวแทนของข้อยกเว้น. ห้ามสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง. ใช้คลาส Exception แทน. ห้ามห่ออินสแตนซ์ของคลาส Exception เข้าไปใน [System::SmartPtr](../smartptr/).

```cpp
class Details_Exception : public System::Object
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual void [DoThrow](./dothrow/)(const [ExceptionPtr](../exceptionptr/)\&) const | โยนอินสแตนซ์ของข้อยกเว้นที่ถูกห่อโดยตัวห่อข้อยกเว้น. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้เซมานติกของ C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในรูปแบบ C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในรูปแบบ C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C#-style ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่า selon IEC 60559:1989 NaN จะไม่เท่ากับค่าต่าง ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C#-style ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่า selon IEC 60559:1989 NaN จะไม่เท่ากับค่าต่าง ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](./get_data/)() | คืนค่า dictionary ที่มีข้อมูลข้อยกเว้นแบบกำหนดเอง. |
| **int32_t** [get_HResult](./get_hresult/)() const | ส่งกลับค่าจำนวนเต็ม 32 บิตซึ่งเป็นรหัส HRESULT ที่เชื่อมโยงกับข้อยกเว้นที่แสดงโดยอ็อบเจกต์ปัจจุบัน. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](./)\> [get_InnerException](./get_innerexception/)() const | ส่งกลับการอ้างอิงไปยังอ็อบเจกต์ที่แสดงข้อยกเว้นภายใน. |
| virtual [String](../string/) [get_Message](./get_message/)() const | ส่งกลับสตริงที่บรรจุคำอธิบายข้อผิดพลาด. |
| virtual [String](../string/) [get_StackTrace](./get_stacktrace/)() const | ส่งกลับสตริงที่บรรจุสแตกเทรซ. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](./)\> [GetBaseException](./getbaseexception/)() const | ส่งกลับสำเนาของอ็อบเจกต์ Exception ที่แสดงข้อยกเว้นที่ลึกที่สุด. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | อเนกแบบของเมธอด C# [Object.GetHashCode()](../object/gethashcode/). ให้สามารถทำแฮชของอ็อบเจกต์แบบกำหนดเอง. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | รับชนิดจริงของอ็อบเจกต์. อเนกแบบของการเรียก C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของชนิดที่อธิบายโดย targetType. อเนกแบบของโอเปอเรเตอร์ 'is' ของ C#. |
| void [Lock](../object/lock/)() | ทำหน้าที่เป็นการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | อเนกแบบของเมธอด C# [Object.MemberwiseClone()](../object/memberwiseclone/). ให้สามารถโคลนประเภทที่กำหนดเองได้. |
|  [Object](../object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../object/object/)([Object](../object/) const\&) | คอนสตรัคเตอร์สำเนา. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดให้สร้างสำเนาสำหรับคลาสย่อย. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | ตัวดำเนินการมอบหมายค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดให้สร้างสำเนาสำหรับคลาสย่อย. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์ตามการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์ตามการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบการอ้างอิงอ็อบเจกต์ประเภทค่ากับ nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | รูปแบบพิเศษของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | รูปแบบพิเศษของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | ลดค่าตัวนับการอ้างอิงร่วมโดยค่าที่ระบุ. |
| void [set_HResult](./set_hresult/)(**int32_t**) | ตั้งค่า HRESULT ซึ่งเป็นค่าตัวเลขที่เข้ารหัสและกำหนดให้กับข้อยกเว้นเฉพาะ. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงร่วม. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | เพิ่มค่าตัวนับการอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ควรใช้สมาโทพอยน์เตอร์หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ลดค่าตัวนับการอ้างอิงร่วมและส่งกลับค่า. ไม่ควรเรียกโดยตรง; ควรใช้สมาโทพอยน์เตอร์หรือ ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | ส่งกลับการแสดงผลเป็นสตริงของอ็อบเจกต์ปัจจุบัน. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | ทำหน้าที่เป็นการสร้าง typeof([System.Object](../object/)) ของ C#. |
| void [Unlock](../object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | เพิ่มค่าตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้สมาโทพอยน์เตอร์หรือ ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ลดค่าตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้สมาโทพอยน์เตอร์หรือ ThisProtector. |
| virtual const char * [what](./what/)() const | ทำหน้าที่เป็นเมธอด [what()](./what/) ที่ถูกเรียกโดยคลาส [ExceptionWrapper](../exceptionwrapper/). แม้ว่าคลาสนี้ไม่ได้สืบทอดจาก std::exception แต่คลาสที่สืบทอดสามารถใช้สมาชิก protected/private เพื่อทำตรรกะของตนได้ การย้ายการทำงานของเมธอดนี้ไปที่ [ExceptionWrapper](../exceptionwrapper/) อาจทำให้ตรรกะนั้นเสียหาย. |
| virtual  [~Object](../object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [Object](../object/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)