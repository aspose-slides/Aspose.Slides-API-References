---
title: HashSetPtr
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: พอยน์เตอร์เพื่อเก็บการอ้างอิง HashSet. ประเภทนี้เป็นพอยน์เตอร์ที่จัดการการลบของอ็อบเจ็กต์อื่น. ควรจัดสรรบนสแตกและส่งต่อให้ฟังก์ชันโดยค่า หรือโดยการอ้างอิงแบบคอนสท์.
type: docs
weight: 235
url: /th/system.collections.generic/hashsetptr/
---
## HashSetPtr คลาส


Pointer to keep [HashSet](../hashset/) references. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<typename T>class HashSetPtr : public System::SmartPtr<HashSet<T>>
```

## เมธอด

| Method | Description |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | ตัวเข้าถึงสำหรับเมธอด [begin()](../../system/smartptr/begin/) ของคอลเลกชันที่อยู่ภายใต้. จะคอมไพล์เท่านั้นหาก SmartPtr_ เป็นประเภทพิเศษที่มีเมธอด [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | ตัวเข้าถึงสำหรับเมธอด [begin()](../../system/smartptr/begin/) ของคอลเลกชันที่อยู่ภายใต้. จะคอมไพล์เท่านั้นหาก SmartPtr_ เป็นประเภทพิเศษที่มีเมธอด [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | แคสต์พอยน์เตอร์เป็นประเภทของมันเอง. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | แคสต์พอยน์เตอร์เป็นประเภทฐานโดยใช้ static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | แคสต์พอยน์เตอร์เป็นประเภทที่สืบทอดโดยใช้ dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | แคสต์พอยน์เตอร์เป็นประเภทที่สืบทอดโดยใช้ dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | ตัวเข้าถึงสำหรับเมธอด [cbegin()](../../system/smartptr/cbegin/) ของคอลเลกชันที่อยู่ภายใต้. จะคอมไพล์เท่านั้นหาก SmartPtr_ เป็นประเภทพิเศษที่มีเมธอด [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | ตัวเข้าถึงสำหรับเมธอด [cend()](../../system/smartptr/cend/) ของคอลเลกชันที่อยู่ภายใต้. จะคอมไพล์เท่านั้นหาก SmartPtr_ เป็นประเภทพิเศษที่มีเมธอด [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | แคสต์พอยน์เตอร์เป็นประเภทต่าง ๆ โดยใช้ const_cast กับอ็อบเจ็กต์ที่ชี้. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | แคสต์พอยน์เตอร์เป็นประเภทต่าง ๆ โดยใช้ dynamic_cast กับอ็อบเจ็กต์ที่ชี้. |
| auto [end](../../system/smartptr/end/)() | ตัวเข้าถึงสำหรับเมธอด [end()](../../system/smartptr/end/) ของคอลเลกชันที่อยู่ภายใต้. จะคอมไพล์เท่านั้นหาก SmartPtr_ เป็นประเภทพิเศษที่มีเมธอด [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | ตัวเข้าถึงสำหรับเมธอด [end()](../../system/smartptr/end/) ของคอลเลกชันที่อยู่ภายใต้. จะคอมไพล์เท่านั้นหาก SmartPtr_ เป็นประเภทพิเศษที่มีเมธอด [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | รับอ็อบเจ็กต์ที่ชี้. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | รับโหมดพอยน์เตอร์. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | รับอ็อบเจ็กต์ที่ชี้ แต่ตรวจสอบว่าพอยน์เตอร์อยู่ในโหมด shared. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | รับจำนวนพอยน์เตอร์แบบ shared ที่อ้างอิงอ็อบเจ็กต์นี้ รวมถึงตัวปัจจุบันด้วย. ตรวจสอบว่าพอยน์เตอร์ปัจจุบันอยู่ในโหมด shared. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | เรียก [GetHashCode()](../../system/smartptr/gethashcode/) บนอ็อบเจ็กต์ที่ชี้. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | รับอ็อบเจ็กต์ที่อ้างอิงในขณะนี้ (ถ้ามี) หรือขว้างข้อผิดพลาด. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | รับอ็อบเจ็กต์ที่ชี้ (ถ้ามี) หรือ nullptr. เทียบกับ [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | รับอ็อบเจ็กต์ที่อ้างอิง. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | รับอ็อบเจ็กต์ที่ชี้ (ถ้ามี) หรือ nullptr. เทียบกับ [get()](../../system/smartptr/get/). |
|  [HashSetPtr](./hashsetptr/)() | คอนสตรัคเตอร์พอยน์เตอร์เป็นค่า null. |
|  [HashSetPtr](./hashsetptr/)(const [SharedPtr](../../system/sharedptr/)\<[HashSet](../hashset/)\<T\>\>\&) | คอนสตรัคเตอร์สำเนา. |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์ที่ชี้เป็นประเภทเฉพาะหรือประเภทลูกของมัน ตามหลักการของ C# 'is'. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | ตรวจสอบว่าพอยน์เตอร์ชี้ไปยังอ็อบเจ็กต์อื่นที่ไม่ได้เป็นของมัน (สร้างจากคอนสตรัคเตอร์ aliasing). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | ตรวจสอบว่าพอยน์เตอร์อยู่ในโหมด shared. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | ตรวจสอบว่าพอยน์เตอร์อยู่ในโหมด weak. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | ตรวจสอบว่าพอยน์เตอร์ไม่เป็น null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | ตรวจสอบว่าพอยน์เตอร์เป็น null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | รับอ้างอิงของอ็อบเจ็กต์ที่ชี้ ตรวจสอบว่าพอยน์เตอร์ไม่เป็น null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | อนุญาตให้เข้าถึงสมาชิกของอ็อบเจ็กต์ที่อ้างอิง. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | ให้ความหมายการเปรียบเทียบน้อยกว่า (less) สำหรับคลาส [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | ให้ความหมายการเปรียบเทียบน้อยกว่า (less) สำหรับคลาส [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | ย้ายกำหนดให้กับอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/). x จะไม่สามารถใช้ได้. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | คัดลอกกำหนดให้กับอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | คัดลอกกำหนดให้กับอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/). ทำการแปลงประเภทที่จำเป็น. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | กำหนดพอยน์เตอร์ดิบให้กับอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | ตั้งค่าพอยน์เตอร์เป็น nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | ตรวจสอบว่าพอยน์เตอร์ชี้ไปที่ nullptr. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | ลบ aliasing (ที่สร้างโดยคอนสตรัคเตอร์ aliasing) จากพอยน์เตอร์ ทำให้แน่ใจว่ามันจัดการ (หาก shared) หรือ ติดตาม (หาก weak) อ็อบเจ็กต์เดียวกันที่มันชี้. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | ตั้งค่าอ็อบเจ็กต์ที่ชี้. |
| void [reset](../../system/smartptr/reset/)() | ทำให้พอยน์เตอร์ชี้ไปที่ nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | ตั้งค่าโหมดพอยน์เตอร์. อาจเปลี่ยนจำนวนอ้างอิงของอ็อบเจ็กต์ที่อ้างอิง. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | เรียกเมธอด SetTemplateWeakPtr() บนอ็อบเจ็กต์ที่ชี้ (ถ้ามี). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | สร้างอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/) ตามโหมดที่ต้องการ. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | สร้างอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/) แบบ null-pointer ตามโหมดที่ต้องการ. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | สร้าง [SmartPtr](../../system/smartptr/) ที่ชี้ไปยังอ็อบเจ็กต์ที่ระบุ หรือแปลงพอยน์เตอร์ดิบเป็น [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | คัดลอกสร้างอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/). พอยน์เตอร์ทั้งสองจะชี้ไปยังอ็อบเจ็กต์เดียวกันหลังจากนั้น. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | คัดลอกสร้างอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/). พอยน์เตอร์ทั้งสองจะชี้ไปยังอ็อบเจ็กต์เดียวกันหลังจากนั้น. ทำการแปลงประเภทหากอนุญาต. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | ย้ายสร้างอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/). โดยทำการสลับพอยน์เตอร์สองตัว หากทั้งสองอยู่ในโหมดเดียวกัน. x อาจไม่สามารถใช้ได้หลังจากเรียก. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | แปลงประเภทของอาร์เรย์ที่อ้างอิงโดยสร้างอาร์เรย์ใหม่ของประเภทที่ต่างออกไป. มีประโยชน์เมื่อใน C# มีการแคสต์อาร์เรย์ที่ไม่รองรับใน C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | กำหนดค่าอาร์เรย์เปล่า. ใช้เพื่อแปลบางโครงสร้างโค้ด C#. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | สร้าง [SmartPtr](../../system/smartptr/) ที่แชร์ข้อมูลการเป็นเจ้าของกับค่าเริ่มต้นของ ptr, แต่ถือพอยน์เตอร์ p ที่ไม่มีความสัมพันธ์และไม่ได้จัดการ. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | แคสต์พอยน์เตอร์เป็นประเภทต่าง ๆ โดยใช้ static_cast กับอ็อบเจ็กต์ที่ชี้. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | แปลงประเภทพอยน์เตอร์ใด ๆ ให้เป็นพอยน์เตอร์ไปยัง [Object](../../system/object/). ไม่จำเป็นต้องให้ประเภท Pointee_ สมบูรณ์. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | ทางลัดเพื่อรับอ็อบเจ็กต์ [System::TypeInfo](../../system/typeinfo/) สำหรับประเภท Pointee_. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | ทำลายอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/). หากจำเป็นจะลดตัวนับอ้างอิงของอ็อบเจ็กต์ที่ชี้และลบอ็อบเจ็กต์. |

## ดูเพิ่มเติม

* คลาส [SmartPtr](../../system/smartptr/)
* เนมสเปซ [System::Collections::Generic](../)
* ไลบรารี [Aspose.Slides](../../)