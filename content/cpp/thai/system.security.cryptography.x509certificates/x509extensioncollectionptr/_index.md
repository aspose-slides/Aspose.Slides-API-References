---
title: X509ExtensionCollectionPtr
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตัวชี้ไปยังคอลเลกชันของส่วนขยาย X509. ชนิดนี้เป็นตัวชี้ที่จัดการการลบของอ็อบเจกต์อื่น. ควรจัดสรรบนสแตกและส่งให้ฟังก์ชันโดยค่า หรือโดยการอ้างอิงแบบ const.
type: docs
weight: 170
url: /th/system.security.cryptography.x509certificates/x509extensioncollectionptr/
---
## X509ExtensionCollectionPtr คลาส

ตัวชี้ไปยังคอลเลกชันของส่วนขยาย X509. ชนิดนี้เป็นตัวชี้ที่จัดการการลบของอ็อบเจกต์อื่น. ควรจัดสรรบนสแตกและส่งให้ฟังก์ชันโดยค่า หรือโดยการอ้างอิงแบบ const.

```cpp
class X509ExtensionCollectionPtr : public System::SmartPtr<X509ExtensionCollection>
```

## Methods

| Method | Description |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | ตัวเข้าถึงสำหรับเมธอด [begin()](../../system/smartptr/begin/) ของคอลเลกชันพื้นฐาน. จะคอมไพล์ได้เท่านั้นหาก SmartPtr_ เป็นชนิดพิเศษที่มีเมธอด [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | ตัวเข้าถึงสำหรับเมธอด [begin()](../../system/smartptr/begin/) ของคอลเลกชันพื้นฐาน. จะคอมไพล์ได้เท่านั้นหาก SmartPtr_ เป็นชนิดพิเศษที่มีเมธอด [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | แปลงตัวชี้เป็นประเภทของตัวมันเอง. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | แปลงตัวชี้เป็นประเภทฐานโดยใช้ static\_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | แปลงตัวชี้เป็นประเภทที่สืบทอดโดยใช้ dynamic\_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | แปลงตัวชี้เป็นประเภทที่สืบทอดโดยใช้ dynamic\_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | ตัวเข้าถึงสำหรับเมธอด [cbegin()](../../system/smartptr/cbegin/) ของคอลเลกชันพื้นฐาน. จะคอมไพล์ได้เท่านั้นหาก SmartPtr_ เป็นชนิดพิเศษที่มีเมธอด [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | ตัวเข้าถึงสำหรับเมธอด [cend()](../../system/smartptr/cend/) ของคอลเลกชันพื้นฐาน. จะคอมไพล์ได้เท่านั้นหาก SmartPtr_ เป็นชนิดพิเศษที่มีเมธอด [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | แปลงตัวชี้เป็นประเภทอื่นโดยใช้ const\_cast กับอ็อบเจกต์ที่ชี้. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | แปลงตัวชี้เป็นประเภทอื่นโดยใช้ dynamic\_cast กับอ็อบเจกต์ที่ชี้. |
| auto [end](../../system/smartptr/end/)() | ตัวเข้าถึงสำหรับเมธอด [end()](../../system/smartptr/end/) ของคอลเลกชันพื้นฐาน. จะคอมไพล์ได้เท่านั้นหาก SmartPtr_ เป็นชนิดพิเศษที่มีเมธอด [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | ตัวเข้าถึงสำหรับเมธอด [end()](../../system/smartptr/end/) ของคอลเลกชันพื้นฐาน. จะคอมไพล์ได้เท่านั้นหาก SmartPtr_ เป็นชนิดพิเศษที่มีเมธอด [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | รับอ็อบเจกต์ที่ชี้. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | รับโหมดของตัวชี้. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | รับอ็อบเจกต์ที่ชี้, แต่ตรวจสอบว่าตัวชี้อยู่ในโหมด shared. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | รับจำนวนตัวชี้แบบ shared ที่มีต่ออ็อบเจกต์ที่อ้างอิง, รวมถึงตัวปัจจุบัน. ตรวจสอบว่าตัวชี้ปัจจุบันอยู่ในโหมด shared. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | เรียก [GetHashCode()](../../system/smartptr/gethashcode/) บนอ็อบเจกต์ที่ชี้. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | รับอ็อบเจกต์ที่อ้างอิงอยู่ในขณะนี้ (ถ้ามี) หรือโยนข้อยกเว้น. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | รับอ็อบเจกต์ที่ชี้ (ถ้ามี) หรือ nullptr. เหมือนกับ [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | รับอ็อบเจกต์ที่อ้างอิง. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | รับอ็อบเจกต์ที่ชี้ (ถ้ามี) หรือ nullptr. เหมือนกับ [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์ที่ชี้เป็นประเภทเฉพาะหรือชนิดลูกของมัน. ปฏิบัติตาม semantics ของ C# 'is'. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | ตรวจสอบว่าตัวชี้ชี้ไปยังอ็อบเจกต์อื่นที่ไม่ใช่ของที่เป็นเจ้าของ (ถูกสร้างโดยคอนสตรักเตอร์ aliasing). |
| **bool** [IsNull](./isnull/)() const |  |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | ตรวจสอบว่าตัวชี้อยู่ในโหมด shared. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | ตรวจสอบว่าตัวชี้อยู่ในโหมด weak. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | ตรวจสอบว่าตัวชี้ไม่เป็น null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | ตรวจสอบว่าตัวชี้เป็น null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | รับอ้างอิงถึงอ็อบเจกต์ที่ชี้. ตรวจสอบว่าตัวชี้ไม่เป็น null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | อนุญาตให้เข้าถึงสมาชิกของอ็อบเจกต์ที่อ้างอิง. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | ให้ semantics การเปรียบเทียบแบบน้อยกว่า สำหรับคลาส [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | ให้ semantics การเปรียบเทียบแบบน้อยกว่า สำหรับคลาส [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | ย้ายกำหนดค่าให้กับอ็อบเจกต์ [SmartPtr](../../system/smartptr/). x จะไม่สามารถใช้ได้. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | คัดลอกกำหนดค่าให้กับอ็อบเจกต์ [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | คัดลอกกำหนดค่าให้กับอ็อบเจกต์ [SmartPtr](../../system/smartptr/). ทำการแปลงประเภทตามที่จำเป็น. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | กำหนดค่าตัวชี้ดิบให้กับอ็อบเจกต์ [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | ตั้งค่าตัวชี้เป็น nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | ตรวจสอบว่าตัวชี้ชี้ไปที่ nullptr. |
| [SharedPtr](../../system/sharedptr/)\<[X509Extension](../x509extension/)\>\& [operator[]](./operator[]/)(**int32_t**) const | ตัวเข้าถึง. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | ลบ aliasing (ที่สร้างโดยคอนสตรักเตอร์ aliasing) จากตัวชี้, ทำให้แน่ใจว่ามันจัดการ (หาก shared) หรือ ติดตาม (หาก weak) อ็อบเจกต์เดียวกันที่มันชี้. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | ตั้งค่าอ็อบเจกต์ที่ชี้. |
| void [reset](../../system/smartptr/reset/)() | ทำให้ตัวชี้ชี้ไปที่ nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | ตั้งค่าโหมดของตัวชี้. อาจทำให้จำนวนการอ้างอิงของอ็อบเจกต์ที่อ้างอิงเปลี่ยนแปลง. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | เรียกเมธอด SetTemplateWeakPtr() บนอ็อบเจกต์ที่ชี้ (ถ้ามี). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | สร้างอ็อบเจกต์ [SmartPtr](../../system/smartptr/) ในโหมดที่ต้องการ. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | สร้างอ็อบเจกต์ [SmartPtr](../../system/smartptr/) ตัว null-pointer ในโหมดที่ต้องการ. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | สร้าง [SmartPtr](../../system/smartptr/) ที่ชี้ไปยังอ็อบเจกต์ที่ระบุ, หรือแปลงตัวชี้ดิบเป็น [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | คัดลอกสร้างอ็อบเจกต์ [SmartPtr](../../system/smartptr/). ตัวชี้ทั้งสองจะชี้ไปยังอ็อบเจกต์เดียวกันหลังจากนั้น. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | คัดลอกสร้างอ็อบเจกต์ [SmartPtr](../../system/smartptr/). ตัวชี้ทั้งสองจะชี้ไปยังอ็อบเจกต์เดียวกันหลังจากนั้น. ทำการแปลงประเภทหากอนุญาต. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | ย้ายสร้างอ็อบเจกต์ [SmartPtr](../../system/smartptr/). โดยหลักการสลับตัวชี้สองตัวหากโหมดเดียวกัน. x อาจไม่สามารถใช้ได้หลังจากเรียก. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | แปลงประเภทของอาร์เรย์ที่อ้างอิงโดยสร้างอาร์เรย์ใหม่ของประเภทอื่น. มีประโยชน์หากใน C# มีการแคสประเภทอาร์เรย์ที่ไม่รองรับใน C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | เริ่มต้นอาร์เรย์ว่าง. ใช้เพื่อแปลงโครงสร้างโค้ด C# บางส่วน. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | สร้าง [SmartPtr](../../system/smartptr/) ที่แชร์ข้อมูลการเป็นเจ้าของกับค่าตั้งต้นของ ptr, แต่ถือ pointer p ที่ไม่มีความเกี่ยวข้องและไม่ได้จัดการ. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | แปลงตัวชี้เป็นประเภทอื่นโดยใช้ static\_cast กับอ็อบเจกต์ที่ชี้. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | แปลงประเภทตัวชี้ใดๆ ให้เป็นตัวชี้ไปยัง [Object](../../system/object/). ไม่จำเป็นต้องให้ประเภท Pointee_ สมบูรณ์. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | ทางลัดเพื่อรับอ็อบเจกต์ [System::TypeInfo](../../system/typeinfo/) สำหรับประเภท Pointee_. |
|  [X509ExtensionCollectionPtr](./x509extensioncollectionptr/)() | คอนสตรักเตอร์ตัวชี้ null. |
|  [X509ExtensionCollectionPtr](./x509extensioncollectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[X509ExtensionCollection](../x509extensioncollection/)\>\&) | คอนสตรักเตอร์. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | ทำลายอ็อบเจกต์ [SmartPtr](../../system/smartptr/). หากจำเป็นจะลดตัวนับอ้างอิงของอ็อบเจกต์ที่ชี้และลบอ็อบเจกต์. |

## ดูเพิ่มเติม

* คลาส [SmartPtr](../../system/smartptr/)
* เนมสเปซ [System::Security::Cryptography::X509Certificates](../)
* ไลบรารี [Aspose.Slides](../../)