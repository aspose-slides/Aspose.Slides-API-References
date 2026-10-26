---
title: X509Certificate2CollectionPtr
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: พอยน์เตอร์ไปยังคอลเล็กชันของใบรับรอง X509. ชนิดนี้เป็นพอยน์เตอร์เพื่อจัดการการลบอ็อบเจกต์อื่น. ควรจัดสรรบนสแตกและส่งต่อไปยังฟังก์ชันทั้งโดยค่าและโดยการอ้างอิงคอนสแตนต์.
type: docs
weight: 66
url: /th/system.security.cryptography.x509certificates/x509certificate2collectionptr/
---
## X509Certificate2CollectionPtr คลาส

Pointer to collection of X509 certificates. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
class X509Certificate2CollectionPtr : public System::SmartPtr<X509Certificate2Collection>
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | ตัวเข้าถึงสำหรับเมธอด [begin()](../../system/smartptr/begin/) ของคอลเล็กชันภายใน. จะคอมไพล์ได้เท่านั้นหาก SmartPtr_ เป็นประเภทพิเศษที่มีเมธอด [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | ตัวเข้าถึงสำหรับเมธอด [begin()](../../system/smartptr/begin/) ของคอลเล็กชันภายใน. จะคอมไพล์ได้เท่านั้นหาก SmartPtr_ เป็นประเภทพิเศษที่มีเมธอด [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | แคสต์พอยน์เตอร์เป็นประเภทของมันเอง. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | แคสต์พอยน์เตอร์เป็นประเภทฐานโดยใช้ static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | แคสต์พอยน์เตอร์เป็นประเภทที่สืบทอดโดยใช้ dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | แคสต์พอยน์เตอร์เป็นประเภทที่สืบทอดโดยใช้ dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | ตัวเข้าถึงสำหรับเมธอด [cbegin()](../../system/smartptr/cbegin/) ของคอลเล็กชันภายใน. จะคอมไพล์ได้เท่านั้นหาก SmartPtr_ เป็นประเภทพิเศษที่มีเมธอด [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | ตัวเข้าถึงสำหรับเมธอด [cend()](../../system/smartptr/cend/) ของคอลเล็กชันภายใน. จะคอมไพล์ได้เท่านั้นหาก SmartPtr_ เป็นประเภทพิเศษที่มีเมธอด [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | แคสต์พอยน์เตอร์เป็นประเภทอื่นโดยใช้ const_cast บนอ็อบเจกต์ที่ชี้. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | แคสต์พอยน์เตอร์เป็นประเภทอื่นโดยใช้ dynamic_cast บนอ็อบเจกต์ที่ชี้. |
| auto [end](../../system/smartptr/end/)() | ตัวเข้าถึงสำหรับเมธอด [end()](../../system/smartptr/end/) ของคอลเล็กชันภายใน. จะคอมไพล์ได้เท่านั้นหาก SmartPtr_ เป็นประเภทพิเศษที่มีเมธอด [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | ตัวเข้าถึงสำหรับเมธอด [end()](../../system/smartptr/end/) ของคอลเล็กชันภายใน. จะคอมไพล์ได้เท่านั้นหาก SmartPtr_ เป็นประเภทพิเศษที่มีเมธอด [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | รับอ็อบเจกต์ที่ชี้. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | รับโหมดของพอยน์เตอร์. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | ดึงอ็อบเจกต์ที่ชี้, แต่ตรวจสอบว่าพอยน์เตอร์อยู่ในโหมด shared. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | รับจำนวนพอยน์เตอร์ shared ที่มีต่ออ็อบเจกต์ที่อ้างอิง, รวมถึงพอยน์เตอร์ปัจจุบัน. ตรวจสอบว่าพอยน์เตอร์ปัจจุบันอยู่ในโหมด shared. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | เรียก [GetHashCode()](../../system/smartptr/gethashcode/) บนอ็อบเจกต์ที่ชี้. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | รับอ็อบเจกต์ที่อ้างอิงอยู่ในขณะนี้ (ถ้ามี) หรือโยนข้อยกเว้น. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | รับอ็อบเจกต์ที่ชี้ (ถ้ามี) หรือ nullptr. มีค่าเท่ากับ [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | รับอ็อบเจกต์ที่อ้างอิง. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | รับอ็อบเจกต์ที่ชี้ (ถ้ามี) หรือ nullptr. มีค่าเท่ากับ [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์ที่ชี้เป็นประเภทเฉพาะหรือเป็นประเภทลูกของมัน. ปฏิบัติตาม semantics ของ C# 'is'. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | ตรวจสอบว่าพอยน์เตอร์ชี้ไปยังอ็อบเจกต์อื่นที่ไม่ได้เป็นเจ้าของ (สร้างโดยคอนสตรัคเตอร์ aliasing). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | ตรวจสอบว่าพอยน์เตอร์อยู่ในโหมด shared. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | ตรวจสอบว่าพอยน์เตอร์อยู่ในโหมด weak. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | ตรวจสอบว่าพอยน์เตอร์ไม่เป็น null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | ตรวจสอบว่าพอยน์เตอร์เป็น null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | รับอ้างอิงไปยังอ็อบเจกต์ที่ชี้. ตรวจสอบว่าพอยน์เตอร์ไม่เป็น null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | ให้เข้าถึงสมาชิกของอ็อบเจกต์ที่อ้างอิง. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | ให้ semantics การเปรียบเทียบน้อยกว่าสำหรับคลาส [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | ให้ semantics การเปรียบเทียบน้อยกว่าสำหรับคลาส [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | ทำการมูฟ-แอสไซน์อ็อบเจกต์ [SmartPtr](../../system/smartptr/). x จะใช้ไม่ได้. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | ทำการคอปี้-แอสไซน์อ็อบเจกต์ [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | ทำการคอปี้-แอสไซน์อ็อบเจกต์ [SmartPtr](../../system/smartptr/). ทำการแปลงประเภทตามที่ต้องการ. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | กำหนดพอยน์เตอร์ดิบให้กับอ็อบเจกต์ [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | ตั้งค่าพอยน์เตอร์เป็น nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | ตรวจสอบว่าพอยน์เตอร์ชี้ไปที่ nullptr. |
| [SharedPtr](../../system/sharedptr/)\<[X509Certificate2](../x509certificate2/)\>\& [operator[]](./operator[]/)(size_t) const | ตัวเข้าถึง. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | ลบการทำ aliasing (ที่สร้างโดยคอนสตรัคเตอร์ aliasing) จากพอยน์เตอร์, ทำให้แน่ใจว่ามันจัดการ (หาก shared) หรือทำตาม (หาก weak) อ็อบเจกต์เดียวกันที่ชี้. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | ตั้งค่าอ็อบเจกต์ที่ชี้. |
| void [reset](../../system/smartptr/reset/)() | ทำให้พอยน์เตอร์ชี้ไปที่ nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | ตั้งค่าโหมดพอยน์เตอร์. อาจเปลี่ยนจำนวนอ้างอิงของอ็อบเจกต์ที่อ้างอิง. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | เรียกเมธอด SetTemplateWeakPtr() บนอ็อบเจกต์ที่ชี้ (ถ้ามี). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | สร้างอ็อบเจกต์ [SmartPtr](../../system/smartptr/) ในโหมดที่ต้องการ. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | สร้างอ็อบเจกต์ [SmartPtr](../../system/smartptr/) แบบ null-pointer ในโหมดที่ต้องการ. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | สร้าง [SmartPtr](../../system/smartptr/) ที่ชี้ไปยังอ็อบเจกต์ที่ระบุ, หรือแปลงพอยน์เตอร์ดิบเป็น [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | คัดลอกสร้างอ็อบเจกต์ [SmartPtr](../../system/smartptr/). พอยน์เตอร์ทั้งสองจะชี้ไปยังอ็อบเจกต์เดียวกันหลังจากนั้น. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | คัดลอกสร้างอ็อบเจกต์ [SmartPtr](../../system/smartptr/). พอยน์เตอร์ทั้งสองจะชี้ไปยังอ็อบเจกต์เดียวกันหลังจากนั้น. ทำการแปลงประเภทหากอนุญาต. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | มูฟสร้างอ็อบเจกต์ [SmartPtr](../../system/smartptr/). โดยการสลับพอยน์เตอร์สองตัวหากทั้งสองอยู่ในโหมดเดียวกัน. x อาจใช้ไม่ได้หลังจากเรียก. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | แปลงประเภทของอาเรย์ที่อ้างอิงโดยสร้างอาเรย์ใหม่ที่เป็นประเภทต่างกัน. มีประโยชน์หากใน C# มีการคาสต์อาเรย์ที่ไม่รองรับใน C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | เริ่มต้นอาเรย์เปล่า. ใช้สำหรับแปลโครงสร้างโค้ดบางส่วนของ C#. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | สร้าง [SmartPtr](../../system/smartptr/) ที่แชร์ข้อมูลการเป็นเจ้าของกับค่าเริ่มต้นของ ptr, แต่ถือพอยน์เตอร์ p ที่ไม่เกี่ยวข้องและไม่มีการจัดการ. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | แคสต์พอยน์เตอร์เป็นประเภทอื่นโดยใช้ static_cast บนอ็อบเจกต์ที่ชี้. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | แปลงประเภทพอยน์เตอร์ใดก็ได้เป็นพอยน์เตอร์ไปยัง [Object](../../system/object/). ไม่จำเป็นต้องให้ประเภท Pointee_ เสร็จสมบูรณ์. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | ทางลัดเพื่อรับอ็อบเจกต์ [System::TypeInfo](../../system/typeinfo/) สำหรับประเภท Pointee_. |
|  [X509Certificate2CollectionPtr](./x509certificate2collectionptr/)() | คอนสตรัคเตอร์พอยน์เตอร์ null. |
|  [X509Certificate2CollectionPtr](./x509certificate2collectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[X509Certificate2Collection](../x509certificate2collection/)\>\&) | คอนสตรัคเตอร์. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | ทำลายอ็อบเจกต์ [SmartPtr](../../system/smartptr/). หากจำเป็น, ลดตัวนับอ้างอิงของอ็อบเจกต์ที่ชี้และลบอ็อบเจกต์. |

## ดูเพิ่มเติม

* คลาส [SmartPtr](../../system/smartptr/)
* เนมสเปซ [System::Security::Cryptography::X509Certificates](../)
* ไลบรารี [Aspose.Slides](../../)