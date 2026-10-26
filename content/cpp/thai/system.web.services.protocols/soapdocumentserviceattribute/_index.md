---
title: SoapDocumentServiceAttribute
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "ตั้งค่ารูปแบบเริ่มต้นสำหรับคำขอและการตอบสนอง SOAP. ออบเจกต์ของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. ห้ามสร้างอินสแตนซ์ของชนิดนี้บนสแตกหรือใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดเวลาเรียกใช้และ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อหุ้มคลาสนี้ด้วย pointer System::SmartPtr เสมอและใช้ pointer นี้ส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 66
url: /th/system.web.services.protocols/soapdocumentserviceattribute/
---
## SoapDocumentServiceAttribute คลาส


ตั้งค่ารูปแบบเริ่มต้นสำหรับคำขอและการตอบสนอง SOAP. ออบเจกต์ของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. ห้ามสร้างอินสแตนซ์ของชนิดนี้บนสแตกหรือใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดเวลาเรียกใช้งานและ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อหุ้มคลาสนี้ด้วย pointer [System::SmartPtr](../../system/smartptr/) เสมอและใช้ pointer นี้ส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน.

```cpp
class SoapDocumentServiceAttribute : public System::Attribute
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบออบเจกต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจกต์แบบ reference type ในรูปแบบ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจกต์แบบ value type ในรูปแบบ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่า floating point สไตล์ C# โดยที่ NaN สองค่าถูกพิจารณาเท่ากัน แม้ว่า ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่า floating point สไตล์ C# โดยที่ NaN สองค่าถูกพิจารณาเท่ากัน แม้ว่า ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| [SoapParameterStyle](../soapparameterstyle/) [get_ParameterStyle](./get_parameterstyle/)() | รับค่าที่บ่งชี้ว่าพารามิเตอร์ถูกห่อหุ้มอยู่ใน XML element เดียวใต้ element 'Body' |
| [SoapServiceRoutingStyle](../soapserviceroutingstyle/) [get_RoutingStyle](./get_routingstyle/)() | รับค่าที่แสดงว่า SOAP messages ถูกกำหนดเส้นทางไปยัง service อย่างไร |
| [Description::SoapBindingUse](../../system.web.services.description/soapbindinguse/) [get_Use](./get_use/)() | รับการจัดรูปแบบของพารามิเตอร์. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลของ reference counter ที่สัมพันธ์กับออบเจกต์. |
| static [Object::ptr](../../system/object/ptr/) [GetCustomAttribute](../../system/attribute/getcustomattribute/)(const [TypeInfo](../../system/typeinfo/)\&, const [TypeInfo](../../system/typeinfo/)\&) | คืนค่า custom attribute ของประเภทที่ระบุที่ถูกนำไปใช้กับประเภทที่ระบุ |
| static [ArrayPtr](../../system/arrayptr/)\<[Object::ptr](../../system/object/ptr/)\> [GetCustomAttributes](../../system/attribute/getcustomattributes/)(const [TypeInfo](../../system/typeinfo/)\&) | คืนค่า custom attributes ทั้งหมดที่นำไปใช้กับประเภทที่ระบุ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถทำ hashing ของออบเจกต์ custom ได้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของออบเจกต์ คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าออบเจกต์เป็นอินสแตนซ์ของประเภทที่ targetType อธิบายไว้หรือไม่ คล้ายกับ operator 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C# เพื่อทำการล็อก เรียกโดยตรงหรือใช้วัตถุ sentry [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถคล cloning custom types ได้ |
|  [Object](../../system/object/object/)() | สร้างออบเจกต์และเริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริงๆ เพียงแค่เริ่มต้นออบเจกต์ใหม่และเปิดให้สามารถ copy construct subclasses |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การมอบหมายค่า ไม่ได้คัดลอกอะไรจริงๆ เพียงแค่เริ่มต้นออบเจกต์ใหม่และเปิดให้สามารถ copy construct subclasses |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบออบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบออบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | ทำการอ้างอิงเปรียบเทียบออบเจกต์ value type กับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การกำหนดพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ string และ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การกำหนดพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ strings |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวน shared reference count ลงตามค่าที่ระบุ |
| void [set_ParameterStyle](./set_parameterstyle/)([SoapParameterStyle](../soapparameterstyle/)) | ตั้งค่าที่บ่งชี้ว่าพารามิเตอร์ถูกห่อหุ้มอยู่ใน XML element เดียวใต้ element 'Body' |
| void [set_RoutingStyle](./set_routingstyle/)([SoapServiceRoutingStyle](../soapserviceroutingstyle/)) | ตั้งค่าที่แสดงว่า SOAP messages ถูกกำหนดเส้นทางไปยัง service อย่างไร |
| void [set_Use](./set_use/)([Description::SoapBindingUse](../../system.web.services.description/soapbindinguse/)) | ตั้งค่าการจัดรูปแบบของพารามิเตอร์ |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทน shared) ทำให้สามารถสลับ pointer ในคอนเทนเนอร์เป็นโหมด weak ได้ |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของ shared reference counter |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่า shared reference count ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าและคืนค่า shared reference count ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
|  [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/)() | สร้างอินสแตนซ์ใหม่ |
|  [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/)([Description::SoapBindingUse](../../system.web.services.description/soapbindinguse/)) | สร้างอินสแตนซ์ใหม่ |
|  [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/)([Description::SoapBindingUse](../../system.web.services.description/soapbindinguse/), [SoapParameterStyle](../soapparameterstyle/)) | สร้างอินสแตนซ์ใหม่ |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงออบเจกต์ custom เป็น string ได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็น construct typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentry [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่า weak reference count ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่า weak reference count ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายออบเจกต์และปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [Attribute](../../system/attribute/)
* เนมสเปซ [System::Web::Services::Protocols](../)
* ไลบรารี [Aspose.Slides](../../)