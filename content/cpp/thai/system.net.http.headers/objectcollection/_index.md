---
title: ObjectCollection
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงคอลเลกชันของวัตถุ
type: docs
weight: 196
url: /th/system.net.http.headers/objectcollection/
---
## ObjectCollection คลาส

แสดงถึงคอลเลกชันของวัตถุ.

```cpp
template<typename T>class ObjectCollection : public System::Collections::ObjectModel::Collection<T>
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของวัตถุ วัตถุของคลาสนี้ควรได้รับการจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการอ้างอิงเสมอ ควรห่อคลาสนี้ด้วยพอยเตอร์ [System::SmartPtr](../../system/smartptr/) และใช้พอยเตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| void [Add](../../system.collections.objectmodel/collection/add/)(const T\&) override | เพิ่มค่าเข้าไปในคอนเทนเนอร์ |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | รับ iterator ที่ชี้ไปยังอิลิเมนต์แรก (ถ้ามี) ของคอลเลกชัน iterator นี้ไม่สามารถใช้เพื่อเปลี่ยนอ็อบเจกต์ที่อ้างอิงได้เพราะ [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) คืนค่าอ็อบเจ็กต์สำเนาของ T |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | รับ iterator ที่ชี้ไปยังอิลิเมนต์แรก (ถ้ามี) ของอินสแตนซ์ที่กำหนดค่าคงที่ของคอลเลกชัน |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | รับ iterator ที่ชี้ไปยังอิลิเมนต์ที่กำหนดค่าคงที่แรก (ถ้ามี) ของคอลเลกชัน |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | รับ iterator ที่ชี้หลังอิลิเมนต์ที่กำหนดค่าคงที่สุดท้าย (ถ้ามี) ของคอลเลกชัน |
| void [Clear](../../system.collections.objectmodel/collection/clear/)() override | ลบทุกอิลิเมนต์ |
|  [Collection](../../system.collections.objectmodel/collection/collection/)() | สร้างคอลเลกชันเปล่า |
|  [Collection](../../system.collections.objectmodel/collection/collection/)([SharedPtr](../../system/sharedptr/)\<[Generic::IList](../../system.collections.generic/ilist/)\<T\>\>) |  |
| **bool** [Contains](../../system.collections.objectmodel/collection/contains/)(const T\&) const override | ตรวจสอบว่ารายการมีอยู่ในคอลเลกชันหรือไม่ |
| void [CopyTo](../../system.collections.objectmodel/collection/copyto/)([ArrayPtr](../../system/arrayptr/)\<T\>, int) override | คัดลอกอิลิเมนต์ของคอลเลกชันเข้าไปในอาร์เรย์ที่มีอยู่แล้ว |
| [const_reverse_iterator](../../system.collections.objectmodel/collection/const_reverse_iterator/) [crbegin](../../system.collections.objectmodel/collection/crbegin/)() const | รับ reverse iterator ไปยังอิลิเมนต์คงที่สุดท้ายของคอลเลกชัน (อิลิเมนต์แรกในลำดับย้อนกลับ) |
| [const_reverse_iterator](../../system.collections.objectmodel/collection/const_reverse_iterator/) [crend](../../system.collections.objectmodel/collection/crend/)() const | รับ reverse iterator สำหรับอิลิเมนต์คงที่ที่ไม่มีอยู่ก่อนจุดเริ่มต้นของคอลเลกชัน |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | รับ iterator ที่ชี้หลังอิลิเมนต์สุดท้าย (ถ้ามี) ของคอลเลกชัน iterator นี้ไม่สามารถใช้เพื่อเปลี่ยนอ็อบเจกต์ที่อ้างอิงได้เพราะ [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) คืนค่าอ็อบเจ็กต์สำเนาของ T |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | รับ iterator ที่ชี้หลังอิลิเมนต์สุดท้าย (ถ้ามี) ของอินสแตนซ์ที่กำหนดค่าคงที่ของคอลเลกชัน |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์แบบอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์แบบค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดทศนิยมสไตล์ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดทศนิยมสไตล์ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้ภายในเท่านั้น |
| int [get_Count](../../system.collections.objectmodel/collection/get_count/)() const override | รับจำนวนอิลิเมนต์ |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | ตรวจสอบว่าคอลเลกชันมีขนาดคงที่หรือไม่ |
| virtual **bool** [get_IsReadOnly](../../system.collections.generic/icollection/get_isreadonly/)() const | ตรวจสอบว่าคอลเลกชันเป็นแบบอ่านอย่างเดียวหรือไม่ |
| [SharedPtr](../../system/sharedptr/)\<[Generic::IList](../../system.collections.generic/ilist/)\<T\>\> [get_Items](../../system.collections.objectmodel/collection/get_items/)() | ตัวเข้าถึงโครงสร้างข้อมูลภายใน |
| const [Generic::ListPtr](../../system.collections.generic/listptr/)\<T\> [get_Items](../../system.collections.objectmodel/collection/get_items/)() const | ตัวเข้าถึงโครงสร้างข้อมูลภายใน |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | รับอ็อบเจกต์ที่คอลเลกชันซิงค์ไว้ผ่าน |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์ |
| [SharedPtr](../../system/sharedptr/)\<[Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<T\>\> [GetEnumerator](../../system.collections.objectmodel/collection/getenumerator/)() override | รับ enumerator เพื่อวนผ่านคอลเลกชัน |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | อนาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) เปิดใช้งานการแฮชอ็อบเจกต์ที่กำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับชนิดจริงของอ็อบเจกต์ อนาล็อกของการเรียก [System.Object.GetType()](../../system/object/gettype/) ของ C# |
|  [ICollection](../../system.collections.generic/icollection/icollection/)() | ตัวสร้างเริ่มต้น |
|  [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | ตัวสร้างสำเนา |
|  [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | ตัวสร้างย้าย |
| T [idx_get](../../system.collections.objectmodel/collection/idx_get/)(int) const override | รับค่าที่ตำแหน่งดัชนีที่ระบุ |
| void [idx_set](../../system.collections.objectmodel/collection/idx_set/)(int, T) override | ตั้งค่าที่ตำแหน่งดัชนีที่ระบุ |
| int [IndexOf](../../system.collections.objectmodel/collection/indexof/)(const T\&) const override | ค้นหาอิลิเมนต์ในคอลเลกชัน |
| void [Insert](../../system.collections.objectmodel/collection/insert/)(int, const T\&) override | แทรกรายการที่ตำแหน่งที่ระบุ |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของชนิดที่อธิบายโดย targetType หรือไม่ อนาล็อกของโอเปอร์เตอร์ 'is' ของ C# |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | ใช้ฟังก์ชัน accumulator กับลำดับ |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | กำหนดว่าทุกอิลิเมนต์ของลำดับเป็นไปตามเงื่อนไขหรือไม่ |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | กำหนดว่าลำดับมีอิลิเมนต์ใด ๆ หรือไม่ |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | กำหนดว่ามีอิลิเมนต์ใดที่ตรงกับเงื่อนไขหรือไม่ |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | คำนวณค่าเฉลี่ยของลำดับค่าตัวเลข |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | คำนวณค่าเฉลี่ยของลำดับค่าที่ได้จากการเรียกฟังก์ชันแปลงบนแต่ละอิลิเมนต์ของลำดับอินพุต |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | แปลงประเภทของอิลิเมนต์เป็นชนิดที่ระบุ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | ต่อเชื่อมสองลำดับ |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | กำหนดว่าลำดับประกอบด้วยค่าที่ระบุหรือไม่ |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | คืนจำนวนอิลิเมนต์ในลำดับ (คำนวณโดยการนับโดยตรง) |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | คืนจำนวนอิลิเมนต์ในลำดับที่ตรงตามเงื่อนไขที่ระบุ |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | คืนอิลิเมนต์ที่ตำแหน่งดัชนีที่ระบุในลำดับ |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | คืนอิลิเมนต์ที่ตำแหน่งดัชนีที่ระบุในลำดับ |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | คืนอิลิเมนต์แรกของลำดับ |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | คืนอิลิเมนต์แรกของลำดับที่ตรงตามเงื่อนไขที่ระบุ |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | คืนอิลิเมนต์แรกของลำดับหรือค่าดีฟอลต์หากลำดับว่าง |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | คืนอิลิเมนต์แรกของลำดับที่ตรงตามเงื่อนไขหรือค่าดีฟอลต์หากไม่พบ |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | จัดกลุ่มอิลิเมนต์ของลำดับ |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | จัดกลุ่มอิลิเมนต์ของลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | คืนอิลิเมนต์สุดท้ายของลำดับ |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | คืนอิลิเมนต์สุดท้ายของลำดับหรือค่าดีฟอลต์หากลำดับว่าง |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกฟังก์ชันแปลงบนแต่ละอิลิเมนต์ของลำดับทั่วไปและคืนค่าที่ได้สูงสุด |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกฟังก์ชันแปลงบนแต่ละอิลิเมนต์ของลำดับทั่วไปและคืนค่าที่ได้ต่ำสุด |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | กรองอิลิเมนต์ของลำดับตามชนิดที่ระบุ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | เรียงลำดับอิลิเมนต์ของลำดับในลำดับเพิ่มตามค่าคีย์ที่เลือกโดย keySelector |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | เรียงลำดับอิลิเมนต์ของลำดับในลำดับลดตามค่าคีย์ที่เลือกโดย keySelector |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | สลับลำดับของอิลิเมนต์ในลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | แปลงอิลิเมนต์ของลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | แปลงแต่ละอิลิเมนต์ของลำดับเป็นรูปแบบใหม่โดยใช้ดัชนีของอิลิเมนต์ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | ส่งต่อแต่ละอิลิเมนต์ของลำดับและรวมลำดับที่ได้เป็นลำดับเดียว |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | ข้ามจำนวนอิลิเมนต์ต่อเนื่องที่ระบุจากจุดเริ่มต้นของลำดับและคืนส่วนที่เหลือ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | คืนจำนวนอิลิเมนต์ต่อเนื่องที่ระบุจากจุดเริ่มต้นของลำดับ |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | สร้างอาร์เรย์จากลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | สร้าง List<T> จากลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | กรองลำดับตามเงื่อนไขที่ระบุ |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เหมือนคำสั่ง lock() ของ C# การล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | อนาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) เปิดใช้งานการโคลนชนิดที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | ตัวสร้างสำเนา ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการสร้างสำเนาในคลาสย่อย |
|  [ObjectCollection](./objectcollection/)() | สร้างอินสแตนซ์ใหม่ |
|  [ObjectCollection](./objectcollection/)([Action](../../system/action/)\<T\>) | สร้างอินสแตนซ์ใหม่ |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | ตัวดำเนินการกำหนดค่าแบบย้าย |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | ตัวดำเนินการกำหนดค่าแบบย้าย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการสร้างสำเนาในคลาสย่อย |
| T\& [operator[]](../../system.collections.objectmodel/collection/operator[]/)(int) | รับค่าที่ตำแหน่งดัชนีที่ระบุ |
| const T\& [operator[]](../../system.collections.objectmodel/collection/operator[]/)(int) const | รับค่าที่ตำแหน่งดัชนีที่ระบุ |
| [reverse_iterator](../../system.collections.objectmodel/collection/reverse_iterator/) [rbegin](../../system.collections.objectmodel/collection/rbegin/)() | รับ reverse iterator ไปยังอิลิเมนต์สุดท้ายของคอลเลกชัน (อิลิเมนต์แรกในลำดับย้อนกลับ) |
| [const_reverse_iterator](../../system.collections.objectmodel/collection/const_reverse_iterator/) [rbegin](../../system.collections.objectmodel/collection/rbegin/)() const | รับ reverse iterator ไปยังอิลิเมนต์สุดท้ายของคอลเลกชันที่กำหนดค่าคงที่ (อิลิเมนต์แรกในลำดับย้อนกลับ) |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์แบบค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำเฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำเฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริง |
| **bool** [Remove](../../system.collections.objectmodel/collection/remove/)(const T\&) override | ลบรายการเฉพาะ |
| void [RemoveAt](../../system.collections.objectmodel/collection/removeat/)(int) override | ลบรายการที่ตำแหน่งเฉพาะ |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงร่วมโดยค่าที่ระบุ |
| [reverse_iterator](../../system.collections.objectmodel/collection/reverse_iterator/) [rend](../../system.collections.objectmodel/collection/rend/)() | รับ reverse iterator สำหรับอิลิเมนต์ที่ไม่มีอยู่ก่อนจุดเริ่มต้นของคอลเลกชัน |
| [const_reverse_iterator](../../system.collections.objectmodel/collection/const_reverse_iterator/) [rend](../../system.collections.objectmodel/collection/rend/)() const | รับ reverse iterator สำหรับอิลิเมนต์ที่ไม่มีอยู่ก่อนจุดเริ่มต้นของคอลเลกชันที่กำหนดค่าคงที่ |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทน shared) อนุญาตสลับพอยเตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงร่วม ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงร่วม ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | อนาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/) เปิดใช้งานการแปลงอ็อบเจกต์กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เหมือนการสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่เหมือนคำสั่ง lock() ของ C# การปลดล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](../../system.collections.objectmodel/collection/virtualizebeginconstiterator/)() const override | รับการทำงานของ begin const iterator สำหรับคอนเทนเนอร์ปัจจุบัน |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](../../system.collections.objectmodel/collection/virtualizebeginiterator/)() override | รับการทำงานของ begin iterator สำหรับคอนเทนเนอร์ปัจจุบัน |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](../../system.collections.objectmodel/collection/virtualizeendconstiterator/)() const override | รับการทำงานของ end const iterator สำหรับคอนเทนเนอร์ปัจจุบัน |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](../../system.collections.objectmodel/collection/virtualizeenditerator/)() override | รับการทำงานของ end iterator สำหรับคอนเทนเนอร์ปัจจุบัน |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิง weak ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิง weak ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | ตัวทำลาย |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* Class [Collection](../../system.collections.objectmodel/collection/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.Slides](../../)