---
title: VideoCollection
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เป็นคอลเลกชันของวัตถุ Video.
type: docs
weight: 5539
url: /th/aspose.slides/videocollection/
---
## คลาส VideoCollection

แสดงถึงคอลเลกชันของ [Video](../video/) วัตถุ.

```cpp
class VideoCollection : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Presentation>>,
                        public Aspose::Slides::IVideoCollection
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\> [AddVideo](./addvideo/)([System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\>) override | เพิ่มสำเนาของไฟล์วิดีโอจากงานนำเสนออื่น |
| [System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\> [AddVideo](./addvideo/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [LoadingStreamBehavior](../loadingstreambehavior/)) override | สร้างและเพิ่มวิดีโอไปยังงานนำเสนอจากสตรีม |
| [System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\> [AddVideo](./addvideo/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | สร้างและเพิ่มวิดีโอไปยังงานนำเสนอจากอาเรย์ไบต์ |
| [iterator](./iterator/) [begin](./begin/)() | รับ iterator ที่ชี้ไปยังสมาชิกตัวแรก (ถ้ามี) ของคอลเลกชัน |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | รับ iterator ที่ชี้ไปยังสมาชิกตัวแรก (ถ้ามี) ของอินสแตนซ์ที่กำหนดเป็น const ของคอลเลกชัน |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | รับ iterator ที่ชี้ไปยังสมาชิกที่กำหนดเป็น const ตัวแรก (ถ้ามี) ของคอลเลกชัน |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | รับ iterator ที่ชี้ไปหลังสมาชิกที่กำหนดเป็น const ตัวสุดท้าย (ถ้ามี) ของคอลเลกชัน |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\>\>, **int32_t**) override | คัดลอกวิดีโอไปยังอาเรย์ที่ระบุโดยเริ่มจากดัชนีที่ระบุ |
| virtual void [CopyTo](../igenericcollection/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, **int32_t**) | คัดลอกสมาชิกทั้งหมดจากคอลเลกชันไปยังอาเรย์ที่ระบุ |
| [iterator](./iterator/) [end](./end/)() | รับ iterator ที่ชี้ไปหลังสมาชิกสุดท้าย (ถ้ามี) ของคอลเลกชัน |
| [const_iterator](./const_iterator/) [end](./end/)() const | รับ iterator ที่ชี้ไปหลังสมาชิกสุดท้าย (ถ้ามี) ของอินสแตนซ์ที่กำหนดเป็น const ของคอลเลกชัน |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุของประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุของประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยแบบ C#-style ซึ่ง NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าทั้งหมดรวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยแบบ C#-style ซึ่ง NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าทั้งหมดรวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อวัตถุประสงค์ภายในเท่านั้น |
| **int32_t** [get_Count](./get_count/)() override | ส่งคืนจำนวนไฟล์วิดีโอในคอลเลกชัน อ่านอย่างเดียว **int32_t** |
| **bool** [get_IsSynchronized](./get_issynchronized/)() override | ส่งคืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันได้รับการซิงโครไนซ์ (ปลอดภัยต่อเธรด) อ่านอย่างเดียว **bool** |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_SyncRoot](./get_syncroot/)() override | ส่งคืนรากการซิงโครไนซ์ อ่านอย่างเดียว [System::Object](../../system/object/) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\>\>\> [GetEnumerator](./getenumerator/)() override | ส่งคืน enumerator ที่วนซ้ำผ่านคอลเลกชัน |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เทียบเท่ากับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชวัตถุแบบกำหนดเองได้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | เทียบเท่ากับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\> [idx_get](./idx_get/)(**int32_t**) override | รับสมาชิกที่ตำแหน่งดัชนีที่ระบุ อ่านอย่างเดียว [IVideo](../ivideo/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เทียบเท่ากับตัวดำเนินการ 'is' ของ C# |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | ใช้ฟังก์ชัน accumulator กับลำดับ |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | กำหนดว่าสมาชิกทั้งหมดของลำดับเป็นไปตามเงื่อนไขหรือไม่ |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | กำหนดว่าลำดับมีสมาชิกใดๆ หรือไม่ |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | กำหนดว่ามีสมาชิกใดในลำดับที่มีอยู่หรือเป็นไปตามเงื่อนไขหรือไม่ |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | คำนวณค่าเฉลี่ยของลำดับของค่าตัวเลข |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | คำนวณค่าเฉลี่ยของลำดับของค่าที่ได้จากการเรียกฟังก์ชันแปลงบนแต่ละสมาชิกของลำดับอินพุต |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | แคสต์สมาชิกไปยังประเภทที่ระบุ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | ต่อสองลำดับ |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | กำหนดว่าลำดับมีค่าที่ระบุหรือไม่ |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | ส่งคืนจำนวนสมาชิกในลำดับ (คำนวณโดยการนับโดยตรง) |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | ส่งคืนจำนวนสมาชิกในลำดับที่เป็นไปตามเงื่อนไขที่ระบุ |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | รับสมาชิกที่ตำแหน่งดัชนีที่ระบุในลำดับ |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | รับสมาชิกที่ตำแหน่งดัชนีที่ระบุในลำดับ |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | ส่งคืนสมาชิกแรกของลำดับ |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | ส่งคืนสมาชิกแรกของลำดับที่เป็นไปตามเงื่อนไขที่ระบุ |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | ส่งคืนสมาชิกแรกของลำดับ หรือค่าดีฟอลต์หากลำดับว่าง |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | ส่งคืนสมาชิกแรกของลำดับที่เป็นไปตามเงื่อนไข หรือค่าดีฟอลต์หากไม่พบสมาชิกดังกล่าว |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | จัดกลุ่มสมาชิกของลำดับ |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | จัดกลุ่มสมาชิกของลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | ส่งคืนสมาชิกสุดท้ายของลำดับ |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | ส่งคืนสมาชิกสุดท้ายของลำดับ หรือค่าดีฟอลต์หากลำดับว่าง |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกฟังก์ชันแปลงบนแต่ละสมาชิกของลำดับทั่วไปและส่งคืนค่าที่ได้สูงสุด |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกฟังก์ชันแปลงบนแต่ละสมาชิกของลำดับทั่วไปและส่งคืนค่าที่ได้ต่ำสุด |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | กรองสมาชิกของลำดับตามประเภทที่ระบุ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | เรียงลำดับสมาชิกของลำดับในลำดับจากน้อยไปมากตามค่ากุญแจที่เลือกโดย keySelector |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | เรียงลำดับสมาชิกของลำดับในลำดับจากมากไปน้อยตามค่ากุญแจที่เลือกโดย keySelector |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | กลับลำดับของสมาชิกในลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | แปลงสมาชิกของลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | แปลงแต่ละสมาชิกของลำดับเป็นรูปแบบใหม่โดยรวมดัชนีของสมาชิก |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | โปรเจกต์แต่ละสมาชิกของลำดับและรวมลำดับผลลัพธ์เป็นลำดับเดียว |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | ข้ามจำนวนสมาชิกต่อเนื่องที่ระบุจากจุดเริ่มต้นของลำดับและส่งคืนส่วนที่เหลือ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | ส่งคืนจำนวนสมาชิกต่อเนื่องที่ระบุจากจุดเริ่มต้นของลำดับ |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | สร้างอาเรย์จากลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | สร้าง List<T> จากลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | กรองลำดับตามเงื่อนไขที่ระบุ |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เทียบเท่ากับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถสร้างสำเนาประเภทที่กำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริงๆ เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรจริงๆ เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เทียบอ้างอิงวัตถุประเภทค่า กับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงร่วมโดยค่าที่ระบุ |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | ตั้งค่า template argument ที่ n ให้เป็น weak pointer (แทน shared) อนุญาตสลับ pointer ใน container ไปเป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนอ้างอิงร่วม ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนอ้างอิงร่วมและส่งคืน ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบเท่ากับเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงวัตถุกำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่ typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | รับ iterator ที่ชี้ไปยังสมาชิกตัวแรก (ถ้ามี) ของอินสแตนซ์ที่กำหนดเป็น const ของคอลเลกชัน |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | รับ iterator ที่ชี้ไปยังสมาชิกตัวแรก (ถ้ามี) ของคอลเลกชัน |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | รับ iterator ที่ชี้ไปหลังสมาชิกสุดท้าย (ถ้ามี) ของอินสแตนซ์ที่กำหนดเป็น const ของคอลเลกชัน |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeEndIterator](./virtualizeenditerator/)() override | รับ iterator ที่ชี้ไปหลังสมาชิกสุดท้าย (ถ้ามี) ของคอลเลกชัน |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวน weak reference count ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวน weak reference count ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์ ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ประเภทนิยาม

| ชนิดนิยาม | คำอธิบาย |
| --- | --- |
| [iterator_holder_type](./iterator_holder_type/) | ประเภทคอลเลกชันที่ประเภท iterator ของมันถูกใช้เป็นประเภท iterator ในคอลเลกชันปัจจุบัน |
| [iterator](./iterator/) | ประเภท iterator |
| [const_iterator](./const_iterator/) | ประเภท iterator ที่เป็น const |
| [virtualized_iterator_element](./virtualized_iterator_element/) | ประเภทสมาชิกที่ถูก virtualized |
| [virtualized_iterator](./virtualized_iterator/) | ประเภทที่ virtualized |

## ดูเพิ่มเติม

* คลาส [DomObject](../domobject/)
* คลาส [IVideoCollection](../ivideocollection/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)