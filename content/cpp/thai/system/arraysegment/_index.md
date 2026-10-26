---
title: ArraySegment
second_title: "อ้างอิง API Aspose.Slides สำหรับ C++"
description: "แสดงส่วนของอาร์เรย์มิติเดียว ประเภทนี้ควรจัดสรรบนสแตกและส่งผ่านให้ฟังก์ชันโดยค่าหรือโดยอ้างอิง ไม่ควรใช้คลาส System::SmartPtr เพื่อจัดการอ็อบเจ็กต์ประเภทนี้"
type: docs
weight: 40
url: /th/system/arraysegment/
---
## ArraySegment คลาส


Represents a segment of the one-dimensional array. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
template<typename T>class ArraySegment : public System::Object
```


### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T | The type of the array segment elements. |
## เมธอด

| Method | Description |
| --- | --- |
|  [ArraySegment](./arraysegment/)([System::ArrayPtr](../arrayptr/)\<T\>) |  |
|  [ArraySegment](./arraysegment/)([System::ArrayPtr](../arrayptr/)\<T\>, **int32_t**, **int32_t**) |  |
|  [ArraySegment](./arraysegment/)() |  |
| **bool** [Equals](./equals/)([System::SharedPtr](../sharedptr/)\<[Object](../object/)\>) override |  |
| **bool** [Equals](./equals/)([ArraySegment](./)\<T\>) |  |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้รูปแบบ C# [Object.Equals](../object/equals/) |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C# |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# โดยถือว่า NaN สองค่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# โดยถือว่า NaN สองค่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับการทำงานภายในเท่านั้น |
| [System::ArrayPtr](../arrayptr/)\<T\> [get_Array](./get_array/)() const |  |
| **int32_t** [get_Count](./get_count/)() const |  |
| **int32_t** [get_Offset](./get_offset/)() const |  |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมกับอ็อบเจ็กต์ |
| **int32_t** [GetHashCode](./gethashcode/)() const override | สมการของเมธอด C# [Object.GetHashCode()](../object/gethashcode/) เปิดใช้งานการแฮชอ็อบเจ็กต์แบบกำหนดเอง |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | รับประเภทที่แท้จริงของอ็อบเจ็กต์ สมการของการเรียก C# [System.Object.GetType()](../object/gettype/) |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่ระบุโดย targetType สมการของตัวดำเนินการ C# 'is' |
| void [Lock](../object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# การล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/) |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | สมการของเมธอด C# [Object.MemberwiseClone()](../object/memberwiseclone/) เปิดใช้งานการโคลนประเภทกำหนดเอง |
|  [Object](../object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../object/object/)([Object](../object/) const\&) | ตัวสร้างสำเนา ไม่ได้คัดลอกสิ่งใด เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสร้างสำเนาสำหรับคลาสย่อย |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกสิ่งใด เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสร้างสำเนาสำหรับคลาสย่อย |
| T\& [operator[]](./operator[]/)(**int32_t**) const |  |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีสตริงและ nullptr |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีสตริง |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | ลดค่าเคาน์เตอร์อ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทน shared) อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../object/sharedcount/)() const | รับค่าปัจจุบันของเคาน์เตอร์อ้างอิงที่แชร์ |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | เพิ่มค่าเคาน์เตอร์อ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง ใช้ smart pointer หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ลดค่าและคืนค่าเคาน์เตอร์อ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง ใช้ smart pointer หรือ ThisProtector แทน |
| [ArraySegment](./)\<T\> [Slice](./slice/)(**int32_t**, **int32_t**) |  |
| [System::ArrayPtr](../arrayptr/)\<T\> [ToArray](./toarray/)() const |  |
| virtual [String](../string/) [ToString](../object/tostring/)() const | สมการของเมธอด C# [Object.ToString()](../object/tostring/) เปิดใช้งานการแปลงอ็อบเจ็กต์แบบกำหนดเองเป็นสตริง |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | ทำงานตาม construct C# typeof([System.Object](../object/)) |
| void [Unlock](../object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# การปลดล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | เพิ่มค่าเคาน์เตอร์อ้างอิงที่ weak ไม่ควรเรียกโดยตรง ใช้ smart pointer หรือ ThisProtector แทน |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ลดค่าเคาน์เตอร์อ้างอิงที่ weak ไม่ควรเรียกโดยตรง ใช้ smart pointer หรือ ThisProtector แทน |
| virtual  [~Object](../object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |
## หมายเหตุ



```cpp
#include <system/array_segment.h>
#include <system/smart_ptr.h>

using namespace System;

void Print(const SmartPtr<ArraySegment<String>> &segment)
{
  for (auto i = segment->get_Offset(); i < segment->get_Offset() + segment->get_Count(); i++)
  {
    std::cout << segment->get_Array()[i] << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // สร้างและเติมข้อมูลในอาร์เรย์.
  auto array = System::MakeObject<Array<String>>(3);
  array[0] = u"First";
  array[1] = u"Second";
  array[2] = u"Third";

  // สร้างส่วนของอาร์เรย์ที่ประกอบด้วยอาร์เรย์ทั้งหมด.
  auto fullArray = MakeObject<ArraySegment<String>>(array);

  // พิมพ์รายการของส่วนอาร์เรย์.
  Print(fullArray);

  // สร้างส่วนของอาร์เรย์.
  auto segment = MakeObject<ArraySegment<String>>(array, 1, 2);

  // พิมพ์รายการของส่วนอาร์เรย์.
  Print(segment);

  return 0;
}
/*
ตัวอย่างโค้ดนี้แสดงผลตามต่อไปนี้:
First Second Third
Second Third
*/
```

## ดูเพิ่มเติม

* คลาส [Object](../object/)
* เนมส페ซ [System](../)
* ไลบรารี [Aspose.Slides](../../)