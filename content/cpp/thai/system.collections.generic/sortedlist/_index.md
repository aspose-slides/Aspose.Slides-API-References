---
title: SortedList
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "รายการที่เรียงลำดับโดยใช้โครงสร้าง FlatMap. วัตถุของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะทำงานและ/หรือการตรวจสอบความถูกต้อง. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 547
url: /th/system.collections.generic/sortedlist/
---
## คลาส SortedList

รายการที่เรียงลำดับโดยใช้โครงสร้าง FlatMap. วัตถุของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะทำงานและ/หรือการตรวจสอบความถูกต้อง. ควรห่อคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน.

```cpp
template<typename TKey,typename TValue>class SortedList : public System::Collections::Generic::SortedListHelper<TKey, TValue>,
                                                          public System::Collections::Generic::BaseDictionary<Detail::FlatMap<TKey, TValue, ComparerAdapter<TKey>>>
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TKey | ประเภทคีย์ |
| TValue | ประเภทค่า |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual void [Add](../idictionary/add/)(const TKey&, const TValue&) | เพิ่มคู่คีย์-ค่าเข้าไปในคอนเทนเนอร์ |
| virtual void [Add](../icollection/add/)(const T&) | เพิ่มองค์ประกอบเข้าไปในคอลเลกชัน |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | รับตัววนซ้ำที่ชี้ไปยังองค์ประกอบแรก (หากมี) ของคอลเลกชัน ตัววนซ้ำนี้ไม่สามารถใช้เปลี่ยนแปลงออบเจ็กต์ที่อ้างอิงได้เนื่องจาก [GetEnumerator()](../ienumerable/getenumerator/) คืนค่าออบเจ็กต์สำเนาของ T |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | รับตัววนซ้ำที่ชี้ไปยังองค์ประกอบแรก (หากมี) ของอินสแตนซ์ที่มี const ของคอลเลกชัน |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | รับตัววนซ้ำที่ชี้ไปยังองค์ประกอบที่กำหนด const แรก (หากมี) ของคอลเลกชัน |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | รับตัววนซ้ำที่ชี้ไปหลังจากองค์ประกอบ const สุดท้าย (หากมี) ของคอลเลกชัน |
| virtual void [Clear](../icollection/clear/)() | ลบองค์ประกอบทั้งหมดจากคอลเลกชัน |
| virtual **bool** [Contains](../icollection/contains/)(const T&) const | ตรวจสอบว่าองค์ประกอบมีอยู่ในคอลเลกชันหรือไม่ |
| virtual **bool** [ContainsKey](../idictionary/containskey/)(const TKey&) const | ตรวจสอบว่าคอนเทนเนอร์มีคีย์หรือไม่ |
| void [CopyTo](../idictionary/copyto/)([ArrayPtr](../../system/arrayptr/)<[KeyValuePair](../keyvaluepair/)<TKey, TValue>>, int) override | คัดลอกเนื้อหาดิกชันนารีลงในอาเรย์ที่มีอยู่ |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | รับตัววนซ้ำนำกลับที่ชี้ไปยังองค์ประกอบ const สุดท้ายของคอลเลกชัน (ที่แรกในลำดับย้อนกลับ) |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | รับตัววนซ้ำนำกลับสำหรับองค์ประกอบ const ที่ไม่มีอยู่ก่อนจุดเริ่มต้นของคอลเลกชัน |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | รับตัววนซ้ำที่ชี้ไปหลังจากองค์ประกอบสุดท้าย (หากมี) ของคอลเลกชัน ตัววนซ้ำนี้ไม่สามารถใช้เปลี่ยนแปลงออบเจ็กต์ที่อ้างอิงได้เนื่องจาก [GetEnumerator()](../ienumerable/getenumerator/) คืนค่าออบเจ็กต์สำเนาของ T |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | รับตัววนซ้ำที่ชี้ไปหลังจากองค์ประกอบสุดท้าย (หากมี) ของอินสแตนซ์ที่กำหนด const ของคอลเลกชัน |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบออบเจ็กต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if<[IsSmartPtr](../../system/issmartptr/)<T1>::value&&[IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | เปรียบเทียบออบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C# |
| static std::enable_if<![IsSmartPtr](../../system/issmartptr/)<T1>::value&&![IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | เปรียบเทียบออบเจ็กต์ประเภทค่าในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const&, **float** const&) | จำลองการเปรียบเทียบตัวเลขแบบ floating point สไตล์ C# ที่ NaN สองค่าถูกถือเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าตัวใด ๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const&, **double** const&) | จำลองการเปรียบเทียบตัวเลขแบบ floating point สไตล์ C# ที่ NaN สองค่าถูกถือเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าตัวใด ๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase&, void **) const | เพื่อการใช้งานภายในเท่านั้น |
| int [get_Capacity](./get_capacity/)() const | รับความจุปัจจุบันของรายการ |
| virtual int [get_Count](../icollection/get_count/)() const | รับจำนวนองค์ประกอบในคอลเลกชัน |
| **bool** [get_IsFixedSize](../idictionary/get_isfixedsize/)() const | ตรวจสอบว่าขนาดของคอลเลกชันเป็นคงที่หรือไม่ |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | ตรวจสอบว่าคอลเลกชันเป็นแบบอ่านอย่างเดียวหรือไม่ |
| **bool** [get_IsSynchronized](../idictionary/get_issynchronized/)() const | ตรวจสอบว่าคอนเทนเนอร์ปลอดภัยต่อเธรดหรือไม่ |
| virtual [SharedPtr](../../system/sharedptr/)<[IList](../ilist/)<TKey>> [get_Keys](./get_keys/)() const | เข้าถึงคอลเลกชันของคีย์ |
| [SharedPtr](../../system/sharedptr/)<[Object](../../system/object/)> [get_SyncRoot](../icollection/get_syncroot/)() const | รับออบเจ็กต์ที่คอลเลกชันทำการซิงโครไนซ์ผ่าน |
| virtual [SharedPtr](../../system/sharedptr/)<[IList](../ilist/)<TValue>> [get_Values](./get_values/)() const | เข้าถึงคอลเลกชันของค่า |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับออบเจ็กต์ |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | รับ enumerator ที่วนซ้ำรายการปัจจุบัน |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอเนกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้การแฮชของออบเจ็กต์ที่กำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของออบเจ็กต์. เป็นอเนกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey&) const | คืนค่าหากพบ; หรือ **Value()** หากไม่พบ |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey&, const TValue&) const | คืนค่าหากพบ; หรือ **defaultValue** หากไม่พบ |
| virtual TValue [GetValueOrNull](../idictionary/getvalueornull/)(const TKey&) const | คืนค่าหากพบ; หรือ **null** หากไม่พบ, ใช้ได้เฉพาะประเภทอ้างอิง |
| [ICollection](../icollection/icollection/)() | คอนสตรักเตอร์เริ่มต้น |
| [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)&) | คอนสตรักเตอร์คัดลอก |
| [ICollection](../icollection/icollection/)([ICollection](../icollection/)&&) | คอนสตรักเตอร์ย้าย |
| virtual TValue [idx_get](../idictionary/idx_get/)(const TKey&) const | ฟังก์ชัน getter |
| virtual void [idx_set](../idictionary/idx_set/)(const TKey&, TValue) | ฟังก์ชัน setter |
| int [IndexOfKey](./indexofkey/)(TKey) const | ค้นหาคีย์เฉพาะ |
| int [IndexOfValue](./indexofvalue/)(TValue) const | ค้นหาค่าเฉพาะ |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)&) const | ตรวจสอบว่าออบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. เป็นอเนกของตัวดำเนินการ C# 'is' |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)<T, T, T>&) | ใช้ฟังก์ชันสะสมกับลำดับ |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function<**bool**(T)>) | กำหนดว่าทุกองค์ประกอบของลำดับเป็นไปตามเงื่อนไขหรือไม่ |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | กำหนดว่าลำดับมีองค์ประกอบใด ๆ หรือไม่ |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function<**bool**(T)>) | กำหนดว่ามีองค์ประกอบใดในลำดับที่เป็นไปตามเงื่อนไขหรือไม่ |
| T [LINQ_Average](../ienumerable/linq_average/)() | คำนวณค่าเฉลี่ยของลำดับของค่าตัวเลข |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)<T, ResultType>&) | คำนวณค่าเฉลี่ยของลำดับของค่าที่ได้โดยเรียกฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับอินพุต |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Cast](../ienumerable/linq_cast/)() | แปลงประเภทขององค์ประกอบเป็นประเภทที่ระบุ |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>>) | ต่อเนื่องสองลำดับ |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | กำหนดว่าลำดับมีค่าที่ระบุหรือไม่ |
| int [LINQ_Count](../ienumerable/linq_count/)() | คืนจำนวนองค์ประกอบในลำดับ (คำนวณโดยการนับโดยตรง) |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)<T, **bool**>&) | คืนจำนวนองค์ประกอบในลำดับที่ตรงตามเงื่อนไขที่ระบุ |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | คืนองค์ประกอบที่ตำแหน่งที่ระบุในลำดับ |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | คืนองค์ประกอบที่ตำแหน่งที่ระบุในลำดับ |
| T [LINQ_First](../ienumerable/linq_first/)() | คืนองค์ประกอบแรกของลำดับ |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)<T, **bool**>&) | คืนองค์ประกอบแรกของลำดับที่ตรงตามเงื่อนไขที่ระบุ |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | คืนองค์ประกอบแรกของลำดับ หรือค่าดีฟอลต์หากลำดับว่าง |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function<**bool**(T)>) | คืนองค์ประกอบแรกของลำดับที่ตรงกับเงื่อนไข หรือค่าดีฟอลต์หากไม่พบ |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, T>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>) | จัดกลุ่มองค์ประกอบของลำดับ |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>, [System::Func](../../system/func/)<T, Element>) | จัดกลุ่มองค์ประกอบของลำดับ |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Source>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>, [System::Func](../../system/func/)<Source, Element>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | คืนองค์ประกอบสุดท้ายของลำดับ |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | คืนองค์ประกอบสุดท้ายของลำดับ หรือค่าดีฟอลต์หากลำดับว่าง |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)<T, ResultType>&) | เรียกฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับทั่วไปและคืนค่าสูงสุดที่ได้ |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)<T, ResultType>&) | เรียกฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับทั่วไปและคืนค่าต่ำสุดที่ได้ |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_OfType](../ienumerable/linq_oftype/)() | กรององค์ประกอบของลำดับตามประเภทที่ระบุ |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)<T, Key>&) | จัดเรียงองค์ประกอบของลำดับในลำดับเพิ่มตามค่าคีย์ที่เลือกโดย keySelector |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<T, Key>&) | จัดเรียงองค์ประกอบของลำดับในลำดับลดลงตามค่าคีย์ที่เลือกโดย keySelector |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Reverse](../ienumerable/linq_reverse/)() | กลับลำดับขององค์ประกอบในลำดับ |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<T, ResultType>&) | แปลงองค์ประกอบของลำดับ |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<T, **int32_t**, ResultType>&) | แปลงแต่ละองค์ประกอบของลำดับเป็นรูปแบบใหม่โดยรวมดัชนีขององค์ประกอบ |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<Source, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<Source, **int32_t**, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)<T, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>>> &) | ทำการโปรเจกต์แต่ละองค์ประกอบของลำดับและรวมลำดับที่ได้เป็นลำดับเดียว |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)<Source, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>>> &) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | ข้ามจำนวนกำหนดขององค์ประกอบต่อเนื่องจากจุดเริ่มต้นของลำดับและคืนส่วนที่เหลือ |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | คืนจำนวนกำหนดขององค์ประกอบต่อเนื่องจากจุดเริ่มต้นของลำดับ |
| [System::ArrayPtr](../../system/arrayptr/)<T> [LINQ_ToArray](../ienumerable/linq_toarray/)() | สร้างอาเรย์จากลำดับ |
| [SharedPtr](../../system/sharedptr/)<[List](../list/)<T>> [LINQ_ToList](../ienumerable/linq_tolist/)() | สร้าง List<T> จากลำดับ |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Where](../ienumerable/linq_where/)(std::function<**bool**(T)>) | กรองลำดับตามเงื่อนไขที่ระบุ |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุเฝ้ารอ [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอเนกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง |
| [Object](../../system/object/object/)() | สร้างออบเจ็กต์. เขียนค่าเริ่มต้นให้โครงสร้างข้อมูลภายในทั้งหมด |
| [Object](../../system/object/object/)([Object](../../system/object/) const&) | คอนสตรักเตอร์คัดลอก. จริง ๆ ไม่ได้คัดลอกอะไรเลย เพียงแค่เขียนค่าเริ่มต้นให้ออบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรักเตอร์ของคลาสย่อย |
| [ICollection](../icollection/)& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)&&) | ตัวดำเนินการกำหนดค่าแบบย้าย |
| [ICollection](../icollection/)& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)&) | ตัวดำเนินการกำหนดค่าแบบย้าย |
| [Object](../../system/object/)& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | ตัวดำเนินการกำหนดค่า. จริง ๆ ไม่ได้คัดลอกอะไร เพียงเขียนค่าเริ่มต้นให้ออบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรักเตอร์ของคลาสย่อย |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | รับตัววนซ้ำนำกลับไปยังองค์ประกอบสุดท้ายของคอลเลกชัน (ที่แรกในลำดับย้อนกลับ) |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | รับตัววนซ้ำนำกลับไปยังองค์ประกอบสุดท้ายของคอลเลกชันที่กำหนด const (ที่แรกในลำดับย้อนกลับ) |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง |
| static std::enable_if<![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง |
| static std::enable_if<![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | เปรียบเทียบออบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| virtual **bool** [Remove](../idictionary/remove/)(const TKey&) | ลบคีย์จากคอนเทนเนอร์ |
| virtual **bool** [Remove](../icollection/remove/)(const T&) | ลบองค์ประกอบจากคอลเลกชัน |
| void [RemoveAt](./removeat/)(int) | ลบรายการที่ตำแหน่งที่ระบุ |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงแบบแชร์โดยค่าที่ระบุ |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | รับตัววนซ้ำนำกลับสำหรับองค์ประกอบที่ไม่มีอยู่ก่อนจุดเริ่มต้นของคอลเลกชัน |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | รับตัววนซ้ำนำกลับสำหรับองค์ประกอบที่ไม่มีอยู่ก่อนจุดเริ่มต้นของคอลเลกชันที่กำหนด const |
| void [set_Capacity](./set_capacity/)(int) | ตั้งค่าความจุปัจจุบันของรายการ |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทน shared) เพื่อสลับ pointer ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงแบบแชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบแชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงแบบแชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector |
| [SortedList](./sortedlist/)() | สร้างรายการเปล่า |
| [SortedList](./sortedlist/)(const [SharedPtr](../../system/sharedptr/)<[IComparer](../icomparer/)<TKey>>&) | สร้างรายการเปล่า |
| [SortedList](./sortedlist/)(const [SharedPtr](../../system/sharedptr/)<[IDictionary](../idictionary/)<TKey, TValue>>&) | คอนสตรักเตอร์คัดลอก |
| [SortedList](./sortedlist/)(const [map_t](./map_t/)&) | คอนสตรักเตอร์คัดลอก |
| [SortedList](./sortedlist/)(int) | สร้างรายการเปล่า |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอเนกของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงออบเจ็กต์ที่กำหนดเองเป็นสตริง |
| virtual **bool** [TryGetValue](../idictionary/trygetvalue/)(const TKey&, TValue&) const | ค้นหาค่าและดึงคืนหากพบ |
| static const [TypeInfo](../../system/typeinfo/)& [Type](../../system/object/type/)() | จำลอง construct C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุเฝ้ารอ [LockContext](../../system/lockcontext/) |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../ienumerable/virtualizebeginconstiterator/)() const | รับการทำงานของ begin const iterator สำหรับคอนเทนเนอร์ปัจจุบัน |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../ienumerable/virtualizebeginiterator/)() | รับการทำงานของ begin iterator สำหรับคอนเทนเนอร์ปัจจุบัน |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../ienumerable/virtualizeendconstiterator/)() const | รับการทำงานของ end const iterator สำหรับคอนเทนเนอร์ปัจจุบัน |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../ienumerable/virtualizeenditerator/)() | รับการทำงานของ end iterator สำหรับคอนเทนเนอร์ปัจจุบัน |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector |
| virtual  [~ICollection](../icollection/~icollection/)() | ตัวทำลาย |
| virtual  [~Object](../../system/object/~object/)() | ทำลายออบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## นิยามประเภท

| ชนิดนิยาม | คำอธิบาย |
| --- | --- |
| [KeyCollection](./keycollection/) | ประเภทคอลเลกชันคีย์ |
| [ValueCollection](./valuecollection/) | ประเภทคอลเลกชันค่า |
| [map_t](./map_t/) | ประเภทข้อมูลพื้นฐาน |
| [this_t](./this_t/) | ประเภทนี้ |
| [Ptr](./ptr/) | ประเภทพอยน์เตอร์ |
| [KVPair](./kvpair/) | ประเภทคู่คีย์ค่า |
| [IEnumerablePtr](./ienumerableptr/) | ประเภทคอลเลกชันของคู่เดียวกัน |
| [IEnumeratorPtr](./ienumeratorptr/) | ประเภท **Enumerator** |
| [iterator](./iterator/) | ประเภท iterator |
| [const_iterator](./const_iterator/) | ประเภท const iterator |
| [reverse_iterator](./reverse_iterator/) | ประเภท reverse iterator |
| [const_reverse_iterator](./const_reverse_iterator/) | ประเภท const reverse iterator |

## ดูเพิ่มเติม

* คลาส [SortedListHelper](../sortedlisthelper/)
* คลาส [BaseDictionary](../basedictionary/)
* เนมสเปซ [System::Collections::Generic](../)
* ไลบรารี [Aspose.Slides](../../)