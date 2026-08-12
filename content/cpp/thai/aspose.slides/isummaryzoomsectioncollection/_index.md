---
title: ISummaryZoomSectionCollection
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: แสดงถึงคอลเลกชันของอ็อบเจกต์ Summary Zoom Section
type: docs
weight: 3940
url: /th/aspose.slides/isummaryzoomsectioncollection/
---
## ISummaryZoomSectionCollection คลาส

แสดงถึงคอลเลกชันของอ็อบเจกต์ Summary Zoom [Section](../section/).

```cpp
class ISummaryZoomSectionCollection : public Aspose::Slides::IGenericCollection<System::SharedPtr<Aspose::Slides::ISummaryZoomSection>>
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISummaryZoomSection](../isummaryzoomsection/)\> [AddSummaryZoomSection](./addsummaryzoomsection/)([System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>) | สร้างอ็อบเจกต์ Summary Zoom [Section](../section/) ใหม่และเพิ่มมันลงในคอลเลกชัน |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | รับ iterator ที่ชี้ไปยังองค์ประกอบแรก (ถ้ามี) ของคอลเลกชัน. iterator นี้ไม่สามารถใช้ในการเปลี่ยนแปลงอ็อบเจกต์ที่อ้างอิงได้เนื่องจาก [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) คืนค่าอ็อบเจกต์สำเนาของ T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | รับ iterator ที่ชี้ไปยังองค์ประกอบแรก (ถ้ามี) ของอินสแตนซ์ที่เป็น const ของคอลเลกชัน. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | รับ iterator ที่ชี้ไปยังองค์ประกอบที่เป็น const แรก (ถ้ามี) ของคอลเลกชัน. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | รับ iterator ที่ชี้ไปหลังจากองค์ประกอบที่เป็น const สุดท้าย (ถ้ามี) ของคอลเลกชัน. |
| virtual void [Clear](./clear/)() | ลบอ็อบเจกต์ [SummaryZoomSection](../summaryzoomsection/) ทั้งหมดออกจากคอลเลกชัน. |
| virtual void [CopyTo](../igenericcollection/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, **int32_t**) | คัดลอกองค์ประกอบทั้งหมดจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | รับ iterator ที่ชี้ไปหลังจากองค์ประกอบสุดท้าย (ถ้ามี) ของคอลเลกชัน. iterator นี้ไม่สามารถใช้เพื่อเปลี่ยนแปลงอ็อบเจกต์ที่อ้างอิงได้เนื่องจาก [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) คืนค่าอ็อบเจกต์สำเนาของ T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | รับ iterator ที่ชี้ไปหลังจากองค์ประกอบสุดท้าย (ถ้ามี) ของอินสแตนซ์ที่เป็น const ของคอลเลกชัน. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าจุดลอยตัวสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ว่า ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าที่ใดๆ รวมถึง NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าจุดลอยตัวสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ว่า ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าที่ใดๆ รวมถึง NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| virtual **int32_t** [get_Count](../igenericcollection/get_count/)() | คืนค่าจำนวนพฤติกรรมในคอลเลกชัน. อ่านอย่างเดียว **int32_t**. |
| virtual **bool** [get_IsSynchronized](../igenericcollection/get_issynchronized/)() | คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด). อ่านอย่างเดียว **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_SyncRoot](../igenericcollection/get_syncroot/)() | คืนค่ารากของการซิงโครไนซ์. อ่านอย่างเดียว [System::Object](../../system/object/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../../system.collections.generic/ienumerator/)\<T\>\> [GetEnumerator](../../system.collections.generic/ienumerable/getenumerator/)() | รับ enumerator. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจกต์ที่กำหนดเอง. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISummaryZoomSection](../isummaryzoomsection/)\> [GetSummarySection](./getsummarysection/)([System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>) | คืนค่าอิลิเมนต์ Summary Zoom [Section](../section/) สำหรับส่วนที่กำหนด. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISummaryZoomSection](../isummaryzoomsection/)\> [idx_get](./idx_get/)(**int32_t**) | รับอิลิเมนต์ที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [ISummaryZoomSection](../isummaryzoomsection/). |
| virtual **int32_t** [IndexOf](./indexof/)([System::SharedPtr](../../system/sharedptr/)\<[ISummaryZoomSection](../isummaryzoomsection/)\>) | คืนดัชนีของอ็อบเจกต์ [SummaryZoomSection](../summaryzoomsection/) ที่ระบุ. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. คล้ายกับตัวดำเนินการ 'is' ของ C#. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | นำฟังก์ชันสะสมไปใช้กับลำดับ. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | กำหนดว่าทุกอิลิเมนต์ของลำดับเป็นไปตามเงื่อนไขหรือไม่. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | กำหนดว่าลำดับมีอิลิเมนต์ใดบ้างหรือไม่. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | กำหนดว่ามีอิลิเมนต์ใดในลำดับที่มีอยู่หรือเป็นไปตามเงื่อนไขหรือไม่. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | คำนวณค่าเฉลี่ยของลำดับของค่าตัวเลข. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | คำนวณค่าเฉลี่ยของลำดับของค่าโดยการเรียกฟังก์ชันแปลงบนแต่ละอิลิเมนต์ของลำดับอินพุต. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | แคสต์อิลิเมนต์เป็นประเภทที่ระบุ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | ต่อเนื่องสองลำดับ. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | กำหนดว่าลำดับมีค่าที่ระบุหรือไม่. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | คืนค่าจำนวนอิลิเมนต์ในลำดับ (คำนวณโดยการนับโดยตรง). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | คืนค่าจำนวนอิลิเมนต์ในลำดับที่ตรงตามเงื่อนไขที่ระบุ. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | คืนอิลิเมนต์ที่ตำแหน่งที่ระบุในลำดับ. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | คืนอิลิเมนต์ที่ตำแหน่งที่ระบุในลำดับ. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | คืนอิลิเมนต์แรกของลำดับ. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | คืนอิลิเมนต์แรกของลำดับที่ตรงตามเงื่อนไขที่ระบุ. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | คืนอิลิเมนต์แรกของลำดับ หรือค่าดีฟอลต์หากลำดับว่างเปล่า. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | คืนอิลิเมนต์แรกของลำดับที่ตรงตามเงื่อนไขหรือค่าดีฟอลต์หากไม่พบอิลิเมนต์. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | จัดกลุ่มอิลิเมนต์ของลำดับ. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | จัดกลุ่มอิลิเมนต์ของลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | คืนอิลิเมนต์สุดท้ายของลำดับ. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | คืนอิลิเมนต์สุดท้ายของลำดับ หรือค่าดีฟอลต์หากลำดับว่างเปล่า. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกฟังก์ชันแปลงบนแต่ละอิลิเมนต์ของลำดับทั่วไปและคืนค่าที่ได้สูงสุด. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกฟังก์ชันแปลงบนแต่ละอิลิเมนต์ของลำดับทั่วไปและคืนค่าที่ได้ต่ำสุด. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | กรองอิลิเมนต์ของลำดับตามประเภทที่ระบุ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | จัดเรียงอิลิเมนต์ของลำดับในลำดับจากน้อยไปมากตามค่าคีย์ที่เลือกโดย keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | จัดเรียงอิลิเมนต์ของลำดับในลำดับจากมากไปน้อยตามค่าคีย์ที่เลือกโดย keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | กลับลำดับของอิลิเมนต์ในลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | แปลงอิลิเมนต์ของลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | แปลงแต่ละอิลิเมนต์ของลำดับเป็นรูปร่างใหม่โดยใช้ดัชนีของอิลิเมนต์. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | โปรเจคอิลิเมนต์แต่ละตัวของลำดับและรวมลำดับผลลัพธ์เป็นลำดับเดียว. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | ข้ามจำนวนอิลิเมนต์ต่อเนื่องที่ระบุจากจุดเริ่มต้นของลำดับและคืนส่วนที่เหลือ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | คืนจำนวนอิลิเมนต์ต่อเนื่องที่ระบุจากจุดเริ่มต้นของลำดับ. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | สร้างอาร์เรย์จากลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | สร้าง List<T> จากลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | กรองลำดับตามพรีดิเซตที่ระบุ. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อค. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | โอเปอร์เรเตอร์การกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | เป็นการจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | เป็นการจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| virtual void [RemoveSummaryZoomSection](./removesummaryzoomsection/)([System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>) | ลบอ็อบเจกต์ Summary Zoom [Section](../section/) ออกจากคอลเลกชัน. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งเทมเพลตอากิวเมนต์ที่ n ให้เป็น weak pointer (แทนที่เป็น shared). อนุญาตให้เปลี่ยนพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แชร์ขึ้น. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงที่แชร์ลงและคืนค่า. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อค. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | รับการดำเนินการของ begin const iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | รับการดำเนินการของ begin iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | รับการดำเนินการของ end const iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | รับการดำเนินการของ end iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยทรัพยากรโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [IGenericCollection](../igenericcollection/)
* เนมสเปส [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)