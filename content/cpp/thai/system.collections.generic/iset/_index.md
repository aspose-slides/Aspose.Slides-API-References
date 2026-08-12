---
title: ISet
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "อินเทอร์เฟซของคอลเลกชันที่มีชุดขององค์ประกอบที่ไม่ซ้ำกัน. อ็อบเจกต์ของคลาสนี้ควรจัดสรรเท่านั้นโดยใช้ฟังก์ชัน System::MakeObject(). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแต็กหรือโดยใช้ตัวดำเนินการ new, เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือการขัดจังหวะ assertion. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งผ่านให้กับฟังก์ชันเป็นอาร์กิวเมนต์."
type: docs
weight: 352
url: /th/system.collections.generic/iset/
---
## ISet คลาส

อินเทอร์เฟซของคอลเลกชันที่มีชุดขององค์ประกอบที่ไม่ซ้ำกัน. ออบเจกต์ของคลาสนี้ควรจะถูกจัดสรรเท่านั้นโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแต็กหรือโดยใช้ตัวดำเนินการ new, เนื่องจากจะทำให้เกิดข้อผิดพลาดเวลาเรียกใช้งานและ/หรือการขัดจังหวะ assertion. ควรห่อหุ้มคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งผ่านให้กับฟังก์ชันเป็นอาร์กิวเมนต์.

```cpp
template<typename T>class ISet : public System::Collections::Generic::ICollection<T>
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบ. |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual void [Add](../icollection/add/)(const T\&) | เพิ่มองค์ประกอบเข้าไปในคอลเลกชัน. |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | รับอิเทอเรเตอร์ที่ชี้ไปยังองค์ประกอบแรก (ถ้ามี) ของคอลเลกชัน. อิเทอเรเตอร์นี้ไม่สามารถใช้เพื่อเปลี่ยนแปลงอ็อบเจกต์ที่อ้างอิงได้เนื่องจาก [GetEnumerator()](../ienumerable/getenumerator/) ส่งคืนอ็อบเจกต์สำเนาของ T. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | รับอิเทอเรเตอร์ที่ชี้ไปยังองค์ประกอบแรก (ถ้ามี) ของอินสแตนซ์คอลเลกชันที่กำหนดเป็น const. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | รับอิเทอเรเตอร์ที่ชี้ไปยังองค์ประกอบแรกที่กำหนดเป็น const (ถ้ามี) ของคอลเลกชัน. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | รับอิเทอเรเตอร์ที่ชี้หลังจากองค์ประกอบ const ตัวสุดท้าย (ถ้ามี) ของคอลเลกชัน. |
| virtual void [Clear](../icollection/clear/)() | ลบทุกองค์ประกอบจากคอลเลกชัน. |
| virtual **bool** [Contains](../icollection/contains/)(const T\&) const | ตรวจสอบว่าองค์ประกอบมีอยู่ในคอลเลกชันหรือไม่. |
| virtual void [CopyTo](../icollection/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) | คัดลอกทุกองค์ประกอบของคอลเลกชันไปยังอาเรย์ที่มีอยู่. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | รับอิเทอเรเตอร์ที่ชี้หลังจากองค์ประกอบสุดท้าย (ถ้ามี) ของคอลเลกชัน. อิเทอเรเตอร์นี้ไม่สามารถใช้เพื่อเปลี่ยนอ็อบเจกต์ที่อ้างอิงได้เนื่องจาก [GetEnumerator()](../ienumerable/getenumerator/) ส่งคืนอ็อบเจกต์สำเนาของ T. |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | รับอิเทอเรเตอร์ที่ชี้หลังจากองค์ประกอบสุดท้าย (ถ้ามี) ของอินสแตนซ์คอลเลกชันที่กำหนดเป็น const. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในรูปแบบ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในรูปแบบ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ซึ่ง NaN สองค่าถือว่าเท่ากันถึงแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าที่ใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# สำหรับ double โดย NaN สองค่าถือว่าเท่ากัน. |
| virtual void [ExceptWith](./exceptwith/)([IEnumerablePtr](./ienumerableptr/)) | ลบกลุ่มขององค์ประกอบ. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับการทำงานภายในเท่านั้น. |
| virtual int [get_Count](../icollection/get_count/)() const | รับจำนวนองค์ประกอบในคอลเลกชัน. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | ตรวจสอบว่าคอลเลกชันเป็นแบบอ่านอย่างเดียวหรือไม่. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | รับอ็อบเจกต์ที่คอลเลกชันซิงโครไนซ์ผ่าน. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<T\>\> [GetEnumerator](../ienumerable/getenumerator/)() | รับ enumerator. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการทำแฮชของอ็อบเจกต์แบบกำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับชนิดจริงของอ็อบเจกต์. คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| [ICollection](../icollection/icollection/)() | คอนสตรัคเตอร์เริ่มต้น. |
| [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | คอนสตรัคเตอร์คัดลอก. |
| [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | คอนสตรัคเตอร์ย้าย. |
| virtual void [IntersectWith](./intersectwith/)([IEnumerablePtr](./ienumerableptr/)) | ลบองค์ประกอบที่ไม่มีอยู่ในคอนเทนเนอร์อื่น. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. คล้ายกับตัวดำเนินการ 'is' ของ C#. |
| virtual **bool** [IsProperSubsetOf](./ispropersubsetof/)([IEnumerablePtr](./ienumerableptr/)) | ตรวจสอบว่าชุดปัจจุบันเป็น subset อย่างเคร่งครัดของคอนเทนเนอร์อื่นหรือไม่. |
| virtual **bool** [IsProperSupersetOf](./ispropersupersetof/)([IEnumerablePtr](./ienumerableptr/)) | ตรวจสอบว่าชุดปัจจุบันเป็น superset อย่างเคร่งครัดของคอนเทนเนอร์อื่นหรือไม่. |
| virtual **bool** [IsSubsetOf](./issubsetof/)([IEnumerablePtr](./ienumerableptr/)) | ตรวจสอบว่าชุดปัจจุบันเป็น subset ของคอนเทนเนอร์อื่นหรือไม่. |
| virtual **bool** [IsSupersetOf](./issupersetof/)([IEnumerablePtr](./ienumerableptr/)) | ตรวจสอบว่าชุดปัจจุบันเป็น superset ของคอนเทนเนอร์อื่นหรือไม่. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | ใช้ฟังก์ชัน accumulator กับลำดับ. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | กำหนดว่าทุกองค์ประกอบของลำดับเป็นไปตามเงื่อนไขหรือไม่. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | กำหนดว่าลำดับมีองค์ประกอบใด ๆ หรือไม่. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | กำหนดว่ามีองค์ประกอบใดในลำดับหรือเป็นไปตามเงื่อนไขหรือไม่. |
| T [LINQ_Average](../ienumerable/linq_average/)() | คำนวณค่าเฉลี่ยของลำดับของค่าตัวเลข. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | คำนวณค่าเฉลี่ยของลำดับของค่าที่ได้จากการเรียกฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับอินพุต. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | แคสต์องค์ประกอบเป็นประเภทที่ระบุ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | เชื่อมต่อสองลำดับต่อกัน. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | กำหนดว่าลำดับมีค่าที่ระบุหรือไม่. |
| int [LINQ_Count](../ienumerable/linq_count/)() | คืนจำนวนองค์ประกอบในลำดับ (คำนวณโดยการนับโดยตรง). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | คืนจำนวนองค์ประกอบในลำดับที่เป็นไปตามเงื่อนไขที่ระบุ. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | คืนองค์ประกอบที่ตำแหน่งที่กำหนดในลำดับ. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | คืนองค์ประกอบที่ตำแหน่งที่กำหนดในลำดับ. |
| T [LINQ_First](../ienumerable/linq_first/)() | คืนองค์ประกอบแรกของลำดับ. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | คืนองค์ประกอบแรกของลำดับที่เป็นไปตามเงื่อนไขที่ระบุ. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | คืนองค์ประกอบแรกของลำดับ หรือค่าดีฟอลต์หากลำดับว่าง. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | คืนองค์ประกอบแรกของลำดับที่ตรงกับเงื่อนไข หรือค่าดีฟอลต์ถ้าไม่พบ. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | จัดกลุ่มองค์ประกอบของลำดับ. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | จัดกลุ่มองค์ประกอบของลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | คืนองค์ประกอบสุดท้ายของลำดับ. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | คืนองค์ประกอบสุดท้ายของลำดับ หรือค่าดีฟอลต์หากลำดับว่าง. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับทั่วไปและคืนค่าสูงสุดที่ได้. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับทั่วไปและคืนค่าต่ำสุดที่ได้. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | กรององค์ประกอบของลำดับตามประเภทที่ระบุ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | เรียงลำดับองค์ประกอบของลำดับในลำดับเพิ่มตามค่ากุญแจที่เลือกโดย keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | เรียงลำดับองค์ประกอบของลำดับในลำดับลดลงตามค่ากุญแจที่เลือกโดย keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | กลับลำดับขององค์ประกอบในลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | แปลงองค์ประกอบของลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | แปลงแต่ละองค์ประกอบของลำดับเป็นรูปแบบใหม่โดยรวมดัชนีขององค์ประกอบ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | โปรเจกต์แต่ละองค์ประกอบของลำดับและรวมลำดับที่ได้เป็นลำดับเดียว. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | ข้ามจำนวนองค์ประกอบต่อเนื่องที่ระบุจากจุดเริ่มต้นของลำดับและคืนส่วนที่เหลือ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | คืนจำนวนองค์ประกอบต่อเนื่องที่ระบุจากจุดเริ่มต้นของลำดับ. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | สร้างอาเรย์จากลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | สร้าง List<T> จากลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | กรองลำดับตามเงื่อนไขที่ระบุ. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
| [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริงๆ ไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสับคลาสย่อย. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | ตัวดำเนินการกำหนดค่าแบบย้าย. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | ตัวดำเนินการกำหนดค่าแบบย้าย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริงๆ ไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสับคลาสย่อย. |
| virtual **bool** [Overlaps](./overlaps/)([IEnumerablePtr](./ienumerableptr/)) | ตรวจสอบว่าชุดทับซ้อนกับคอนเทนเนอร์อื่นหรือไม่. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจกต์ประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| virtual **bool** [Remove](../icollection/remove/)(const T\&) | ลบองค์ประกอบจากคอลเลกชัน. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| virtual **bool** [SetEquals](./setequals/)([IEnumerablePtr](./ienumerableptr/)) | ตรวจสอบว่าชุดและคอนเทนเนอร์มีองค์ประกอบเดียวกันหรือไม่. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทน shared) เพื่อให้สามารถสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak ได้. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
| virtual void [SymmetricExceptWith](./symmetricexceptwith/)([IEnumerablePtr](./ienumerableptr/)) | คำนวณ symmetric exception ของสองคอนเทนเนอร์. ลบทุกองค์ประกอบที่อยู่ในทั้งสองคอนเทนเนอร์ ในขณะเดียวกันเพิ่มทุกองค์ประกอบที่อยู่ใน **other** แต่ไม่มีในชุดปัจจุบัน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจกต์แบบกำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็น construct ของ C# typeof([System.Object](../../system/object/)). |
| virtual void [UnionWith](./unionwith/)([IEnumerablePtr](./ienumerableptr/)) | เพิ่มองค์ประกอบจากคอลเลกชันที่ระบุที่ยังไม่มีในชุดปัจจุบัน. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../ienumerable/virtualizebeginconstiterator/)() const | รับการทำงานของ begin const iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../ienumerable/virtualizebeginiterator/)() | รับการทำงานของ begin iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../ienumerable/virtualizeendconstiterator/)() const | รับการทำงานของ end const iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../ienumerable/virtualizeenditerator/)() | รับการทำงานของ end iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | ตัวทำลาย. |
| virtual  [~ISet](./~iset/)() | ตัวทำลาย. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ประเภทนิยาม

| ประเภทนิยาม | คำอธิบาย |
| --- | --- |
| [IEnumerablePtr](./ienumerableptr/) | ประเภท Enumerable เพื่อเปรียบเทียบเนื้อหากับชุดปัจจุบัน. |

## ดูเพิ่มเติม

* คลาส [ICollection](../icollection/)
* เนมสเปซ [System::Collections::Generic](../)
* ไลบรารี [Aspose.Slides](../../)