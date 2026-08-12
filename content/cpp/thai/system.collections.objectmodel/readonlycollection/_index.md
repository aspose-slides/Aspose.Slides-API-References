---
title: ReadOnlyCollection
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: "ห่อหุ้มคอนเทนเนอร์เฉพาะเพื่อเข้าถึงในโหมดอ่านอย่างเดียว. วัตถุของคลาสนี้ควรได้รับการจัดสรรเท่านั้นโดยใช้ฟังก์ชัน System::MakeObject(). ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้ส่งต่อเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 27
url: /th/system.collections.objectmodel/readonlycollection/
---
## ReadOnlyCollection คลาส


ห่อหุ้มคอนเทนเนอร์เฉพาะเพื่อเข้าถึงในโหมดอ่านอย่างเดียว. วัตถุของคลาสนี้ควรได้รับการจัดสรรเท่านั้นโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/). ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดขณะทำงานและ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อหุ้มคลาสนี้เข้าในพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) และใช้พอยน์เตอร์นี้ส่งต่อเป็นอาร์กิวเมนต์ให้ฟังก์ชัน.

```cpp
template<typename T>class ReadOnlyCollection : public virtual System::Object,
                                               public System::Collections::Generic::IList<T>
```


### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T | ประเภทขององค์ประกอบ. |
## เมธอด

| Method | Description |
| --- | --- |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | รับ iterator ชี้ไปยังองค์ประกอบแรก (ถ้ามี) ของคอลเลกชัน. iterator นี้ไม่สามารถใช้เปลี่ยนวัตถุที่อ้างอิงได้ เพราะ [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) คืนค่า copy-object ของ T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | รับ iterator ชี้ไปยังองค์ประกอบแรก (ถ้ามี) ของอินสแตนซ์ที่มี const-qualified ของคอลเลกชัน. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | รับ iterator ชี้ไปยังองค์ประกอบแรกที่มี const-qualified (ถ้ามี) ของคอลเลกชัน. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | รับ iterator ชี้หลังจากองค์ประกอบสุดท้ายที่มี const-qualified (ถ้ามี) ของคอลเลกชัน. |
| **bool** [Contains](./contains/)(const T\&) const override | ตรวจสอบว่าคอนเทนเนอร์มีรายการเฉพาะที่ระบุอยู่หรือไม่. |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | คัดลอกองค์ประกอบของคอนเทนเนอร์ไปยังอาร์เรย์ที่มีอยู่แล้ว. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | รับ iterator ชี้หลังจากองค์ประกอบสุดท้าย (ถ้ามี) ของคอลเลกชัน. iterator นี้ไม่สามารถใช้เปลี่ยนวัตถุที่อ้างอิงได้ เพราะ [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) คืนค่า copy-object ของ T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | รับ iterator ชี้หลังจากองค์ประกอบสุดท้าย (ถ้ามี) ของอินสแตนซ์ที่มี const-qualified ของคอลเลกชัน. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่า floating-point แบบ C# ที่ NaN สองค่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่า floating-point แบบ C# ที่ NaN สองค่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| int [get_Count](./get_count/)() const override | รับจำนวนขององค์ประกอบในคอนเทนเนอร์. |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | ตรวจสอบว่าคอลเลกชันมีขนาดคงที่หรือไม่. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const override | ตรวจสอบว่าคอลเลกชันเป็นแบบอ่าน-อย่างเดียวหรือไม่. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | รับอ็อบเจ็กต์ที่คอลเลกชันซิงโครไนซ์ผ่าน. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | รับ enumerator ของคอลเลกชัน. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue ของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจ็กต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. Analogue ของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICollection](../../system.collections.generic/icollection/icollection/)() | ตัวสร้างเริ่มต้น. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | ตัวสร้างสำเนา. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | ตัวสร้างย้าย. |
| T [idx_get](./idx_get/)(int) const override | รับรายการที่ตำแหน่งเฉพาะ. |
| int [IndexOf](./indexof/)(const T\&) const override | ค้นหารายการเฉพาะในคอลเลกชัน. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. Analogue ของออปอเรเตอร์ C# `is`. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | ใช้ฟังก์ชัน accumulator กับลำดับ. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | ตรวจสอบว่าทุกองค์ประกอบของลำดับเป็นไปตามเงื่อนไขหรือไม่. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | ตรวจสอบว่าลำดับมีองค์ประกอบใด ๆ หรือไม่. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | ตรวจสอบว่ามีองค์ประกอบใดในลำดับที่ตรงกับเงื่อนไขหรือไม่. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | คำนวณค่าเฉลี่ยของลำดับของค่าตัวเลข. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | คำนวณค่าเฉลี่ยของลำดับของค่าที่ได้จากการเรียกฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับอินพุต. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | แคสท์องค์ประกอบเป็นประเภทที่ระบุ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | ต่อสตริงสองลำดับเข้าด้วยกัน. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | ตรวจสอบว่าลำดับมีค่าที่ระบุหรือไม่. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | คืนจำนวนขององค์ประกอบในลำดับ (คำนวณจากการนับโดยตรง). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | คืนจำนวนขององค์ประกอบในลำดับที่ตรงตามเงื่อนไขที่ระบุ. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | คืนองค์ประกอบที่ตำแหน่งที่ระบุในลำดับ. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | คืนองค์ประกอบที่ตำแหน่งที่ระบุในลำดับ. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | คืนองค์ประกอบแรกของลำดับ. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | คืนองค์ประกอบแรกของลำดับที่ตรงกับเงื่อนไขที่ระบุ. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | คืนองค์ประกอบแรกของลำดับ, หรือค่าตั้งต้นถ้าลำดับว่าง. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | คืนองค์ประกอบแรกของลำดับที่ตรงตามเงื่อนไขหรือค่าตั้งต้นถ้าไม่มีองค์ประกอบดังกล่าว. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | จัดกลุ่มองค์ประกอบของลำดับ. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | จัดกลุ่มองค์ประกอบของลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | คืนองค์ประกอบสุดท้ายของลำดับ. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | คืนองค์ประกอบสุดท้ายของลำดับ, หรือค่าตั้งต้นถ้าลำดับว่าง. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับทั่วไปและคืนค่าผลลัพธ์สูงสุด. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับทั่วไปและคืนค่าผลลัพธ์ต่ำสุด. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | กรององค์ประกอบของลำดับตามประเภทที่ระบุ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | เรียงลำดับองค์ประกอบของลำดับตามค่าคีย์ที่เลือกโดย keySelector ในลำดับเพิ่ม. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | เรียงลำดับองค์ประกอบของลำดับตามค่าคีย์ที่เลือกโดย keySelector ในลำดับลด. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | สลับลำดับขององค์ประกอบในลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | แปลงองค์ประกอบของลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | แปลงแต่ละองค์ประกอบของลำดับเป็นรูปแบบใหม่โดยใช้ดัชนีขององค์ประกอบ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | โปรเจคท์แต่ละองค์ประกอบของลำดับและรวมลำดับผลลัพธ์เป็นลำดับเดียว. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | ข้ามจำนวนองค์ประกอบต่อเนื่องที่ระบุจากจุดเริ่มของลำดับและคืนส่วนที่เหลือ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | คืนจำนวนองค์ประกอบต่อเนื่องที่ระบุจากจุดเริ่มของลำดับ. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | สร้างอาร์เรย์จากลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | สร้าง List<T> จากลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | กรองลำดับตามเงื่อนไขที่ระบุ. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง C# `lock()` เพื่อล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue ของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการคล cloning ประเภทกำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | ตัวสร้างสำเนา. ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสร้างสำเนาสำหรับคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสร้างสำเนาสำหรับคลาสย่อย. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | ตัวดำเนินการกำหนดค่าด้วยการเคลื่อนย้าย. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | ตัวดำเนินการกำหนดค่าด้วยการเคลื่อนย้าย. |
|  [ReadOnlyCollection](./readonlycollection/)(const [SharedPtr](../../system/sharedptr/)\<[Generic::IList](../../system.collections.generic/ilist/)\<T\>\>\&) | ห่อคอลเลกชันแบบอ่าน-อย่างเดียวรอบคอลเลกชันเฉพาะ. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงร่วมโดยค่าที่ระบุ. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | ไม่ทำอะไร เพราะคอลเลกชันอ่าน-อย่างเดียวเพียงห่อข้อมูลและไม่ได้เก็บอะไร. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงร่วมและคืนค่า. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue ของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามคอนสตรัคต์ C# `typeof([System.Object](../../system/object/))`. |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง C# `lock()` เพื่อปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | รับการทำงานของ iterator เริ่มต้นแบบ const สำหรับคอนเทนเนอร์ปัจจุบัน. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | รับการทำงานของ iterator เริ่มต้นสำหรับคอนเทนเนอร์ปัจจุบัน. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | รับการทำงานของ iterator สิ้นสุดแบบ const สำหรับคอนเทนเนอร์ปัจจุบัน. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | รับการทำงานของ iterator สิ้นสุดสำหรับคอนเทนเนอร์ปัจจุบัน. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ弱. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ弱. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | ตัวทำลาย. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
## การกำหนด typedef

| Typedef | Description |
| --- | --- |
| [ValueType](./valuetype/) | ประเภทค่า. |
| [BaseType](./basetype/) | อินเทอร์เฟซที่นำไปใช้. |
| [IEnumeratorPtr](./ienumeratorptr/) | คอนเทนเนอร์ขององค์ประกอบเดียวกัน. |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* คลาส [IList](../../system.collections.generic/ilist/)
* เนมสเปซ [System::Collections::ObjectModel](../)
* ไลบรารี [Aspose.Slides](../../)