---
title: List
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: การประกาศล่วงหน้า List.
type: docs
weight: 430
url: /th/system.collections.generic/list/
---
## คลาส List

[List](./) การประกาศล่วงหน้า.

```cpp
template<typename T>class List : public virtual System::Object,
                                 public System::Collections::Generic::IList<T>
```

### พารามิเตอร์เทมเพลต

| Parameter | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบ. |

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| void [_add_range](./_add_range/)(std::initializer_list\<T\>) | เฉพาะ C++. |
| void [Add](./add/)(const T\&) override | เพิ่มองค์ประกอบต่อท้ายของรายการ. |
| void [AddInitializer](./addinitializer/)(int, const T *) | เพิ่มองค์ประกอบหลายรายการ; ใช้เมื่อแปลค่าเริ่มต้น. |
| void [AddRange](./addrange/)([IEnumerablePtr](./ienumerableptr/)) | เพิ่มองค์ประกอบทั้งหมดจากคอลเลกชัน (หรือจากตัวเอง) ต่อท้ายของรายการปัจจุบัน. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)() | รับอ้างอิงแบบอ่านอย่างเดียวไปยังคอลเลกชันนี้. |
| [iterator](../ienumerable/iterator/) [begin](./begin/)() | รับอิเทอเรเตอร์ไปยังองค์ประกอบแรกของคอลเลกชัน. |
| [const_iterator](../ienumerable/const_iterator/) [begin](./begin/)() const | รับอิเทอเรเตอร์ไปยังองค์ประกอบแรกของคอลเลกชันที่กำหนดค่า const. |
| int [BinarySearch](./binarysearch/)(const T\&) const | ค้นหาไอเท็มในรายการที่เรียงลำดับ. |
| int [BinarySearch](./binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | ค้นหาไอเท็มในรายการที่เรียงลำดับ. |
| int [BinarySearch](./binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | ค้นหาไอเท็มในรายการที่เรียงลำดับ. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](./cbegin/)() const | รับอิเทอเรเตอร์ไปยังองค์ประกอบ const แรกของคอลเลกชัน. |
| [const_iterator](../ienumerable/const_iterator/) [cend](./cend/)() const | รับอิเทอเรเตอร์สำหรับองค์ประกอบที่ไม่มีอยู่จริงแบบ const ที่อยู่หลังจุดสิ้นสุดของคอลเลกชัน. |
| void [Clear](./clear/)() override | ลบองค์ประกอบทั้งหมด. |
| **bool** [Contains](./contains/)(const T\&) const override | ตรวจสอบว่าไอเท็มมีอยู่ในรายการหรือไม่. |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<OutputType\>\> [ConvertAll](./convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | สร้างรายการขององค์ประกอบที่แปลงเป็นชนิดอื่น. |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | คัดลอกองค์ประกอบของรายการไปยังอาร์เรย์ที่มีอยู่. |
| void [CopyTo](./copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | คัดลอกองค์ประกอบทั้งหมดไปยังอาร์เรย์ที่มีอยู่. |
| void [CopyTo](./copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | คัดลอกองค์ประกอบเริ่มจากดัชนีที่ระบุไปยังอาร์เรย์ที่มีอยู่. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | รับอิเทอเรเตอร์ย้อนกลับไปยังองค์ประกอบ const สุดท้ายของคอลเลกชัน (เป็นอันแรกในลำดับย้อนกลับ). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | รับอิเทอเรเตอร์ย้อนกลับสำหรับองค์ประกอบที่ไม่มีอยู่จริงแบบ const ก่อนจุดเริ่มต้นของคอลเลกชัน. |
| [vector_t](./vector_t/)\& [data](./data/)() | ฟังก์ชันเข้าถึงโครงสร้างข้อมูลพื้นฐาน. |
| const [vector_t](./vector_t/)\& [data](./data/)() const | ฟังก์ชันเข้าถึงโครงสร้างข้อมูลพื้นฐาน. |
| [iterator](../ienumerable/iterator/) [end](./end/)() | รับอิเทอเรเตอร์สำหรับองค์ประกอบที่ไม่มีอยู่จริงหลังจุดสิ้นสุดของคอลเลกชัน. |
| [const_iterator](../ienumerable/const_iterator/) [end](./end/)() const | รับอิเทอเรเตอร์สำหรับองค์ประกอบที่ไม่มีอยู่จริงหลังจุดสิ้นสุดของคอลเลกชันที่กำหนดค่า const. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เทียบวัตถุโดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เทียบออบเจ็กต์แบบอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เทียบออบเจ็กต์แบบค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C# ที่ NaN สองค่าเท่ากันแม้ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C# ที่ NaN สองค่าเท่ากันแม้ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN. |
| **bool** [Exists](./exists/)([System::Predicate](../../system/predicate/)\<T\>) | ตรวจสอบว่ามีองค์ประกอบที่ตรงตามเงื่อนไขที่กำหนดในรายการหรือไม่. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| T [Find](./find/)([System::Predicate](../../system/predicate/)\<T\>) | ค้นหาองค์ประกอบที่ตรงตามเงื่อนไขที่กำหนด. |
| [ListPtr](../listptr/)\<T\> [FindAll](./findall/)([System::Predicate](../../system/predicate/)\<T\>) | ค้นหาองค์ประกอบหลายรายการที่ตรงตามเงื่อนไขที่กำหนด. |
| int [FindIndex](./findindex/)([System::Predicate](../../system/predicate/)\<T\>) | ค้นหาองค์ประกอบที่ตรงตามเงื่อนไขที่กำหนด. |
| int [FindIndex](./findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | ค้นหาองค์ประกอบที่ตรงตามเงื่อนไขที่กำหนด. |
| int [FindIndex](./findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | ค้นหาองค์ประกอบที่ตรงตามเงื่อนไขที่กำหนด. |
| T [FindLast](./findlast/)([System::Predicate](../../system/predicate/)\<T\>) | ค้นหาองค์ประกอบสุดท้ายที่ตรงตามเงื่อนไขที่กำหนด. |
| void [ForEach](./foreach/)([System::Action](../../system/action/)\<T\>) | ดำเนินการต่อทุกองค์ประกอบในรายการ. |
| int [get_Capacity](./get_capacity/)() const | รับความจุปัจจุบันของรายการ. |
| int [get_Count](./get_count/)() const override | รับจำนวนองค์ประกอบในรายการปัจจุบัน. |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | ตรวจสอบว่าคอลเลกชันมีขนาดคงที่หรือไม่. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | ตรวจสอบว่าคอลเลกชันเป็นแบบอ่านอย่างเดียวหรือไม่. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | รับอ็อบเจ็กต์ที่คอลเลกชันซิงโครไนซ์ผ่าน. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | รับอีเทอเรเตอร์สำหรับวนลูปผ่านองค์ประกอบของรายการ. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | สมการของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชอ็อบเจ็กต์แบบกำหนดเอง. |
| **ThisPtr** [GetRange](./getrange/)(int, int) | สร้างสไลซ์ของรายการ. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับชนิดจริงของอ็อบเจ็กต์. สมการของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICollection](../icollection/icollection/)() | คอนสตรัคเตอร์เริ่มต้น. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | คอนสตรัคเตอร์คัดลอก. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | คอนสตรัคเตอร์ย้าย. |
| T [idx_get](./idx_get/)(int) const override | รับองค์ประกอบที่ตำแหน่งเฉพาะ. |
| void [idx_set](./idx_set/)(int, T) override | ตั้งค่าองค์ประกอบที่ตำแหน่งเฉพาะ. |
| int [IndexOf](./indexof/)(const T\&) const override | รับดัชนีแรกของไอเท็มที่ระบุ. |
| int [IndexOf](./indexof/)(const T\&, int) const | ค้นหาไอเท็มที่ระบุในรายการ. |
| void [Insert](./insert/)(int, const T\&) override | แทรกไอเท็มที่ตำแหน่งที่ระบุ. |
| void [InsertRange](./insertrange/)(int, [IEnumerablePtr](./ienumerableptr/)) | แทรกช่วงข้อมูลที่ตำแหน่งที่ระบุ. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าสิ่งนี้เป็นอินสแตนซ์ของชนิดที่ระบุโดย targetType หรือไม่. สมการของตัวดำเนินการ C# 'is'. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&) const | ค้นหาวัตถุที่ระบุและคืนดัชนีฐานศูนย์ของการปรากฏครั้งสุดท้ายในรายการทั้งหมด. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**) const | ค้นหาวัตถุที่ระบุและคืนดัชนีฐานศูนย์ของการปรากฏครั้งสุดท้ายภายในช่วงขององค์ประกอบใน [List](./) ที่ขยายจากองค์ประกอบแรกถึงดัชนีที่ระบุ. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**, **int32_t**) const | ค้นหาวัตถุที่ระบุและคืนดัชนีฐานศูนย์ของการปรากฏครั้งสุดท้ายภายในช่วงขององค์ประกอบใน [List](./) ที่มีจำนวนองค์ประกอบตามที่ระบุและสิ้นสุดที่ดัชนีที่ระบุ. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | ประยุกต์ฟังก์ชัน accumulator กับลำดับ. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | ตรวจสอบว่าทุกองค์ประกอบของลำดับตรงตามเงื่อนไขหรือไม่. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | ตรวจสอบว่าลำดับมีองค์ประกอบใด ๆ หรือไม่. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | ตรวจสอบว่ามีองค์ประกอบใดในลำดับที่ตรงตามเงื่อนไขหรือไม่. |
| T [LINQ_Average](../ienumerable/linq_average/)() | คำนวณค่าเฉลี่ยของลำดับของค่าตัวเลข. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | คำนวณค่าเฉลี่ยของลำดับของค่าที่ได้จากการเรียกฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับอินพุต. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | แปลงชนิดขององค์ประกอบเป็นชนิดที่ระบุ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | ต่อสานสองลำดับ. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | ตรวจสอบว่าลำดับมีค่าที่ระบุหรือไม่. |
| int [LINQ_Count](../ienumerable/linq_count/)() | คืนจำนวนองค์ประกอบในลำดับ (คำนวณโดยการนับโดยตรง). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | คืนจำนวนองค์ประกอบในลำดับที่ตรงตามเงื่อนไขที่ระบุ. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | คืนองค์ประกอบที่ตำแหน่งที่ระบุในลำดับ. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | คืนองค์ประกอบที่ตำแหน่งที่ระบุในลำดับ. |
| T [LINQ_First](../ienumerable/linq_first/)() | คืนองค์ประกอบแรกของลำดับ. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | คืนองค์ประกอบแรกของลำดับที่ตรงกับเงื่อนไขที่ระบุ. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | คืนองค์ประกอบแรกของลำดับ, หรือค่าดีฟอลต์หากลำดับว่าง. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | คืนองค์ประกอบแรกของลำดับที่ตรงตามเงื่อนไขหรือค่าดีฟอลต์หากไม่มีองค์ประกอบดังกล่าว. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | จัดกลุ่มองค์ประกอบของลำดับ. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | จัดกลุ่มองค์ประกอบของลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | คืนองค์ประกอบสุดท้ายของลำดับ. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | คืนองค์ประกอบสุดท้ายของลำดับ, หรือค่าดีฟอลต์หากลำดับว่าง. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับทั่วไปและคืนค่าผลลัพธ์สูงสุด. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับทั่วไปและคืนค่าผลลัพธ์ต่ำสุด. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | ตัวกรององค์ประกอบของลำดับตามชนิดที่ระบุ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | เรียงลำดับองค์ประกอบของลำดับในลำดับเพิ่มตามค่าคีย์ที่เลือกโดย keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | เรียงลำดับองค์ประกอบของลำดับในลำดับลดตามค่าคีย์ที่เลือกโดย keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | กลับลำดับขององค์ประกอบในลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | แปลงองค์ประกอบของลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | แปลงแต่ละองค์ประกอบของลำดับเป็นรูปแบบใหม่โดยรวมดัชนีขององค์ประกอบ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | โปรเจคต์แต่ละองค์ประกอบของลำดับและรวมลำดับผลลัพธ์เป็นลำดับเดียว. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | ข้ามจำนวนองค์ประกอบต่อเนื่องที่ระบุจากจุดเริ่มต้นของลำดับและคืนส่วนที่เหลือ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | คืนจำนวนองค์ประกอบต่อเนื่องที่ระบุจากจุดเริ่มต้นของลำดับ. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | สร้างอาร์เรย์จากลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | สร้าง List<T> จากลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | ตัวกรองลำดับตามเงื่อนไขที่กำหนด. |
|  [List](./list/)() | สร้างรายการว่าง. |
|  [List](./list/)(int) | สร้างรายการด้วยความจุที่กำหนดล่วงหน้า. |
|  [List](./list/)([IEnumerablePtr](./ienumerableptr/)) | คอนสตรัคเตอร์คัดลอก. |
| void [Lock](../../system/object/lock/)() | Implement C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Move assignment operator. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Move assignment operator. |
| vector_t::reference [operator[]](./operator[]/)(int) | Accessor function. |
| vector_t::const_reference [operator[]](./operator[]/)(int) const | Accessor function. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | Gets a reverse iterator to the last element of collection (first in reverse). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | Gets a reverse iterator to the last element of the const-qualified collection (first in reverse). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| **bool** [Remove](./remove/)(const T\&) override | Removes first instance of specific item from list. |
| int [RemoveAll](./removeall/)([Predicate](../../system/predicate/)\<T\>) | Removes all elements matching specific predicate. |
| void [RemoveAt](./removeat/)(int) override | Removes item at specified position. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| void [RemoveRange](./removerange/)(int, int) | Removes slice of list. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | Gets a reverse iterator for a non-existent element before the start of the collection. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | Gets a reverse iterator for a non-existent element before the start of the const-qualified collection. |
| void [Reverse](./reverse/)() | Reverses elements order of the whole list. |
| void [Reverse](./reverse/)(int, int) | Reverses elements order of the list slice. |
| void [set_Capacity](./set_capacity/)(int) | Sets list capacity. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [Sort](./sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Sorts elements in the list. |
| void [Sort](./sort/)() | Sorts elements in the list using default comparator. |
| void [Sort](./sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>) | Sorts elements in the list slice. |
| void [Sort](./sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | Sorts elements in the list. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](./toarray/)() const | Converst list to array. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| void [TrimExcess](./trimexcess/)() | Makes list capacity to fit its size. |
| **bool** [TrueForAll](./trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | Determines whether every element in the collection matches the conditions defined by the specified predicate. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Gets the implementation of begin const iterator for the current container. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Gets the implementation of begin iterator for the current container. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Gets the implementation of end const iterator for the current container. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | Gets the implementation of end iterator for the current container. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | Destructor. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |

## Typedefs

| Typedef | คำอธิบาย |
| --- | --- |
| [ValueType](./valuetype/) | This type. |
| [BaseType](./basetype/) | Interface type. |
| [vector_t](./vector_t/) | Underlying data type. |
| [iterator](./iterator/) | Iterator type. |
| [const_iterator](./const_iterator/) | Const iterator type. |
| [reverse_iterator](./reverse_iterator/) | Reverse iterator type. |
| [const_reverse_iterator](./const_reverse_iterator/) | Const reverse iterator type. |
| [IEnumerablePtr](./ienumerableptr/) | Container holding elements of same type we hold. |
| [IEnumeratorPtr](./ienumeratorptr/) | **Enumerator** type. |

## รายละเอียด

[List](./) - wrapper รอบ std::vector เพื่อใช้ในโค้ดที่แปล. ต้องการ operator == ที่ถูกกำหนดสำหรับประเภทขององค์ประกอบ. วัตถุของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือใช้ operator new, เนื่องจากจะทำให้เกิดข้อผิดพลาด runtime และ/หรือการทำ assertion. ควรห่อคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งให้ฟังก์ชันเป็นอาร์กิวเมนต์.

```cpp
#include <system/collections/list.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // สร้างรายการแรก.
  auto list1 = MakeObject<List<int>>();

  // เติมรายการแรก.
  list1->Add(3);
  list1->Add(1);
  list1->Add(-5);
  list1->Add(8);

  // เรียงลำดับรายการแรก.
  // รายการแรกจะเป็น: {-5, 1, 3, 8}
  list1->Sort();

  // ลบรายการที่ตำแหน่งดัชนี 2.
  // รายการแรกจะเป็น: {-5, 1, 8}
  list1->RemoveAt(2);

  // แทรกรายการที่ตำแหน่งดัชนี 1.
  // รายการแรกจะเป็น: {-5, 15, 1, 8}
  list1->Insert(1, 15);

  // สร้างรายการที่สอง.
  auto list2 = MakeObject<List<int>>();

  // เติมรายการที่สอง.
  list2->Add(10);
  list2->Add(20);
  list2->Add(30);

  // ต่อท้ายองค์ประกอบจากรายการที่สองไปยังรายการแรก.
  list1->AddRange(list2);

  // พิมพ์รายการแรก.
  for (const auto item: list1)
  {
    std::cout << item << ' ';
  }

  return 0;
}
/*
ตัวอย่างโค้ดนี้แสดงผลลัพธ์ต่อไปนี้:
- 5 15 1 8 10 20 30
*/
```

## ดูเพิ่มเติม

* Class [Object](../../system/object/)
* Class [IList](../ilist/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.Slides](../../)