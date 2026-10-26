---
title: SortedDictionary
second_title: Aspose.Slides สำหรับ C++ – อ้างอิง API
description: การประกาศล่วงหน้าของประเภทพจนานุกรมที่เรียงลำดับ
type: docs
weight: 521
url: /th/system.collections.generic/sorteddictionary/
---
## SortedDictionary คลาส

Sorted dictionary type forward declaration.

```cpp
template<typename TKey,typename TValue>class SortedDictionary : public System::Collections::Generic::BaseDictionary<std::map<TKey, TValue, ComparerAdapter<BasePointerType<TKey>::type>, ASPOSE_MAP_ALLOCATOR_TYPE(TKey, TValue)>>
```

### พารามิเตอร์ของเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TKey | ประเภทคีย์ |
| TValue | ประเภทค่า |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual void [Add](../idictionary/add/)(const TKey&, const TValue&) | เพิ่มคู่คีย์-ค่าเข้าไปในคอนเทนเนอร์ |
| virtual void [Add](../icollection/add/)(const T&) | เพิ่มองค์ประกอบเข้าในคอลเลกชัน |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | รับอิเทอเรเตอร์ที่ชี้ไปยังองค์ประกอบแรก (ถ้ามี) ของคอลเลกชัน. อิเทอเรเตอร์นี้ไม่สามารถใช้เพื่อเปลี่ยนวัตถุที่อ้างอิงได้เนื่องจาก [GetEnumerator()](../ienumerable/getenumerator/) คืนอ็อบเจ็กต์สำเนาของ T |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | รับอิเทอเรเตอร์ที่ชี้ไปยังองค์ประกอบแรก (ถ้ามี) ของอินสแตนซ์ที่มีคุณลักษณะ const ของคอลเลกชัน |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | รับอิเทอเรเตอร์ที่ชี้ไปยังองค์ประกอบแรกที่เป็น const (ถ้ามี) ของคอลเลกชัน |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | รับอิเทอเรเตอร์ที่ชี้หลังจากองค์ประกอบ const ตัวสุดท้าย (ถ้ามี) ของคอลเลกชัน |
| virtual void [Clear](../icollection/clear/)() | ลบองค์ประกอบทั้งหมดออกจากคอลเลกชัน |
| virtual **bool** [Contains](../icollection/contains/)(const T&) const | ตรวจสอบว่ามีองค์ประกอบอยู่ในคอลเลกชันหรือไม่ |
| virtual **bool** [ContainsKey](../idictionary/containskey/)(const TKey&) const | ตรวจสอบว่าคอนเทนเนอร์มีคีย์หรือไม่ |
| void [CopyTo](../idictionary/copyto/)([ArrayPtr](../../system/arrayptr/)<[KeyValuePair](../keyvaluepair/)<TKey, TValue>>, int) override | คัดลอกเนื้อหาของพจนานุกรมลงในอาเรย์ที่มีอยู่ |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | รับอิเทอเรเตอร์ย้อนกลับไปยังองค์ประกอบ const ตัวสุดท้ายของคอลเลกชัน (เป็นตัวแรกเมื่อลำดับย้อนกลับ) |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | รับอิเทอเรเตอร์ย้อนกลับสำหรับองค์ประกอบ const ที่ไม่มีอยู่ก่อนจุดเริ่มต้นของคอลเลกชัน |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | รับอิเทอเรเตอร์ที่ชี้หลังจากองค์ประกอบสุดท้าย (ถ้ามี) ของคอลเลกชัน. อิเทอเรเตอร์นี้ไม่สามารถใช้เพื่อเปลี่ยนวัตถุที่อ้างอิงได้เนื่องจาก [GetEnumerator()](../ienumerable/getenumerator/) คืนอ็อบเจ็กต์สำเนาของ T |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | รับอิเทอเรเตอร์ที่ชี้หลังจากองค์ประกอบสุดท้าย (ถ้ามี) ของอินสแตนซ์ที่มีคุณลักษณะ const ของคอลเลกชัน |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if<[IsSmartPtr](../../system/issmartptr/)<T1>::value&&[IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | เปรียบเทียบอ็อบเจ็กต์ชนิดอ้างอิงในสไตล์ของ C# |
| static std::enable_if<![IsSmartPtr](../../system/issmartptr/)<T1>::value&&![IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | เปรียบเทียบอ็อบเจ็กต์ชนิดค่าในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const&, **float** const&) | จำลองการเปรียบเทียบเลขจุดลอยแบบ C# ที่ NaN สองค่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const&, **double** const&) | จำลองการเปรียบเทียบเลขทศนิยมคู่แบบ C# ที่ NaN สองค่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase&, void **) const | ใช้สำหรับวัตถุประสงค์ภายในเท่านั้น |
| [SharedPtr](../../system/sharedptr/)<[System::Collections::Generic::IComparer](../icomparer/)<TKey>> [get_Comparer](./get_comparer/)() const | รับ IComparer<TKey> ที่ใช้เรียงลำดับองค์ประกอบของ SortedDictionary<TKey,TValue> |
| virtual int [get_Count](../icollection/get_count/)() const | รับจำนวนขององค์ประกอบในคอลเลกชัน |
| **bool** [get_IsFixedSize](../idictionary/get_isfixedsize/)() const | ตรวจสอบว่าขนาดคอลเลกชันคงที่หรือไม่ |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | ตรวจสอบว่าคอลเลกชันเป็นแบบอ่านอย่างเดียวหรือไม่ |
| **bool** [get_IsSynchronized](../idictionary/get_issynchronized/)() const | ตรวจสอบว่าคอนเทนเนอร์ปลอดภัยต่อเธรดหรือไม่ |
| virtual [SharedPtr](../../system/sharedptr/)<[ICollection](../icollection/)<TKey>> [get_Keys](../idictionary/get_keys/)() const | เข้าถึงคอลเลกชันของคีย์ |
| [SharedPtr](../../system/sharedptr/)<[Object](../../system/object/)> [get_SyncRoot](../icollection/get_syncroot/)() const | รับอ็อบเจ็กต์ที่คอลเลกชันทำการซิงโครไนซ์ผ่าน |
| virtual [SharedPtr](../../system/sharedptr/)<[ICollection](../icollection/)<TValue>> [get_Values](../idictionary/get_values/)() const | เข้าถึงคอลเลกชันของค่า |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| static [SharedPtr](../../system/sharedptr/)<[IComparer](../icomparer/)<typename BasePointerType<TKey>::type>> [GetDefaultKeyComparer](./getdefaultkeycomparer/)() | ฟังก์ชันเข้าถึงซิงเกิลตัน |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | รับ enumerator เพื่อทำการวนผ่านพจนานุกรมปัจจุบัน |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอะแนลงของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ช่วยให้ทำแฮชของอ็อบเจ็กต์ที่กำหนดเองได้ |
| virtual const [TypeInfo](../../system/typeinfo/)& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เป็นอะแนลงของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey&) const | คืนค่าที่พบ; หรือ **Value()** หากไม่พบ |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey&, const TValue&) const | คืนค่าที่พบ; หรือ **defaultValue** หากไม่พบ |
| virtual TValue [GetValueOrNull](../idictionary/getvalueornull/)(const TKey&) const | คืนค่าที่พบ; หรือ **null** หากไม่พบ, มีความหมายเฉพาะกับชนิดอ้างอิง |
| [ICollection](../icollection/icollection/)() | คอนสตรัคเตอร์เริ่มต้น |
| [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)&) | คอนสตรัคเตอร์คัดลอก |
| [ICollection](../icollection/icollection/)([ICollection](../icollection/)&&) | คอนสตรัคเตอร์ย้าย |
| virtual TValue [idx_get](../idictionary/idx_get/)(const TKey&) const | ฟังก์ชัน getter |
| virtual void [idx_set](../idictionary/idx_set/)(const TKey&, TValue) | ฟังก์ชัน setter |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นตัวอย่างของประเภทที่อธิบายโดย targetType หรือไม่. เป็นอะแนลงของโอเปเรเตอร์ 'is' ของ C# |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)<T, T, T>&) | ใช้ฟังก์ชันสะสมบนลำดับ |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function<**bool**(T)>) | กำหนดว่าทุกองค์ประกอบของลำดับเป็นไปตามเงื่อนไขหรือไม่ |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | กำหนดว่าลำดับมีองค์ประกอบใด ๆ หรือไม่ |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function<**bool**(T)>) | กำหนดว่ามีองค์ประกอบใดในลำดับที่มีอยู่หรือเป็นไปตามเงื่อนไขหรือไม่ |
| T [LINQ_Average](../ienumerable/linq_average/)() | คำนวณค่าเฉลี่ยของลำดับของค่าตัวเลข |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)<T, ResultType>&) | คำนวณค่าเฉลี่ยของลำดับของค่าที่ได้จากการเรียกฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับอินพุต |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Cast](../ienumerable/linq_cast/)() | แปลงชนิดขององค์ประกอบเป็นประเภทที่ระบุ |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> ) | ต่อสองลำดับเข้าด้วยกัน |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | กำหนดว่าลำดับมีค่าที่ระบุหรือไม่ |
| int [LINQ_Count](../ienumerable/linq_count/)() | คืนจำนวนขององค์ประกอบในลำดับ (คำนวณโดยการนับโดยตรง) |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)<T, **bool**>&) | คืนจำนวนขององค์ประกอบในลำดับที่เป็นไปตามเงื่อนไขที่ระบุ |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | คืนองค์ประกอบที่ตำแหน่งที่ระบุในลำดับ |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | คืนองค์ประกอบที่ตำแหน่งที่ระบุในลำดับ |
| T [LINQ_First](../ienumerable/linq_first/)() | คืนองค์ประกอบแรกของลำดับ |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)<T, **bool**>&) | คืนองค์ประกอบแรกของลำดับที่เป็นไปตามเงื่อนไขที่ระบุ |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | คืนองค์ประกอบแรกของลำดับ, หรือค่าเริ่มต้นหากลำดับว่าง |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function<**bool**(T)>) | คืนองค์ประกอบแรกของลำดับที่ตรงตามเงื่อนไขหรือค่าเริ่มต้นหากไม่พบ |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, T>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>) | จัดกลุ่มองค์ประกอบของลำดับ |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>, [System::Func](../../system/func/)<T, Element>) | จัดกลุ่มองค์ประกอบของลำดับ |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Source>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>, [System::Func](../../system/func/)<Source, Element>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | คืนองค์ประกอบสุดท้ายของลำดับ |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | คืนองค์ประกอบสุดท้ายของลำดับ, หรือค่าเริ่มต้นหากลำดับว่าง |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)<T, ResultType>&) | เรียกใช้ฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับทั่วไปและคืนค่าที่ได้สูงสุด |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)<T, ResultType>&) | เรียกใช้ฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับทั่วไปและคืนค่าที่ได้ต่ำสุด |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_OfType](../ienumerable/linq_oftype/)() | กรององค์ประกอบของลำดับตามประเภทที่ระบุ |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)<T, Key>&) | เรียงลำดับองค์ประกอบของลำดับในลำดับจากน้อยไปมากตามค่าคีย์ที่เลือกโดย keySelector |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<T, Key>&) | เรียงลำดับองค์ประกอบของลำดับในลำดับจากมากไปน้อยตามค่าคีย์ที่เลือกโดย keySelector |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Reverse](../ienumerable/linq_reverse/)() | กลับลำดับขององค์ประกอบในลำดับ |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<T, ResultType>&) | แปลงองค์ประกอบของลำดับ |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<T, **int32_t**, ResultType>&) | แปลงแต่ละองค์ประกอบของลำดับเป็นรูปแบบใหม่โดยรวมดัชนีขององค์ประกอบ |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<Source, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<Source, **int32_t**, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)<T, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>>>>&) | โปรเจคแต่ละองค์ประกอบของลำดับและรวมลำดับที่ได้เป็นลำดับเดียว |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)<Source, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>>>>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | ข้ามจำนวนที่กำหนดขององค์ประกอบต่อเนื่องจากจุดเริ่มต้นของลำดับและคืนส่วนที่เหลือ |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | คืนจำนวนที่กำหนดขององค์ประกอบต่อเนื่องจากจุดเริ่มต้นของลำดับ |
| [System::ArrayPtr](../../system/arrayptr/)<T> [LINQ_ToArray](../ienumerable/linq_toarray/)() | สร้างอาเรย์จากลำดับ |
| [SharedPtr](../../system/sharedptr/)<[List](../list/)<T>> [LINQ_ToList](../ienumerable/linq_tolist/)() | สร้าง List<T> จากลำดับ |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Where](../ienumerable/linq_where/)(std::function<**bool**(T)>) | กรองลำดับตามเงื่อนไขที่ระบุ |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อคตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอะแนลงของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ช่วยให้คลอนประเภทที่กำหนดเองได้ |
| [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
| [Object](../../system/object/object/)([Object](../../system/object/) const&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และทำให้สามารถคัดลอกสร้างคลาสย่อยได้ |
| [ICollection](../icollection/)& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)&&) | โอเปเรเตอร์มอบหมายแบบย้าย |
| [ICollection](../icollection/)& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)&) | โอเปเรเตอร์มอบหมายแบบย้าย |
| [Object](../../system/object/)& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | โอเปเรเตอร์มอบหมาย. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และทำให้สามารถคัดลอกสร้างคลาสย่อยได้ |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | รับอิเทอเรเตอร์ย้อนกลับไปยังองค์ประกอบสุดท้ายของคอลเลกชัน (เป็นตัวแรกเมื่อลำดับย้อนกลับ) |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | รับอิเทอเรเตอร์ย้อนกลับไปยังองค์ประกอบสุดท้ายของคอลเลกชันที่มีคุณลักษณะ const (เป็นตัวแรกเมื่อลำดับย้อนกลับ) |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ชนิดค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | การทำเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | การทำเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| virtual **bool** [Remove](../idictionary/remove/)(const TKey&) | ลบคีย์ออกจากคอนเทนเนอร์ |
| virtual **bool** [Remove](../icollection/remove/)(const T&) | ลบองค์ประกอบจากคอลเลกชัน |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงที่แชร์โดยค่าที่ระบุ |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | รับอิเทอเรเตอร์ย้อนกลับสำหรับองค์ประกอบที่ไม่มีอยู่ก่อนจุดเริ่มต้นของคอลเลกชัน |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | รับอิเทอเรเตอร์ย้อนกลับสำหรับองค์ประกอบที่ไม่มีอยู่ก่อนจุดเริ่มต้นของคอลเลกชันที่มีคุณลักษณะ const |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทน shared). อนุญาตให้เปลี่ยน pointer ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนและคืนค่าตัวนับการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน |
| [SortedDictionary](./sorteddictionary/)() | สร้างพจนานุกรมว่าง |
| [SortedDictionary](./sorteddictionary/)(const [SharedPtr](../../system/sharedptr/)<[IComparer](../icomparer/)<typename BasePointerType<TKey>::type>>) | สร้างพจนานุกรมว่าง |
| [SortedDictionary](./sorteddictionary/)(const [SharedPtr](../../system/sharedptr/)<[IDictionary](../idictionary/)<TKey, TValue>>) | คอนสตรัคเตอร์คัดลอก |
| [SortedDictionary](./sorteddictionary/)(const [SharedPtr](../../system/sharedptr/)<[IDictionary](../idictionary/)<TKey, TValue>>, const [SharedPtr](../../system/sharedptr/)<[IComparer](../icomparer/)<typename BasePointerType<TKey>::type>>) | คอนสตรัคเตอร์คัดลอก |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอะแนลงของเมธอด C# [Object.ToString()](../../system/object/tostring/). ช่วยให้แปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้ |
| virtual **bool** [TryGetValue](../idictionary/trygetvalue/)(const TKey&, TValue&) const | ค้นหาค่าและดึงคืนหากพบ |
| static const [TypeInfo](../../system/typeinfo/)& [Type](../../system/object/type/)() | ทำหน้าที่สร้าง construct typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../ienumerable/virtualizebeginconstiterator/)() const | รับการทำงานของ begin const iterator สำหรับคอนเทนเนอร์ปัจจุบัน |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../ienumerable/virtualizebeginiterator/)() | รับการทำงานของ begin iterator สำหรับคอนเทนเนอร์ปัจจุบัน |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../ienumerable/virtualizeendconstiterator/)() const | รับการทำงานของ end const iterator สำหรับคอนเทนเนอร์ปัจจุบัน |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../ienumerable/virtualizeenditerator/)() | รับการทำงานของ end iterator สำหรับคอนเทนเนอร์ปัจจุบัน |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน |
| virtual  [~ICollection](../icollection/~icollection/)() | ตัวทำลาย |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## นิยามประเภท

| การนิยามประเภท | คำอธิบาย |
| --- | --- |
| [KeyCollection](./keycollection/) | ประเภทคอลเลกชันของคีย์ |
| [ValueCollection](./valuecollection/) | ประเภทคอลเลกชันของค่า |
| [map_t](./map_t/) | ประเภทข้อมูลพื้นฐาน |
| [this_t](./this_t/) | ประเภทของตนเอง |
| [Ptr](./ptr/) | ประเภทของตัวชี้ |
| [KVPair](./kvpair/) | ประเภทคู่คีย์-ค่า |
| [IEnumerablePtr](./ienumerableptr/) | คอลเลกชันขององค์ประกอบที่เหมือนกัน |
| [IEnumeratorPtr](./ienumeratorptr/) | **Enumerator** ประเภท |
| [iterator](./iterator/) | ประเภทอิเทอเรเตอร์ |
| [const_iterator](./const_iterator/) | ประเภทอิเทอเรเตอร์แบบ const |
| [reverse_iterator](./reverse_iterator/) | ประเภทอิเทอเรเตอร์ย้อนกลับ |
| [const_reverse_iterator](./const_reverse_iterator/) | ประเภทอิเทอเรเตอร์ย้อนกลับแบบ const |

## หมายเหตุ

คลาสพจนานุกรมที่เรียงลำดับซึ่งห่อหุ้ม STL map. วัตถุของคลาสนี้ควรสร้างด้วยฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะทำงานและ/หรือการยืนยันข้อผิดพลาด. ควรห่อคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../../system/smartptr/) เสมอและใช้ตัวชี้นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้ฟังก์ชัน

## ดูเพิ่มเติม

* คลาส [BaseDictionary](../basedictionary/)
* เนมสเปซ [System::Collections::Generic](../)
* ไลบรารี [Aspose.Slides](../../)