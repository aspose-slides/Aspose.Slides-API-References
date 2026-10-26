---
title: Random
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "แสดงถึงตัวสร้างตัวเลขสุ่มแบบเทียม วัตถุของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการตรวจสอบล้มเหลว ควรห่อคลาสนี้ด้วยพอยเตอร์ System::SmartPtr และใช้พอยเตอร์นี้ส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน"
type: docs
weight: 1184
url: /th/system/random/
---
## คลาส Random


แสดงถึงตัวสร้างตัวเลขสุ่มแบบเทียม วัตถุของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../makeobject/) เท่านั้น หลีกเลี่ยงการสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการตรวจสอบล้มเหลว เสมอห่อคลาสนี้ไว้ในพอยเตอร์ [System::SmartPtr](../smartptr/) และใช้พอยเตอร์นี้ส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน

```cpp
class Random : public System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ semantics ของ C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบตัวเลขแบบ floating point สไตล์ C# โดยถือว่า NaN สองค่ามีค่าเท่ากันแม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบตัวเลขแบบ floating point สไตล์ C# โดยถือว่า NaN สองค่ามีค่าเท่ากันแม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | เป็นการทำงานเทียมของเมธอด C# [Object.GetHashCode()](../object/gethashcode/). เปิดใช้งานการแฮชออบเจ็กต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | รับชนิดจริงของวัตถุ. เป็นการทำงานเทียมของการเรียก C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของชนิดที่อธิบายโดย targetType หรือไม่. เป็นการทำงานเทียมของโอเปอเรเตอร์ C# 'is'. |
| **bool** [IsNull](./isnull/)() const | คืนค่า false เสมอ. |
| void [Lock](../object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# สำหรับการล็อค. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | เป็นการทำงานเทียมของเมธอด C# [Object.MemberwiseClone()](../object/memberwiseclone/). เปิดใช้งานการโคลนชนิดที่กำหนดเอง. |
| virtual **int32_t** [Next](./next/)() | คืนค่าตัวเลขสุ่มที่ไม่เป็นลบซึ่งน้อยกว่าค่าสูงสุดของ int32. |
| virtual **int32_t** [Next](./next/)(**int32_t**) | คืนค่าตัวเลขสุ่มที่ไม่เป็นลบซึ่งน้อยกว่าค่าสูงสุดที่ระบุ. |
| virtual **int32_t** [Next](./next/)(**int32_t**, **int32_t**) | คืนค่าตัวเลขสุ่มภายในช่วงที่ระบุ. |
| virtual void [NextBytes](./nextbytes/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | เติมสมาชิกของอาร์เรย์ไบต์ที่ระบุด้วยตัวเลขสุ่ม. |
| virtual **double** [NextDouble](./nextdouble/)() | คืนค่าตัวเลขสุ่มระหว่าง 0.0 ถึง 1.0. |
|  [Object](../object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../object/object/)([Object](../object/) const\&) | คอนสตรักเตอร์สำเนา. ไม่ได้คัดลอกอะไรจริงๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาสำหรับซับคลาส. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกอะไรจริงๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาสำหรับซับคลาส. |
|  [Random](./random/)() | เริ่มต้นอินสแตนซ์ใหม่โดยใช้ค่า seed เริ่มต้นที่ขึ้นกับเวลา. |
|  [Random](./random/)(**int32_t**) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [System.Random](./) โดยใช้ค่า seed ที่ระบุ. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงออบเจ็กต์ประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | การปรับใช้พิเศษของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณี string และ nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | การปรับใช้พิเศษของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงแบบแชร์โดยค่าที่ระบุ. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | กำหนดอาร์กิวเมนต์แม่แบบที่ n ให้เป็น weak pointer (แทนที่จะแชร์). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงแบบแชร์. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบแชร์. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงแบบแชร์และคืนค่า. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | เป็นการทำงานเทียมของเมธอด C# [Object.ToString()](../object/tostring/). เปิดใช้งานการแปลงออบเจ็กต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | ทำงานตามโครงสร้าง typeof([System.Object](../object/)) ของ C#. |
| void [Unlock](../object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อค. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
## หมายเหตุ



```cpp
#include "system/random.h"
#include "system/smart_ptr.h"
#include <iostream>

int main()
{
  const auto rnd = System::MakeObject<System::Random>();

  // รับเลขเดือนแบบสุ่มและพิมพ์ออกมา.
  auto monthNumber = rnd->Next(1, 13);
  std::cout << "Month: " << monthNumber << std::endl;

  // เติมอาร์เรย์ด้วยตัวเลขสุ่ม.
  auto arr = System::MakeObject<System::Array<uint8_t>>(12);
  rnd->NextBytes(arr);

  // พิมพ์อาร์เรย์.
  for (auto i = 0; i < arr->get_Length(); ++i)
  {
    std::cout << static_cast<int>(arr[i]) << ' ';
  }
  std::cout << std::endl;

  return 0;
}
/*
ตัวอย่างโค้ดนี้จะสร้างผลลัพธ์ต่อไปนี้:
Month: 4
177 213 89 240 68 182 18 96 109 131 1 78
*/
```

## ดูเพิ่มเติม

* คลาส [Object](../object/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)