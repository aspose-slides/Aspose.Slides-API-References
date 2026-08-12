---
title: IDictionary
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: "อินเทอร์เฟซสำหรับคอนเทนเนอร์แบบพจนานุกรม. วัตถุของคลาสนี้ควรจัดสรรเท่านั้นโดยใช้ฟังก์ชัน System::MakeObject() . ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสะแคิร์หรือลักษณะการใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการละเมิด assertion . ควรหุ้มคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr เสมอและใช้พอยน์เตอร์นี้เพื่อส่งต่อเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 274
url: /th/system.collections.generic/idictionary/
---
## IDictionary คลาส

อินเทอร์เฟซสำหรับคอนเทนเนอร์ที่คล้ายพจนานุกรม. วัตถุของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new, เนื่องจากจะทำให้เกิดข้อผิดพลาดเวลารันและ/หรือการตรวจสอบข้อผิดพลาด. ควรห่อหุ้มคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งผ่านให้ฟังก์ชันเป็นอาร์กิวเมนต์.

```cpp
template<typename TKey,typename TValue>class IDictionary : public System::Collections::Generic::ICollection<KeyValuePair<TKey, TValue>>
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TKey | ประเภทคีย์. |
| TValue | ประเภทค่า. |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual void [Add](./add/)(const TKey\&, const TValue\&) | เพิ่มคู่คีย์-ค่าเข้าในคอนเทนเนอร์. |
| virtual void [Add](../icollection/add/)(const T\&) | เพิ่มองค์ประกอบเข้าในคอลเลกชัน. |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | รับ iterator ที่ชี้ไปยังองค์ประกอบแรก (ถ้ามี) ของคอลเลกชัน. iterator นี้ไม่สามารถใช้เปลี่ยนวัตถุที่อ้างอิงได้เนื่องจาก [GetEnumerator()](../ienumerable/getenumerator/) คืนออบเจ็กต์สำเนาของ T. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | รับ iterator ที่ชี้ไปยังองค์ประกอบแรก (ถ้ามี) ของอินสแตนซ์ที่มี const ของคอลเลกชัน. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | รับ iterator ที่ชี้ไปยังองค์ประกอบที่มี const แรก (ถ้ามี) ของคอลเลกชัน. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | รับ iterator ที่ชี้ไปหลังจากองค์ประกอบ const ตัวสุดท้าย (ถ้ามี) ของคอลเลกชัน. |
| virtual void [Clear](../icollection/clear/)() | ลบองค์ประกอบทั้งหมดออกจากคอลเลกชัน. |
| virtual **bool** [Contains](../icollection/contains/)(const T\&) const | ตรวจสอบว่าองค์ประกอบมีอยู่ในคอลเลกชันหรือไม่. |
| virtual **bool** [ContainsKey](./containskey/)(const TKey\&) const | ตรวจสอบว่าคอนเทนเนอร์มีคีย์หรือไม่. |
| void [CopyTo](./copyto/)([ArrayPtr](../../system/arrayptr/)\<[KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\>, int) override | คัดลอกเนื้อหาพจนานุกรมเข้าสู่สมาชิกอาร์เรย์ที่มีอยู่. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | รับ iterator ที่ชี้ไปหลังจากองค์ประกอบสุดท้าย (ถ้ามี) ของคอลเลกชัน. iterator นี้ไม่สามารถใช้เปลี่ยนวัตถุที่อ้างอิงได้เนื่องจาก [GetEnumerator()](../ienumerable/getenumerator/) คืนออบเจ็กต์สำเนาของ T. |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | รับ iterator ที่ชี้ไปหลังจากองค์ประกอบสุดท้าย (ถ้ามี) ของอินสแตนซ์ที่มี const ของคอลเลกชัน. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบออบเจ็กต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่า floating point แบบ C# ที่ NaN สองค่าเป็นเท่าเทียมกันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่า floating point แบบ C# ที่ NaN สองค่าเป็นเท่าเทียมกันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| virtual int [get_Count](../icollection/get_count/)() const | รับจำนวนองค์ประกอบในคอลเลกชัน. |
| **bool** [get_IsFixedSize](./get_isfixedsize/)() const | ตรวจสอบว่าขนาดคอลเลกชันเป็นคงที่หรือไม่. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | ตรวจสอบว่าคอลเลกชันเป็นแบบอ่านอย่างเดียวหรือไม่. |
| **bool** [get_IsSynchronized](./get_issynchronized/)() const | ตรวจสอบว่าคอนเทนเนอร์ปลอดภัยต่อเธรดหรือไม่. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICollection](../icollection/)\<TKey\>\> [get_Keys](./get_keys/)() const | เข้าถึงคอลเลกชันคีย์. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | รับออบเจ็กต์ที่คอลเลกชันซิงโครไนซ์ผ่าน. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICollection](../icollection/)\<TValue\>\> [get_Values](./get_values/)() const | เข้าถึงคอลเลกชันค่า. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับออบเจ็กต์. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<T\>\> [GetEnumerator](../ienumerable/getenumerator/)() | รับ enumerator. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอนาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชออบเจ็กต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของออบเจ็กต์. เป็นอนาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual TValue [GetValueOrDefault](./getvalueordefault/)(const TKey\&) const | คืนค่าถ้าพบ; หรือ **Value()** หากไม่พบ. |
| virtual TValue [GetValueOrDefault](./getvalueordefault/)(const TKey\&, const TValue\&) const | คืนค่าถ้าพบ; หรือ **defaultValue** หากไม่พบ. |
| virtual TValue [GetValueOrNull](./getvalueornull/)(const TKey\&) const | คืนค่าถ้าพบ; หรือ **null** หากไม่พบ, มีความหมายเฉพาะสำหรับประเภทอ้างอิง. |
|  [ICollection](../icollection/icollection/)() | คอนสตรัคเตอร์เริ่มต้น. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | คอนสตรัคเตอร์คัดลอก. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | คอนสตรัคเตอร์ย้าย. |
| virtual TValue [idx_get](./idx_get/)(const TKey\&) const | ฟังก์ชัน getter. |
| virtual void [idx_set](./idx_set/)(const TKey\&, TValue) | ฟังก์ชัน setter. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าออบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นอนาล็อกของโอเปอเรเตอร์ 'is' ของ C#. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | ใช้ฟังก์ชัน accumulator กับลำดับ. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | กำหนดว่าทุกองค์ประกอบของลำดับเป็นไปตามเงื่อนไขหรือไม่. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | กำหนดว่าลำดับมีองค์ประกอบใด ๆ หรือไม่. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | กำหนดว่ามีองค์ประกอบใดในลำดับที่มีอยู่หรือเป็นไปตามเงื่อนไขหรือไม่. |
| T [LINQ_Average](../ienumerable/linq_average/)() | คำนวณค่าเฉลี่ยของลำดับของค่าตัวเลข. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | คำนวณค่าเฉลี่ยของลำดับของค่าโดยเรียกฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับอินพุต. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | แคสท์องค์ประกอบเป็นประเภทที่ระบุ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | ต่อสองลำดับเข้าด้วยกัน. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | ตรวจสอบว่าลำดับมีค่าที่ระบุหรือไม่. |
| int [LINQ_Count](../ienumerable/linq_count/)() | คืนจำนวนองค์ประกอบในลำดับ (คำนวณโดยการนับโดยตรง). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | คืนจำนวนองค์ประกอบในลำดับที่เป็นไปตามเงื่อนไขที่ระบุ. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | คืนองค์ประกอบที่ตำแหน่งที่ระบุในลำดับ. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | คืนองค์ประกอบที่ตำแหน่งที่ระบุในลำดับ. |
| T [LINQ_First](../ienumerable/linq_first/)() | คืนองค์ประกอบแรกของลำดับ. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | คืนองค์ประกอบแรกของลำดับที่เป็นไปตามเงื่อนไขที่ระบุ. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | คืนองค์ประกอบแรกของลำดับ, หรือค่าตั้งต้นหากลำดับว่าง. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | คืนองค์ประกอบแรกของลำดับที่เป็นไปตามเงื่อนไขหรือค่าตั้งต้นหากไม่พบองค์ประกอบดังกล่าว. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | จัดกลุ่มองค์ประกอบของลำดับ. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | จัดกลุ่มองค์ประกอบของลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | คืนองค์ประกอบสุดท้ายของลำดับ. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | คืนองค์ประกอบสุดท้ายของลำดับ, หรือค่าตั้งต้นหากลำดับว่าง. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับทั่วไปและคืนค่าที่ได้มากที่สุด. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับทั่วไปและคืนค่าที่ได้ต่ำที่สุด. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | กรององค์ประกอบของลำดับตามประเภทที่ระบุ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | จัดเรียงองค์ประกอบของลำดับในลำดับเพิ่มตามค่าคีย์ที่เลือกโดย keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | จัดเรียงองค์ประกอบของลำดับในลำดับลดตามค่าคีย์ที่เลือกโดย keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | กลับลำดับขององค์ประกอบในลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | แปลงองค์ประกอบของลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | แปลงแต่ละองค์ประกอบของลำดับเป็นรูปแบบใหม่โดยรวมดัชนีขององค์ประกอบ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | โปรเจกต์แต่ละองค์ประกอบของลำดับและรวมลำดับที่ได้เป็นหนึ่งลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | ข้ามจำนวนองค์ประกอบต่อเนื่องที่ระบุจากจุดเริ่มต้นของลำดับและคืนส่วนที่เหลือ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | คืนจำนวนองค์ประกอบต่อเนื่องที่ระบุจากจุดเริ่มต้นของลำดับ. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | สร้างอาร์เรย์จากลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | สร้าง List<T> จากลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | กรองลำดับตามพร็อดิกาตาที่ระบุ. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อก. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentry. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอนาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างออบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นออบเจ็กต์ใหม่และเปิดให้สามารถคัดลอกสับคลาสได้. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | โอเปอเรเตอร์กำหนดค่าแบบย้าย. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | โอเปอเรเตอร์กำหนดค่าแบบย้าย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์กำหนดค่า. ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นออบเจ็กต์ใหม่และเปิดให้สามารถคัดลอกสับคลาสได้. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบออบเจ็กต์โดยการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบออบเจ็กต์โดยการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| virtual **bool** [Remove](./remove/)(const TKey\&) | ลบคีย์จากคอนเทนเนอร์. |
| virtual **bool** [Remove](../icollection/remove/)(const T\&) | ลบองค์ประกอบจากคอลเลกชัน. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงแบบแชร์โดยค่าที่ระบุ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทนที่จะเป็น shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงแบบแชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบแชร์. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงแบบแชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอนาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดให้แปลงออบเจ็กต์ที่กำหนดเองเป็นสตริง. |
| virtual **bool** [TryGetValue](./trygetvalue/)(const TKey\&, TValue\&) const | ค้นหาค่าและดึงคืนหากพบ. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentry. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../ienumerable/virtualizebeginconstiterator/)() const | รับการทำงานของ begin const iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../ienumerable/virtualizebeginiterator/)() | รับการทำงานของ begin iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../ienumerable/virtualizeendconstiterator/)() const | รับการทำงานของ end const iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../ienumerable/virtualizeenditerator/)() | รับการทำงานของ end iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | ตัวทำลาย. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายออบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## นิยามประเภท

| นิยามประเภท | คำอธิบาย |
| --- | --- |
| [BaseType](./basetype/) | Base interface type. |
| [KeyValuePairType](./keyvaluepairtype/) | Key value pair type. |

## ดูเพิ่มเติม

* คลาส [ICollection](../icollection/)
* เนมสเปซ [System::Collections::Generic](../)
* ไลบรารี [Aspose.Slides](../../)