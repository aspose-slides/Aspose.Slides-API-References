---
title: Details_BadImageFormatException
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "ข้อยกเว้นที่ถูกโยนเมื่อไฟล์ภาพของไดนามิกลิงก์ไลบรารี (DLL) หรือโปรแกรมที่ทำงานได้มีรูปแบบไม่ถูกต้อง. ห้ามสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง. ใช้คลาส BadImageFormatException แทน. ห้ามห่อหุ้มอินสแตนซ์ของคลาส BadImageFormatException ไว้ใน System::SmartPtr."
type: docs
weight: 378
url: /th/system/details_badimageformatexception/
---
## Details_BadImageFormatException คลาส

ข้อยกเว้นที่ถูกโยนเมื่อไฟล์รูปภาพของไดนามิกลิงก์ไลบรารี (DLL) หรือโปรแกรมที่ทำงานได้มีรูปแบบไม่ถูกต้อง. ห้ามสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง. ใช้ BadImageFormatException คลาสแทน. ห้ามห่อหุ้มอินสแตนซ์ของ BadImageFormatException คลาสเข้าไปใน [System::SmartPtr](../smartptr/).

```cpp
class Details_BadImageFormatException : public System::Details_ExceptionWithFilename<Details_SystemException>
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | เปรียบเทียบวัตถุโดยใช้แนวคิดของ C# [Object.Equals](../object/equals/) |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจริงสไตล์ C# ที่สองค่า NaN ถือว่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมทั้ง NaN |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจริงสไตล์ C# ที่สองค่า NaN ถือว่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมทั้ง NaN |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับวัตถุภายในเท่านั้น |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | ส่งคืนพจนานุกรมที่มีข้อมูลข้อยกเว้นแบบกำหนดเอง |
| virtual [String](../string/) [get_FileName](../details_exceptionwithfilename/get_filename/)() const | รับชื่อไฟล์ที่ทำให้เกิดข้อยกเว้นนี้ |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | ส่งคืนค่าจำนวนเต็ม 32 บิตที่เป็นรหัส HRESULT ที่เกี่ยวข้องกับข้อยกเว้นที่อธิบายโดยวัตถุปัจจุบัน |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | ส่งคืนการอ้างอิงถึงวัตถุที่แทนข้อยกเว้นภายใน |
| [String](../string/) [get_Message](../details_exceptionwithfilename/get_message/)() const override |  |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | ส่งคืนสตริงที่มีข้อมูลสแตกเทรซ |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | ส่งคืนสำเนาของวัตถุ Exception ที่แทนข้อยกเว้นที่อยู่ในระดับลึกที่สุด |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | เป็นเทียบเคียงของเมธอด C# [Object.GetHashCode()](../object/gethashcode/). ทำให้สามารถแฮชวัตถุแบบกำหนดเองได้ |
| const [System::TypeInfo](../typeinfo/)\& [GetType](../details_systemexception/gettype/)() const override | รับชนิดจริงของวัตถุ. เทียบเคียงกับการเรียก C# [System.Object.GetType()](../object/gettype/) |
| **bool** [Is](../details_systemexception/is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/) |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | เทียบเคียงกับเมธอด C# [Object.MemberwiseClone()](../object/memberwiseclone/). ทำให้สามารถโคลนประเภทกำหนดเองได้ |
|  [Object](../object/object/)() | สร้างวัตถุ. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../object/object/)([Object](../object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นวัตถุใหม่และเปิดใช้งานการสร้างคัดลอกของคลาสย่อย |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นวัตถุใหม่และเปิดใช้การสร้างคัดลอกของคลาสย่อย |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบการอ้างอิงวัตถุประเภทค่ากับ nullptr |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | การกำหนดค่าพิเศษของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | การกำหนดค่าพิเศษของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่ใช้ร่วมกันโดยค่าที่ระบุ |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | กำหนดค่า HRESULT, ค่าตัวเลขที่เข้ารหัสซึ่งมอบให้กับข้อยกเว้นเฉพาะ |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทนที่ shared). อนุญาตให้เปลี่ยนพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่ใช้ร่วมกัน |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่ใช้ร่วมกัน. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงที่ใช้ร่วมกันและส่งค่ากลับ. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| [String](../string/) [ToString](../details_exceptionwithfilename/tostring/)() const override |  |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../details_systemexception/type/)() |  |
| void [Unlock](../object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| virtual const char * [what](../details_exception/what/)() const | ดำเนินการเมธอด [what()](../details_exception/what/) ที่ถูกเรียกโดยคลาส [ExceptionWrapper](../exceptionwrapper/). แม้ว่าคลาสนี้จะไม่ได้สืบทอดจาก std::exception แต่คลาสที่สืบทอดสามารถใช้สมาชิกที่ปกป้อง/ส่วนตัวเพื่อทำให้ตรรกะทำงานได้ การย้ายการทำงานของเมธอดนี้ไปที่ [ExceptionWrapper](../exceptionwrapper/) อาจทำให้ตรรกะเสียหาย |
| virtual  [~Object](../object/~object/)() | ทำลายวัตถุ. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [Details_ExceptionWithFilename](../details_exceptionwithfilename/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)