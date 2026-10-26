---
title: DictionaryPtr
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คลาสพอยน์เตอร์ของ Dictionary ที่มีการโอเวอร์โหลดตัวดำเนินการ ชนิดนี้เป็นพอยน์เตอร์เพื่อจัดการการลบของอ็อบเจ็กต์อื่น ควรจัดสรรบนสแตกและส่งต่อให้ฟังก์ชันโดยค่าหรือโดยการอ้างอิงคอนสท์
type: docs
weight: 170
url: /th/system.collections.generic/dictionaryptr/
---
## DictionaryPtr คลาส

[Dictionary](../dictionary/) คลาสพอยน์เตอร์ที่มีการโอเวอร์โหลดตัวดำเนินการ. ชนิดนี้เป็นพอยน์เตอร์เพื่อจัดการการลบของอ็อบเจ็กต์อื่น. ควรจัดสรรบนสแตกและส่งต่อให้ฟังก์ชันโดยค่าหรือโดยการอ้างอิงคอนสท์.

```cpp
template<typename T,typename V>class DictionaryPtr : public System::SmartPtr<Dictionary<T, V>>
```

### พารามิเตอร์ของเทมเพลต

| Parameter | Description |
| --- | --- |
| T | ประเภทคีย์. |
| V | ประเภทค่า. |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | ตัวเข้าถึงสำหรับเมธอด [begin()](../../system/smartptr/begin/) ของคอลเลกชันพื้นฐาน. คอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นชนิดเทมเพลตพิเศษที่มีเมธอด [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | ตัวเข้าถึงสำหรับเมธอด [begin()](../../system/smartptr/begin/) ของคอลเลกชันพื้นฐาน. คอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นชนิดเทมเพลตพิเศษที่มีเมธอด [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | แปลงพอยน์เตอร์เป็นชนิดของมันเอง. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | แปลงพอยน์เตอร์เป็นชนิดฐานโดยใช้ static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | แปลงพอยน์เตอร์เป็นชนิดที่สืบทอดโดยใช้ dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | แปลงพอยน์เตอร์เป็นชนิดที่สืบทอดโดยใช้ dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | ตัวเข้าถึงสำหรับเมธอด [cbegin()](../../system/smartptr/cbegin/) ของคอลเลกชันพื้นฐาน. คอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นชนิดเทมเพลตพิเศษที่มีเมธอด [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | ตัวเข้าถึงสำหรับเมธอด [cend()](../../system/smartptr/cend/) ของคอลเลกชันพื้นฐาน. คอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นชนิดเทมเพลตพิเศษที่มีเมธอด [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | แปลงพอยน์เตอร์เป็นชนิดอื่นโดยใช้ const_cast กับอ็อบเจ็กต์ที่ชี้. |
|  [DictionaryPtr](./dictionaryptr/)() | เริ่มต้นพอยน์เตอร์เป็น null. |
|  [DictionaryPtr](./dictionaryptr/)(const [SharedPtr](../../system/sharedptr/)\<[Dictionary](../dictionary/)\<T, V\>\>\&) | แปลงชนิดของพอยน์เตอร์. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | แปลงพอยน์เตอร์เป็นชนิดอื่นโดยใช้ dynamic_cast กับอ็อบเจ็กต์ที่ชี้. |
| auto [end](../../system/smartptr/end/)() | ตัวเข้าถึงสำหรับเมธอด [end()](../../system/smartptr/end/) ของคอลเลกชันพื้นฐาน. คอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นชนิดเทมเพลตพิเศษที่มีเมธอด [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | ตัวเข้าถึงสำหรับเมธอด [end()](../../system/smartptr/end/) ของคอลเลกชันพื้นฐาน. คอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นชนิดเทมเพลตพิเศษที่มีเมธอด [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | คืนค่าอ็อบเจ็กต์ที่ชี้. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | คืนค่าโหมดของพอยน์เตอร์. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | คืนค่าอ็อบเจ็กต์ที่ชี้, แต่ตรวจสอบว่าพอยน์เตอร์อยู่ในโหมด shared. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | คืนค่าจำนวนพอยน์เตอร์แบบ shared ที่อ้างอิงอ็อบเจ็กต์เดียวกัน, รวมถึงพอยน์เตอร์ปัจจุบัน. ตรวจสอบว่าพอยน์เตอร์อยู่ในโหมด shared. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | เรียก [GetHashCode()](../../system/smartptr/gethashcode/) บนอ็อบเจ็กต์ที่ชี้. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | คืนค่าอ็อบเจ็กต์ที่อ้างอิงอยู่ในขณะนั้น (ถ้ามี) หรือโยนข้อยกเว้น. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | คืนค่าอ็อบเจ็กต์ที่ชี้ (ถ้ามี) หรือ nullptr. ทำเหมือน [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | คืนค่าอ็อบเจ็กต์ที่อ้างอิง. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | คืนค่าอ็อบเจ็กต์ที่ชี้ (ถ้ามี) หรือ nullptr. ทำเหมือน [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์ที่ชี้เป็นชนิดเฉพาะหรือชนิดลูก. ทำตาม semantics ของ C# `is`. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | ตรวจสอบว่าพอยน์เตอร์ชี้ไปยังอ็อบเจ็กต์อื่นที่ไม่ได้เป็นของตัวเอง (สร้างโดยคอนสตรัคเตอร์ aliasing). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | ตรวจสอบว่าพอยน์เตอร์อยู่ในโหมด shared. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | ตรวจสอบว่าพอยน์เตอร์อยู่ในโหมด weak. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | ตรวจสอบว่าพอยน์เตอร์ไม่เป็น null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | ตรวจสอบว่าพอยน์เตอร์เป็น null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | คืนค่าการอ้างอิงไปยังอ็อบเจ็กต์ที่ชี้. ตรวจสอบว่าพอยน์เตอร์ไม่เป็น null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | อนุญาตให้เข้าถึงสมาชิกของอ็อบเจ็กต์ที่อ้างอิง. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | ให้ semantics การเปรียบเทียบแบบน้อยกว่าสำหรับคลาส [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | ให้ semantics การเปรียบเทียบแบบน้อยกว่าสำหรับคลาส [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | ย้ายกำหนดอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/). x จะไม่สามารถใช้ได้ต่อ. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | คัดลอกกำหนดอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | คัดลอกกำหนดอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/). ทำการแปลงชนิดตามที่จำเป็น. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | กำหนดพอยน์เตอร์ดิบให้กับอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | ตั้งค่าค่าพอยน์เตอร์เป็น nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | ตรวจสอบว่าพอยน์เตอร์ชี้ไปที่ nullptr. |
| V\& [operator[]](./operator[]/)(const X\&) const | ตัวดำเนินการเข้าถึงเพื่อทำการแปลงประเภทคีย์. |
| V\& [operator[]](./operator[]/)(const T\&) const | ตัวดำเนินการเข้าถึง. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | ลบการ aliasing (ที่สร้างโดยคอนสตรัคเตอร์ aliasing) จากพอยน์เตอร์, ทำให้แน่ใจว่าพอยน์เตอร์จัดการ (ถ้าเป็น shared) หรือ ติดตาม (ถ้าเป็น weak) อ็อบเจ็กต์เดียวกัน. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | ตั้งค่าอ็อบเจ็กต์ที่ชี้. |
| void [reset](../../system/smartptr/reset/)() | ทำให้พอยน์เตอร์ชี้ไปที่ nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | ตั้งค่าโหมดของพอยน์เตอร์. อาจเปลี่ยนจำนวนอ้างอิงของอ็อบเจ็กต์ที่อ้างอิง. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | เรียกเมธอด SetTemplateWeakPtr() บนอ็อบเจ็กต์ที่ชี้ (ถ้ามี). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | สร้างอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/) ในโหมดที่ต้องการ. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | สร้างอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/) ที่เป็น null-pointer ในโหมดที่ต้องการ. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | สร้าง [SmartPtr](../../system/smartptr/) ที่ชี้ไปยังอ็อบเจ็กต์ที่ระบุ, หรือแปลงพอยน์เตอร์ดิบเป็น [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | คอนสตรัคต์ออบเจ็กต์ [SmartPtr](../../system/smartptr/) แบบคัดลอก. ทั้งสองพอยน์เตอร์จะชี้ไปยังอ็อบเจ็กต์เดียวกันหลังจากนั้น. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | คอนสตรัคต์ออบเจ็กต์ [SmartPtr](../../system/smartptr/) แบบคัดลอก. ทั้งสองพอยน์เตอร์จะชี้ไปยังอ็อบเจ็กต์เดียวกันหลังจากนั้น. ทำการแปลงชนิดหากอนุญาต. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | คอนสตรัคต์ออบเจ็กต์ [SmartPtr](../../system/smartptr/) แบบย้าย. โดยพื้นฐานสลับพอยน์เตอร์สองตัวหากเป็นโหมดเดียวกัน. x อาจไม่สามารถใช้ได้หลังจากเรียก. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | แปลงชนิดของแอเรย์ที่อ้างอิงโดยสร้างแอเรย์ใหม่ที่มีชนิดต่างกัน. มีประโยชน์เมื่อ C# มีการแคสต์แอเรย์ซึ่งไม่รองรับใน C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | เริ่มต้นแอเรย์ว่าง. ใช้เพื่อแปลงโครงสร้างโค้ด C#. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | คอนสตรัคต์ [SmartPtr](../../system/smartptr/) ที่แชร์ข้อมูลการเป็นเจ้าของกับค่าเริ่มต้นของ ptr, แต่ถือพอยน์เตอร์ p ที่ไม่ได้จัดการ. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | แปลงพอยน์เตอร์เป็นชนิดอื่นโดยใช้ static_cast บนอ็อบเจ็กต์ที่ชี้. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | แปลงพอยน์เตอร์เป็นพอยน์เตอร์ไปยัง [Object](../../system/object/). ไม่ต้องการให้ชนิด Pointee_ สมบูรณ์. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | ทางลัดเพื่อรับอ็อบเจ็กต์ [System::TypeInfo](../../system/typeinfo/) สำหรับชนิด Pointee_. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | ทำลายอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/). หากจำเป็นจะลดตัวนับอ้างอิงของอ็อบเจ็กต์ที่ชี้และลบอ็อบเจ็กต์. |

## ดูเพิ่มเติม

* Class [SmartPtr](../../system/smartptr/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.Slides](../../)