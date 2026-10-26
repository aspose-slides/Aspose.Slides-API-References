---
title: Details_ArgumentException
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "ArgumentException ถูกโยนเมื่ออาร์กิวเมนต์ที่ส่งให้เมธอดที่กำลังเรียกใช้นั้นไม่ถูกต้อง ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง ใช้คลาส ArgumentException แทน ไม่ควรห่อหุ้มอินสแตนซ์ของคลาส ArgumentException ด้วย System::SmartPtr."
type: docs
weight: 326
url: /th/system/details_argumentexception/
---
## Details_ArgumentException คลาส

ArgumentException ถูกโยนเมื่ออาร์กิวเมนต์ที่ส่งให้เมธอดที่กำลังเรียกใช้นั้นไม่ถูกต้อง ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง ใช้คลาส ArgumentException แทน ไม่ควรห่อหุ้มอินสแตนซ์ของคลาส ArgumentException ด้วย [System::SmartPtr](../smartptr/).

```cpp
class Details_ArgumentException : public System::Details_SystemException
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | เปรียบเทียบออบเจกต์โดยใช้เซมานติกของ C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจกต์แบบอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจกต์แบบค่าในสไตล์ C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ที่สองค่า NaN ถือเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 ค่า NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ที่สองค่า NaN ถือเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 ค่า NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับการทำงานภายในเท่านั้น. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | คืนพจนานุกรมที่มีข้อมูลข้อยกเว้นที่กำหนดเอง. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | คืนค่าเต็มจำนวน 32-bit ที่เป็นรหัส HRESULT เชื่อมโยงกับข้อยกเว้นที่วัตถุปัจจุบันแสดง. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | คืนอ้างอิงไปยังวัตถุที่แทนข้อยกเว้นภายใน. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | คืนสตริงที่มีคำอธิบายข้อผิดพลาด. |
| [String](../string/) [get_ParamName](./get_paramname/)() |  |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | คืนสตริงที่มีสแตกเทรซ. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | คืนสำเนาของวัตถุ Exception ที่แทนข้อยกเว้นที่อยู่ในระดับสุดลึก. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../object/gethashcode/) ทำให้สามารถแฮชออบเจกต์ที่กำหนดเองได้. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | รับประเภทจริงของวัตถุ คล้ายกับการเรียก C# [System.Object.GetType()](../object/gettype/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อการล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../object/memberwiseclone/) ทำให้สามารถโคลนประเภทที่กำหนดเองได้. |
|  [Object](../object/object/)() | สร้างวัตถุ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../object/object/)([Object](../object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริงๆ เพียงเริ่มต้นวัตถุใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของคลาสย่อย. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรจริงๆ เพียงเริ่มต้นวัตถุใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของคลาสย่อย. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | เปรียบเทียบออบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบออบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงกับออบเจกต์ประเภทค่าเมื่อเทียบกับ nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริงหลายรายการ. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | ตั้งค่า HRESULT ซึ่งเป็นค่าตัวเลขที่เข้ารหัสและถูกกำหนดให้กับข้อยกเว้นเฉพาะ. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทนที่ shared) ทำให้สามารถสลับ pointer ในคอนเทนเนอร์เป็นโหมด weak ได้. |
| int [SharedCount](../object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แชร์ ควรไม่เรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงที่แชร์และคืนค่า ควรไม่เรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | คืนการแสดงผลเป็นสตริงของวัตถุปัจจุบัน. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | เพิ่มจำนวน weak reference count ควรไม่เรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ลดจำนวน weak reference count ควรไม่เรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| virtual const char * [what](../details_exception/what/)() const | ทำงานตามเมธอด [what()](../details_exception/what/) ที่ถูกเรียกโดยคลาส [ExceptionWrapper](../exceptionwrapper/) แม้ว่าคลาสนี้จะไม่ได้สืบทอดจาก std::exception แต่คลาสที่สืบทอดสามารถใช้สมาชิกที่เป็น protected/private เพื่อดำเนินตรรกะ การย้ายการดำเนินการของเมธอดนี้ไปยัง [ExceptionWrapper](../exceptionwrapper/) อาจทำให้ตรรกะเสียหาย. |
| virtual  [~Object](../object/~object/)() | ทำลายวัตถุ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## หมายเหตุ

ArgumentNullException ถูกโยนเมื่อเมธอดที่กำลังเรียกใช้งานได้รับอาร์กิวเมนต์เป็น null แม้ว่าต้องการค่าที่ไม่เป็น null ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง ใช้คลาส ArgumentNullException แทน ไม่ควรห่อหุ้มอินสแตนซ์ของคลาส ArgumentNullException ด้วย [System::SmartPtr](../smartptr/). 

## ดูเพิ่มเติม

* คลาส [Details_SystemException](../details_systemexception/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)