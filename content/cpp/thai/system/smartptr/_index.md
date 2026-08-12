---
title: SmartPtr
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: "คลาสพอยเตอร์เพื่อห่อหุ้มประเภทที่จัดสรรบน heap. ใช้มันเพื่อจัดการหน่วยความจำสำหรับคลาสที่สืบทอดจาก Object. ประเภทพอยเตอร์นี้ทำตามหลักการของ intrusive pointer. ตัวนับการอ้างอิงจะถูกเก็บไว้ใน Object เองหรือในโครงสร้างตัวนับที่ผูกกับอินสแตนซ์ของ Object อย่างแน่นหนา. ไม่ว่ากรณีใด อินสแตนซ์ทั้งหมดของ SmartPtr จะเป็นกลุ่มความเป็นเจ้าของเดียวกันโดยไม่คำนึงว่าถูกสร้างอย่างไร ซึ่งแตกต่างจากพฤติกรรมของคลาส std::shared_ptr. การแปลงพอยเตอร์ดิบเป็น SmartPtr จะปลอดภัยเมื่อมีอินสแตนซ์ของ SmartPtr อื่น ๆ ถืออ้างอิงแบบ shared ไปยังออบเจกต์เดียวกัน. อินสแตนซ์ของคลาส SmartPtr สามารถอยู่ในสองสถานะ: พอยเตอร์ shared และพอยเตอร์ weak. เพื่อให้วัตถุยังคงอยู่ ควรมีจำนวนการอ้างอิงแบบ shared ที่ชี้ไปยังมันเป็นบวก. พอยเตอร์แบบ weak และ shared สามารถใช้เข้าถึงออบเจกต์ที่ชี้ (เพื่อเรียกเมธอด, อ่านหรือเขียนฟิลด์ ฯลฯ) ได้ แต่พอยเตอร์ weak จะไม่เข้าร่วมในการนับการอ้างอิงของพอยเตอร์ shared. Object จะถูกลบเมื่อพอยเตอร์ 'shared' SmartPtr ตัวสุดท้ายที่ชี้ไปยังมันถูกทำลาย. ดังนั้นตรวจสอบให้แน่ใจว่ากรณีนี้ไม่เกิดขึ้นเมื่อไม่มีพอยเตอร์ shared SmartPtr ตัวอื่นชี้ไปยังออบเจกต์, เช่น ระหว่างการสร้างหรือทำลายออบเจกต์. ใช้วัตถุส่งสัญญาณ System::Object::ThisProtector (ในโค้ด C++) หรือแอตทริบิวต์ CppCTORSelfReference หรือ CppSelfReference (ในโค้ด C# ที่กำลังแปล) เพื่อแก้ไขปัญหานี้. อีกทั้งตรวจสอบให้แน่ใจว่าตัดการอ้างอิงวนกลับโดยใช้คลาสพอยเตอร์ System::WeakPtr หรือโหมดพอยเตอร์ System::SmartPtrMode::Weak (ในโค้ด C++) หรือแอตทริบิวต์ CppWeakPtr (ในโค้ด C# ที่กำลังแปล). หากสองหรือมากกว่าออบเจกต์อ้างอิงถึงกันโดยใช้พอยเตอร์ 'shared' พวกมันจะไม่ถูกลบเลย. หากต้องการสลับประเภทพอยเตอร์ (weak หรือ shared) ระหว่างการทำงาน ให้ใช้เมธอด System::SmartPtr<T>::set_Mode() หรือคลาส System::DynamicWeakPtr. คลาส SmartPtr ไม่มีเมธอด virtual ใด ๆ. คุณควรสืบทอดคลาสนี้เฉพาะเมื่อสร้างกลยุทธ์การจัดการหน่วยความจำของคุณเอง. ประเภทนี้เป็นพอยเตอร์เพื่อจัดการการลบของออบเจ็กต์อื่น. ควรจัดสรรบน stack และส่งต่อให้ฟังก์ชันโดยค่า หรือโดยการอ้างอิงแบบ const."
type: docs
weight: 1236
url: /th/system/smartptr/
---
## SmartPtr คลาส

คลาสพอยเตอร์เพื่อห่อหุ้มประเภทที่จัดสรรบน heap. ใช้เพื่อจัดการหน่วยความจำสำหรับคลาสที่สืบทอดจาก [Object](../object/). ประเภทพอยเตอร์นี้ทำตามหลักการของ intrusive pointer. ตัวนับการอ้างอิงจะถูกเก็บไว้ใน [Object](../object/) เองหรือในโครงสร้างตัวนับที่ผูกกับอินสแตนซ์ของ [Object](../object/) อย่างแน่นหนา. ในทุกกรณี อินสแตนซ์ของ [SmartPtr](./) ทั้งหมดจะอยู่ในกลุ่มความเป็นเจ้าของเดียวกันโดยไม่คำนึงว่าถูกสร้างอย่างไร ซึ่งต่างจากพฤติกรรมของคลาส std::shared_ptr. การแปลงพอยเตอร์ดิบเป็น [SmartPtr](./) จะปลอดภัยเมื่อมีอินสแตนซ์ของ [SmartPtr](./) อื่น ๆ ถืออ้างอิงแบบ shared ไปยังออบเจกต์เดียวกัน. อินสแตนซ์ของคลาส [SmartPtr](./) สามารถอยู่ในสองสถานะ: พอยเตอร์ shared และพอยเตอร์ weak. เพื่อให้วัตถุยังคงมีชีวิตอยู่ ควรมีจำนวนการอ้างอิงแบบ shared ที่ชี้ไปยังมันเป็นบวก. พอยเตอร์แบบ weak และ shared สามารถใช้เข้าถึงออบเจกต์ที่ชี้ (เพื่อเรียกเมธอด, อ่านหรือเขียนฟิลด์ ฯลฯ) ได้ แต่พอยเตอร์ weak จะไม่เข้าร่วมในการนับการอ้างอิงของพอยเตอร์ shared. [Object](../object/) จะถูกลบเมื่อพอยเตอร์ 'shared' [SmartPtr](./) ตัวสุดท้ายที่ชี้ไปยังมันถูกทำลาย. ดังนั้นตรวจสอบให้แน่ใจว่ากรณีนี้ไม่เกิดขึ้นเมื่อไม่มีพอยเตอร์ shared [SmartPtr](./) ตัวอื่นชี้ไปยังออบเจกต์, เช่น ระหว่างการสร้างหรือทำลายออบเจกต์. ใช้วัตถุส่งสัญญาณ System::Object::ThisProtector (ในโค้ด C++) หรือแอตทริบิวต์ CppCTORSelfReference หรือ CppSelfReference (ในโค้ด C# ที่กำลังแปล) เพื่อแก้ไขปัญหานี้. อีกทั้งตรวจสอบให้แน่ใจว่าตัดการอ้างอิงวนกลับโดยใช้คลาสพอยเตอร์ [System::WeakPtr](../weakptr/) หรือโหมดพอยเตอร์ [System::SmartPtrMode::Weak](../smartptrmode/) (ในโค้ด C++) หรือแอตทริบิวต์ CppWeakPtr (ในโค้ด C# ที่กำลังแปล). หากสองหรือมากกว่าออบเจกต์อ้างอิงถึงกันโดยใช้พอยเตอร์ 'shared' พวกมันจะไม่ถูกลบเลย. หากต้องการสลับประเภทพอยเตอร์ (weak หรือ shared) ระหว่างการทำงาน ให้ใช้เมธอด [System::SmartPtr<T>::set_Mode()](./set_mode/) หรือคลาส [System::DynamicWeakPtr](../dynamicweakptr/). คลาส [SmartPtr](./) ไม่มีเมธอด virtual ใด ๆ. คุณควรสืบทอดคลาสนี้เฉพาะเมื่อคุณกำลังสร้างกลยุทธ์การจัดการหน่วยความจำของคุณเอง. ประเภทนี้เป็นพอยเตอร์เพื่อจัดการการลบของออบเจกต์อื่น. ควรจัดสรรบน stack และส่งต่อให้ฟังก์ชันโดยค่า หรือโดยการอ้างอิงแบบ const.

```cpp
template<class T>class SmartPtr
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของออบเจกต์ที่ถูกชี้. ต้องเป็น [System::Object](../object/) หรือคลาสย่อยของมัน. |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| auto [begin](./begin/)() | ตัวเข้าถึงสำหรับเมธอด [begin()](./begin/) ของคอลเลกชันพื้นฐาน. คอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นประเภทพิเศษที่มีเมธอด [begin()](./begin/). |
| auto [begin](./begin/)() const | ตัวเข้าถึงสำหรับเมธอด [begin()](./begin/) ของคอลเลกชันพื้นฐาน. คอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นประเภทพิเศษที่มีเมธอด [begin()](./begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | แคสต์พอยเตอร์เป็นประเภทของตัวมันเอง. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | แคสต์พอยเตอร์เป็นประเภทฐานโดยใช้ static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | แคสต์พอยเตอร์เป็นประเภทที่สืบทอดโดยใช้ dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | แคสต์พอยเตอร์เป็นประเภทที่สืบทอดโดยใช้ dynamic_cast. |
| auto [cbegin](./cbegin/)() const | ตัวเข้าถึงสำหรับเมธอด [cbegin()](./cbegin/) ของคอลเลกชันพื้นฐาน. คอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นประเภทพิเศษที่มีเมธอด [cbegin()](./cbegin/). |
| auto [cend](./cend/)() const | ตัวเข้าถึงสำหรับเมธอด [cend()](./cend/) ของคอลเลกชันพื้นฐาน. คอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นประเภทพิเศษที่มีเมธอด [cend()](./cend/). |
| [SmartPtr](./)\<Y\> [const_pointer_cast](./const_pointer_cast/)() const | แคสต์พอยเตอร์เป็นประเภทที่แตกต่างโดยใช้ const_cast บนออบเจกต์ที่ชี้. |
| [SmartPtr](./)\<Y\> [dynamic_pointer_cast](./dynamic_pointer_cast/)() const | แคสต์พอยเตอร์เป็นประเภทที่แตกต่างโดยใช้ dynamic_cast บนออบเจกต์ที่ชี้. |
| auto [end](./end/)() | ตัวเข้าถึงสำหรับเมธอด [end()](./end/) ของคอลเลกชันพื้นฐาน. คอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นประเภทพิเศษที่มีเมธอด [end()](./end/). |
| auto [end](./end/)() const | ตัวเข้าถึงสำหรับเมธอด [end()](./end/) ของคอลเลกชันพื้นฐาน. คอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นประเภทพิเศษที่มีเมธอด [end()](./end/). |
| [Pointee_](./pointee_/) * [get](./get/)() const | รับออบเจกต์ที่ถูกชี้. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](./get_mode/)() const | รับโหมดของพอยเตอร์. |
| [Pointee_](./pointee_/) * [get_shared](./get_shared/)() const | รับออบเจกต์ที่ถูกชี้, แต่ตรวจสอบว่าพอยเตอร์อยู่ในโหมด shared. |
| int [get_shared_count](./get_shared_count/)() const | รับจำนวนพอยเตอร์ shared ที่มีต่อออบเจกต์ที่อ้างอิง, รวมถึงพอยเตอร์ปัจจุบัน. ตรวจสอบว่าพอยเตอร์ปัจจุบันอยู่ในโหมด shared. |
| int [GetHashCode](./gethashcode/)() const | เรียก [GetHashCode()](./gethashcode/) บนออบเจกต์ที่ชี้. |
| T * [GetObjectNotNull](./getobjectnotnull/)() const | รับออบเจกต์ที่อ้างอิงอยู่ในขณะนี้ (หากมี) หรือขว้างข้อยกเว้น. |
| [Object](../object/) * [GetObjectOrNull](./getobjectornull/)() const | รับออบเจกต์ที่ชี้ (หากมี) หรือ nullptr. เท่ากับ [get()](./get/). |
| [Object](../object/) * [GetObjectOwner](./getobjectowner/)() const | รับออบเจกต์ที่อ้างอิง. |
| [Pointee_](./pointee_/) * [GetPointer](./getpointer/)() const | รับออบเจ็กต์ที่ชี้ (หากมี) หรือ nullptr. เท่ากับ [get()](./get/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | ตรวจสอบว่าออบเจกต์ที่ชี้เป็นประเภทเฉพาะหรือประเภทลูกของมัน. ทำตามหลักการของ C# 'is'. |
| **bool** [IsAliasingPtr](./isaliasingptr/)() const | ตรวจสอบว่าพอยเตอร์ชี้ไปยังออบเจกต์อื่นที่ไม่ใช่ออบเจกต์ที่เป็นเจ้าของ (ที่สร้างโดยคอนสตรัคเตอร์ aliasing). |
| **bool** [IsShared](./isshared/)() const | ตรวจสอบว่าพอยเตอร์อยู่ในโหมด shared. |
| **bool** [IsWeak](./isweak/)() const | ตรวจสอบว่าพอยเตอร์อยู่ในโหมด weak. |
| explicit  [operator bool](./operator_bool/)() const | ตรวจสอบว่าพอยเตอร์ไม่เป็น null. |
| **bool** [operator!](./operator_not/)() const | ตรวจสอบว่าพอยเตอร์เป็น null. |
| [Pointee_](./pointee_/)\& [operator*](./operator_star/)() const | รับการอ้างอิงไปยังออบเจกต์ที่ชี้. ตรวจสอบว่าพอยเตอร์ไม่เป็น null. |
| [Pointee_](./pointee_/) * [operator->](./operator_minus_greater/)() const | อนุญาตให้เข้าถึงสมาชิกของออบเจกต์ที่อ้างอิง. |
| **bool** [operator<](./operator_less/)(Y *) const | ให้ความหมายการเปรียบเทียบแบบ less สำหรับคลาส [SmartPtr](./). |
| **bool** [operator<](./operator_less/)([SmartPtr](./)\<Y\> const\&) const | ให้ความหมายการเปรียบเทียบแบบ less สำหรับคลาส [SmartPtr](./). |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | มอบหมายแบบย้ายให้กับออบเจ็กต์ [SmartPtr](./). x จะไม่สามารถใช้ได้. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | มอบหมายแบบคัดลอกให้กับออบเจ็กต์ [SmartPtr](./). |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](./)\<Q\>\&) | มอบหมายแบบคัดลอกให้กับออบเจ็กต์ [SmartPtr](./). ทำการแปลงประเภทที่จำเป็น. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([Pointee_](./pointee_/) *) | กำหนดพอยเตอร์ดิบให้กับออบเจ็กต์ [SmartPtr](./). |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | ตั้งค่าพอยเตอร์เป็น nullptr. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | ตรวจสอบว่าพอยเตอร์ชี้ไปที่ nullptr. |
| [SmartPtr_](./smartptr_/) [RemoveAliasing](./removealiasing/)() const | ลบการทำ aliasing (ที่สร้างโดยคอนสตรัคเตอร์ aliasing) จากพอยเตอร์, ทำให้มั่นใจว่ามันจัดการ (หากเป็น shared) หรือทำตาม (หากเป็น weak) กับออบเจ็กต์เดียวกันที่ชี้. |
| void [reset](./reset/)([Pointee_](./pointee_/) *) | ตั้งค่าออบเจ็กต์ที่ชี้. |
| void [reset](./reset/)() | ทำให้พอยเตอร์ชี้ไปที่ nullptr. |
| void [set_Mode](./set_mode/)([SmartPtrMode](../smartptrmode/)) | ตั้งค่าโหมดพอยเตอร์. อาจเปลี่ยนแปลงจำนวนการอ้างอิงของออบเจ็กต์ที่อ้างอิง. |
| void [SetContainedTemplateWeakPtr](./setcontainedtemplateweakptr/)(**uint32_t**) const | เรียกเมธอด SetTemplateWeakPtr() บนออบเจ็กต์ที่ชี้ (หากมี). |
|  [SmartPtr](./smartptr/)([SmartPtrMode](../smartptrmode/)) | สร้างออบเจ็กต์ [SmartPtr](./) ในโหมดที่ต้องการ. |
|  [SmartPtr](./smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | สร้างออบเจ็กต์ [SmartPtr](./) ที่เป็น null-pointer ในโหมดที่ต้องการ. |
|  [SmartPtr](./smartptr/)([Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | สร้าง [SmartPtr](./) ที่ชี้ไปยังออบเจ็กต์ที่ระบุ, หรือแปลงพอยเตอร์ดิบเป็น [SmartPtr](./). |
|  [SmartPtr](./smartptr/)(const [SmartPtr_](./smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | สร้างออบเจ็กต์ [SmartPtr](./) ด้วยการคัดลอก. ทั้งสองพอยเตอร์จะชี้ไปยังออบเจ็กต์เดียวกันหลังจากนั้น. |
|  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | สร้างออบเจ็กต์ [SmartPtr](./) ด้วยการคัดลอก. ทั้งสองพอยเตอร์จะชี้ไปยังออบเจ็กต์เดียวกันหลังจากนั้น. ทำการแปลงประเภทหากอนุญาต. |
|  [SmartPtr](./smartptr/)([SmartPtr_](./smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | สร้างออบเจ็กต์ [SmartPtr](./) ด้วยการย้าย. โดยจริง ๆ จะสลับพอยเตอร์สองตัว หากทั้งสองอยู่ในโหมดเดียวกัน. x อาจใช้ไม่ได้หลังจากเรียก. |
| explicit  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | แปลงประเภทของอาร์เรย์ที่อ้างอิงโดยสร้างอาร์เรย์ใหม่ที่เป็นประเภทต่างกัน. มีประโยชน์เมื่อใน C# มีการแคสต์ประเภทอาร์เรย์ที่ไม่รองรับใน C++. |
| explicit  [SmartPtr](./smartptr/)(const Y\&) | กำหนดค่าเริ่มต้นให้กับอาร์เรย์เปล่า. ใช้สำหรับแปลโครงสร้างโค้ดบางส่วนใน C#. |
|  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<P\>\&, [Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | สร้าง [SmartPtr](./) ที่แชร์ข้อมูลความเป็นเจ้าของกับค่าเริ่มต้นของ ptr, แต่ถือพอยเตอร์ p ที่ไม่เกี่ยวข้องและไม่มีการจัดการ. |
| [SmartPtr](./)\<Y\> [static_pointer_cast](./static_pointer_cast/)() const | แคสต์พอยเตอร์เป็นประเภทที่แตกต่างโดยใช้ static_cast บนออบเจ็กต์ที่ชี้. |
| [SmartPtr](./)\<[Object](../object/)\> [ToObjectPtr](./toobjectptr/)() const | แปลงพอยเตอร์ประเภทใด ๆ ให้เป็นพอยเตอร์ไปยัง [Object](../object/). ไม่จำเป็นต้องให้ประเภท Pointee_ สมบูรณ์. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | ทางลัดเพื่อรับออบเจ็กต์ [System::TypeInfo](../typeinfo/) สำหรับประเภท Pointee_. |
|  [~SmartPtr](./~smartptr/)() | ทำลายออบเจ็กต์ [SmartPtr](./). หากต้องการ จะลดตัวนับการอ้างอิงของออบเจ็กต์ที่ชี้และลบออบเจ็กต์นั้น. |

## ประเภทนิยาม

| ประเภทนิยาม | คำอธิบาย |
| --- | --- |
| [Pointee_](./pointee_/) | ประเภทที่ชี้. |
| [SmartPtr_](./smartptr_/) | ประเภทพอยเตอร์อัจฉริยะที่กำหนดเฉพาะ. |
| [ArrayType](./arraytype/) | เหมือนกับ Pointee_, หากเป็นการกำหนดเฉพาะของ [System::Array](../array/), มิฉะนั้นเป็น void. |
| [ValueType](./valuetype/) | ประเภทการจัดเก็บของอาร์เรย์ที่ชี้. มีความหมายเฉพาะเมื่อ T เป็นการกำหนดเฉพาะของ [System::Array](../array/). |

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)