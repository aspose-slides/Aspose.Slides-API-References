---
title: SortedSetPtr
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตัวชี้เพื่อเก็บการอ้างอิงของ SortedSet. ชนิดนี้เป็นตัวชี้เพื่อจัดการการลบของอ็อบเจ็กต์อื่น. ควรจัดสรรบนสแตกและส่งต่อไปยังฟังก์ชันโดยค่าหรือโดยการอ้างอิงคงที่.
type: docs
weight: 586
url: /th/system.collections.generic/sortedsetptr/
---
## SortedSetPtr คลาส

ตัวชี้เพื่อเก็บการอ้างอิง [SortedSet](../sortedset/). ประเภทนี้เป็นตัวชี้เพื่อจัดการการลบของอ็อบเจ็กต์อื่น. ควรจัดสรรบนสเท๊กและส่งต่อไปยังฟังก์ชันโดยค่าหรือโดยการอ้างอิงคงที่.

```cpp
template<typename T>class SortedSetPtr : public System::SmartPtr<SortedSet<T>>
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | ตัวเข้าถึงสำหรับเมธอด [begin()](../../system/smartptr/begin/) ของคอลเลกชันที่อยู่ภายใต้. คอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นชนิดพิเศษที่มีเมธอด [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | ตัวเข้าถึงสำหรับเมธอด [begin()](../../system/smartptr/begin/) ของคอลเลกชันที่อยู่ภายใต้. คอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นชนิดพิเศษที่มีเมธอด [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | แคสต์ตัวชี้เป็นประเภทของมันเอง. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | แคสต์ตัวชี้เป็นชนิดฐานโดยใช้ static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | แคสต์ตัวชี้เป็นชนิดที่สืบทอดโดยใช้ dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | แคสต์ตัวชี้เป็นชนิดที่สืบทอดโดยใช้ dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | ตัวเข้าถึงสำหรับเมธอด [cbegin()](../../system/smartptr/cbegin/) ของคอลเลกชันที่อยู่ภายใต้. คอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นชนิดพิเศษที่มีเมธอด [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | ตัวเข้าถึงสำหรับเมธอด [cend()](../../system/smartptr/cend/) ของคอลเลกชันที่อยู่ภายใต้. คอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นชนิดพิเศษที่มีเมธอด [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | แคสต์ตัวชี้เป็นประเภทอื่นโดยใช้ const_cast กับอ็อบเจ็กต์ที่ชี้. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | แคสต์ตัวชี้เป็นประเภทอื่นโดยใช้ dynamic_cast กับอ็อบเจ็กต์ที่ชี้. |
| auto [end](../../system/smartptr/end/)() | ตัวเข้าถึงสำหรับเมธอด [end()](../../system/smartptr/end/) ของคอลเลกชันที่อยู่ภายใต้. คอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นชนิดพิเศษที่มีเมธอด [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | ตัวเข้าถึงสำหรับเมธอด [end()](../../system/smartptr/end/) ของคอลเลกชันที่อยู่ภายใต้. คอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นชนิดพิเศษที่มีเมธอด [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | ดึงอ็อบเจ็กต์ที่ชี้. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | ดึงโหมดของตัวชี้. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | ดึงอ็อบเจ็กต์ที่ชี้, แต่ตรวจสอบว่าตัวชี้อยู่ในโหมดแชร์. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | ดึงจำนวนของตัวชี้แชร์ที่มีอยู่สำหรับอ็อบเจ็กต์ที่อ้างอิง, รวมถึงตัวชี้ปัจจุบัน. ตรวจสอบว่าตัวชี้ปัจจุบันอยู่ในโหมดแชร์. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | เรียก [GetHashCode()](../../system/smartptr/gethashcode/) บนอ็อบเจ็กต์ที่ชี้. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | ดึงอ็อบเจ็กต์ที่อ้างอิงอยู่ในปัจจุบัน (ถ้ามี) หรือโยนข้อยกเว้น. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | ดึงอ็อบเจ็กต์ที่ชี้ (ถ้ามี) หรือ nullptr. เหมือนกับ [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | ดึงอ็อบเจ็กต์ที่อ้างอิง. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | ดึงอ็อบเจ็กต์ที่ชี้ (ถ้ามี) หรือ nullptr. เหมือนกับ [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่ามีอ็อบเจ็กต์ที่ชี้เป็นประเภทเฉพาะหรือประเภทลูก. ปฏิบัติตาม semantics ของ C# 'is'. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | ตรวจสอบว่าตัวชี้ชี้ไปยังอ็อบเจ็กต์อื่นที่ไม่ใช่ที่เป็นเจ้าของ (ที่สร้างโดยคอนสตรัคเตอร์ aliasing). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | ตรวจสอบว่าตัวชี้อยู่ในโหมดแชร์. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | ตรวจสอบว่าตัวชี้อยู่ในโหมด weak. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | ตรวจสอบว่าตัวชี้ไม่ได้เป็น null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | ตรวจสอบว่าตัวชี้เป็น null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | ดึงอ้างอิงของอ็อบเจ็กต์ที่ชี้. ตรวจสอบว่าตัวชี้ไม่เป็น null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | อนุญาตให้เข้าถึงสมาชิกของอ็อบเจ็กต์ที่อ้างอิง. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | ให้ semantics การเปรียบเทียบน้อยกว่า สำหรับคลาส [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | ให้ semantics การเปรียบเทียบน้อยกว่า สำหรับคลาส [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | กำหนดค่าแบบย้ายให้กับอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/). x จะไม่สามารถใช้ได้. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | กำหนดค่าคัดลอกให้กับอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | กำหนดค่าคัดลอกให้กับอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/). ทำการแปลงประเภทที่จำเป็น. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | กำหนดตัวชี้ดิบให้กับอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | ตั้งค่าตัวชี้เป็น nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | ตรวจสอบว่าตัวชี้ชี้ไปที่ nullptr. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | ลบการอ้างถึงแบบ aliasing (ที่สร้างโดยคอนสตรัคเตอร์ aliasing) ออกจากตัวชี้, ทำให้แน่ใจว่ามันจัดการ (ถ้าแชร์) หรือทำการติดตาม (ถ้า weak) อ็อบเจ็กต์เดียวกันที่ชี้. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | ตั้งค่าอ็อบเจ็กต์ที่ชี้. |
| void [reset](../../system/smartptr/reset/)() | ทำให้ตัวชี้ชี้ไปที่ nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | ตั้งค่าโหมดของตัวชี้. อาจเปลี่ยนจำนวนการอ้างอิงของอ็อบเจ็กต์ที่อ้างอิง. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | เรียกเมธอด SetTemplateWeakPtr() บนอ็อบเจ็กต์ที่ชี้ (ถ้ามี). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | สร้างอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/) ในโหมดที่ต้องการ. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | สร้างอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/) ที่เป็น null-pointer ในโหมดที่ต้องการ. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | สร้าง [SmartPtr](../../system/smartptr/) ชี้ไปยังอ็อบเจ็กต์ที่ระบุ, หรือแปลงตัวชี้ดิบเป็น [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | คัดลอกสร้างอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/). ทั้งสองตัวชี้จะชี้ไปยังอ็อบเจ็กต์เดียวกันหลังจากนั้น. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | คัดลอกสร้างอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/). ทั้งสองตัวชี้จะชี้ไปยังอ็อบเจ็กต์เดียวกันหลังจากนั้น. ทำการแปลงประเภทหากอนุญาต. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | ย้ายสร้างอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/). โดยหลักการสลับสองตัวชี้ถ้าทั้งคู่อยู่ในโหมดเดียวกัน. x อาจใช้งไม่ได้หลังจากเรียก. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | แปลงประเภทของอาร์เรย์ที่อ้างอิงโดยสร้างอาร์เรย์ใหม่ของประเภทที่ต่างกัน. มีประโยชน์หากใน C# มีการแคสต์ประเภทอาร์เรย์ที่ไม่ได้รับการสนับสนุนใน C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | กำหนดค่าอาร์เรย์เปล่า. ใช้เพื่อแปลงโครงสร้างโค้ด C# บางส่วน. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | สร้าง [SmartPtr](../../system/smartptr/) ที่แชร์ข้อมูลการเป็นเจ้าของกับค่าเริ่มต้นของ ptr, แต่ถือ pointer p ที่ไม่เกี่ยวข้องและไม่ได้จัดการ. |
|  [SortedSetPtr](./sortedsetptr/)() | คอนสตรัคเตอร์ตัวชี้ null. |
|  [SortedSetPtr](./sortedsetptr/)(const [SharedPtr](../../system/sharedptr/)\<[SortedSet](../sortedset/)\<T\>\>\&) | คอนสตรัคเตอร์คัดลอก. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | แคสต์ตัวชี้เป็นประเภทอื่นโดยใช้ static_cast กับอ็อบเจ็กต์ที่ชี้. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | แปลงประเภทตัวชี้ใด ๆ ให้เป็นตัวชี้ไปยัง [Object](../../system/object/). ไม่จำเป็นต้องให้ประเภท Pointee_ สมบูรณ์. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | ทางลัดเพื่อรับอ็อบเจ็กต์ [System::TypeInfo](../../system/typeinfo/) สำหรับประเภท Pointee_. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | ทำลายอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/). หากจำเป็นจะลดคานับการอ้างอิงของอ็อบเจ็กต์ที่ชี้และลบอ็อบเจ็กต์. |

## ดูเพิ่มเติม

* คลาส [SmartPtr](../../system/smartptr/)
* เนมสเปซ [System::Collections::Generic](../)
* ไลบรารี [Aspose.Slides](../../)