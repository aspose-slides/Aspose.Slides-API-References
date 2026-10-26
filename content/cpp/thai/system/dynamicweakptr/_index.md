---
title: DynamicWeakPtr
second_title: Aspose.Slides สำหรับ C++ API Reference
description: คลาส smart pointer ที่ติดตามโหมดของพอยน์เตอร์ของเทมเพลตอาร์กิวเมนต์ของอ็อบเจกต์ที่จัดเก็บและอัปเดตหลังจากการมอบหมายแต่ละครั้ง ประเภทนี้เป็นพอยน์เตอร์เพื่อจัดการการลบของอ็อบเจกต์อื่น ควรจัดสรรบนสแตกและส่งต่อให้ฟังก์ชันโดยค่าหรือโดยการอ้างอิงคอนสท์.
type: docs
weight: 781
url: /th/system/dynamicweakptr/
---
## DynamicWeakPtr คลาส

Smart pointer class ที่ติดตามโหมดของพอยน์เตอร์ของเทมเพลตอาร์กิวเมนต์ของอ็อบเจกต์ที่จัดเก็บและอัปเดตพวกมันหลังจากการมอบหมายแต่ละครั้ง. ประเภทนี้เป็นพอยน์เตอร์เพื่อจัดการการลบของอ็อบเจกต์อื่น. ควรจัดสรรบนสแตกและส่งต่อให้ฟังก์ชันโดยค่าหรือโดยการอ้างอิงคอนสท์.

```cpp
template<typename T,SmartPtrMode,unsigned int ...>class DynamicWeakPtr : public System::SmartPtr<T>
```

### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| Pointee | ประเภท. |
| trunkMode | โหมดของ smart pointer เอง, shared หรือ weak. |
| weakLeafs | ดัชนีของเทมเพลตอาร์กิวเมนต์ของประเภทที่จัดเก็บซึ่งควรตั้งเป็นโหมด weak pointer. |

## เมธอด

| Method | Description |
| --- | --- |
| auto [begin](../smartptr/begin/)() | ตัวเข้าถึงสำหรับเมธอด [begin()](../smartptr/begin/) ของคอลล렉ชันที่อยู่ภายใต้. จะคอมไพล์ได้ก็ต่อเมื่อ SmartPtr_ เป็นประเภทสเปเชียลไลเซชันที่มีเมธอด [begin()](../smartptr/begin/). |
| auto [begin](../smartptr/begin/)() const | ตัวเข้าถึงสำหรับเมธอด [begin()](../smartptr/begin/) ของคอลล렉ชันที่อยู่ภายใต้. จะคอมไพล์ได้ก็ต่อเมื่อ SmartPtr_ เป็นประเภทสเปเชียลไลเซชันที่มีเมธอด [begin()](../smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | แคสต์พอยน์เตอร์เป็นชนิดของมันเอง. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | แคสต์พอยน์เตอร์เป็นชนิดฐานโดยใช้ static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | แคสต์พอยน์เตอร์เป็นชนิดย่อยโดยใช้ dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | แคสต์พอยน์เตอร์เป็นชนิดย่อยโดยใช้ dynamic_cast. |
| auto [cbegin](../smartptr/cbegin/)() const | ตัวเข้าถึงสำหรับเมธอด [cbegin()](../smartptr/cbegin/) ของคอลล렉ชันที่อยู่ภายใต้. จะคอมไพล์ได้ก็ต่อเมื่อ SmartPtr_ เป็นประเภทสเปเชียลไลเซชันที่มีเมธอด [cbegin()](../smartptr/cbegin/). |
| auto [cend](../smartptr/cend/)() const | ตัวเข้าถึงสำหรับเมธอด [cend()](../smartptr/cend/) ของคอลล렉ชันที่อยู่ภายใต้. จะคอมไพล์ได้ก็ต่อเมื่อ SmartPtr_ เป็นประเภทสเปเชียลไลเซชันที่มีเมธอด [cend()](../smartptr/cend/). |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | แคสต์พอยน์เตอร์เป็นชนิดอื่นโดยใช้ const_cast กับอ็อบเจกต์ที่ชี้. |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | แคสต์พอยน์เตอร์เป็นชนิดอื่นโดยใช้ dynamic_cast กับอ็อบเจกต์ที่ชี้. |
| [DynamicWeakPtr](./dynamicweakptr/)(std::nullptr_t) | สร้าง smart pointer ที่เป็น null. |
| [DynamicWeakPtr](./dynamicweakptr/)([Pointee_](../smartptr/pointee_/) *) | สร้าง smart pointer ที่ชี้ไปยังอ็อบเจกต์ที่กำหนด. |
| [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr_](./smartptr_/)\&) | คัดลอกสร้าง smart pointer. |
| [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | คัดลอกสร้าง smart pointer. |
| [DynamicWeakPtr](./dynamicweakptr/)(const [DynamicWeakPtr_](./dynamicweakptr_/)\&) | คัดลอกสร้าง smart pointer. |
| [DynamicWeakPtr](./dynamicweakptr/)([SmartPtr_](./smartptr_/)\&&) | ย้ายสร้าง smart pointer. |
| auto [end](../smartptr/end/)() | ตัวเข้าถึงสำหรับเมธอด [end()](../smartptr/end/) ของคอลล렉ชันที่อยู่ภายใต้. จะคอมไพล์ได้ก็ต่อเมื่อ SmartPtr_ เป็นประเภทสเปเชียลไลเซชันที่มีเมธอด [end()](../smartptr/end/). |
| auto [end](../smartptr/end/)() const | ตัวเข้าถึงสำหรับเมธอด [end()](../smartptr/end/) ของคอลล렉ชันที่อยู่ภายใต้. จะคอมไพล์ได้ก็ต่อเมื่อ SmartPtr_ เป็นประเภทสเปเชียลไลเซชันที่มีเมธอด [end()](../smartptr/end/). |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | รับอ็อบเจกต์ที่ชี้. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | รับโหมดพอยน์เตอร์. |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | รับอ็อบเจกต์ที่ชี้, แต่ยืนยันว่าพอยน์เตอร์อยู่ในโหมด shared. |
| int [get_shared_count](../smartptr/get_shared_count/)() const | รับจำนวนของ shared pointer ที่มีอยู่ต่ออ็อบเจกต์ที่อ้างอิง, รวมถึงตัวปัจจุบัน. ยืนยันว่าพอยน์เตอร์ปัจจุบันอยู่ในโหมด shared. |
| int [GetHashCode](../smartptr/gethashcode/)() const | เรียก [GetHashCode()](../smartptr/gethashcode/) บนอ็อบเจกต์ที่ชี้. |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | รับอ็อบเจกต์ที่อ้างอิงอยู่ในขณะนี้ (ถ้ามี) หรือโยนข้อยกเว้น. |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | รับอ็อบเจกต์ที่ชี้ (ถ้ามี) หรือ nullptr. เช่นเดียวกับ [get()](../smartptr/get/). |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | รับอ็อบเจกต์ที่อ้างอิง. |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | รับอ็อบเจกต์ที่ชี้ (ถ้ามี) หรือ nullptr. เช่นเดียวกับ [get()](../smartptr/get/). |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์ที่ชี้เป็นชนิดเฉพาะหรือชนิดลูกของมัน. ปฏิบัติตาม semantics ของ C# 'is'. |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | ตรวจสอบว่าพอยน์เตอร์ชี้ไปยังอ็อบเจกต์อื่นที่ไม่ใช่ของตน (ที่สร้างโดยคอนสตรัคเตอร์ aliasing). |
| **bool** [IsShared](../smartptr/isshared/)() const | ตรวจสอบว่าพอยน์เตอร์อยู่ในโหมด shared. |
| **bool** [IsWeak](../smartptr/isweak/)() const | ตรวจสอบว่าพอยน์เตอร์อยู่ในโหมด weak. |
| explicit [operator bool](../smartptr/operator_bool/)() const | ตรวจสอบว่าพอยน์เตอร์ไม่เป็น null. |
| **bool** [operator!](../smartptr/operator_not/)() const | ตรวจสอบว่าพอยน์เตอร์เป็น null. |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | รับการอ้างอิงไปยังอ็อบเจกต์ที่ชี้. ยืนยันว่าพอยน์เตอร์ไม่เป็น null. |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | อนุญาตให้เข้าถึงสมาชิกของอ็อบเจกต์ที่อ้างอิง. |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | ให้การเปรียบเทียบแบบ less-compare สำหรับคลาส [SmartPtr](../smartptr/). |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | ให้การเปรียบเทียบแบบ less-compare สำหรับคลาส [SmartPtr](../smartptr/). |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | ย้ายกำหนดค่า smart pointer. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | คัดลอกกำหนดค่า smart pointer. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | คัดลอกกำหนดค่า smart pointer. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(typename [SmartPtr_::Pointee_](../smartptr/pointee_/) *) | กำหนดค่า smart pointer. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | ตั้งค่า smart pointer เป็น null. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | ตรวจสอบว่า smart pointer เป็น null. |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | ลบการ aliasing (ที่สร้างโดยคอนสตรัคเตอร์ aliasing) จากพอยน์เตอร์, ทำให้แน่ใจว่ามันจัดการ (ถ้าเป็น shared) หรือ ติดตาม (ถ้าเป็น weak) อ็อบเจกต์เดียวกันที่ชี้ถึง. |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | ตั้งค่าอ็อบเจกต์ที่ชี้. |
| void [reset](../smartptr/reset/)() | ทำให้พอยน์เตอร์ชี้ไปยัง nullptr. |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | ตั้งค่าโหมดพอยน์เตอร์. อาจเปลี่ยนการนับอ้างอิงของอ็อบเจกต์ที่อ้างอิง. |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | เรียกเมธอด SetTemplateWeakPtr() บนอ็อบเจกต์ที่ชี้ (ถ้ามี). |
| [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | สร้างอ็อบเจกต์ [SmartPtr](../smartptr/) ในโหมดที่ต้องการ. |
| [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | สร้างอ็อบเจกต์ [SmartPtr](../smartptr/) แบบ null-pointer ในโหมดที่ต้องการ. |
| [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | สร้าง [SmartPtr](../smartptr/) ชี้ไปยังอ็อบเจกต์ที่ระบุ, หรือแปลง raw pointer เป็น [SmartPtr](../smartptr/). |
| [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | คัดลอกสร้างอ็อบเจกต์ [SmartPtr](../smartptr/). ทั้งสองพอยน์เตอร์ชี้ไปยังอ็อบเจกต์เดียวกันหลังจากนั้น. |
| [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | คัดลอกสร้างอ็อบเจกต์ [SmartPtr](../smartptr/). ทั้งสองพอยน์เตอร์ชี้ไปยังอ็อบเจกต์เดียวกันหลังจากนั้น. ทำการแปลงประเภทหากอนุญาต. |
| [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | ย้ายสร้างอ็อบเจกต์ [SmartPtr](../smartptr/). โดยพื้นฐานแล้วสลับพอยน์เตอร์สองตัวถ้าเป็นโหมดเดียวกัน. x อาจใช้งไม่ได้หลังจากเรียก. |
| explicit [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | แปลงประเภทของอาร์เรย์ที่อ้างอิงโดยสร้างอาร์เรย์ใหม่ของประเภทอื่น. มีประโยชน์หากใน C# มีการแคสต์อาร์เรย์ที่ไม่สนับสนุนใน C++. |
| explicit [SmartPtr](../smartptr/smartptr/)(const Y\&) | เริ่มต้นอาร์เรย์เปล่า. ใช้เพื่อแปลโค้ด C# บางส่วน. |
| [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | สร้าง [SmartPtr](../smartptr/) ที่แชร์ข้อมูลความเป็นเจ้าของกับค่าเริ่มต้นของ ptr, แต่ถือพอยน์เตอร์ที่ไม่ได้จัดการและไม่มีการจัดการ p. |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | แคสต์พอยน์เตอร์เป็นชนิดอื่นโดยใช้ static_cast บนอ็อบเจกต์ที่ชี้. |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | แปลงพอยน์เตอร์ประเภทใดก็ได้เป็นพอยน์เตอร์ไปยัง [Object](../object/). ไม่จำเป็นต้องให้ประเภท Pointee_ สมบูรณ์. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | ทางลัดเพื่อรับอ็อบเจกต์ [System::TypeInfo](../typeinfo/) สำหรับประเภท Pointee_. |
| [~SmartPtr](../smartptr/~smartptr/)() | ทำลายอ็อบเจกต์ [SmartPtr](../smartptr/). หากต้องการ, ลดตัวนับการอ้างอิงของอ็อบเจกต์ที่ชี้และลบอ็อบเจกต์. |

## ชนิดนิยาม

| Typedef | Description |
| --- | --- |
| [SmartPtr_](./smartptr_/) | [SmartPtr](../smartptr/) alias ของคลาสฐาน. |
| [DynamicWeakPtr_](./dynamicweakptr_/) | alias ของประเภทตัวเอง. |
| [Pointee_](./pointee_/) | ชนิดที่พอยน์เตอร์ชี้. |

## ดูเพิ่มเติม

* คลาส [SmartPtr](../smartptr/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)