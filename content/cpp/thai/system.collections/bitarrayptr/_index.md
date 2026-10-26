---
title: BitArrayPtr
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: ตัวชี้ไปยัง BitArray. ชนิดนี้เป็นตัวชี้ที่ใช้จัดการการลบอ็อบเจ็กต์อื่น. ควรจัดสรรบนสแตกและส่งผ่านให้ฟังก์ชันโดยค่าหรือโดยการอ้างอิงแบบ const.
type: docs
weight: 14
url: /th/system.collections/bitarrayptr/
---
## BitArrayPtr คลาส

Pointer to [BitArray](../bitarray/). This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
class BitArrayPtr : public System::SmartPtr<BitArray>
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | ตัวเข้าถึงสำหรับเมธอด [begin()](../../system/smartptr/begin/) ของคอลเลกชันพื้นฐาน. คอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นชนิดพิเศษที่มีเมธอด [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | ตัวเข้าถึงสำหรับเมธอด [begin()](../../system/smartptr/begin/) ของคอลเลกชันพื้นฐาน. คอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นชนิดพิเศษที่มีเมธอด [begin()](../../system/smartptr/begin/). |
| [BitArrayPtr](./bitarrayptr/)() | กำหนดค่าเริ่มต้นให้ตัวชี้เป็น null. |
| [BitArrayPtr](./bitarrayptr/)(const [SharedPtr](../../system/sharedptr/)\<[BitArray](../bitarray/)\>\&) | คอนสตรัคเตอร์แปลงค่า. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | แคสต์ตัวชี้เป็นประเภทของมันเอง. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | แคสต์ตัวชี้เป็นชนิดฐานโดยใช้ static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | แคสต์ตัวชี้เป็นชนิดที่สืบทอดโดย dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | แคสต์ตัวชี้เป็นชนิดที่สืบทอดโดย dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | ตัวเข้าถึงสำหรับเมธอด [cbegin()](../../system/smartptr/cbegin/) ของคอลเลกชันพื้นฐาน. คอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นชนิดพิเศษที่มีเมธอด [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | ตัวเข้าถึงสำหรับเมธอด [cend()](../../system/smartptr/cend/) ของคอลเลกชันพื้นฐาน. คอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นชนิดพิเศษที่มีเมธอด [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | แคสต์ตัวชี้เป็นประเภทอื่นโดยใช้ const_cast กับอ็อบเจ็กต์ที่ชี้. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | แคสต์ตัวชี้เป็นประเภทอื่นโดยใช้ dynamic_cast กับอ็อบเจ็กต์ที่ชี้. |
| auto [end](../../system/smartptr/end/)() | ตัวเข้าถึงสำหรับเมธอด [end()](../../system/smartptr/end/) ของคอลเลกชันพื้นฐาน. คอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นชนิดพิเศษที่มีเมธอด [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | ตัวเข้าถึงสำหรับเมธอด [end()](../../system/smartptr/end/) ของคอลเลกชันพื้นฐาน. คอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นชนิดพิเศษที่มีเมธอด [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | รับอ็อบเจ็กต์ที่ชี้. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | รับโหมดของตัวชี้. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | รับอ็อบเจ็กต์ที่ชี้, แต่ตรวจสอบว่าตัวชี้อยู่ในโหมด shared. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | รับจำนวนตัวชี้ shared ที่มีอยู่ต่ออ็อบเจ็กต์ที่อ้างอิง, รวมถึงตัวปัจจุบัน. ตรวจสอบว่าตัวชี้ปัจจุบันอยู่ในโหมด shared. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | เรียก [GetHashCode()](../../system/smartptr/gethashcode/) บนอ็อบเจ็กต์ที่ชี้. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | รับอ็อบเจ็กต์ที่อ้างอิงอยู่ในขณะนี้ (หากมี) หรือโยนข้อยกเว้น. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | รับอ็อบเจ็กต์ที่ชี้ (ถ้ามี) หรือ nullptr. เท่ากับ [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | รับอ็อบเจ็กต์ที่อ้างอิง. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | รับอ็อบเจ็กต์ที่ชี้ (ถ้ามี) หรือ nullptr. เท่ากับ [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่ามีอ็อบเจ็กต์ที่ชี้เป็นชนิดเฉพาะหรือชนิดลูกของมัน. ทำตามหลักการของ C# 'is'. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | ตรวจสอบว่าตัวชี้ชี้ไปยังอ็อบเจ็กต์อื่นที่ไม่ใช่อ็อบเจ็กต์ที่เป็นเจ้าของ (ที่สร้างโดยคอนสตรัคเตอร์ aliasing). |
| **bool** [IsNull](./isnull/)() const | ตรวจสอบว่าค่าที่ระบุเป็น null หรือไม่. |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | ตรวจสอบว่าตัวชี้อยู่ในโหมด shared หรือไม่. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | ตรวจสอบว่าตัวชี้อยู่ในโหมด weak หรือไม่. |
| explicit [operator bool](../../system/smartptr/operator_bool/)() const | ตรวจสอบว่าตัวชี้ไม่เป็น null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | ตรวจสอบว่าตัวชี้เป็น null หรือไม่. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | รับอ้างอิงไปยังอ็อบเจ็กต์ที่ชี้. ตรวจสอบว่าตัวชี้ไม่เป็น null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | อนุญาตให้เข้าถึงสมาชิกของอ็อบเจ็กต์ที่อ้างอิง. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | ให้ความหมายการเปรียบเทียบแบบน้อยกว่า สำหรับคลาส [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | ให้ความหมายการเปรียบเทียบแบบน้อยกว่า สำหรับคลาส [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | ย้ายค่าตำแหน่งที่กำหนดให้กับอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/). x จะไม่สามารถใช้งานได้. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | คัดลอกค่าตำแหน่งให้กับอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | คัดลอกค่าตำแหน่งให้กับอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/). ทำการแปลงชนิดที่จำเป็น. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | กำหนดตัวชี้ดิบให้กับอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | ตั้งค่าตัวชี้เป็น nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | ตรวจสอบว่าตัวชี้ชี้ไปที่ nullptr หรือไม่. |
| **BitArray::Reference** [operator[]](./operator[]/)(int) const | ตัวเข้าถึงบิต. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | ลบการทำ aliasing (ที่สร้างโดยคอนสตรัคเตอร์ aliasing) จากตัวชี้, ทำให้แน่ใจว่ามันจัดการ (ถ้า shared) หรือ ติดตาม (ถ้า weak) อ็อบเจ็กต์เดียวกันที่มันชี้. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | กำหนดอ็อบเจ็กต์ที่ชี้. |
| void [reset](../../system/smartptr/reset/)() | ทำให้ตัวชี้ชี้ไปที่ nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | ตั้งค่าโหมดของตัวชี้. อาจเปลี่ยนจำนวนการอ้างอิงของอ็อบเจ็กต์ที่อ้างอิง. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | เรียกเมธอด SetTemplateWeakPtr() บนอ็อบเจ็กต์ที่ชี้ (ถ้ามี). |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | สร้างอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/) ด้วยโหมดที่ต้องการ. |
| [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | สร้างอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/) ที่เป็น null-pointer ด้วยโหมดที่ต้องการ. |
| [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | สร้าง [SmartPtr](../../system/smartptr/) ที่ชี้ไปยังอ็อบเจ็กต์ที่ระบุ, หรือแปลงตัวชี้ดิบเป็น [SmartPtr](../../system/smartptr/). |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | คัดลอกสร้างอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/). ตัวชี้ทั้งสองจะชี้ไปยังอ็อบเจ็กต์เดียวกันหลังจากนั้น. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | คัดลอกสร้างอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/). ตัวชี้ทั้งสองจะชี้ไปยังอ็อบเจ็กต์เดียวกันหลังจากนั้น. ทำการแปลงชนิดหากอนุญาต. |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | ย้ายสร้างอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/). โดยจริง ๆ แล้วสลับตัวชี้สองตัวหากทั้งสองอยู่ในโหมดเดียวกัน. x อาจไม่สามารถใช้ได้หลังจากเรียก. |
| explicit [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | แปลงประเภทของอาเรย์ที่อ้างอิงโดยสร้างอาเรย์ใหม่ของประเภทต่างหาก. มีประโยชน์หากใน C# มีการแคสต์อาเรย์ที่ไม่ได้รองรับใน C++. |
| explicit [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | เริ่มต้นอาเรย์เปล่า. ใช้เพื่อแปลงโครงสร้างโค้ดบางอย่างของ C#. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | สร้าง [SmartPtr](../../system/smartptr/) ที่แชร์ข้อมูลการเป็นเจ้าของกับค่าเริ่มต้นของ ptr, แต่ถือ pointer p ที่ไม่เกี่ยวข้องและไม่ได้จัดการ. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | แคสต์ตัวชี้เป็นประเภทอื่นโดยใช้ static_cast บนอ็อบเจ็กต์ที่ชี้. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | แปลงประเภทตัวชี้ใด ๆ ให้เป็นตัวชี้ไปยัง [Object](../../system/object/). ไม่จำเป็นต้องให้ชนิด Pointee_ สมบูรณ์. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | ทางลัดเพื่อรับอ็อบเจ็กต์ [System::TypeInfo](../../system/typeinfo/) สำหรับชนิด Pointee_. |
| [~SmartPtr](../../system/smartptr/~smartptr/)() | ทำลายอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/). หากต้องการ, ลดตัวนับอ้างอิงของอ็อบเจ็กต์ที่ชี้และลบอ็อบเจ็กต์. |

## ดูเพิ่มเติม

* คลาส [SmartPtr](../../system/smartptr/)
* เนมสเปซ [System::Collections](../)
* ไลบรารี [Aspose.Slides](../../)