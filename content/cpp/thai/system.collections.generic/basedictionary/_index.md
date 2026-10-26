---
title: BaseDictionary
second_title: Aspose.Slides สำหรับอ้างอิง API C++
description: "ดำเนินการโค้ดทั่วไปสำหรับโครงสร้างข้อมูลแบบพจนานุกรมหลายประเภท (เช่น Dictionary, SortedDictionary) ไม่ควรใช้โดยตรง ยกเว้นเพื่อสืบทอดเมื่อกำหนดคอนเทนเนอร์ อ็อบเจ็กต์ของคลาสนี้ควรสร้างด้วยฟังก์ชัน System::MakeObject() เท่านั้น ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการตรวจสอบข้อผิดพลาด เสมอให้หุ้มคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้ส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน"
type: docs
weight: 53
url: /th/system.collections.generic/basedictionary/
---
## BaseDictionary คลาส

Implements common code for various dictionary-alike data structures (เช่น [Dictionary](../dictionary/), [SortedDictionary](../sorteddictionary/)). Shouldn't be used directly, except for inheritance when defining containers. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename Map>class BaseDictionary : public System::Collections::Generic::IDictionary<Map::key_type, Map::mapped_type>
```

### พารามิเตอร์ของเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Map | ประเภทแผนที่พื้นฐาน. |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| void [_add_range](./_add_range/)(std::initializer_list\<typename Map::value_type\>) | เฉพาะ C++. |
| void [Add](./add/)(const key_t\&, const mapped_t\&) override | เพิ่มคู่คีย์-ค่าเข้าไปในพจนานุกรม. |
|  [BaseDictionary](./basedictionary/)() | สร้างโครงสร้างข้อมูลว่าง. |
|  [BaseDictionary](./basedictionary/)(int, const Args\&...) | คอนสตรัคเตอร์ส่งต่อเพื่อส่งอาร์กิวเมนต์ไปยังคอนสตรัคเตอร์แผนที่พื้นฐาน. |
|  [BaseDictionary](./basedictionary/)([BaseType](./basetype/) *, const Args\&...) | คอนสตรัคเตอร์คัดลอก. |
|  [BaseDictionary](./basedictionary/)([BaseType](./basetype/) *) | คอนสตรัคเตอร์คัดลอก. |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | คืน iterator ไปยัง KVPair-wrapper สำหรับอิลิเมนต์คีย์-ค่าในคอนเทนเนอร์ Implemented in C# style - iterator ควรคืน KVPair-object พร้อมอินเทอร์เฟซ get_Key() และ get_Value() หากคอนเทนเนอร์ว่าง iterator ที่คืนจะเท่ากับ [end()](../ienumerable/end/). |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | รับ iterator ที่ชี้ไปยังอิลิเมนต์แรก (ถ้ามี) ของคอลเลกชัน iterator นี้ไม่สามารถใช้เปลี่ยนแปลงอ็อบเจกต์ที่อ้างอิงได้เนื่องจาก [GetEnumerator()](../ienumerable/getenumerator/) คืนอ็อบเจกต์สำเนาของ T. |
| stl_const_iterator [cbegin](./cbegin/)() const | คืน iterator ไปยังอิลิเมนต์แรกของคอนเทนเนอร์ Implemented in STL-style. หากคอนเทนเนอร์ว่าง iterator ที่คืนจะเท่ากับ [end()](../ienumerable/end/). |
| stl_const_iterator [cend](./cend/)() const | คืน iterator ไปยังอิลิเมนต์ที่ตามหลังอิลิเมนต์สุดท้ายของคอนเทนเนอร์ Implemented in STL-style. อิลิเมนต์นี้ทำหน้าที่เป็นตัวแทน; การพยายามเข้าถึงจะทำให้เกิดพฤติกรรมไม่กำหนด. |
| void [Clear](./clear/)() override | ลบอิลิเมนต์ทั้งหมด. |
| **bool** [ContainsKey](./containskey/)(const key_t\&) const override | ตรวจสอบว่าคีย์มีอยู่ในพจนานุกรมหรือไม่. |
| **bool** [ContainsValue](./containsvalue/)(const mapped_t\&) | ตรวจสอบว่าค่ามีอยู่ในพจนานุกรมหรือไม่ ใช้ตัวดำเนินการ == เพื่อเปรียบเทียบค่า. |
| void [CopyTo](../idictionary/copyto/)([ArrayPtr](../../system/arrayptr/)\<[KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\>, int) override | คัดลอกเนื้อหาพจนานุกรมเข้าสู่สมาชิกอาร์เรย์ที่มีอยู่. |
| Map\& [data](./data/)() | ตัวเข้าถึงที่จัดเก็บข้อมูลพื้นฐาน. |
| const Map\& [data](./data/)() const | ตัวเข้าถึงที่จัดเก็บข้อมูลพื้นฐาน. |
| [const_iterator](./const_iterator/) [end](./end/)() const | คืน iterator ไปยัง KVPair-wrapper สำหรับอิลิเมนต์คีย์-ค่าที่ตามหลังอิลิเมนต์สุดท้ายของคอนเทนเนอร์ Implemented in C# style - iterator ควรคืน KVPair-object พร้อมอินเทอร์เฟซ get_Key() และ get_Value() อิลิเมนต์นี้ทำหน้าที่เป็นตัวแทน; การพยายามเข้าถึงจะทำให้พฤติกรรมไม่กำหนด. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | รับ iterator ที่ชี้หลังอิลิเมนต์สุดท้าย (ถ้ามี) ของคอลเลกชัน iterator นี้ไม่สามารถใช้เปลี่ยนอ็อบเจกต์ที่อ้างอิงได้เนื่องจาก [GetEnumerator()](../ienumerable/getenumerator/) คืนอ็อบเจกต์สำเนาของ T. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมสไตล์ C# ที่ NaN สองค่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมสไตล์ C# ที่ NaN สองค่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อใช้ภายในเท่านั้น. |
| **int32_t** [get_Count](./get_count/)() const override | รับจำนวนอิลิเมนต์. |
| **bool** [get_IsFixedSize](../idictionary/get_isfixedsize/)() const | ตรวจสอบว่าขนาดคอลเลกชันคงที่หรือไม่. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | ตรวจสอบว่าคอลเลกชันเป็นแบบอ่านอย่างเดียวหรือไม่. |
| **bool** [get_IsSynchronized](../idictionary/get_issynchronized/)() const | ตรวจสอบว่าคอนเทนเนอร์เป็นแบบ thread-safe หรือไม่. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICollection](../icollection/)\<TKey\>\> [get_Keys](../idictionary/get_keys/)() const | เข้าถึงคอลเลกชันของคีย์. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | รับอ็อบเจกต์ที่คอลเลกชันซิงโครไนซ์ผ่าน. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICollection](../icollection/)\<TValue\>\> [get_Values](../idictionary/get_values/)() const | เข้าถึงคอลเลกชันของค่า. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมกับอ็อบเจ็กต์. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<[KeyValuePair](../keyvaluepair/)\<key_t, mapped_t\>\>\> [GetEnumerator](./getenumerator/)() | สร้างอินสแตนซ์ enumerator ควรทำโดย subclass. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | ฟังก์ชันคล้าย C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถทำแฮชอ็อบเจ็กต์กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ ฟังก์ชันคล้าย C# [System.Object.GetType()](../../system/object/gettype/). |
| mapped_t [GetValueOrDefault](./getvalueordefault/)(const key_t\&) const override | คืนค่า หากพบ; หรือ **Value()** หากไม่พบ. |
| mapped_t [GetValueOrDefault](./getvalueordefault/)(const key_t\&, const mapped_t\&) const override | คืนค่า หากพบ; หรือ **defaultValue** หากไม่พบ. |
| mapped_t [GetValueOrNull](./getvalueornull/)(const key_t\&) const override | คืนค่า หากพบ; หรือ **null** หากไม่พบ ใช้ได้เฉพาะประเภทอ้างอิง. |
|  [ICollection](../icollection/icollection/)() | คอนสตรัคเตอร์เริ่มต้น. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | คอนสตรัคเตอร์คัดลอก. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | คอนสตรัคเตอร์ย้าย. |
| mapped_t [idx_get](./idx_get/)(const key_t\&) const override | ฟังก์ชัน getter ตามคีย์. |
| void [idx_set](./idx_set/)(const key_t\&, mapped_t) override | ฟังก์ชัน setter ตามคีย์. แก้ไขหรือสร้างอิลิเมนต์. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType ฟังก์ชันคล้ายตัวดำเนินการ 'is' ของ C#. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | ใช้ฟังก์ชัน accumulator กับลำดับ. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | กำหนดว่าทุกรายการในลำดับเป็นไปตามเงื่อนไขหรือไม่. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | กำหนดว่าลำดับมีอิลิเมนต์ใดหรือไม่. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | กำหนดว่ามีอิลิเมนต์ใดในลำดับที่ตรงตามเงื่อนไขหรือไม่. |
| T [LINQ_Average](../ienumerable/linq_average/)() | คำนวณค่าเฉลี่ยของลำดับค่าตัวเลข. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | คำนวณค่าเฉลี่ยของลำดับค่าที่ได้จากการเรียกฟังก์ชันแปลงบนแต่ละอิลิเมนต์ของลำดับอินพุต. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | แคสต์อิลิเมนต์ไปเป็นประเภทที่ระบุ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | ต่อสองลำดับเข้าด้วยกัน. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | กำหนดว่าลำดับมีค่าที่ระบุหรือไม่. |
| int [LINQ_Count](../ienumerable/linq_count/)() | คืนจำนวนอิลิเมนต์ในลำดับ (คำนวณโดยการนับโดยตรง). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | คืนจำนวนอิลิเมนต์ในลำดับที่ตรงกับเงื่อนไขที่ระบุ. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | คืนอิลิเมนต์ที่ตำแหน่งที่ระบุในลำดับ. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | คืนอิลิเมนต์ที่ตำแหน่งที่ระบุในลำดับ. |
| T [LINQ_First](../ienumerable/linq_first/)() | คืนอิลิเมนต์แรกของลำดับ. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | คืนอิลิเมนต์แรกของลำดับที่ตรงกับเงื่อนไขที่ระบุ. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | คืนอิลิเมนต์แรกของลำดับ หรือค่าปริยายหากลำดับว่าง. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | คืนอิลิเมนต์แรกของลำดับที่ตรงกับเงื่อนไข หรือค่าปริยายหากไม่พบ. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | จัดกลุ่มอิลิเมนต์ของลำดับ. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | จัดกลุ่มอิลิเมนต์ของลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | คืนอิลิเมนต์สุดท้ายของลำดับ. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | คืนอิลิเมนต์สุดท้ายของลำดับ หรือค่าปริยายหากลำดับว่าง. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกฟังก์ชันแปลงบนแต่ละอิลิเมนต์ของลำดับทั่วไปและคืนค่าที่ได้สูงสุด. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกฟังก์ชันแปลงบนแต่ละอิลิเมนต์ของลำดับทั่วไปและคืนค่าที่ได้ต่ำสุด. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | กรองอิลิเมนต์ของลำดับตามประเภทที่ระบุ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | เรียงลำดับอิลิเมนต์ของลำดับจากน้อยไปมากตามค่าคีย์ที่เลือกโดย keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | เรียงลำดับอิลิเมนต์ของลำดับจากมากไปน้อยตามค่าคีย์ที่เลือกโดย keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | กลับลำดับของอิลิเมนต์ในลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | แปลงอิลิเมนต์ของลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | แปลงแต่ละอิลิเมนต์ของลำดับเป็นรูปแบบใหม่โดยใช้ดัชนีของอิลิเมนต์. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | โปรเจกต์แต่ละอิลิเมนต์ของลำดับและรวมลำดับผลลัพธ์เป็นหนึ่งลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | ข้ามจำนวนอิลิเมนต์ต่อเนื่องที่ระบุจากจุดเริ่มต้นของลำดับและคืนส่วนที่เหลือ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | คืนจำนวนอิลิเมนต์ต่อเนื่องที่ระบุจากจุดเริ่มต้นของลำดับ. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | สร้างอาเรย์จากลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | สร้าง List<T> จากลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | กรองลำดับตามเงื่อนไขที่ระบุ. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อก เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | ฟังก์ชันคล้าย C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทกำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์และเริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริงๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และทำให้ subclass สามารถคัดลอกได้. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | ตัวดำเนินการมอบหมายแบบย้าย. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | ตัวดำเนินการมอบหมายแบบย้าย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมาย ไม่ได้คัดลอกอะไรจริงๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และทำให้ subclass สามารถคัดลอกได้. |
| virtual mapped_t\& [operator[]](./operator[]/)(const key_t\&) | ฟังก์ชัน accessor. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| **bool** [Remove](./remove/)(const key_t\&) override | ลบคีย์เฉพาะจากพจนานุกรม. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงร่วมโดยค่าที่ระบุ. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(unsigned int) override |  |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (ไม่ใช่ shared) ให้เปลี่ยนพอยเตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนอ้างอิงร่วม ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนอ้างอิงร่วมและคืนค่า ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | ฟังก์ชันคล้าย C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจ็กต์กำหนดเองเป็นสตริงได้. |
| **bool** [TryGetValue](./trygetvalue/)(const key_t\&, mapped_t\&) const override | ค้นหาค่าตามคีย์และดึงคืนหากพบ. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/). |
| System::Details::VirtualizedIteratorBase\<[KVPair](./kvpair/)\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | รับการทำงานของ begin const iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| System::Details::VirtualizedIteratorBase\<[KVPair](./kvpair/)\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | รับการทำงานของ begin iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| System::Details::VirtualizedIteratorBase\<[KVPair](./kvpair/)\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | รับการทำงานของ end const iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| System::Details::VirtualizedIteratorBase\<[KVPair](./kvpair/)\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | รับการทำงานของ end iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual  [~ICollection](../icollection/~icollection/)() | ตัวทำลาย. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์และปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## นิยามประเภท

| นิยามประเภท | คำอธิบาย |
| --- | --- |
| [map_t](./map_t/) | ประเภทแผนที่ภายใน. |
| [KeyCollection](./keycollection/) | ตรวจสอบว่าเราใช้ allocator ที่ถูกต้องกับประเภทการจัดเก็บพื้นฐาน. |
| [ValueCollection](./valuecollection/) | คอลเลกชันของค่า. |
| [KVPair](./kvpair/) | ประเภทคู่คีย์-ค่า. |
| [BaseType](./basetype/) | อินเทอร์เฟซที่ทำงาน. |
| [iterator](./iterator/) | ประเภท iterator. |
| [const_iterator](./const_iterator/) | ประเภท const iterator. |

## ดูเพิ่มเติม

* คลาส [IDictionary](../idictionary/)
* เนมสเปซ [System::Collections::Generic](../)
* ไลบรารี [Aspose.Slides](../../)