---
title: ConcurrentDictionary
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "การดำเนินการพจนานุกรมแบบปลอดภัยต่อเธรด. ออบเจ็กต์ของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอ็อบเจ็กต์ให้กับฟังก์ชันเป็นอาร์กิวเมนต์."
type: docs
weight: 1
url: /th/system.collections.concurrent/concurrentdictionary/
---
## ConcurrentDictionary คลาส

Thread-safe dictionary implementation. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<class TKey,class TValue>class ConcurrentDictionary : public System::Collections::Generic::Dictionary<TKey, TValue>
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TKey | ประเภทคีย์. |
| TValue | ประเภทค่า. |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| void [Add](./add/)(const TKey&, const TValue&) override | เพิ่มค่าเข้าไปในพจนานุกรม. |
| virtual void [Add](../../system.collections.generic/idictionary/add/)(const TKey&, const TValue&) | เพิ่มคู่คีย์-ค่าเข้าในคอนเทนเนอร์. |
| virtual void [Add](../../system.collections.generic/icollection/add/)(const T&) | เพิ่มอิลิเมนต์เข้าในคอลเลกชัน. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | รับอิเทอเรเตอร์ที่ชี้ไปยังอิลิเมนต์แรก (ถ้ามี) ของคอลเลกชัน. อิเทอเรเตอร์นี้ไม่สามารถใช้ในการเปลี่ยนแปลงออบเจ็กต์ที่อ้างอิงได้ เนื่องจาก [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) คืนค่าออบเจ็กต์สำเนาของ T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | รับอิเทอเรเตอร์ที่ชี้ไปยังอิลิเมนต์แรก (ถ้ามี) ของอินสแตนซ์ที่กำหนดเป็น const ของคอลเลกชัน. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | รับอิเทอเรเตอร์ที่ชี้ไปยังอิลิเมนต์แรกที่กำหนดเป็น const (ถ้ามี) ของคอลเลกชัน. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | รับอิเทอเรเตอร์ที่ชี้หลังอิลิเมนต์ const ตัวสุดท้าย (ถ้ามี) ของคอลเลกชัน. |
| void [Clear](./clear/)() override | ลบอิลิเมนต์ทั้งหมดในคอนเทนเนอร์. |
| virtual **bool** [Contains](../../system.collections.generic/icollection/contains/)(const T&) const | ตรวจสอบว่าอิลิเมนต์มีอยู่ในคอลเลกชันหรือไม่. |
| virtual **bool** [ContainsKey](../../system.collections.generic/idictionary/containskey/)(const TKey&) const | ตรวจสอบว่าคอนเทนเนอร์มีคีย์หรือไม่. |
| void [CopyTo](./copyto/)([ArrayPtr](../../system/arrayptr/)<[System::Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)<TKey, TValue>>, int) override | คัดลอกอิลิเมนต์ของคอนเทนเนอร์ไปยังอาเรย์ที่มีอยู่แล้ว. |
| void [CopyTo](../../system.collections.generic/idictionary/copyto/)([ArrayPtr](../../system/arrayptr/)<[KeyValuePair](../../system.collections.generic/keyvaluepair/)<TKey, TValue>>, int) override | คัดลอกเนื้อหาของพจนานุกรมไปยังอาเรย์ที่มีอยู่แล้ว. |
| [Dictionary](../../system.collections.generic/dictionary/dictionary/)() | สร้างพจนานุกรมเปล่า. |
| [Dictionary](../../system.collections.generic/dictionary/dictionary/)(const [map_t](../../system.collections.generic/dictionary/map_t/)&) | คัดลอกข้อมูลจากแมพ. |
| [Dictionary](../../system.collections.generic/dictionary/dictionary/)(int) | โอเวอร์โหลดที่สอดคล้องกับการสร้างพจนานุกรมที่จัดสรรล่วงหน้า; จริง ๆ ไม่ทำการจัดสรรใด ๆ. |
| [Dictionary](../../system.collections.generic/dictionary/dictionary/)(const [SharedPtr](../../system/sharedptr/)<[IDictionary](../../system.collections.generic/idictionary/)<TKey, TValue>> &) | คอนสตรักเตอร์สำเนา. |
| [Dictionary](../../system.collections.generic/dictionary/dictionary/)(const [SharedPtr](../../system/sharedptr/)<[IDictionary](../../system.collections.generic/idictionary/)<TKey, TValue>> &, const [SharedPtr](../../system/sharedptr/)<[IEqualityComparer](../../system.collections.generic/iequalitycomparer/)<TKey>> &) | คอนสตรักเตอร์สำเนา. |
| [Dictionary](../../system.collections.generic/dictionary/dictionary/)(const [SharedPtr](../../system/sharedptr/)<[IEqualityComparer](../../system.collections.generic/iequalitycomparer/)<TKey>> &) | สร้างพจนานุกรมเปล่า. |
| [Dictionary](../../system.collections.generic/dictionary/dictionary/)(int, const [SharedPtr](../../system/sharedptr/)<[IEqualityComparer](../../system.collections.generic/iequalitycomparer/)<TKey>> &) | สร้างพจนานุกรมเปล่า. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | รับอิเทอเรเตอร์ที่ชี้หลังอิลิเมนต์สุดท้าย (ถ้ามี) ของคอลเลกชัน. อิเทอเรเตอร์นี้ไม่สามารถใช้เปลี่ยนออบเจ็กต์ที่อ้างอิงได้ เนื่องจาก [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) คืนค่าออบเจ็กต์สำเนาของ T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | รับอิเทอเรเตอร์ที่ชี้หลังอิลิเมนต์สุดท้าย (ถ้ามี) ของอินสแตนซ์ที่กำหนดเป็น const ของคอลเลกชัน. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบออบเจ็กต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if<[IsSmartPtr](../../system/issmartptr/)<T1>::value&&[IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | เปรียบเทียบออบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<![IsSmartPtr](../../system/issmartptr/)<T1>::value&&![IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | เปรียบเทียบออบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const&, **float** const&) | จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C# ที่ถือว่า NaN สองค่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const&, **double** const&) | จำลองการเปรียบเทียบประเภท double แบบ C# ที่ถือว่า NaN สองค่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| virtual int [get_Count](../../system.collections.generic/icollection/get_count/)() const | รับจำนวนอิลิเมนต์ในคอลเลกชัน. |
| **bool** [get_IsFixedSize](../../system.collections.generic/idictionary/get_isfixedsize/)() const | ตรวจสอบว่าขนาดคอลเลกชันเป็นคงที่หรือไม่. |
| virtual **bool** [get_IsReadOnly](../../system.collections.generic/icollection/get_isreadonly/)() const | ตรวจสอบว่าคอลเลกชันเป็นแบบอ่านอย่างเดียวหรือไม่. |
| **bool** [get_IsSynchronized](../../system.collections.generic/idictionary/get_issynchronized/)() const | ตรวจสอบว่าคอนเทนเนอร์ปลอดภัยต่อเธรดหรือไม่. |
| virtual [SharedPtr](../../system/sharedptr/)<[ICollection](../../system.collections.generic/icollection/)<TKey>> [get_Keys](../../system.collections.generic/idictionary/get_keys/)() const | เข้าถึงคอลเลกชันของคีย์. |
| [SharedPtr](../../system/sharedptr/)<typename [ThisType::KeyCollection](../../system.collections.generic/dictionary/keycollection/)> [get_KeysInternal](./get_keysinternal/)() const override | รับคอลเลกชันห่อเพื่อเข้าถึงคีย์ของพจนานุกรม. |
| [SharedPtr](../../system/sharedptr/)<[Object](../../system/object/)> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | รับออบเจ็กต์ที่คอลเลกชันทำการซิงโครไนซ์ผ่าน. |
| virtual [SharedPtr](../../system/sharedptr/)<[ICollection](../../system.collections.generic/icollection/)<TValue>> [get_Values](../../system.collections.generic/idictionary/get_values/)() const | เข้าถึงคอลเลกชันของค่า. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับออบเจ็กต์. |
| [IEnumeratorPtr](../../system.collections.generic/dictionary/ienumeratorptr/) [GetEnumerator](../../system.collections.generic/dictionary/getenumerator/)() override | สร้างออบเจ็กต์อีนูเมอเรเตอร์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอเนกประเภของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของออบเจ็กต์แบบกำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของออบเจ็กต์. เป็นอเนกประเภของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual TValue [GetValueOrDefault](../../system.collections.generic/idictionary/getvalueordefault/)(const TKey&) const | คืนค่าหากพบ; หรือ **Value()** ในกรณีอื่น. |
| virtual TValue [GetValueOrDefault](../../system.collections.generic/idictionary/getvalueordefault/)(const TKey&, const TValue&) const | คืนค่าหากพบ; หรือ **defaultValue** ในกรณีอื่น. |
| virtual TValue [GetValueOrNull](../../system.collections.generic/idictionary/getvalueornull/)(const TKey&) const | คืนค่าหากพบ; หรือ **null** ในกรณีอื่น, มีความหมายเฉพาะกับประเภทอ้างอิง. |
| [ICollection](../../system.collections.generic/icollection/icollection/)() | คอนสตรักเตอร์เริ่มต้น. |
| [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)&) | คอนสตรักเตอร์สำเนา. |
| [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)&&) | คอนสตรักเตอร์ย้าย. |
| virtual TValue [idx_get](../../system.collections.generic/idictionary/idx_get/)(const TKey&) const | ฟังก์ชัน getter. |
| void [idx_set](./idx_set/)(const TKey&, TValue) override | ตั้งค่าอิลิเมนต์ที่ตำแหน่งเฉพาะ. |
| virtual void [idx_set](../../system.collections.generic/idictionary/idx_set/)(const TKey&, TValue) | ฟังก์ชัน setter. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)&) const | ตรวจสอบว่าออบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นอเนกประเภของตัวดำเนินการ C# 'is'. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)<T, T, T>&) | ใช้ฟังก์ชัน accumulator กับลำดับ. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function<**bool**(T)>) | กำหนดว่าทุกอิลิเมนต์ของลำดับตรงตามเงื่อนไขหรือไม่. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | กำหนดว่าลำดับมีอิลิเมนต์ใดหรือไม่. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function<**bool**(T)>) | กำหนดว่ามีอิลิเมนต์ใดในลำดับที่มีอยู่หรือเป็นไปตามเงื่อนไขหรือไม่. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | คำนวณค่าเฉลี่ยของลำดับของค่าตัวเลข. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)<T, ResultType>&) | คำนวณค่าเฉลี่ยของลำดับของค่าที่ได้โดยเรียกใช้ฟังก์ชันแปลงบนแต่ละอิลิเมนต์ของลำดับอินพุต. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<ResultType>> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | แปลงประเภทของอิลิเมนต์เป็นประเภทที่ระบุ. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<Result>> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<T>> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<T>>) | เชื่อมต่อสองลำดับเข้าด้วยกัน. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | กำหนดว่าลำดับมีค่าที่ระบุหรือไม่. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | คืนจำนวนอิลิเมนต์ในลำดับ (คำนวณโดยการนับโดยตรง). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)<T, **bool**>&) | คืนจำนวนอิลิเมนต์ในลำดับที่ตรงตามเงื่อนไขที่ระบุ. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | คืนอิลิเมนต์ที่ตำแหน่งที่ระบุในลำดับ. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | คืนอิลิเมนต์ที่ตำแหน่งที่ระบุในลำดับ. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | คืนอิลิเมนต์แรกของลำดับ. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)<T, **bool**>&) | คืนอิลิเมนต์แรกของลำดับที่ตรงตามเงื่อนไขที่ระบุ. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | คืนอิลิเมนต์แรกของลำดับ หรือค่าตั้งต้นหากลำดับว่าง. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function<**bool**(T)>) | คืนอิลิเมนต์แรกของลำดับที่ตรงตามเงื่อนไข หรือค่าตั้งต้นหากไม่พบอิลิเมนต์ที่ตรง. |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, T>>>> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>) | จัดกลุ่มอิลิเมนต์ของลำดับ. |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>, [System::Func](../../system/func/)<T, Element>) | จัดกลุ่มอิลิเมนต์ของลำดับ. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Source>>>> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>, [System::Func](../../system/func/)<Source, Element>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | คืนอิลิเมนต์สุดท้ายของลำดับ. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | คืนอิลิเมนต์สุดท้ายของลำดับ หรือค่าตั้งต้นหากลำดับว่าง. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)<T, ResultType>&) | เรียกฟังก์ชันแปลงบนแต่ละอิลิเมนต์ของลำดับทั่วไปและคืนค่าผลลัพธ์สูงสุด. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)<T, ResultType>&) | เรียกฟังก์ชันแปลงบนแต่ละอิลิเมนต์ของลำดับทั่วไปและคืนค่าผลลัพธ์ต่ำสุด. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<ResultType>> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | กรองอิลิเมนต์ของลำดับตามประเภทที่ระบุ. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<Result>> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)<T, Key>&) | เรียงลำดับอิลิเมนต์ของลำดับในลำดับจากน้อยไปมากตามค่าคีย์ที่เลือกโดย keySelector. |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<T, Key>&) | เรียงลำดับอิลิเมนต์ของลำดับในลำดับจากมากไปน้อยตามค่าคีย์ที่เลือกโดย keySelector. |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<T>> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | สลับลำดับของอิลิเมนต์ในลำดับ. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<ResultType>> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)<T, ResultType>&) | แปลงอิลิเมนต์ของลำดับ. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<ResultType>> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)<T, **int32_t**, ResultType>&) | แปลงแต่ละอิลิเมนต์ของลำดับเป็นรูปแบบใหม่โดยรวมดัชนีของอิลิเมนต์. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<Result>> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)<Source, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<Result>> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)<Source, **int32_t**, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<ResultType>> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)<T, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<ResultType>>> &) | โปรเจกต์แต่ละอิลิเมนต์ของลำดับและรวมลำดับผลลัพธ์ให้เป็นลำดับเดียว. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<Result>> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)<Source, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<Result>>> &) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<T>> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | ข้ามจำนวนอิลิเมนต์ต่อเนื่องที่กำหนดจากตอนเริ่มของลำดับและคืนส่วนที่เหลือ. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<T>> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | คืนจำนวนอิลิเมนต์ต่อเนื่องที่กำหนดจากตอนเริ่มของลำดับ. |
| [System::ArrayPtr](../../system/arrayptr/)<T> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | สร้างอาเรย์จากลำดับ. |
| [SharedPtr](../../system/sharedptr/)<[List](../../system.collections.generic/list/)<T>> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | สร้าง List<T> จากลำดับ. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<T>> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function<**bool**(T)>) | กรองลำดับตามเงื่อนไขที่ระบุ. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอเนกประเภของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทกำหนดเอง. |
| [Object](../../system/object/object/)() | สร้างออบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
| [Object](../../system/object/object/)([Object](../../system/object/) const&) | คอนสตรักเตอร์สำเนา. จริง ๆ ไม่คัดลอกอะไรเลย เพียงเริ่มต้นออบเจ็กต์ใหม่และเปิดการคอปี้คอนสตรักเตอร์ของซับคลาส. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)&&) | โอเปอเรเตอร์การกำหนดค่าแบบย้าย. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)&) | โอเปอเรเตอร์การกำหนดค่าแบบย้าย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | โอเปอเรเตอร์การกำหนดค่า. จริง ๆ ไม่คัดลอกอะไรเลย เพียงเริ่มต้นออบเจ็กต์ใหม่และเปิดการคอปี้คอนสตรักเตอร์ของซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | เปรียบเทียบออบเจ็กต์ประเภทค่าด้วย nullptr โดยอ้างอิง. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| **bool** [Remove](./remove/)(const TKey&) override | ลบอิลิเมนต์จากคอนเทนเนอร์. |
| virtual **bool** [Remove](../../system.collections.generic/idictionary/remove/)(const TKey&) | ลบคีย์จากคอนเทนเนอร์. |
| virtual **bool** [Remove](../../system.collections.generic/icollection/remove/)(const T&) | ลบอิลิเมนต์จากคอลเลกชัน. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอเนกประเภของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงออบเจ็กต์กำหนดเองเป็นสตริง. |
| **bool** [TryAdd](./tryadd/)(const TKey&, const TValue&) | พยายามเพิ่มคู่คีย์/ค่าเข้าไปในพจนานุกรม. |
| virtual **bool** [TryGetValue](../../system.collections.generic/idictionary/trygetvalue/)(const TKey&, TValue&) const | ค้นหาค่าและดึงคืนหากพบ. |
| static const [TypeInfo](../../system/typeinfo/)& [Type](../../system/object/type/)() | ทำหน้าที่เหมือน construct typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | รับการนำไปใช้ของ begin const iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | รับการนำไปใช้ของ begin iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | รับการนำไปใช้ของ end const iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | รับการนำไปใช้ของ end iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | ตัวทำลาย. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายออบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## นิยามประเภท

| นิยามประเภท | คำอธิบาย |
| --- | --- |
| [ThisType](./thistype/) | ประเภทนี้. |
| [BaseType](./basetype/) | ประเภทการนำไปใช้. |

## หมายเหตุ

```cpp
#include <system/collections/concurrent/concurrent_dictionary.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  const int itemsCount = 32;

  // สร้างอินสแตนซ์ของคลาส ConcurrentDictionary.
  auto concurrentDictionary = MakeObject<ConcurrentDictionary<int, int>>();

  // เติมข้อมูลใน concurrent dictionary.
  for (auto i = 0; i < itemsCount; ++i)
  {
    concurrentDictionary->Add(i, i * i);
  }

  Console::WriteLine(concurrentDictionary->idx_get(3));

  return 0;
}
/*
ตัวอย่างโค้ดนี้สร้างผลลัพธ์ต่อไปนี้:
9
*/
```

## ดูเพิ่มเติม

* คลาส [Dictionary](../../system.collections.generic/dictionary/)
* เนมสเปซ [System::Collections::Concurrent](../)
* ไลบรารี [Aspose.Slides](../../)