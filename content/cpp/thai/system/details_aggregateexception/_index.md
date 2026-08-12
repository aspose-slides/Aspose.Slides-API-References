---
title: Details_AggregateException
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: แสดงถึงข้อยกเว้นที่มีข้อยกเว้นภายในหลายรายการ.
type: docs
weight: 300
url: /th/system/details_aggregateexception/
---
## Details_AggregateException คลาส


แทนข้อยกเว้นที่มีข้อยกเว้นภายในหลายรายการ.

```cpp
class Details_AggregateException : public System::Details_Exception
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้เซมานติกของ C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงแบบ C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าแบบ C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยตามสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยตามสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| [AggregateException](../aggregateexception/) [Flatten](./flatten/)() | ทำให้ข้อยกเว้นเชิงรวมแบนโดยการคลายข้อยกเว่น AggregateExceptions ที่ซ้อนกันทั้งหมดเป็นรายการระดับเดียว. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | ส่งคืนดิกชันนารีที่มีข้อมูลข้อยกเว้นแบบกำหนดเอง. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | ส่งคืนค่าเต็ม 32 บิตซึ่งเป็นรหัส HRESULT ที่เชื่อมโยงกับข้อยกเว้นที่วัตถุปัจจุบันแสดง. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | ส่งคืนอ้างอิงไปยังอ็อบเจ็กต์ที่แสดงข้อยกเว้นภายใน. |
| **int32_t** [get_InnerExceptionCount](./get_innerexceptioncount/)() | รับจำนวนข้อยกเว้นภายในที่อยู่ในข้อยกเว้นเชิงรวมนี้. |
| [SharedPtr](../sharedptr/)\<[Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<[Exception](../exception/)\>\> [get_InnerExceptions](./get_innerexceptions/)() | รับคอลเลกชันแบบอ่านอย่างเดียวของข้อยกเว้นภายใน. |
| const [ArrayPtr](../arrayptr/)\<[Exception](../exception/)\>\& [get_InternalInnerExceptions](./get_internalinnerexceptions/)() | ส่งคืนอาเรย์ภายในของข้อยกเว้นภายใน. |
| [String](../string/) [get_Message](./get_message/)() const override | เขียนทับข้อความฐานเพื่อรวมข้อมูลเชิงรวมจากข้อยกเว้นภายในทั้งหมด. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | ส่งคืนสตริงที่มีข้อมูล stack trace. |
| [Exception](../exception/) [GetBaseException](./getbaseexception/)() const override | ส่งคืนข้อยกเว้นสาเหตุรากโดยการคลายข้อยกเว้นภายในแบบเรียกซ้ำ. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | อนาล็อกของเมธอด C# [Object.GetHashCode()](../object/gethashcode/) ทำให้สามารถแฮชอ็อบเจ็กต์แบบกำหนดเองได้. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. ออนาล็อกของการเรียก C# [System.Object.GetType()](../object/gettype/). |
| void [Handle](./handle/)(const [Func](../func/)\<[Exception](../exception/), **bool**\>\&) | เรียกฟังก์ชันจัดการบนแต่ละข้อยกเว้นภายในและโยนข้อยกเว้นที่ไม่ได้จัดการต่อ. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. ออนาล็อกของตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../object/lock/)() | ทำการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | ออนาล็อกของเมธอด C# [Object.MemberwiseClone()](../object/memberwiseclone/) ทำให้สามารถโคลนประเภทที่กำหนดเองได้. |
|  [Object](../object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../object/object/)([Object](../object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และอนุญาตให้สร้างสำเนาสำหรับซับคลาส. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไร เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และอนุญาตให้สร้างสำเนาสำหรับซับคลาส. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่ากับ nullptr โดยอ้างอิง. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | การเจาะจงของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | การเจาะจงของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงร่วมโดยค่าที่ระบุ. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | ตั้งค่า HRESULT ซึ่งเป็นค่าตัวเลขที่เข้ารหัสและกำหนดให้กับข้อยกเว้นเฉพาะ. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n ให้เป็นพอยเตอร์แบบอ่อน (weak) (แทนการแชร์). อนุญาตให้สลับพอยเตอร์ในคอนเทนเนอร์เป็นโหมดอ่อน. |
| int [SharedCount](../object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงร่วม. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงร่วมและส่งค่ากลับ. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน. |
| [String](../string/) [ToString](./tostring/)() const override | ส่งคืนสตริงที่แสดงข้อยกเว้นรวมถึงข้อยกเว้นภายในทั้งหมด. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | ทำการสร้าง typeof([System.Object](../object/)) ของ C#. |
| void [Unlock](../object/unlock/)() | ทำการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงอ่อน. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ลดจำนวนการอ้างอิงอ่อน. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน. |
| virtual const char * [what](../details_exception/what/)() const | ทำการดำเนินเมธอด [what()](../details_exception/what/) ซึ่งถูกเรียกโดยคลาส [ExceptionWrapper](../exceptionwrapper/). แม้ว่าคลาสนี้จะไม่ได้สืบทอดจาก std::exception แต่คลาสที่สืบทอดสามารถใช้สมาชิกที่เป็น protected/private เพื่อทำตรรกะของตนได้ การย้ายการดำเนินเมธอดนี้ไปยัง [ExceptionWrapper](../exceptionwrapper/) อาจทำให้ตรรกะนั้นเสียหาย. |
| virtual  [~Object](../object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## หมายเหตุ


คลาสนี้โดยทั่วไปใช้เพื่อจัดกลุ่มข้อยกเว้นหลายรายการที่เกิดขึ้นพร้อมกัน เช่น ในกรณีของการประมวลผลแบบขนานหรือสถานการณ์การดำเนินงานแบบอะซิงโครนัส มันอนุญาตให้ผู้ใช้ตรวจสอบ แบน หรือจัดการข้อยกเว้นที่บรรจุอยู่ตามความต้องการได้. 

## ดูเพิ่มเติม

* คลาส [Details_Exception](../details_exception/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)