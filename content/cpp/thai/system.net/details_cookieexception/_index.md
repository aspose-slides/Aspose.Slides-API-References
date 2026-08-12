---
title: Details_CookieException
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "แสดงถึงข้อยกเว้นที่ถูกโยนเมื่อขนาดของ CookieContainer มากกว่าค่าคุณสมบัติ MaxCookieSize. อย่าสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง. ใช้คลาส CookieException แทน. อย่าห่ออินสแตนซ์ของคลาส CookieException เข้าไปใน System::SmartPtr."
type: docs
weight: 79
url: /th/system.net/details_cookieexception/
---
## Details_CookieException คลาส


แสดงถึงข้อยกเว้นที่ถูกโยนเมื่อขนาดของ [CookieContainer](../cookiecontainer/) มากกว่าค่าคุณสมบัติ MaxCookieSize. ห้ามสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง. ใช้คลาส CookieException แทน. ห้ามห่ออินสแตนซ์ของคลาส CookieException เข้าไปใน [System::SmartPtr](../../system/smartptr/).

```cpp
class Details_CookieException : public System::Details_FormatException
```

## เมธอด

| Method | Description |
| --- | --- |
|  [Details_CookieException](./details_cookieexception/)() | สร้างอินสแตนซ์ใหม่. |
|  [Details_CookieException](./details_cookieexception/)(std::nullptr_t) | สร้างอินสแตนซ์ใหม่. |
|  [Details_CookieException](./details_cookieexception/)([String](../../system/string/)) | สร้างอินสแตนซ์ใหม่. |
|  [Details_CookieException](./details_cookieexception/)([String](../../system/string/), [Exception](../../system/exception/)) | สร้างอินสแตนซ์ใหม่. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขจุดลอยแบบ C# ที่สองค่า NaN ถือว่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 ค่า NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขจุดลอยแบบ C# ที่สองค่า NaN ถือว่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 ค่า NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | คืนพจนานุกรมที่มีข้อมูลข้อยกเว้นแบบกำหนดเอง. |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | คืนค่าจำนวนเต็ม 32 บิตซึ่งเป็นโค้ด HRESULT ที่เชื่อมโยงกับข้อยกเว้นที่แสดงโดยอ็อบเจ็กต์ปัจจุบัน. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | คืนการอ้างอิงไปยังอ็อบเจ็กต์ที่แสดงข้อยกเว้นภายใน. |
| virtual [String](../../system/string/) [get_Message](../../system/details_exception/get_message/)() const | คืนสตริงที่บรรจุคำอธิบายข้อผิดพลาด. |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | คืนสตริงที่บรรจุข้อมูล stack trace. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | คืนสำเนาของอ็อบเจ็กต์ Exception ที่แสดงข้อยกเว้นในระดับที่ลึกที่สุด. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นออนาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ให้การแฮชอ็อบเจ็กต์แบบกำหนดเอง. |
| const [System::TypeInfo](../../system/typeinfo/)\& [GetType](../../system/details_formatexception/gettype/)() const override | รับประเภทจริงของอ็อบเจ็กต์. เป็นออนาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [Is](../../system/details_formatexception/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const override |  |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เป็นการล็อคของคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentry. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นออนาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ให้การคัดลอกประเภทแบบกำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาแบบคอนสตรัคเตอร์ของซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาแบบคอนสตรัคเตอร์ของซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงของอ็อบเจ็กต์ประเภทค่ากับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การกำหนดค่าเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การกำหนดค่าเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงร่วมโดยค่าที่ระบุ. |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | กำหนดค่า HRESULT, ค่าตัวเลขที่เข้ารหัสซึ่งถูกกำหนดให้กับข้อยกเว้นเฉพาะ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทนที่ shared). อนุญาตให้เปลี่ยนพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงร่วมและคืนค่า. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | คืนสตริงที่เป็นการแสดงตัวของอ็อบเจ็กต์ปัจจุบัน. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/details_formatexception/type/)() |  |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อคของคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentry. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวน weak reference count. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวน weak reference count. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual const char * [what](../../system/details_exception/what/)() const | ทำหน้าที่เป็นเมธอด [what()](../../system/details_exception/what/) ที่ถูกเรียกโดยคลาส [ExceptionWrapper](../../system/exceptionwrapper/). แม้ว่าคลาสนี้จะไม่ได้สืบทอดจาก std::exception แต่คลาสที่สืบทอดสามารถใช้สมาชิกที่ protected/private เพื่อทำตรรกะของตน การย้ายการทำงานของเมธอดนี้ไปยัง [ExceptionWrapper](../../system/exceptionwrapper/) อาจทำให้ตรรกะนั้นเสียหาย. |
| virtual  [~Details_CookieException](./~details_cookieexception/)() | ทำลายอินสแตนซ์ปัจจุบัน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [Details_FormatException](../../system/details_formatexception/)
* เนมสเปซ [System::Net](../)
* ไลบรารี [Aspose.Slides](../../)