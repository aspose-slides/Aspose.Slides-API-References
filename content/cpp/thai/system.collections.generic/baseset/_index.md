---
title: BaseSet
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: 
type: docs
weight: 92
url: /th/system.collections.generic/baseset/
---
## BaseSet คลาส




```cpp
template<typename T,typename SET_T>class BaseSet : public virtual System::Object,
                                                   public System::Collections::Generic::ICollection<T>
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| void [_add_range](./_add_range/)(std::initializer_list\<T\>) | เฉพาะ C++. |
| void [Add](./add/)(const T\&) override | เพิ่มองค์ประกอบเข้าไปในชุด. |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | รับ iterator ไปยังองค์ประกอบแรกของคอลเลกชันที่กำหนดเป็น const. |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | รับ iterator ชี้ไปยังองค์ประกอบแรก (ถ้ามี) ของคอลเลกชัน. Iterator นี้ไม่สามารถใช้เพื่อเปลี่ยนวัตถุที่อ้างอิงได้ เพราะ [GetEnumerator()](../ienumerable/getenumerator/) คืนค่าสำเนาของ T. |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | รับ iterator ไปยังองค์ประกอบแรกที่กำหนดเป็น const ของคอลเลกชัน. |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | รับ iterator สำหรับองค์ประกอบที่กำหนดเป็น const ที่ไม่มีอยู่หลังส่วนสุดของคอลเลกชัน. |
| void [Clear](./clear/)() override | ลบทุกองค์ประกอบในชุด. |
| **bool** [Contains](./contains/)(const T\&) const override | ตรวจสอบว่าองค์ประกอบมีอยู่ในชุดหรือไม่. |
| void [CopyTo](./copyto/)([ArrayPtr](../../system/arrayptr/)\<T\>, int) override | คัดลอกเนื้อหา hash ไปยังองค์ประกอบอาร์เรย์ที่มีอยู่. |
| [set_t](./set_t/)\& [data](./data/)() | ตัวเข้าถึงโครงสร้างข้อมูลพื้นฐาน. |
| const [set_t](./set_t/)\& [data](./data/)() const | ตัวเข้าถึงโครงสร้างข้อมูลพื้นฐาน. |
| [const_iterator](./const_iterator/) [end](./end/)() const | รับ iterator สำหรับองค์ประกอบที่ไม่มีอยู่หลังส่วนสุดของคอลเลกชันที่กำหนดเป็น const. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | รับ iterator ชี้หลังจากองค์ประกอบสุดท้าย (ถ้ามี) ของคอลเลกชัน. Iterator นี้ไม่สามารถใช้เพื่อเปลี่ยนวัตถุที่อ้างอิงได้ เพราะ [GetEnumerator()](../ienumerable/getenumerator/) คืนค่าสำเนาของ T. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบตัวเลขแบบ float ตามสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบตัวเลขแบบ double ตามสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| int [get_Count](./get_count/)() const override | รับจำนวนองค์ประกอบในชุด. |
| virtual int [get_Count](./get_count/)() const | ป้องกันไม่ให้ [get_Count()](./get_count/) ถูกซ่อน. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | ตรวจสอบว่าคอลเลกชันเป็นแบบอ่านอย่างเดียวหรือไม่. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | รับอ็อบเจ็กต์ที่คอลเลกชันทำการประสานผ่าน. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมกับอ็อบเจ็กต์. |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | สร้าง enumerator. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นความคล้ายคลึงของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการทำ hash ของอ็อบเจ็กต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. คล้ายเมธอด C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICollection](../icollection/icollection/)() | คอนสตรัคเตอร์ค่าเริ่มต้น. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | คอนสตรัคเตอร์คัดลอก. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | คอนสตรัคเตอร์ย้าย. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. คล้ายกับโอเปอเรเตอร์ 'is' ของ C#. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | ใช้ฟังก์ชัน accumulator กับลำดับ. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | กำหนดว่าทุกองค์ประกอบของลำดับตรงตามเงื่อนไขหรือไม่. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | กำหนดว่าลำดับมีองค์ประกอบใดหรือไม่. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | กำหนดว่ามีองค์ประกอบใดในลำดับที่มีอยู่หรือทำตามเงื่อนไขหรือไม่. |
| T [LINQ_Average](../ienumerable/linq_average/)() | คำนวณค่าเฉลี่ยของลำดับค่าตัวเลข. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | คำนวณค่าเฉลี่ยของลำดับค่าที่ได้จากการเรียกฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับอินพุต. |
| ResultType [LINQ_Average](../ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | แปลงชนิดขององค์ประกอบไปเป็นประเภทที่ระบุ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | ต่อเนื่องสองลำดับ. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | กำหนดว่าลำดับมีค่าที่ระบุหรือไม่. |
| int [LINQ_Count](../ienumerable/linq_count/)() | คืนจำนวนองค์ประกอบในลำดับ (คำนวณโดยการนับโดยตรง). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | คืนจำนวนองค์ประกอบในลำดับที่ตรงกับเงื่อนไขที่ระบุ. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | คืนองค์ประกอบที่ตำแหน่งที่ระบุในลำดับ. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | คืนองค์ประกอบที่ตำแหน่งที่ระบุในลำดับ. |
| T [LINQ_First](../ienumerable/linq_first/)() | คืนองค์ประกอบแรกของลำดับ. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | คืนองค์ประกอบแรกของลำดับที่ตรงกับเงื่อนไขที่ระบุ. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | คืนองค์ประกอบแรกของลำดับ, หรือค่าดีฟอลต์หากลำดับว่าง. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | คืนองค์ประกอบแรกของลำดับที่ตรงตามเงื่อนไข หรือค่าดีฟอลต์หากไม่พบ. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | จัดกลุ่มองค์ประกอบของลำดับ. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | จัดกลุ่มองค์ประกอบของลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | คืนองค์ประกอบสุดท้ายของลำดับ. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | คืนองค์ประกอบสุดท้ายของลำดับ, หรือค่าดีฟอลต์หากลำดับว่าง. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับทั่วไปและคืนค่ามากที่สุดที่ได้. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับทั่วไปและคืนค่าต่ำที่สุดที่ได้. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | กรององค์ประกอบของลำดับตามประเภทที่ระบุ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | จัดเรียงองค์ประกอบของลำดับในลำดับเพิ่มตามค่าคีย์ที่เลือกโดย keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | จัดเรียงองค์ประกอบของลำดับในลำดับลดตามค่าคีย์ที่เลือกโดย keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | สลับลำดับขององค์ประกอบในลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | แปลงองค์ประกอบของลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | แปลงแต่ละองค์ประกอบของลำดับเป็นรูปแบบใหม่โดยใช้ดัชนีขององค์ประกอบ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | ฉายแต่ละองค์ประกอบของลำดับและรวมลำดับที่ได้เป็นหนึ่งลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Skip](../ienumerable/linq_skip/)(**int32_t**) | ข้ามจำนวนที่ระบุขององค์ประกอบต่อเนื่องจากจุดเริ่มต้นของลำดับและคืนส่วนที่เหลือ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | คืนจำนวนที่ระบุขององค์ประกอบต่อเนื่องจากจุดเริ่มต้นของลำดับ. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | สร้างอาร์เรย์จากลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | สร้าง List<T> จากลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | กรองลำดับตามเงื่อนไขที่ระบุ. |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อคตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นความคล้ายคลึงของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้การคัดลอกสำหรับคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้การคัดลอกสำหรับคลาสย่อย. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | ตัวดำเนินการกำหนดค่าการย้าย. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | ตัวดำเนินการกำหนดค่าการย้าย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่ากับ nullptr โดยอ้างอิง. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริง. |
| **bool** [Remove](./remove/)(const T\&) override | ลบองค์ประกอบออกจากชุด. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงแบบแชร์ลงตามค่าที่ระบุ. |
|  [RTTI_INFO_TEMPLATE_CLASS](./rtti_info_template_class/)([ThisType](./thistype/), System::BaseTypesInfo\<[System::Object](../../system/object/)\>) | ข้อมูล RTTI. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n'th ให้เป็น weak pointer (แทน shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงแบบแชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนอ้างอิงแบบแชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงแบบแชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง. |
| **bool** [TryAdd](./tryadd/)(const T\&) | เพิ่มองค์ประกอบเข้าไปในชุด. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อคตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | รับการทำงานของ begin const iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | รับการทำงานของ begin iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | รับการทำงานของ end const iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | รับการทำงานของ end iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual  [~ICollection](../icollection/~icollection/)() | ตัวทำลาย. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## การกำหนดชนิด

| Typedef | คำอธิบาย |
| --- | --- |
| [ThisType](./thistype/) | ประเภทของตัวเอง. |
| [ThisPtr](./thisptr/) | ประเภทพอยน์เตอร์. |
| [set_t](./set_t/) | ประเภทข้อมูลพื้นฐาน. |
| [iterator](./iterator/) | ประเภท iterator. |
| [const_iterator](./const_iterator/) | ประเภท const iterator. |
| [ValueType](./valuetype/) | ประเภทค่า. |
| [BaseType](./basetype/) | อินเทอร์เฟซที่ทำงาน. |
| [IEnumerablePtr](./ienumerableptr/) | พอยน์เตอร์อินเทอร์เฟซ Enumerable. |
| [IEnumeratorPtr](./ienumeratorptr/) | **Enumerator** พอยน์เตอร์. |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* คลาส [ICollection](../icollection/)
* เนมสเปซ [System::Collections::Generic](../)
* ไลบรารี [Aspose.Slides](../../)