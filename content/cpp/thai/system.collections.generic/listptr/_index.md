---
title: ListPtr
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: พอยน์เตอร์รายการพร้อมตัวดำเนินการเข้าถึง. ชนิดนี้เป็นพอยน์เตอร์ที่ใช้จัดการการลบของอ็อบเจ็กต์อื่น. ควรจัดสรรบนสแตกและส่งต่อให้ฟังก์ชันโดยใช้ค่าโดยตรงหรืออ้างอิงคงที่.
type: docs
weight: 456
url: /th/system.collections.generic/listptr/
---
## ListPtr คลาส


[List](../list/) pointer with access operators. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<typename T>class ListPtr : public System::SmartPtr<List<T>>
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | ตัวเข้าถึงสำหรับเมธอด [begin()](../../system/smartptr/begin/) ของคอลเลกชันที่อยู่ภายใต้. คอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นชนิดพิเศษที่มีเมธอด [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | ตัวเข้าถึงสำหรับเมธอด [begin()](../../system/smartptr/begin/) ของคอลเลกชันที่อยู่ภายใต้. คอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นชนิดพิเศษที่มีเมธอด [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | แคสต์พอยน์เตอร์เป็นประเภทของมันเอง. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | แคสต์พอยน์เตอร์เป็นประเภทฐานโดยใช้ static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | แคสต์พอยน์เตอร์เป็นประเภทที่สืบทอดโดยใช้ dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | แคสต์พอยน์เตอร์เป็นประเภทที่สืบทอดโดยใช้ dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | ตัวเข้าถึงสำหรับเมธอด [cbegin()](../../system/smartptr/cbegin/) ของคอลเลกชันที่อยู่ภายใต้. คอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นชนิดพิเศษที่มีเมธอด [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | ตัวเข้าถึงสำหรับเมธอด [cend()](../../system/smartptr/cend/) ของคอลเลกชันที่อยู่ภายใต้. คอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นชนิดพิเศษที่มีเมธอด [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | แคสต์พอยน์เตอร์เป็นประเภทอื่นโดยใช้ const_cast บนอ็อบเจ็กต์ที่ชี้. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | แคสต์พอยน์เตอร์เป็นประเภทอื่นโดยใช้ dynamic_cast บนอ็อบเจ็กต์ที่ชี้. |
| auto [end](../../system/smartptr/end/)() | ตัวเข้าถึงสำหรับเมธอด [end()](../../system/smartptr/end/) ของคอลเลกชันที่อยู่ภายใต้. คอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นชนิดพิเศษที่มีเมธอด [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | ตัวเข้าถึงสำหรับเมธอด [end()](../../system/smartptr/end/) ของคอลเลกชันที่อยู่ภายใต้. คอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นชนิดพิเศษที่มีเมธอด [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | ดึงอ็อบเจ็กต์ที่ชี้. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | ดึงโหมดพอยน์เตอร์. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | ดึงอ็อบเจ็กต์ที่ชี้ แต่ตรวจสอบว่าพอยน์เตอร์อยู่ในโหมดแชร์. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | รับจำนวนพอยน์เตอร์ที่แชร์ที่อ้างอิงถึงอ็อบเจ็กต์รวมถึงพอยน์เตอร์ปัจจุบัน ตรวจสอบว่าพอยน์เตอร์ปัจจุบันอยู่ในโหมดแชร์. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | เรียก [GetHashCode()](../../system/smartptr/gethashcode/) บนอ็อบเจ็กต์ที่ชี้. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | ดึงอ็อบเจ็กต์ที่อ้างอิงอยู่ในขณะนี้ (ถ้ามี) หรือโยนข้อยกเว้น. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | ดึงอ็อบเจ็กต์ที่ชี้ (ถ้ามี) หรือ nullptr. เช่นเดียวกับ [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | ดึงอ็อบเจ็กต์ที่อ้างอิง. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | ดึงอ็อบเจ็กต์ที่ชี้ (ถ้ามี) หรือ nullptr. เช่นเดียวกับ [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์ที่ชี้เป็นประเภทเฉพาะหรือประเภทย่อยของมัน ตามพฤติกรรมของ C# 'is'. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | ตรวจสอบว่าพอยน์เตอร์ชี้ไปยังอ็อบเจ็กต์อื่นที่ไม่ใช่ที่เป็นเจ้าของ (ที่สร้างโดยคอนสตรัคเตอร์ aliasing). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | ตรวจสอบว่าพอยน์เตอร์อยู่ในโหมดแชร์. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | ตรวจสอบว่าพอยน์เตอร์อยู่ในโหมด weak. |
| [ListPtr](./listptr/)(std::nullptr_t) | กำหนดค่าเริ่มต้นเป็น null-pointer. |
| [ListPtr](./listptr/)(const [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\>\&) | กำหนดค่าเริ่มต้นพอยน์เตอร์ไปยังรายการที่ระบุ. |
| explicit [operator bool](../../system/smartptr/operator_bool/)() const | ตรวจสอบว่าพอยน์เตอร์ไม่เป็น null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | ตรวจสอบว่าพอยน์เตอร์เป็น null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | ดึงอ้างอิงไปยังอ็อบเจ็กต์ที่ชี้ ตรวจสอบว่าพอยน์เตอร์ไม่เป็น null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | อนุญาตให้เข้าถึงสมาชิกของอ็อบเจ็กต์ที่อ้างอิง. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | ให้ความหมายของการเปรียบเทียบแบบน้อยกว่า สำหรับคลาส [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | ให้ความหมายของการเปรียบเทียบแบบน้อยกว่า สำหรับคลาส [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | ย้ายการกำหนดค่าให้กับอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/). x จะไม่ใช้ได้. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | กำหนดค่าคัดลอกให้กับอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | กำหนดค่าคัดลอกให้กับอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/). ทำการแปลงประเภทที่จำเป็น. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | กำหนดพอยน์เตอร์ดิบให้กับอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | ตั้งค่าพอยน์เตอร์เป็น nullptr. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | ตรวจสอบว่าพอยน์เตอร์ [List](../list/) เป็น null. |
| std::vector\<T\>::reference [operator[]](./operator[]/)(int) | ตัวเข้าถึง. |
| std::vector\<T\>::const_reference [operator[]](./operator[]/)(int) const | ตัวเข้าถึง. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | ลบการทำ aliasing (ที่สร้างโดยคอนสตรัคเตอร์ aliasing) จากพอยน์เตอร์ ทำให้แน่ใจว่ามันจัดการ (ถ้าแชร์) หรือทำการติดตาม (ถ้า weak) อ็อบเจ็กต์เดียวกันที่ชี้. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | ตั้งค่าอ็อบเจ็กต์ที่ชี้. |
| void [reset](../../system/smartptr/reset/)() | ทำให้พอยน์เตอร์ชี้ไปที่ nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | ตั้งค่าโหมดพอยน์เตอร์ อาจเปลี่ยนจำนวนการอ้างอิงของอ็อบเจ็กต์ที่อ้างอิง. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | เรียกเมธอด SetTemplateWeakPtr() บนอ็อบเจ็กต์ที่ชี้ (ถ้ามี). |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | สร้างอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/) ตามโหมดที่ต้องการ. |
| [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | สร้างอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/) แบบ null-pointer ตามโหมดที่ต้องการ. |
| [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | สร้าง [SmartPtr](../../system/smartptr/) ชี้ไปยังอ็อบเจ็กต์ที่ระบุ หรือแปลงพอยน์เตอร์ดิบเป็น [SmartPtr](../../system/smartptr/). |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | สร้างอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/) ด้วยการคัดลอก ทั้งสองพอยน์เตอร์จะชี้ไปยังอ็อบเจ็กต์เดียวกันหลังจากนั้น. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | สร้างอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/) ด้วยการคัดลอก ทั้งสองพอยน์เตอร์จะชี้ไปยังอ็อบเจ็กต์เดียวกันหลังจากนั้น ทำการแปลงประเภทหากอนุญาต. |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | สร้างอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/) ด้วยการเคลื่อนย้าย ทำการสลับพอยน์เตอร์สองตัวหากทั้งคู่อยู่ในโหมดเดียวกัน x อาจไม่สามารถใช้ได้หลังจากเรียก. |
| explicit [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | แปลงประเภทของอาร์เรย์ที่อ้างอิงโดยการสร้างอาร์เรย์ใหม่ที่มีประเภทต่างกัน มีประโยชน์เมื่อใน C# มีการแคสต์ประเภทของอาร์เรย์ซึ่งไม่รองรับใน C++. |
| explicit [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | กำหนดค่าเริ่มต้นอาร์เรย์ว่าง ใช้ในการแปลงโครงสร้างโค้ดบางส่วนของ C#. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | สร้าง [SmartPtr](../../system/smartptr/) ที่แชร์ข้อมูลความเป็นเจ้าของกับค่าเริ่มต้นของ ptr แต่ถือพอยน์เตอร์ p ที่ไม่มีความสัมพันธ์และไม่ได้จัดการ. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | แคสต์พอยน์เตอร์เป็นประเภทอื่นโดยใช้ static_cast บนอ็อบเจ็กต์ที่ชี้. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | แปลงพอยน์เตอร์ใด ๆ เป็นพอยน์เตอร์ไปยัง [Object](../../system/object/) ไม่จำเป็นต้องให้ประเภท Pointee_ สมบูรณ์. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | ทางลัดเพื่อรับอ็อบเจ็กต์ [System::TypeInfo](../../system/typeinfo/) สำหรับประเภท Pointee_. |
| [~SmartPtr](../../system/smartptr/~smartptr/)() | ทำลายอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/) หากจำเป็นจะลดตัวนับการอ้างอิงของอ็อบเจ็กต์ที่ชี้และลบอ็อบเจ็กต์. |

## ดูเพิ่มเติม

* คลาส [SmartPtr](../../system/smartptr/)
* เนมสเปซ [System::Collections::Generic](../)
* ไลบรารี [Aspose.Slides](../../)