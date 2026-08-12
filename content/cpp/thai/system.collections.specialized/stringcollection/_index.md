---
title: StringCollection
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "รายการสตริงที่จัดทำเป็นดัชนี. วัตถุของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดระหว่างการทำงานและ/หรือการตรวจสอบความถูกต้อง. ให้ห่อหุ้มคลาสนี้ด้วยตัวชี้ System::SmartPtr และใช้ตัวชี้นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 27
url: /th/system.collections.specialized/stringcollection/
---
## StringCollection คลาส


Indexed list of strings. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class StringCollection : public System::Collections::Generic::IEnumerable<System::String>
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| int [Add](./add/)(const [System::String](../../system/string/)\&) | เพิ่มค่าไปยังส่วนท้ายของรายการ. |
| void [AddRange](./addrange/)(const [ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>\&) | เพิ่มองค์ประกอบเข้าไปในคอนเทนเนอร์. |
| [iterator](./iterator/) [begin](./begin/)() | คืนค่า iterator ไปยังองค์ประกอบแรกของคอนเทนเนอร์ หากคอนเทนเนอร์ว่าง iterator ที่คืนค่าจะเท่ากับ [end()](./end/). |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | คืนค่า iterator ไปยังองค์ประกอบแรกของคอนเทนเนอร์ที่กำหนดเป็น const หากคอนเทนเนอร์ว่าง iterator ที่คืนค่าจะเท่ากับ [end()](./end/). |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | คืนค่า iterator ไปยังองค์ประกอบแรกที่กำหนดเป็น const ของคอนเทนเนอร์ หากคอนเทนเนอร์ว่าง iterator ที่คืนค่าจะเท่ากับ [cend()](./cend/). |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | คืนค่า iterator ไปยังองค์ประกอบที่ตามหลังองค์ประกอบสุดท้ายของคอนเทนเนอร์ องค์ประกอบนี้ทำหน้าที่เป็นตัวแทน; การพยายามเข้าถึงจะทำให้เกิดพฤติกรรมไม่กำหนด. |
| void [Clear](./clear/)() | ลบองค์ประกอบทั้งหมด. |
| **bool** [Contains](./contains/)(const [System::String](../../system/string/)\&) const | ตรวจสอบว่ามีสตริงที่ระบุอยู่ในคอนเทนเนอร์หรือไม่. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>\&, const **int32_t**) const | คัดลอกองค์ประกอบไปยังอาร์เรย์ที่มีอยู่. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | คืนค่า reverse iterator ไปยังองค์ประกอบแรกของคอนเทนเนอร์ที่กลับด้าน ซึ่งสอดคล้องกับองค์ประกอบสุดท้ายของคอนเทนเนอร์ที่ไม่กลับด้าน หากคอนเทนเนอร์ว่าง iterator ที่คืนค่าจะเท่ากับ [crend()](./crend/). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | คืนค่า reverse iterator ไปยังองค์ประกอบที่ตามหลังองค์ประกอบสุดท้ายของคอนเทนเนอร์ที่กลับด้าน ซึ่งสอดคล้องกับองค์ประกอบก่อนหน้าองค์ประกอบแรกของคอนเทนเนอร์ที่ไม่กลับด้าน องค์ประกอบนี้ทำหน้าที่เป็นตัวแทน; การพยายามเข้าถึงจะทำให้เกิดพฤติกรรมไม่กำหนด. |
| std::vector\<[System::String](../../system/string/)\>\& [data](./data/)() | ตัวเข้าถึงโครงสร้างข้อมูลภายใน. |
| const std::vector\<[System::String](../../system/string/)\>\& [data](./data/)() const | ตัวเข้าถึงโครงสร้างข้อมูลภายใน. |
| [iterator](./iterator/) [end](./end/)() | คืนค่า iterator ไปยังองค์ประกอบที่ตามหลังองค์ประกอบสุดท้ายของคอนเทนเนอร์ องค์ประกอบนี้ทำหน้าที่เป็นตัวแทน; การพยายามเข้าถึงจะทำให้เกิดพฤติกรรมไม่กำหนด. |
| [const_iterator](./const_iterator/) [end](./end/)() const | คืนค่า iterator ไปยังองค์ประกอบที่ตามหลังองค์ประกอบสุดท้ายของคอนเทนเนอร์ที่กำหนดเป็น const องค์ประกอบนี้ทำหน้าที่เป็นตัวแทน; การพยายามเข้าถึงจะทำให้เกิดพฤติกรรมไม่กำหนด. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่า float แบบ C# ที่ถือว่า NaN สองค่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่า double แบบ C# ที่ถือว่า NaN สองค่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้ภายในเท่านั้น. |
| int [get_Count](./get_count/)() const | รับจำนวนองค์ประกอบในคอลเลกชัน. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมกับอ็อบเจ็กต์. |
| [SharedPtr](../../system/sharedptr/)\<[Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[System::String](../../system/string/)\>\> [GetEnumerator](./getenumerator/)() override | รับ enumerator ที่วนผ่านคอลเลกชันปัจจุบัน. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นคล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ช่วยให้ทำแฮชอ็อบเจ็กต์ที่กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ คล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::String](../../system/string/) [idx_get](./idx_get/)(int) const | รับค่าที่ตำแหน่งที่ระบุ. |
| void [idx_set](./idx_set/)(int, const [System::String](../../system/string/)\&) | ตั้งค่าที่ตำแหน่งที่ระบุ. |
| int [IndexOf](./indexof/)(const [System::String](../../system/string/)\&) const | ค้นหาสตริงที่ระบุในคอนเทนเนอร์. |
| void [Insert](./insert/)(int, const [System::String](../../system/string/)\&) | แทรกค่าที่ระบุเข้าไปในคอนเทนเนอร์. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ คล้ายกับออพเรเตอร์ 'is' ของ C#. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | ใช้ฟังก์ชัน accumulator กับลำดับ. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | กำหนดว่าทุกองค์ประกอบของลำดับเป็นไปตามเงื่อนไขหรือไม่. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | กำหนดว่าลำดับมีองค์ประกอบใด ๆ หรือไม่. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | กำหนดว่ามีองค์ประกอบใดในลำดับที่มีอยู่หรือเป็นไปตามเงื่อนไขหรือไม่. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | คำนวณค่าเฉลี่ยของลำดับของค่าตัวเลข. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | คำนวณค่าเฉลี่ยของลำดับของค่าโดยการเรียกฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับอินพุต. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | แปลงประเภทขององค์ประกอบให้เป็นประเภทที่ระบุ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | ต่อสองลำดับเข้าด้วยกัน. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | กำหนดว่าลำดับมีค่าที่ระบุหรือไม่. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | คืนค่าจำนวนองค์ประกอบในลำดับ (คำนวณโดยการนับโดยตรง). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | คืนค่าจำนวนองค์ประกอบในลำดับที่เป็นไปตามเงื่อนไขที่ระบุ. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | คืนค่าองค์ประกอบที่ตำแหน่งกำหนดในลำดับ. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | คืนค่าองค์ประกอบที่ตำแหน่งกำหนดในลำดับ. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | คืนค่าองค์ประกอบแรกของลำดับ. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | คืนค่าองค์ประกอบแรกของลำดับที่เป็นไปตามเงื่อนไขที่ระบุ. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | คืนค่าองค์ประกอบแรกของลำดับ หรือค่าปริยายหากลำดับว่าง. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | คืนค่าองค์ประกอบแรกของลำดับที่เป็นไปตามเงื่อนไข หรือค่าปริยายหากไม่พบ. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | จัดกลุ่มองค์ประกอบของลำดับ. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | จัดกลุ่มองค์ประกอบของลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | คืนค่าองค์ประกอบสุดท้ายของลำดับ. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | คืนค่าองค์ประกอบสุดท้ายของลำดับ หรือค่าปริยายหากลำดับว่าง. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับทั่วไปและคืนค่าผลลัพธ์สูงสุด. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับทั่วไปและคืนค่าต่ำสุดที่ได้. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | กรององค์ประกอบของลำดับตามประเภทที่ระบุ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | เรียงลำดับองค์ประกอบของลำดับในลำดับจากน้อยไปมากตามค่ากุญแจที่เลือกโดย keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | เรียงลำดับองค์ประกอบของลำดับในลำดับจากมากไปน้อยตามค่ากุญแจที่เลือกโดย keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | กลับลำดับขององค์ประกอบในลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | แปลงองค์ประกอบของลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | แปลงแต่ละองค์ประกอบของลำดับเป็นรูปแบบใหม่โดยรวมดัชนีขององค์ประกอบ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | โปรเจกต์แต่ละองค์ประกอบของลำดับและรวมลำดับที่ได้เป็นหนึ่งลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | ข้ามจำนวนองค์ประกอบต่อเนื่องที่ระบุจากจุดเริ่มต้นของลำดับและคืนส่วนที่เหลือ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | คืนจำนวนองค์ประกอบต่อเนื่องที่ระบุจากจุดเริ่มต้นของลำดับ. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | สร้างอาเรย์จากลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | สร้าง List<T> จากลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | กรองลำดับตามพรีดิเกตที่ระบุ. |
| void [Lock](../../system/object/lock/)() | ทำการล็อคตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ช่วยให้คล cloning ชนิดที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสำหรับซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสำหรับซับคลาส. |
| [System::String](../../system/string/)\& [operator[]](./operator[]/)(int) | ฟังก์ชันเข้าถึง. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | คืนค่า reverse iterator ไปยังองค์ประกอบแรกของคอนเทนเนอร์ที่กลับด้าน ซึ่งสอดคล้องกับองค์ประกอบสุดท้ายของคอนเทนเนอร์ที่ไม่กลับด้าน หากคอนเทนเนอร์ว่าง iterator ที่คืนค่าจะเท่ากับ [rend()](./rend/). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | คืนค่า reverse iterator ไปยังองค์ประกอบแรกของคอนเทนเนอร์ที่กลับด้าน ซึ่งสอดคล้องกับองค์ประกอบสุดท้ายของคอนเทนเนอร์ที่ไม่กลับด้าน หากคอนเทนเนอร์ว่าง iterator ที่คืนค่าจะเท่ากับ [rend()](./rend/). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริง. |
| void [Remove](./remove/)(const [System::String](../../system/string/)\&) | ลบการพบแรกของสตริงที่ระบุ. |
| void [RemoveAt](./removeat/)(int) | ลบองค์ประกอบที่ตำแหน่งที่ระบุ. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงร่วมโดยค่าที่ระบุ. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | คืนค่า reverse iterator ไปยังองค์ประกอบที่ตามหลังองค์ประกอบสุดท้ายของคอนเทนเนอร์ที่กลับด้าน ซึ่งสอดคล้องกับองค์ประกอบก่อนหน้าองค์ประกอบแรกของคอนเทนเนอร์ที่ไม่กลับด้าน องค์ประกอบนี้ทำหน้าที่เป็นตัวแทน; การพยายามเข้าถึงจะทำให้เกิดพฤติกรรมไม่กำหนด. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | คืนค่า reverse iterator ไปยังองค์ประกอบที่ตามหลังองค์ประกอบสุดท้ายของคอนเทนเนอร์ที่กลับด้าน ซึ่งสอดคล้องกับองค์ประกอบก่อนหน้าองค์ประกอบแรกของคอนเทนเนอร์ที่ไม่กลับด้าน องค์ประกอบนี้ทำหน้าที่เป็นตัวแทน; การพยายามเข้าถึงจะทำให้เกิดพฤติกรรมไม่กำหนด. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่า template argument ที่ n เป็น weak pointer (แทน shared) อนุญาตให้เปลี่ยน pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงร่วม ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงร่วมและคืนค่า ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
|  [StringCollection](./stringcollection/)() | สร้างคอลเลกชันสตริงเปล่า. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/) ช่วยให้แปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อคตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| System::Details::VirtualizedIteratorBase\<[System::String](../../system/string/)\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | รับการทำงานของ begin const iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| System::Details::VirtualizedIteratorBase\<[System::String](../../system/string/)\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | รับการทำงานของ begin iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| System::Details::VirtualizedIteratorBase\<[System::String](../../system/string/)\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | รับการทำงานของ end const iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| System::Details::VirtualizedIteratorBase\<[System::String](../../system/string/)\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | รับการทำงานของ end iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิง weak ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิง weak ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## การกำหนดประเภท

| Typedef | คำอธิบาย |
| --- | --- |
| [iterator](./iterator/) | ประเภท iterator. |
| [const_iterator](./const_iterator/) | ประเภท const iterator. |
| [reverse_iterator](./reverse_iterator/) | ประเภท reverse iterator. |
| [const_reverse_iterator](./const_reverse_iterator/) | ประเภท const reverse iterator. |

## ดูเพิ่มเติม

* คลาส [IEnumerable](../../system.collections.generic/ienumerable/)
* เนมสเปซ [System::Collections::Specialized](../)
* ไลบรารี [Aspose.Slides](../../)