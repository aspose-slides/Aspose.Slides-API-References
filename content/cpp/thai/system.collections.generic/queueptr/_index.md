---
title: QueuePtr
second_title: Aspose.Slides สำหรับ API ของ C++
description: ตัวชี้คิว. ชนิดนี้เป็นตัวชี้ที่ใช้จัดการการลบของวัตถุอื่น. ควรจัดสรรบนสแต็กและส่งไปยังฟังก์ชันโดยค่าหรือโดยการอ้างอิงแบบคอนสท์.
type: docs
weight: 482
url: /th/system.collections.generic/queueptr/
---
## QueuePtr คลาส

[Queue](../queue/) ตัวชี้. ชนิดนี้เป็นตัวชี้ที่ใช้จัดการการลบของวัตถุอื่น. ควรได้รับการจัดสรรบนสแตกและส่งไปยังฟังก์ชันโดยค่าหรือโดยการอ้างอิงแบบคอนสท์.

```cpp
template<typename T>class QueuePtr : public System::SmartPtr<Queue<T>>
```

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | ตัวเข้าถึงสำหรับเมธอด [begin()](../../system/smartptr/begin/) ของคอลเลกชันพื้นฐาน. คอมไพล์ได้เท่านั้นหาก SmartPtr_ เป็นชนิดพิเศษที่มีเมธอด [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | ตัวเข้าถึงสำหรับเมธอด [begin()](../../system/smartptr/begin/) ของคอลเลกชันพื้นฐาน. คอมไพล์ได้เท่านั้นหาก SmartPtr_ เป็นชนิดพิเศษที่มีเมธอด [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | แปลงตัวชี้เป็นประเภทของมันเอง. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | แปลงตัวชี้เป็นประเภทฐานโดยใช้ static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | แปลงตัวชี้เป็นประเภทที่สืบทอดโดยใช้ dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | แปลงตัวชี้เป็นประเภทที่สืบทอดโดยใช้ dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | ตัวเข้าถึงสำหรับเมธอด [cbegin()](../../system/smartptr/cbegin/) ของคอลเลกชันพื้นฐาน. คอมไพล์ได้เท่านั้นหาก SmartPtr_ เป็นชนิดพิเศษที่มีเมธอด [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | ตัวเข้าถึงสำหรับเมธอด [cend()](../../system/smartptr/cend/) ของคอลเลกชันพื้นฐาน. คอมไพล์ได้เท่านั้นหาก SmartPtr_ เป็นชนิดพิเศษที่มีเมธอด [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | แปลงตัวชี้เป็นประเภทต่างโดยใช้ const_cast กับวัตถุที่ชี้. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | แปลงตัวชี้เป็นประเภทต่างโดยใช้ dynamic_cast กับวัตถุที่ชี้. |
| auto [end](../../system/smartptr/end/)() | ตัวเข้าถึงสำหรับเมธอด [end()](../../system/smartptr/end/) ของคอลเลกชันพื้นฐาน. คอมไพล์ได้เท่านั้นหาก SmartPtr_ เป็นชนิดพิเศษที่มีเมธอด [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | ตัวเข้าถึงสำหรับเมธอด [end()](../../system/smartptr/end/) ของคอลเลกชันพื้นฐาน. คอมไพล์ได้เท่านั้นหาก SmartPtr_ เป็นชนิดพิเศษที่มีเมธอด [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | รับวัตถุที่ถูกชี้. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | รับโหมดของตัวชี้. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | รับวัตถุที่ถูกชี้, แต่ตรวจสอบว่าตัวชี้อยู่ในโหมดแชร์. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | รับจำนวนตัวชี้แบบแชร์ที่อ้างอิงวัตถุ รวมถึงตัวปัจจุบัน. ตรวจสอบว่าตัวชี้ปัจจุบันอยู่ในโหมดแชร์. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | เรียก [GetHashCode()](../../system/smartptr/gethashcode/) บนวัตถุที่ชี้. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | รับวัตถุที่อ้างอิงอยู่ในขณะนี้ (ถ้ามี) หรือโยนข้อยกเว้น. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | รับวัตถุที่ชี้ (ถ้ามี) หรือ nullptr. เทียบเท่ากับ [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | รับวัตถุที่อ้างอิง. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | รับวัตถุที่ชี้ (ถ้ามี) หรือ nullptr. เทียบเท่ากับ [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุที่ชี้เป็นประเภทเฉพาะหรือประเภทลูกของมัน. ปฏิบัติตาม semantics ของ C# 'is'. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | ตรวจสอบว่าตัวชี้ชี้ไปยังวัตถุอื่นที่ไม่ใช่วัตถุที่เป็นเจ้าของ (สร้างโดยคอนสตรัคเตอร์แบบ aliasing). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | ตรวจสอบว่าตัวชี้อยู่ในโหมดแชร์. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | ตรวจสอบว่าตัวชี้อยู่ในโหมดอ่อน. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | ตรวจสอบว่าตัวชี้ไม่เป็น null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | ตรวจสอบว่าตัวชี้เป็น null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | รับอ้างอิงไปยังวัตถุที่ชี้. ตรวจสอบว่าตัวชี้ไม่เป็น null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | อนุญาตให้เข้าถึงสมาชิกของวัตถุที่อ้างอิง. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | ให้ semantics การเปรียบเทียบแบบ less สำหรับคลาส [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | ให้ semantics การเปรียบเทียบแบบ less สำหรับคลาส [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | ทำการมอบหมายแบบย้ายให้กับอ็อบเจกต์ [SmartPtr](../../system/smartptr/). x จะไม่สามารถใช้ได้. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | ทำการคัดลอกมอบหมายให้กับอ็อบเจกต์ [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | ทำการคัดลอกมอบหมายให้กับอ็อบเจกต์ [SmartPtr](../../system/smartptr/). ทำการแปลงประเภทตามที่ต้องการ. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | มอบหมายตัวชี้ดิบให้กับอ็อบเจกต์ [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | ตั้งค่าตัวชี้เป็น nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | ตรวจสอบว่าตัวชี้ชี้ไปที่ nullptr. |
|  [QueuePtr](./queueptr/)() | สร้างตัวชี้ null. |
|  [QueuePtr](./queueptr/)(const [SharedPtr](../../system/sharedptr/)\<[Queue](../queue/)\<T\>\>\&) | สร้างตัวชี้ไปยังคิวเฉพาะ. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | ลบการ aliasing (สร้างโดยคอนสตรัคเตอร์ aliasing) จากตัวชี้, ทำให้แน่ใจว่ามันจัดการ (ถ้าเป็น shared) หรือบันทึก (ถ้าเป็น weak) วัตถุเดียวกันที่มันชี้. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | ตั้งค่าวัตถุที่ชี้. |
| void [reset](../../system/smartptr/reset/)() | ทำให้ตัวชี้ชี้ไปที่ nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | ตั้งค่าโหมดของตัวชี้. อาจเปลี่ยนจำนวนอ้างอิงของวัตถุที่อ้างอิง. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | เรียกเมธอด SetTemplateWeakPtr() บนวัตถุที่ชี้ (หากมี). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | สร้างอ็อบเจกต์ [SmartPtr](../../system/smartptr/) ในโหมดที่ต้องการ. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | สร้างอ็อบเจกต์ [SmartPtr](../../system/smartptr/) ที่เป็น null-pointer ในโหมดที่ต้องการ. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | สร้าง [SmartPtr](../../system/smartptr/) ที่ชี้ไปยังวัตถุที่ระบุ, หรือแปลงตัวชี้ดิบเป็น [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | สร้างอ็อบเจกต์ [SmartPtr](../../system/smartptr/) ด้วยการคัดลอก. ตัวชี้ทั้งสองจะชี้ไปยังวัตถุเดียวกันหลังจากนั้น. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | สร้างอ็อบเจกต์ [SmartPtr](../../system/smartptr/) ด้วยการคัดลอก. ตัวชี้ทั้งสองจะชี้ไปยังวัตถุเดียวกันหลังจากนั้น. ทำการแปลงประเภทหากอนุญาต. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | สร้างอ็อบเจกต์ [SmartPtr](../../system/smartptr/) ด้วยการย้าย. โดยหลักการสลับตัวชี้สองตัวถ้าทั้งคู่อยู่ในโหมดเดียวกัน. x อาจไม่สามารถใช้ได้หลังจากเรียก. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | แปลงประเภทของอาร์เรย์ที่อ้างอิงโดยสร้างอาร์เรย์ใหม่ของประเภทต่าง. มีประโยชน์ถ้าใน C# มีการแคสอาร์เรย์ที่ไม่รองรับใน C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | เริ่มต้นอาร์เรย์เปล่า. ใช้ในการแปลโค้ดบางส่วนของ C#. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | สร้าง [SmartPtr](../../system/smartptr/) ที่แชร์ข้อมูลการเป็นเจ้าของกับค่าเริ่มต้นของ ptr, แต่เก็บตัวชี้ p ที่ไม่เกี่ยวข้องและไม่ได้จัดการ. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | แปลงตัวชี้เป็นประเภทต่างโดยใช้ static_cast กับวัตถุที่ชี้. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | แปลงประเภทตัวชี้ใด ๆ ให้เป็นตัวชี้ไปยัง [Object](../../system/object/). ไม่จำเป็นให้ประเภท Pointee_ สมบูรณ์. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | ทางลัดเพื่อรับอ็อบเจกต์ [System::TypeInfo](../../system/typeinfo/) สำหรับประเภท Pointee_. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | ทำลายอ็อบเจกต์ [SmartPtr](../../system/smartptr/). หากจำเป็นจะลดตัวนับการอ้างอิงของวัตถุที่ชี้และลบวัตถุ. |

## ดูเพิ่มเติม

* คลาส [SmartPtr](../../system/smartptr/)
* เนมสเปซ [System::Collections::Generic](../)
* ไลบรารี [Aspose.Slides](../../)