---
title: IColumnCollection
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แสดงคอลเลกชันของคอลัมน์ในตาราง
type: docs
weight: 1743
url: /th/aspose.slides/icolumncollection/
---
## IColumnCollection คลาส

แสดงคอลเลกชันของคอลัมน์ในตาราง

```cpp
class IColumnCollection : public Aspose::Slides::IGenericCollection<System::SharedPtr<Aspose::Slides::IColumn>>
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\>\> [AddClone](./addclone/)([System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\>, **bool**) | สร้างสำเนาของแถวเทมเพลตที่ระบุและแทรกลงที่ส่วนล่างของตารางหนึ่ง |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | รับอิเทอเรเตอร์ที่ชี้ไปยังองค์ประกอบแรก (ถ้ามี) ของคอลเลกชันนี้ ตัวอิเทอเรเตอร์นี้ไม่สามารถใช้เพื่อเปลี่ยนวัตถุที่อ้างอิงได้ เนื่องจาก [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) คืนค่าอ็อบเจ็กต์สำเนาของ T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | รับอิเทอเรเตอร์ที่ชี้ไปยังองค์ประกอบแรก (ถ้ามี) ของอินสแตนซ์ที่กำหนดเป็น const ของคอลเลกชัน |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | รับอิเทอเรเตอร์ที่ชี้ไปยังองค์ประกอบแรกที่กำหนดเป็น const (ถ้ามี) ของคอลเลกชัน |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | รับอิเทอเรเตอร์ที่ชี้ไปหลังจากองค์ประกอบสุดท้ายที่กำหนดเป็น const (ถ้ามี) ของคอลเลกชัน |
| virtual void [CopyTo](../igenericcollection/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, **int32_t**) | คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาเรย์ที่ระบุ |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | รับอิเทอเรเตอร์ที่ชี้ไปหลังจากองค์ประกอบสุดท้าย (ถ้ามี) ของคอลเลกชัน ตัวอิเทอเรเตอร์นี้ไม่สามารถใช้เพื่อเปลี่ยนวัตถุที่อ้างอิงได้ เนื่องจาก [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) คืนค่าอ็อบเจ็กต์สำเนาของ T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | รับอิเทอเรเตอร์ที่ชี้ไปหลังจากองค์ประกอบสุดท้าย (ถ้ามี) ของอินสแตนซ์ที่กำหนดเป็น const ของคอลเลกชัน |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้รูปแบบการทำงานของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในรูปแบบ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในรูปแบบ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยตามสไตล์ C# ที่ซึ่ง NaN สองค่า ถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยตามสไตล์ C# ที่ซึ่ง NaN สองค่า ถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| virtual **int32_t** [get_Count](../igenericcollection/get_count/)() | คืนค่าจำนวนพฤติกรรมในคอลเลกชัน อ่านอย่างเดียว **int32_t** |
| virtual **bool** [get_IsSynchronized](../igenericcollection/get_issynchronized/)() | คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันได้รับการซิงโครไนซ์ (ปลอดภัยต่อเธรด) อ่านอย่างเดียว **bool** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_SyncRoot](../igenericcollection/get_syncroot/)() | คืนค่ารากของการซิงโครไนซ์ อ่านอย่างเดียว [System::Object](../../system/object/) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ |
| virtual [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../../system.collections.generic/ienumerator/)\<T\>\> [GetEnumerator](../../system.collections.generic/ienumerable/getenumerator/)() | รับ enumerator |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นเทียบเท่ากับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถทำแฮชวัตถุแบบกำหนดเองได้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของวัตถุ เทียบกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [idx_get](./idx_get/)(**int32_t**) | คืนค่าคอลัมน์ที่ตำแหน่งที่ระบุ อ่านอย่างเดียว [IColumn](../icolumn/) |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\>\> [InsertClone](./insertclone/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\>, **bool**) | สร้างสำเนาของคอลัมน์เทมเพลตที่ระบุและแทรกที่ตำแหน่งที่ระบุในตาราง |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เทียบกับตัวดำเนินการ 'is' ของ C# |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | ใช้ฟังก์ชันตัวสะสมบนลำดับ |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | กำหนดว่าทุกองค์ประกอบของลำดับตรงตามเงื่อนไขหรือไม่ |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | กำหนดว่าลำดับมีองค์ประกอบใด ๆ หรือไม่ |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | กำหนดว่ามีองค์ประกอบใดในลำดับที่มีอยู่หรือปรากฏเงื่อนไขหรือไม่ |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | คำนวณค่าเฉลี่ยของลำดับของค่าตัวเลข |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | คำนวณค่าเฉลี่ยของลำดับของค่าที่ได้จากการเรียกฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับอินพุต |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | แคสต์องค์ประกอบเป็นประเภทที่ระบุ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | ต่อเนื่องสองลำดับ |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | กำหนดว่าลำดับมีค่าที่ระบุหรือไม่ |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | คืนค่าจำนวนองค์ประกอบในลำดับ (คำนวณโดยการนับโดยตรง) |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | คืนค่าจำนวนองค์ประกอบในลำดับที่ตรงตามเงื่อนไขที่ระบุ |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | คืนค่าองค์ประกอบที่ตำแหน่งที่ระบุในลำดับ |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | คืนค่าองค์ประกอบที่ตำแหน่งที่ระบุในลำดับ |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | คืนค่าองค์ประกอบแรกของลำดับ |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | คืนค่าองค์ประกอบแรกของลำดับที่ตรงตามเงื่อนไขที่ระบุ |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | คืนค่าองค์ประกอบแรกของลำดับ หรือค่าดีฟอลต์หากลำดับว่าง |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | คืนค่าองค์ประกอบแรกของลำดับที่ตรงตามเงื่อนไขหรือค่าดีฟอลต์หากไม่พบองค์ประกอบดังกล่าว |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | จัดกลุ่มองค์ประกอบของลำดับ |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | จัดกลุ่มองค์ประกอบของลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | คืนค่าองค์ประกอบสุดท้ายของลำดับ |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | คืนค่าองค์ประกอบสุดท้ายของลำดับ หรือค่าดีฟอลต์หากลำดับว่าง |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกใช้ฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับทั่วไปและคืนค่าสูงสุดที่ได้ |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกใช้ฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับทั่วไปและคืนค่าต่ำสุดที่ได้ |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | กรององค์ประกอบของลำดับตามประเภทที่ระบุ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | เรียงลำดับองค์ประกอบของลำดับในลำดับจากน้อยไปมากตามค่ากุญแจที่เลือกโดย keySelector |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | เรียงลำดับองค์ประกอบของลำดับในลำดับจากมากไปน้อยตามค่ากุญแจที่เลือกโดย keySelector |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | กลับลำดับขององค์ประกอบในลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | แปลงองค์ประกอบของลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | แปลงแต่ละองค์ประกอบของลำดับเป็นรูปแบบใหม่โดยรวมดัชนีขององค์ประกอบ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | โปรเจกต์แต่ละองค์ประกอบของลำดับและรวมลำดับผลลัพธ์เป็นลำดับเดียว |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | ข้ามจำนวนองค์ประกอบต่อเนื่องที่ระบุจากจุดเริ่มต้นของลำดับและคืนส่วนที่เหลือ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | คืนจำนวนองค์ประกอบต่อเนื่องที่ระบุจากจุดเริ่มต้นของลำดับ |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | สร้างอาเรย์จากลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | สร้าง List<T> จากลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | กรองลำดับตามเงื่อนไขที่ระบุ |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentry [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เทียบเท่ากับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทที่กำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างวัตถุ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นวัตถุใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมาย ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นวัตถุใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจ็กต์ประเภทค่ากับ nullptr โดยอ้างอิง |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายตัว |
| virtual void [RemoveAt](./removeat/)(**int32_t**, **bool**) | ลบคอลัมน์ที่ตำแหน่งที่ระบุจากตาราง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์โดยค่าที่ระบุ |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนการแชร์) ให้สามารถสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak ได้ |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงที่แชร์และคืนค่า ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบเท่ากับเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงวัตถุที่กำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentry [LockContext](../../system/lockcontext/) |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | รับการทำงานของ begin const iterator สำหรับคอนเทนเนอร์ปัจจุบัน |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | รับการทำงานของ begin iterator สำหรับคอนเทนเนอร์ปัจจุบัน |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | รับการทำงานของ end const iterator สำหรับคอนเทนเนอร์ปัจจุบัน |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | รับการทำงานของ end iterator สำหรับคอนเทนเนอร์ปัจจุบัน |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| virtual  [~Object](../../system/object/~object/)() | ทำลายวัตถุ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [IGenericCollection](../igenericcollection/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)