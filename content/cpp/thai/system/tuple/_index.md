---
title: Tuple
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คลาสที่เป็นตัวแทนของโครงสร้างข้อมูล tuple จำนวนรายการสูงสุดคือ 8 รายการ.
type: docs
weight: 1353
url: /th/system/tuple/
---
## คลาส Tuple


คลาสที่เป็นตัวแทนของโครงสร้างข้อมูล tuple จำนวนรายการสูงสุดคือ 8 รายการ.

```cpp
template<typename ...>class Tuple : public System::Runtime::CompilerServices::ITuple
```


### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Args | ประเภทขององค์ประกอบ tuple. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) override | กำหนดว่าวัตถุปัจจุบันและวัตถุที่ระบุเป็นเหมือนกันหรือไม่. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | เปรียบเทียบวัตถุโดยใช้แนวคิดของ C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุแบบอ้างอิงในสไตล์ C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับภายในเท่านั้น. |
| std::tuple_element\<[Index](../index/), tuple_t\>::type [get_Item](./get_item/)() const | ดึงค่าของส่วนประกอบของวัตถุ [Tuple](./). |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | ดึงโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | เป็นคล้ายกับเมธอด [Object.GetHashCode()](../object/gethashcode/) ของ C#. ทำให้สามารถแฮชวัตถุที่กำหนดเองได้. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | ดึงประเภทจริงของวัตถุ. คล้ายกับการเรียก [System.Object.GetType()](../object/gettype/) ของ C#. |
| virtual [SharedPtr](../sharedptr/)\<[Object](../object/)\> [idx_get](../../system.runtime.compilerservices/ituple/idx_get/)(**int32_t**) const | ส่งกลับสมาชิกที่ตำแหน่งดัชนี. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. คล้ายกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุกุญแจ [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | เป็นคล้ายกับเมธอด [Object.MemberwiseClone()](../object/memberwiseclone/) ของ C#. ทำให้สามารถทำการคัดลอกประเภทที่กำหนดเองได้. |
|  [Object](../object/object/)() | สร้างวัตถุ. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../object/object/)([Object](../object/) const\&) | คอนสตรัคเตอร์สำเนา. จริงๆ แล้วไม่ได้คัดลอกรายการใดๆ เพียงแค่เริ่มต้นวัตถุใหม่และทำให้สามารถสร้างสำเนาในคล้ายย่อยได้. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | ตัวดำเนินการกำหนดค่า. จริงๆ แล้วไม่ได้คัดลอกรายการใดๆ เพียงแค่เริ่มต้นวัตถุใหม่และทำให้สามารถสร้างสำเนาในคล้ายย่อยได้. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | เปรียบเทียบวัตถุตามการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุตามการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงวัตถุประเภทค่ากับ nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | การเฉพาะสำหรับ [Object::ReferenceEquals](../object/referenceequals/) ในกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | การเฉพาะสำหรับ [Object::ReferenceEquals](../object/referenceequals/) ในกรณีของสตริง. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงแชร์ด้วยค่าที่ระบุ. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทนการเป็น shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../object/sharedcount/)() const | ดึงค่าปัจจุบันของตัวนับอ้างอิงแชร์. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงแชร์. ไม่ควรเรียกโดยตรง; แทนให้ใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ลดจำนวนและคืนค่าตัวนับอ้างอิงแชร์. ไม่ควรเรียกโดยตรง; แทนให้ใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | เป็นคล้ายกับเมธอด [Object.ToString()](../object/tostring/) ของ C#. ทำให้สามารถแปลงวัตถุที่กำหนดเองเป็นสตริงได้. |
|  [Tuple](./tuple/)(Args...) | สร้างวัตถุ tuple. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | ทำหน้าที่ typeof([System.Object](../object/)) ของ C#. |
| void [Unlock](../object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุกุญแจ [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิง weak. ไม่ควรเรียกโดยตรง; แทนให้ใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ลดจำนวนตัวนับอ้างอิง weak. ไม่ควรเรียกโดยตรง; แทนให้ใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../object/~object/)() | ทำลายวัตถุ. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
## หมายเหตุ



```cpp
#include "system/smart_ptr.h"
#include "system/tuple.h"
#include <iostream>

int main()
{
  const auto tuple = System::MakeObject<System::Tuple<int, int, int>>(32, 16, 128);

  std::cout <<
    "Item 1: " << tuple->get_Item<0>() << std::endl <<
    "Item 2: " << tuple->get_Item<1>() << std::endl <<
    "Item 3: " << tuple->get_Item<2>() << std::endl;

  return 0;
}
/*
ตัวอย่างโค้ดนี้สร้างผลลัพธ์ต่อไปนี้:
รายการ 1: 32
รายการ 2: 16
รายการ 3: 128
*/
```

## ดูเพิ่มเติม

* คลาส [ITuple](../../system.runtime.compilerservices/ituple/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)