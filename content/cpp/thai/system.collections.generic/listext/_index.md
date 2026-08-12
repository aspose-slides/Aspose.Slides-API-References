---
title: ListExt
second_title: Aspose.Slides สำหรับ C++ API Reference
description: คลาส List ทั่วไปที่ทำหน้าที่เป็นอินเทอร์เฟซ IListWrapper
type: docs
weight: 443
url: /th/system.collections.generic/listext/
---
## ListExt คลาส

ทั่วไป [List](../list/) คลาสที่ทำหน้าที่เป็น [IListWrapper](../../system.collections/ilistwrapper/) อินเทอร์เฟซ

```cpp
template<typename T>class ListExt : public System::Collections::Generic::List<T>,
                                    public System::Collections::IListWrapper
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| void [_add_range](../list/_add_range/)(std::initializer_list\<T\>) | เฉพาะ C++. |
| void [Add](../list/add/)(const T\&) override | เพิ่มองค์ประกอบไปยังตำแหน่งสุดท้ายของรายการ. |
| void [AddInitializer](../list/addinitializer/)(int, const T *) | เพิ่มองค์ประกอบหลายรายการลงในรายการ; ใช้เมื่อแปลง initializer. |
| void [AddRange](../list/addrange/)([IEnumerablePtr](../list/ienumerableptr/)) | เพิ่มทุกองค์ประกอบจากคอลเลกชัน (หรือจากตัวมันเอง) ไปยังตำแหน่งสุดท้ายของรายการปัจจุบัน. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](../list/asreadonly/)() | รับอ้างอิงแบบอ่านอย่างเดียวต่อคอลเลกชันนี้. |
| [iterator](../ienumerable/iterator/) [begin](../list/begin/)() | รับ iterator ไปยังองค์ประกอบแรกของคอลเลกชัน. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../list/begin/)() const | รับ iterator ไปยังองค์ประกอบแรกของคอลเลกชันที่เป็น const. |
| int [BinarySearch](../list/binarysearch/)(const T\&) const | ค้นหารายการในรายการที่เรียงลำดับ. |
| int [BinarySearch](../list/binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | ค้นหารายการในรายการที่เรียงลำดับ. |
| int [BinarySearch](../list/binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | ค้นหารายการในรายการที่เรียงลำดับ. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../list/cbegin/)() const | รับ iterator ไปยังองค์ประกอบแรกของคอลเลกชันที่เป็น const. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../list/cend/)() const | รับ iterator สำหรับองค์ประกอบ const ที่ไม่มีอยู่หลังจุดสิ้นสุดของคอลเลกชัน. |
| void [Clear](../list/clear/)() override | ลบทุกองค์ประกอบ. |
| **bool** [Contains](../list/contains/)(const T\&) const override | ตรวจสอบว่ามีรายการอยู่ในรายการหรือไม่. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<OutputType\>\> [ConvertAll](../list/convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | สร้างรายการขององค์ประกอบที่แปลงเป็นประเภทต่างกัน. |
| void [CopyTo](../list/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | คัดลอกองค์ประกอบของรายการไปยังองค์ประกอบของอาเรย์ที่มีอยู่. |
| void [CopyTo](../list/copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | คัดลอกทุกองค์ประกอบไปยังองค์ประกอบของอาเรย์ที่มีอยู่. |
| void [CopyTo](../list/copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | คัดลอกองค์ประกอบโดยเริ่มจากดัชนีที่ระบุไปยังองค์ประกอบของอาเรย์ที่มีอยู่. |
| [const_reverse_iterator](../list/const_reverse_iterator/) [crbegin](../list/crbegin/)() const | รับ reverse iterator ไปยังองค์ประกอบ const สุดท้ายของคอลเลกชัน (เป็นลำดับแรกเมื่อย้อนกลับ). |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\> [CreateIListWrapper](./createilistwrapper/)() override | [IListWrapper](../../system.collections/ilistwrapper/) การทำงานของอินเทอร์เฟซ. |
| std::enable_if\<[System::IsSmartPtr](../../system/issmartptr/)\<T1\>::value, [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\>\>::type [CreateIListWrapperImpl](./createilistwrapperimpl/)() | [IListWrapper](../../system.collections/ilistwrapper/) ตัวช่วยการทำงานสำหรับประเภทอ้างอิง. |
| std::enable_if<\![System::IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[System::IsBoxable](../../system/isboxable/)\<T1\>::value, [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\>\>::type [CreateIListWrapperImpl](./createilistwrapperimpl/)() | [IListWrapper](../../system.collections/ilistwrapper/) ตัวช่วยการทำงานสำหรับประเภทค่า. |
| std::enable_if<\![System::IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![System::IsBoxable](../../system/isboxable/)\<T\>::value, [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\>\>::type [CreateIListWrapperImpl](./createilistwrapperimpl/)() | [IListWrapper](../../system.collections/ilistwrapper/) ตัวช่วยการทำงานสำหรับประเภทอื่น. |
| [const_reverse_iterator](../list/const_reverse_iterator/) [crend](../list/crend/)() const | รับ reverse iterator สำหรับองค์ประกอบ const ที่ไม่มีอยู่ก่อนจุดเริ่มต้นของคอลเลกชัน. |
| [vector_t](../list/vector_t/)\& [data](../list/data/)() | ฟังก์ชันเข้าถึงโครงสร้างข้อมูลภายใน. |
| const [vector_t](../list/vector_t/)\& [data](../list/data/)() const | ฟังก์ชันเข้าถึงโครงสร้างข้อมูลภายใน. |
| [iterator](../ienumerable/iterator/) [end](../list/end/)() | รับ iterator สำหรับองค์ประกอบที่ไม่มีอยู่หลังจุดสิ้นสุดของคอลเลกชัน. |
| [const_iterator](../ienumerable/const_iterator/) [end](../list/end/)() const | รับ iterator สำหรับองค์ประกอบที่ไม่มีอยู่หลังจุดสิ้นสุดของคอลเลกชันที่เป็น const. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบตัวเลขแบบ floating point ของ C# ที่ NaN สองค่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบตัวเลขแบบ floating point ของ C# ที่ NaN สองค่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN เอง. |
| **bool** [Exists](../list/exists/)([System::Predicate](../../system/predicate/)\<T\>) | ตรวจสอบว่ามีองค์ประกอบที่ตรงกับเงื่อนไขเฉพาะในรายการหรือไม่. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับการทำงานภายในเท่านั้น. |
| T [Find](../list/find/)([System::Predicate](../../system/predicate/)\<T\>) | ค้นหาองค์ประกอบที่ตรงกับเงื่อนไขเฉพาะ. |
| [ListPtr](../listptr/)\<T\> [FindAll](../list/findall/)([System::Predicate](../../system/predicate/)\<T\>) | ค้นหาองค์ประกอบหลายรายการที่ตรงกับเงื่อนไขเฉพาะ. |
| int [FindIndex](../list/findindex/)([System::Predicate](../../system/predicate/)\<T\>) | ค้นหาองค์ประกอบที่ตรงกับเงื่อนไขเฉพาะ. |
| int [FindIndex](../list/findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | ค้นหาองค์ประกอบที่ตรงกับเงื่อนไขเฉพาะ. |
| int [FindIndex](../list/findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | ค้นหาองค์ประกอบที่ตรงกับเงื่อนไขเฉพาะ. |
| T [FindLast](../list/findlast/)([System::Predicate](../../system/predicate/)\<T\>) | ค้นหาองค์ประกอบสุดท้ายที่ตรงกับเงื่อนไขเฉพาะ. |
| void [ForEach](../list/foreach/)([System::Action](../../system/action/)\<T\>) | ดำเนินการกับทุกองค์ประกอบในรายการ. |
| int [get_Capacity](../list/get_capacity/)() const | รับความจุปัจจุบันของรายการ. |
| int [get_Count](../list/get_count/)() const override | รับจำนวนขององค์ประกอบในรายการปัจจุบัน. |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | ตรวจสอบว่าคอลเลกชันมีขนาดคงที่หรือไม่. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | ตรวจสอบว่าคอลเลกชันเป็นแบบอ่านอย่างเดียวหรือไม่. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | รับอ็อบเจกต์ที่คอลเลกชันซิงโครไนซ์ผ่าน. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมกับอ็อบเจกต์. |
| [IEnumeratorPtr](../list/ienumeratorptr/) [GetEnumerator](../list/getenumerator/)() override | รับ enumerator เพื่อวนซ้ำผ่านองค์ประกอบของรายการ. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นฟังก์ชันที่คล้ายกับ C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจกต์ที่กำหนดเอง. |
| **ThisPtr** [GetRange](../list/getrange/)(int, int) | สร้าง slice ของรายการ. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. คล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICollection](../icollection/icollection/)() | คอนสตรัคเตอร์เริ่มต้น. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | คอนสตรัคเตอร์คัดลอก. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | คอนสตรัคเตอร์ย้าย. |
| T [idx_get](../list/idx_get/)(int) const override | รับองค์ประกอบที่ตำแหน่งเฉพาะ. |
| void [idx_set](../list/idx_set/)(int, T) override | ตั้งค่าองค์ประกอบที่ตำแหน่งเฉพาะ. |
| int [IndexOf](../list/indexof/)(const T\&) const override | รับดัชนีแรกของรายการเฉพาะ. |
| int [IndexOf](../list/indexof/)(const T\&, int) const | ค้นหารายการเฉพาะในรายการ. |
| void [Insert](../list/insert/)(int, const T\&) override | แทรกรายการที่ตำแหน่งที่ระบุ. |
| void [InsertRange](../list/insertrange/)(int, [IEnumerablePtr](../list/ienumerableptr/)) | แทรกช่วงข้อมูลที่ตำแหน่งเฉพาะ. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. คล้ายกับโอเปอเรเตอร์ 'is' ของ C#. |
| **int32_t** [LastIndexOf](../list/lastindexof/)(const T\&) const | ค้นหาอ็อบเจกต์ที่ระบุและส่งคืนดัชนีเริ่มต้นจาก 0 ของการพบครั้งสุดท้ายในรายการทั้งหมด. |
| **int32_t** [LastIndexOf](../list/lastindexof/)(const T\&, **int32_t**) const | ค้นหาอ็อบเจกต์ที่ระบุและส่งคืนดัชนีเริ่มจาก 0 ของการพบครั้งสุดท้ายภายในช่วงขององค์ประกอบใน [List](../list/) ที่ขยายตั้งแต่องค์ประกอบแรกจนถึงดัชนีที่ระบุ. |
| **int32_t** [LastIndexOf](../list/lastindexof/)(const T\&, **int32_t**, **int32_t**) const | ค้นหาอ็อบเจกต์ที่ระบุและส่งคืนดัชนีเริ่มจาก 0 ของการพบครั้งสุดท้ายภายในช่วงขององค์ประกอบใน [List](../list/) ที่มีจำนวนองค์ประกอบตามที่ระบุและสิ้นสุดที่ดัชนีที่ระบุ. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | ใช้ฟังก์ชัน accumulator กับลำดับ. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | กำหนดว่าทุกองค์ประกอบของลำดับเป็นไปตามเงื่อนไขหรือไม่. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | กำหนดว่าลำดับมีองค์ประกอบใด ๆ หรือไม่. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | กำหนดว่ามีองค์ประกอบใดในลำดับที่มีอยู่หรือเป็นไปตามเงื่อนไขหรือไม่. |
| T [LINQ_Average](../ienumerable/linq_average/)() | คำนวณค่าเฉลี่ยของลำดับค่าตัวเลข. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | คำนวณค่าเฉลี่ยของลำดับค่าที่ได้โดยการเรียกฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับอินพุต. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | แปลงประเภทขององค์ประกอบเป็นประเภทที่ระบุ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | ต่อเนื่องสองลำดับเข้าด้วยกัน. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | กำหนดว่าลำดับมีค่าที่ระบุหรือไม่. |
| int [LINQ_Count](../ienumerable/linq_count/)() | ส่งคืนจำนวนขององค์ประกอบในลำดับ (คำนวณโดยการนับโดยตรง). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | ส่งคืนจำนวนขององค์ประกอบในลำดับที่ตรงกับเงื่อนไขที่ระบุ. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | ส่งคืนองค์ประกอบที่ดัชนีที่ระบุในลำดับ. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | ส่งคืนองค์ประกอบที่ดัชนีที่ระบุในลำดับ. |
| T [LINQ_First](../ienumerable/linq_first/)() | ส่งคืนองค์ประกอบแรกของลำดับ. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | ส่งคืนองค์ประกอบแรกของลำดับที่ตรงกับเงื่อนไขที่ระบุ. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | ส่งคืนองค์ประกอบแรกของลำดับ, หรือค่าตั้งต้นหากลำดับว่าง. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | ส่งคืนองค์ประกอบแรกของลำดับที่ตรงกับเงื่อนไข หรือค่าตั้งต้นหากไม่มีองค์ประกอบดังกล่าว. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | จัดกลุ่มองค์ประกอบของลำดับ. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | จัดกลุ่มองค์ประกอบของลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | ส่งคืนองค์ประกอบสุดท้ายของลำดับ. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | ส่งคืนองค์ประกอบสุดท้ายของลำดับ, หรือค่าตั้งต้นหากลำดับว่าง. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับทั่วไปและส่งคืนค่าที่มากที่สุดที่ได้. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับทั่วไปและส่งคืนค่าที่น้อยที่สุดที่ได้. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | กรององค์ประกอบของลำดับตามประเภทที่ระบุ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | จัดเรียงองค์ประกอบของลำดับในลำดับเพิ่มขึ้นตามค่าคีย์ที่เลือกโดย keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | จัดเรียงองค์ประกอบของลำดับในลำดับลดลงตามค่าคีย์ที่เลือกโดย keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | สลับลำดับขององค์ประกอบในลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | แปลงองค์ประกอบของลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | แปลงแต่ละองค์ประกอบของลำดับเป็นรูปแบบใหม่โดยรวมดัชนีขององค์ประกอบ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | โปรเจกต์แต่ละองค์ประกอบของลำดับและรวมลำดับผลลัพธ์ให้เป็นลำดับเดียว. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | ข้ามจำนวนองค์ประกอบต่อเนื่องที่ระบุจากจุดเริ่มต้นของลำดับและส่งคืนส่วนที่เหลือ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | ส่งคืนจำนวนองค์ประกอบต่อเนื่องที่ระบุจากจุดเริ่มต้นของลำดับ. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | สร้างอาเรย์จากลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | สร้าง List<T> จากลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | กรองลำดับตามเงื่อนไขที่ระบุ. |
|  [List](../list/list/)() | สร้างรายการว่าง. |
|  [List](../list/list/)(int) | สร้างรายการที่มีความจุตั้งแต่ต้น. |
|  [List](../list/list/)([IEnumerablePtr](../list/ienumerableptr/)) | คอนสตรัคเตอร์คัดลอก. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อคตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการคล cloning ของประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกในคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกในคลาสย่อย. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | ตัวดำเนินการกำหนดค่าแบบย้าย. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | ตัวดำเนินการกำหนดค่าแบบย้าย. |
| vector_t::reference [operator[]](../list/operator[]/)(int) | ฟังก์ชัน accessor. |
| vector_t::const_reference [operator[]](../list/operator[]/)(int) const | ฟังก์ชัน accessor. |
| [reverse_iterator](../list/reverse_iterator/) [rbegin](../list/rbegin/)() | รับ reverse iterator ไปยังองค์ประกอบสุดท้ายของคอลเลกชัน (เป็นลำดับแรกเมื่อย้อนกลับ). |
| [const_reverse_iterator](../list/const_reverse_iterator/) [rbegin](../list/rbegin/)() const | รับ reverse iterator ไปยังองค์ประกอบสุดท้ายของคอลเลกชันที่เป็น const (เป็นลำดับแรกเมื่อย้อนกลับ). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ string กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ strings. |
| **bool** [Remove](../list/remove/)(const T\&) override | ลบอินสแตนซ์แรกของรายการเฉพาะจากรายการ. |
| int [RemoveAll](../list/removeall/)([Predicate](../../system/predicate/)\<T\>) | ลบทุกองค์ประกอบที่ตรงกับเงื่อนไขที่ระบุ. |
| void [RemoveAt](../list/removeat/)(int) override | ลบรายการที่ตำแหน่งที่ระบุ. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิง shared ลงตามค่าที่ระบุ. |
| void [RemoveRange](../list/removerange/)(int, int) | ลบ slice ของรายการ. |
| [reverse_iterator](../list/reverse_iterator/) [rend](../list/rend/)() | รับ reverse iterator สำหรับองค์ประกอบที่ไม่มีอยู่ก่อนจุดเริ่มต้นของคอลเลกชัน. |
| [const_reverse_iterator](../list/const_reverse_iterator/) [rend](../list/rend/)() const | รับ reverse iterator สำหรับองค์ประกอบที่ไม่มีอยู่ก่อนจุดเริ่มต้นของคอลเลกชันที่เป็น const. |
| void [Reverse](../list/reverse/)() | กลับลำดับขององค์ประกอบทั้งหมดในรายการ. |
| void [Reverse](../list/reverse/)(int, int) | กลับลำดับขององค์ประกอบใน slice ของรายการ. |
| void [set_Capacity](../list/set_capacity/)(int) | ตั้งค่าความจุของรายการ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทน shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิง shared. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิง shared. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิง shared และส่งค่ากลับ. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| void [Sort](../list/sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | จัดเรียงองค์ประกอบในรายการ. |
| void [Sort](../list/sort/)() | จัดเรียงองค์ประกอบในรายการโดยใช้ comparator เริ่มต้น. |
| void [Sort](../list/sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>) | จัดเรียงองค์ประกอบใน slice ของรายการ. |
| void [Sort](../list/sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | จัดเรียงองค์ประกอบในรายการ. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](../list/toarray/)() const | แปลงรายการเป็นอาเรย์. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริง. |
| void [TrimExcess](../list/trimexcess/)() | ปรับความจุของรายการให้พอกับขนาดของมัน. |
| **bool** [TrueForAll](../list/trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | กำหนดว่าทุกองค์ประกอบในคอลเลกชันตรงกับเงื่อนไขที่ระบุหรือไม่. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เหมือน C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อคตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/). |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](../list/virtualizebeginconstiterator/)() const override | รับการทำงานของ begin const iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](../list/virtualizebeginiterator/)() override | รับการทำงานของ begin iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](../list/virtualizeendconstiterator/)() const override | รับการทำงานของ end const iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](../list/virtualizeenditerator/)() override | รับการทำงานของ end iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิง weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิง weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual  [~ICollection](../icollection/~icollection/)() | ตัวทำลาย. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ชนิดนิยาม

| ชนิดนิยาม | คำอธิบาย |
| --- | --- |
| [ThisType](./thistype/) |  |
| [ListType](./listtype/) |  |
| [BaseTypes](./basetypes/) |  |
| [ValueType](./valuetype/) |  |
| [BaseType](./basetype/) |  |

## ดูเพิ่มเติม

* คลาส [List](../list/)
* คลาส [IListWrapper](../../system.collections/ilistwrapper/)
* เนมสเปซ [System::Collections::Generic](../)
* ไลบรารี [Aspose.Slides](../../)