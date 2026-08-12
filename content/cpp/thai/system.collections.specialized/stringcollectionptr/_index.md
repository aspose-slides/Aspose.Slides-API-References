---
title: StringCollectionPtr
second_title: Aspose.Slides สำหรับ C++ API Reference
description: คอลเลกชันสตริงที่มีตัวชี้พร้อมตัวดำเนินการเข้าถึง
type: docs
weight: 40
url: /th/system.collections.specialized/stringcollectionptr/
---
## StringCollectionPtr คลาส

Stirng คอลเลกชันของที่มีตัวชี้พร้อมตัวดำเนินการเข้าถึง.

```cpp
class StringCollectionPtr : public System::SmartPtr<StringCollection>
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | ตัวเข้าถึงสำหรับเมธอด [begin()](../../system/smartptr/begin/) ของคอลเลกชันพื้นฐาน คอมไพล์ได้ก็ต่อเมื่อ SmartPtr_ เป็นประเภทพิเศษที่มีเมธอด [begin()](../../system/smartptr/begin/) |
| auto [begin](../../system/smartptr/begin/)() const | ตัวเข้าถึงสำหรับเมธอด [begin()](../../system/smartptr/begin/) ของคอลเลกชันพื้นฐาน คอมไพล์ได้ก็ต่อเมื่อ SmartPtr_ เป็นประเภทพิเศษที่มีเมธอด [begin()](../../system/smartptr/begin/) |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | แคสต์ตัวชี้เป็นประเภทของมันเอง |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | แคสต์ตัวชี้เป็นประเภทฐานโดยใช้ static_cast |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | แคสต์ตัวชี้เป็นประเภทที่สืบทอดโดยใช้ dynamic_cast |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | แคสต์ตัวชี้เป็นประเภทที่สืบทอดโดยใช้ dynamic_cast |
| auto [cbegin](../../system/smartptr/cbegin/)() const | ตัวเข้าถึงสำหรับเมธอด [cbegin()](../../system/smartptr/cbegin/) ของคอลเลกชันพื้นฐาน คอมไพล์ได้ก็ต่อเมื่อ SmartPtr_ เป็นประเภทพิเศษที่มีเมธอด [cbegin()](../../system/smartptr/cbegin/) |
| auto [cend](../../system/smartptr/cend/)() const | ตัวเข้าถึงสำหรับเมธอด [cend()](../../system/smartptr/cend/) ของคอลเลกชันพื้นฐาน คอมไพล์ได้ก็ต่อเมื่อ SmartPtr_ เป็นประเภทพิเศษที่มีเมธอด [cend()](../../system/smartptr/cend/) |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | แคสต์ตัวชี้เป็นประเภทต่างโดยใช้ const_cast กับอ็อบเจ็กต์ที่ชี้ |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | แคสต์ตัวชี้เป็นประเภทต่างโดยใช้ dynamic_cast กับอ็อบเจ็กต์ที่ชี้ |
| auto [end](../../system/smartptr/end/)() | ตัวเข้าถึงสำหรับเมธอด [end()](../../system/smartptr/end/) ของคอลเลกชันพื้นฐาน คอมไพล์ได้ก็ต่อเมื่อ SmartPtr_ เป็นประเภทพิเศษที่มีเมธอด [end()](../../system/smartptr/end/) |
| auto [end](../../system/smartptr/end/)() const | ตัวเข้าถึงสำหรับเมธอด [end()](../../system/smartptr/end/) ของคอลเลกชันพื้นฐาน คอมไพล์ได้ก็ต่อเมื่อ SmartPtr_ เป็นประเภทพิเศษที่มีเมธอด [end()](../../system/smartptr/end/) |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | ดึงอ็อบเจ็กต์ที่ชี้ |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | รับโหมดของตัวชี้ |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | ดึงอ็อบเจ็กต์ที่ชี้ แต่ตรวจสอบว่าตัวชี้อยู่ในโหมด shared |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | รับจำนวนตัวชี้แบบ shared ที่อ้างอิงอ็อบเจ็กต์ (รวมถึงตัวปัจจุบัน) ตรวจสอบว่าตัวชี้ปัจจุบันอยู่ในโหมด shared |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | เรียก [GetHashCode()](../../system/smartptr/gethashcode/) บนอ็อบเจ็กต์ที่ชี้ |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | รับอ็อบเจ็กต์ที่อ้างอิงอยู่ (ถ้ามี) หรือโยนข้อผิดพลาด |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | ดึงอ็อบเจ็กต์ที่ชี้ (ถ้ามี) หรือ nullptr. เหมือนกับ [get()](../../system/smartptr/get/) |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | รับอ็อบเจ็กต์ที่อ้างอิง |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | ดึงอ็อบเจ็กต์ที่ชี้ (ถ้ามี) หรือ nullptr. เหมือนกับ [get()](../../system/smartptr/get/) |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าตัวชี้อ้างอิงอ็อบเจ็กต์เป็นประเภทเฉพาะหรือเป็นประเภทลูกของมัน ทำตาม semantics ของ C# 'is' |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | ตรวจสอบว่าตัวชี้ชี้ไปยังอ็อบเจ็กต์อื่นที่ไม่ใช่ที่เป็นเจ้าของ (สร้างโดยคอนสตรัคเตอร์ aliasing) |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | ตรวจสอบว่าตัวชี้อยู่ในโหมด shared |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | ตรวจสอบว่าตัวชี้อยู่ในโหมด weak |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | ตรวจสอบว่าตัวชี้ไม่เป็น null |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | ตรวจสอบว่าตัวชี้เป็น null |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | รับอ้างอิงไปยังอ็อบเจ็กต์ที่ชี้ ตรวจสอบว่าตัวชี้ไม่เป็น null |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | อนุญาตให้เข้าถึงสมาชิกของอ็อบเจ็กต์ที่อ้างอิง |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | ให้ semantics การเปรียบเทียบน้อยสำหรับคลาส [SmartPtr](../../system/smartptr/) |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | ให้ semantics การเปรียบเทียบน้อยสำหรับคลาส [SmartPtr](../../system/smartptr/) |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | ย้าย-กำหนดค่าให้กับอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/). x จะไม่สามารถใช้ได้ |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | คัดลอก-กำหนดค่าให้กับอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/) |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | คัดลอก-กำหนดค่าให้กับอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/) ทำการแปลงประเภทตามที่ต้องการ |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | กำหนดตัวชี้ดิบให้กับอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/) |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | ตั้งค่าตัวชี้เป็น nullptr |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | ตรวจสอบว่าตัวชี้ชี้ไปยัง nullptr |
| [System::String](../../system/string/)\& [operator[]](./operator[]/)(int) const | ฟังก์ชันเข้าถึง |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | ลบการ aliasing (ที่สร้างโดยคอนสตรัคเตอร์ aliasing) จากตัวชี้ ทำให้แน่ใจว่ามันจัดการ (ถ้า shared) หรือติดตาม (ถ้า weak) อ็อบเจ็กต์เดียวกันที่ชี้ |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | กำหนดอ็อบเจ็กต์ที่ชี้ |
| void [reset](../../system/smartptr/reset/)() | ทำให้ตัวชี้ชี้ไปยัง nullptr |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | ตั้งค่าโหมดของตัวชี้ อาจเปลี่ยนจำนวนการอ้างอิงของอ็อบเจ็กต์ที่อ้างอิง |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | เรียกเมธอด SetTemplateWeakPtr() บนอ็อบเจ็กต์ที่ชี้ (ถ้ามี) |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | สร้างอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/) ที่มีโหมดตามต้องการ |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | สร้างอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/) ที่เป็น null-pointer ตามโหมดที่ต้องการ |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | สร้าง [SmartPtr](../../system/smartptr/) ที่ชี้ไปยังอ็อบเจ็กต์ที่ระบุ หรือแปลงตัวชี้ดิบเป็น [SmartPtr](../../system/smartptr/) |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | คัดลอกสร้างอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/) ตัวชี้ทั้งสองจะชี้ไปยังอ็อบเจ็กต์เดียวกันหลังจากนั้น |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | คัดลอกสร้างอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/) ตัวชี้ทั้งสองจะชี้ไปยังอ็อบเจ็กต์เดียวกันหลังจากนั้น ทำการแปลงประเภทหากอนุญาต |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | ย้ายสร้างอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/) โดยสลับตัวชี้สองตัว หากทั้งสองอยู่ในโหมดเดียวกัน x อาจใช้ไม่ได้หลังจากเรียก |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | แปลงประเภทของอาร์เรย์ที่อ้างอิงโดยสร้างอาร์เรย์ใหม่ของประเภทต่างกัน มีประโยชน์เมื่อใน C# มีการ cast ประเภทของอาร์เรย์ซึ่งไม่รองรับใน C++ |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | สร้างอาร์เรย์เปล่า ใช้เพื่อแปลงโค้ด C# บางส่วน |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | สร้าง [SmartPtr](../../system/smartptr/) ที่แชร์ข้อมูลความเป็นเจ้าของกับค่าเริ่มต้นของ ptr แต่เก็บตัวชี้ที่ไม่เกี่ยวข้องและไม่ได้จัดการ p |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | แคสต์ตัวชี้เป็นประเภทอื่นโดยใช้ static_cast บนอ็อบเจ็กต์ที่ชี้ |
|  [StringCollectionPtr](./stringcollectionptr/)() | สร้างตัวชี้เป็น null |
|  [StringCollectionPtr](./stringcollectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[StringCollection](../stringcollection/)\>\&) | สร้างตัวชี้ไปยังคอลเลกชันที่ระบุ |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | แปลงประเภทตัวชี้ใดๆ ให้เป็นตัวชี้ไปยัง [Object](../../system/object/) ไม่จำเป็นต้องให้ประเภท Pointee_ สมบูรณ์ |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | ทางลัดเพื่อรับอ็อบเจ็กต์ [System::TypeInfo](../../system/typeinfo/) สำหรับประเภท Pointee_ |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | ทำลายอ็อบเจ็กต์ [SmartPtr](../../system/smartptr/) หากจำเป็นจะลดตัวนับการอ้างอิงของอ็อบเจ็กต์ที่ชี้และลบอ็อบเจ็กต์ |

## ดูเพิ่มเติม

* คลาส [SmartPtr](../../system/smartptr/)
* เนมสเปซ [System::Collections::Specialized](../)
* ไลบรารี [Aspose.Slides](../../)