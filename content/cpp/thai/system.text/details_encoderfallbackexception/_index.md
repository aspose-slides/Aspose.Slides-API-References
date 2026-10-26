---
title: Details_EncoderFallbackException
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "ข้อยกเว้นที่ถูกโยนโดย EncoderExceptionFallback เมื่อการเข้ารหัสล้มเหลว. ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง. ใช้คลาส EncoderFallbackException แทน. ไม่ควรบรรจุอินสแตนซ์ของคลาส EncoderFallbackException ลงใน System::SmartPtr."
type: docs
weight: 118
url: /th/system.text/details_encoderfallbackexception/
---
## Details_EncoderFallbackException คลาส

ข้อยกเว้นที่ถูกโยนโดย [EncoderExceptionFallback](../encoderexceptionfallback/) เมื่อการเข้ารหัสล้มเหลว. ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง. ใช้คลาส EncoderFallbackException แทน. ไม่ควรบรรจุอินสแตนซ์ของคลาส EncoderFallbackException ลงใน [System::SmartPtr](../../system/smartptr/).

```cpp
class Details_EncoderFallbackException : public System::Details_ArgumentException
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้เซมแอนติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์แบบอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์แบบค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบตัวเลขทศนิยมสไตล์ C# ที่ NaN สองค่าถูกถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบตัวเลขทศนิยมสไตล์ C# ที่ NaN สองค่าถูกถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| char_t [get_CharUnknown](./get_charunknown/)() | รับอักขระที่ทำให้เกิดข้อผิดพลาด. |
| char_t [get_CharUnknownHigh](./get_charunknownhigh/)() | รับอักขระสูงของคู่ที่ทำให้เกิดข้อผิดพลาด. |
| char_t [get_CharUnknownLow](./get_charunknownlow/)() | รับอักขระต่ำของคู่ที่ทำให้เกิดข้อผิดพลาด. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | คืนพจนานุกรมที่มีข้อมูลข้อยกเว้นที่กำหนดเอง. |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | คืนค่าเต็ม 32 บิตที่เป็นรหัส HRESULT ที่เชื่อมโยงกับข้อยกเว้นที่ออบเจ็กต์ปัจจุบันแทน. |
| int [get_Index](./get_index/)() | รับตำแหน่งของอักขระที่ทำให้เกิดข้อผิดพลาดในอาร์เรย์อินพุต. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | คืนการอ้างอิงไปยังออบเจ็กต์ที่เป็นตัวแทนของข้อยกเว้นภายใน. |
| virtual [String](../../system/string/) [get_Message](../../system/details_exception/get_message/)() const | คืนสตริงที่มีรายละเอียดข้อผิดพลาด. |
| [String](../../system/string/) [get_ParamName](../../system/details_argumentexception/get_paramname/)() |  |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | คืนสตริงที่มีข้อมูลสแต็กเทรซ. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | คืนสำเนาของออบเจ็กต์ Exception ที่แสดงข้อยกเว้นที่ลึกที่สุด. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับออบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของออบเจ็กต์ที่กำหนดเอง. |
| const [System::TypeInfo](../../system/typeinfo/)\& [GetType](../../system/details_argumentexception/gettype/)() const override | รับประเภทจริงของออบเจ็กต์. คล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [Is](../../system/details_argumentexception/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const override |  |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการทำสำเนาของประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างออบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ ไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นออบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมายค่า. จริง ๆ ไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นออบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจ็กต์แบบค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การสเปเชียลไลซ์ของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การสเปเชียลไลซ์ของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่ใช้ร่วมกันโดยค่าที่ระบุ. |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | ตั้งค่า HRESULT ซึ่งเป็นค่าตัวเลขรหัสที่กำหนดให้กับข้อยกเว้นเฉพาะ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่ใช้ร่วมกัน. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่ใช้ร่วมกัน. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงที่ใช้ร่วมกันและคืนค่า. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | คืนการแสดงผลเป็นสตริงของออบเจ็กต์ปัจจุบัน. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/details_argumentexception/type/)() |  |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual const char * [what](../../system/details_exception/what/)() const | ดำเนินการเมธอด [what()](../../system/details_exception/what/) ที่เรียกโดยคลาส [ExceptionWrapper](../../system/exceptionwrapper/). แม้ว่า คลาสนี้จะไม่ได้สืบทอดจาก std::exception คลาสที่สืบทอดสามารถใช้สมาชิก protected/private เพื่อทำตรรกะของตนได้ การย้ายการทำงานของเมธอดนี้ไปยัง [ExceptionWrapper](../../system/exceptionwrapper/) อาจทำให้ตรรกะดังกล่าวเสียหาย. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายออบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [Details_ArgumentException](../../system/details_argumentexception/)
* เนมสเปซ [System::Text](../)
* ไลบรารี [Aspose.Slides](../../)