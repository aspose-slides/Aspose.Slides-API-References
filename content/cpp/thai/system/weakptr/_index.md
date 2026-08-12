---
title: WeakPtr
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: "คลาสย่อยของ System::SmartPtr ที่ตั้งค่าให้เป็นโหมด weak ตอนสร้าง โปรดทราบว่า คลาสนี้ไม่ได้รับประกันว่าอินสแตนซ์ของมันจะคงอยู่ในโหมด weak เสมอเนื่องจาก set_Mode() ยังสามารถเข้าถึงได้ ชนิดนี้เป็นพอยเตอร์ที่จัดการการลบของอ็อบเจ็กต์อื่น ควรจัดสรรบนสแตคและส่งต่อไปยังฟังก์ชันโดยค่าหรือโดยการอ้างอิงแบบ const."
type: docs
weight: 1496
url: /th/system/weakptr/
---
## คลาส WeakPtr

คลาสย่อยของ [System::SmartPtr](../smartptr/) ที่ตั้งค่าให้เป็นโหมด weak ตอนสร้าง โปรดทราบว่า คลาสนี้ ไม่รับประกันว่าอินสแตนซ์ของมันจะคงอยู่ในโหมด weak เสมอ เนื่องจาก [set_Mode()](../smartptr/set_mode/) ยังเข้าถึงได้ ชนิดนี้เป็นพอยเตอร์ที่จัดการการลบของออบเจ็กต์อื่น ควรจัดสรรบนสแตคและส่งต่อไปยังฟังก์ชันโดยค่าหรือโดยการอ้างอิงแบบ const

```cpp
template<class T>class WeakPtr : public System::SmartPtr<T>
```

### พารามิเตอร์ของเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของ Pointee. |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| auto [begin](../smartptr/begin/)() | ตัวเข้าถึงสำหรับเมธอด [begin()](../smartptr/begin/) ของคอลเลกชันพื้นฐาน คอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นประเภทเชี่ยวชาญที่มีเมธอด [begin()](../smartptr/begin/). |
| auto [begin](../smartptr/begin/)() const | ตัวเข้าถึงสำหรับเมธอด [begin()](../smartptr/begin/) ของคอลเลกชันพื้นฐาน คอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นประเภทเชี่ยวชาญที่มีเมธอด [begin()](../smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | แคสต์พอยเตอร์เป็นชนิดของมันเอง. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | แคสต์พอยเตอร์เป็นชนิดพื้นฐานโดยใช้ static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | แคสต์พอยเตอร์เป็นชนิดที่สืบทอดโดยใช้ dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | แคสต์พอยเตอร์เป็นชนิดที่สืบทอดโดยใช้ dynamic_cast. |
| auto [cbegin](../smartptr/cbegin/)() const | ตัวเข้าถึงสำหรับเมธอด [cbegin()](../smartptr/cbegin/) ของคอลเลกชันพื้นฐาน คอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นประเภทเชี่ยวชาญที่มีเมธอด [cbegin()](../smartptr/cbegin/). |
| auto [cend](../smartptr/cend/)() const | ตัวเข้าถึงสำหรับเมธอด [cend()](../smartptr/cend/) ของคอลเลกชันพื้นฐาน คอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นประเภทเชี่ยวชาญที่มีเมธอด [cend()](../smartptr/cend/). |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | แคสต์พอยเตอร์เป็นชนิดอื่นโดยใช้ const_cast กับอ็อบเจ็กต์ที่ชี้. |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | แคสต์พอยเตอร์เป็นชนิดอื่นโดยใช้ dynamic_cast กับอ็อบเจ็กต์ที่ชี้. |
| auto [end](../smartptr/end/)() | ตัวเข้าถึงสำหรับเมธอด [end()](../smartptr/end/) ของคอลเลกชันพื้นฐาน คอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นประเภทเชี่ยวชาญที่มีเมธอด [end()](../smartptr/end/). |
| auto [end](../smartptr/end/)() const | ตัวเข้าถึงสำหรับเมธอด [end()](../smartptr/end/) ของคอลเลกชันพื้นฐาน คอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นประเภทเชี่ยวชาญที่มีเมธอด [end()](../smartptr/end/). |
| **bool** [expired](./expired/)() const | ตรวจสอบว่ากลุ่มอ็อบเจ็กต์ที่อ้างอิงถูกลบแล้วหรือยัง. |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | ได้รับอ็อบเจ็กต์ที่ชี้. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | ได้รับโหมดของพอยเตอร์. |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | ได้รับอ็อบเจ็กต์ที่ชี้ แต่ตรวจสอบว่าพอยเตอร์อยู่ในโหมด shared. |
| int [get_shared_count](../smartptr/get_shared_count/)() const | ได้รับจำนวนพอยเตอร์ shared ที่อ้างอิงถึงอ็อบเจ็กต์เดียวกันรวมถึงพอยเตอร์ปัจจุบัน ตรวจสอบว่าพอยเตอร์ปัจจุบันอยู่ในโหมด shared. |
| [Object](../object/) * [get_weak](./get_weak/)() const | ได้รับอ็อบเจ็กต์ที่อ้างอิง ตรวจสอบว่าพอยเตอร์อยู่ในโหมด weak. |
| int [GetHashCode](../smartptr/gethashcode/)() const | เรียก [GetHashCode()](../smartptr/gethashcode/) บนอ็อบเจ็กต์ที่ชี้. |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | ได้รับอ็อบเจ็กต์ที่อ้างอิงอยู่ในขณะนี้ (ถ้ามี) หรือโยนข้อยกเว้น. |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | ได้รับอ็อบเจ็กต์ที่ชี้ (ถ้ามี) หรือ nullptr. เหมือนกับ [get()](../smartptr/get/). |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | ได้รับอ็อบเจ็กต์ที่อ้างอิง. |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | ได้รับอ็อบเจ็กต์ที่ชี้ (ถ้ามี) หรือ nullptr. เหมือนกับ [get()](../smartptr/get/). |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | ตรวจสอบว่ามีอ็อบเจ็กต์ที่ชี้เป็นชนิดเฉพาะหรือเป็นชนิดลูกของมัน ตามเซมานติกของ C# ‘is’. |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | ตรวจสอบว่าพอยเตอร์ชี้ไปยังอ็อบเจ็กต์อื่นที่ไม่ได้เป็นเจ้าของ (สร้างโดยคอนสตรัคเตอร์ aliasing). |
| **bool** [IsShared](../smartptr/isshared/)() const | ตรวจสอบว่าพอยเตอร์อยู่ในโหมด shared. |
| **bool** [IsWeak](../smartptr/isweak/)() const | ตรวจสอบว่าพอยเตอร์อยู่ในโหมด weak. |
| explicit  [operator bool](../smartptr/operator_bool/)() const | ตรวจสอบว่าพอยเตอร์ไม่เป็น null. |
| **bool** [operator!](../smartptr/operator_not/)() const | ตรวจสอบว่าพอยเตอร์เป็น null. |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | ได้รับการอ้างอิงของอ็อบเจ็กต์ที่ชี้ ตรวจสอบว่าพอยเตอร์ไม่เป็น null. |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | อนุญาตให้เข้าถึงสมาชิกของอ็อบเจ็กต์ที่อ้างอิง. |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | ให้พฤติกรรมการเปรียบเทียบน้อยกว่าสำหรับคลาส [SmartPtr](../smartptr/). |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | ให้พฤติกรรมการเปรียบเทียบน้อยกว่าสำหรับคลาส [SmartPtr](../smartptr/). |
| [WeakPtr](./)\& [operator=](./operator_equal/)(Q\&&) | กำหนดค่าให้กับพอยเตอร์ weak เรียกตัวดำเนินการกำหนดค่าเฉพาะของ SmartPtr_. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([SmartPtr_](../smartptr/smartptr_/)\&&) | ย้าย-กำหนดค่าอ็อบเจ็กต์ [SmartPtr](../smartptr/) ทำให้ x ไม่สามารถใช้ได้ต่อ. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | คัดลอก-กำหนดค่าอ็อบเจ็กต์ [SmartPtr](../smartptr/). |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | คัดลอก-กำหนดค่าอ็อบเจ็กต์ [SmartPtr](../smartptr/) ทำการแปลงประเภทที่จำเป็น. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([Pointee_](../smartptr/pointee_/) *) | กำหนดพอยเตอร์ดิบให้กับอ็อบเจ็กต์ [SmartPtr](../smartptr/). |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(std::nullptr_t) | ตั้งค่าพอยเตอร์เป็น nullptr. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | ตรวจสอบว่าพอยเตอร์ weak เป็น null. |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | ลบการ aliasing (สร้างโดยคอนสตรัคเตอร์ aliasing) จากพอยเตอร์ ทำให้แน่ใจว่ามันจัดการ (ถ้าเป็น shared) หรือ ติดตาม (ถ้าเป็น weak) อ็อบเจ็กต์เดียวกันที่ชี้. |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | ตั้งค่าอ็อบเจ็กต์ที่ชี้. |
| void [reset](../smartptr/reset/)() | ทำให้พอยเตอร์ชี้ไปที่ nullptr. |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | ตั้งค่าโหมดของพอยเตอร์ อาจเปลี่ยนจำนวนอ้างอิงของอ็อบเจ็กต์ที่อ้างอิง. |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | เรียกเมธอด SetTemplateWeakPtr() บนอ็อบเจ็กต์ที่ชี้ (ถ้ามี). |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | สร้างอ็อบเจ็กต์ [SmartPtr](../smartptr/) ที่มีโหมดตามที่ต้องการ. |
|  [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | สร้างอ็อบเจ็กต์ [SmartPtr](../smartptr/) ที่เป็น null-pointer ตามโหมดที่ต้องการ. |
|  [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | สร้าง [SmartPtr](../smartptr/) ชี้ไปยังอ็อบเจ็กต์ที่ระบุ หรือแปลงพอยเตอร์ดิบเป็น [SmartPtr](../smartptr/). |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | คัดลอกสร้างอ็อบเจ็กต์ [SmartPtr](../smartptr/) ทั้งสองพอยเตอร์ชี้ไปยังอ็อบเจ็กต์เดียวกันหลังจากนั้น. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | คัดลอกสร้างอ็อบเจ็กต์ [SmartPtr](../smartptr/) ทั้งสองพอยเตอร์ชี้ไปยังอ็อบเจ็กต์เดียวกันหลังจากนั้น ทำการแปลงประเภทหากอนุญาต. |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | ย้ายสร้างอ็อบเจ็กต์ [SmartPtr](../smartptr/) โดยสลับพอยเตอร์สองตัว หากอยู่ในโหมดเดียวกัน x อาจไม่สามารถใช้ได้หลังจากเรียก. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | แปลงประเภทของอาร์เรย์ที่อ้างอิงโดยสร้างอาร์เรย์ใหม่ของชนิดต่างกัน มีประโยชน์หากใน C# มีการแคสต์อาร์เรย์ที่ไม่รองรับใน C++. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const Y\&) | เริ่มต้นอาร์เรย์ว่าง ใช้เพื่อแปลโครงสร้างโค้ด C# บางส่วน. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | สร้าง [SmartPtr](../smartptr/) ที่แชร์ข้อมูลการเป็นเจ้าของกับค่าเริ่มต้นของ ptr แต่ถือพอยเตอร์ p ที่ไม่มีการจัดการ. |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | แคสต์พอยเตอร์เป็นชนิดอื่นโดยใช้ static_cast กับอ็อบเจ็กต์ที่ชี้. |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | แปลงพอยเตอร์ชนิดใดก็ได้เป็นพอยเตอร์ไปยัง [Object](../object/) ไม่จำเป็นต้องให้ประเภท Pointee_ สมบูรณ์. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | ทางลัดเพื่อรับอ็อบเจ็กต์ [System::TypeInfo](../typeinfo/) สำหรับประเภท Pointee_. |
|  [WeakPtr](./weakptr/)(std::nullptr_t) | สร้างพอยเตอร์ null. |
|  [WeakPtr](./weakptr/)([Pointee_](../smartptr/pointee_/) *) | สร้างพอยเตอร์ weak ให้กับอ็อบเจ็กต์ที่กำหนด. |
|  [WeakPtr](./weakptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | สร้างพอยเตอร์ weak อ้างอิงพอยเตอร์เดียวกับ ptr. |
|  [WeakPtr](./weakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | สร้างพอยเตอร์ weak อ้างอิงพอยเตอร์เดียวกับ x. |
|  [WeakPtr](./weakptr/)(const [WeakPtr_](./weakptr_/)\&) | คัดลอกสร้างพอยเตอร์ weak. |
|  [WeakPtr](./weakptr/)(const [WeakPtr](./)\<Q\>\&) | คัดลอกสร้างพอยเตอร์ weak. |
|  [WeakPtr](./weakptr/)([SmartPtr_](../smartptr/smartptr_/)\&&) | ย้ายสร้างพอยเตอร์ weak. |
|  [~SmartPtr](../smartptr/~smartptr/)() | ทำลายอ็อบเจ็กต์ [SmartPtr](../smartptr/) หากจำเป็น จะลดตัวนับอ้างอิงของอ็อบเจ็กต์ที่ชี้และลบอ็อบเจ็กต์. |

## การนิยาม

| การนิยาม | คำอธิบาย |
| --- | --- |
| [SmartPtr_](./smartptr_/) | นามแฝงสำหรับคลาส [SmartPtr](../smartptr/) ที่สอดคล้อง. |
| [WeakPtr_](./weakptr_/) | นามแฝงสำหรับประเภทของตัวเอง. |
| [Pointee_](./pointee_/) | ประเภทที่ชี้. |

## ดูเพิ่มเติม

* คลาส [SmartPtr](../smartptr/)
* เนมส페ซ [System](../)
* ไลบรารี [Aspose.Slides](../../)