---
title: TextAnimationCollection
second_title: Aspose.Slides สำหรับ API อ้างอิงของ C++
description: แสดงคอลเลกชันของการแอนิเมชันข้อความ.
type: docs
weight: 612
url: /th/aspose.slides.animation/textanimationcollection/
---
## TextAnimationCollection คลาส

Represents collection of text animations.

```cpp
class TextAnimationCollection : public Aspose::Slides::Animation::ITextAnimationCollection
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[TextAnimation](../textanimation/)\> [Add](./add/)() | เพิ่มข้อความแอนิเมชันใหม่ลงในคอลเลกชัน |
| [iterator](./iterator/) [begin](./begin/)() | รับอิเทอเรเตอร์ที่ชี้ไปที่องค์ประกอบแรก (ถ้ามี) ของคอลเลกชัน |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | รับอิเทอเรเตอร์ที่ชี้ไปที่องค์ประกอบแรก (ถ้ามี) ของอินสแตนซ์ที่มีคุณลักษณะ const ของคอลเลกชัน |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | รับอิเทอเรเตอร์ที่ชี้ไปที่องค์ประกอบที่มีคุณลักษณะ const แรก (ถ้ามี) ของคอลเลกชัน |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | รับอิเทอเรเตอร์ที่ชี้หลังจากองค์ประกอบ const ตัวสุดท้าย (ถ้ามี) ของคอลเลกชัน |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextAnimation](../itextanimation/)\>\>, **int32_t**) override | คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาเรย์ที่ระบุ |
| [iterator](./iterator/) [end](./end/)() | รับอิเทอเรเตอร์ที่ชี้หลังจากองค์ประกอบสุดท้าย (ถ้ามี) ของคอลเลกชัน |
| [const_iterator](./const_iterator/) [end](./end/)() const | รับอิเทอเรเตอร์ที่ชี้หลังจากองค์ประกอบสุดท้าย (ถ้ามี) ของอินสแตนซ์ที่มีคุณลักษณะ const ของคอลเลกชัน |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้เซมานติก C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ซึ่ง NaN สองค่าได้รับการพิจารณาเท่ากันแม้ว่า ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ซึ่ง NaN สองค่าได้รับการพิจารณาเท่ากันแม้ว่า ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อการภายในเท่านั้น |
| **int32_t** [get_Count](./get_count/)() override | คืนค่าจำนวนองค์ประกอบในคอลเลกชัน อ่านอย่างเดียว **int32_t** |
| **bool** [get_IsSynchronized](./get_issynchronized/)() override | คืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันเป็นแบบซิงโครไนซ์ (ปลอดภัยต่อเธรด) อ่านอย่างเดียว **bool** |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_SyncRoot](./get_syncroot/)() override | คืนค่ารากของการซิงโครไนซ์ อ่านอย่างเดียว [System::Object](../../system/object/) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่สัมพันธ์กับอ็อบเจกต์ |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextAnimation](../itextanimation/)\>\>\> [GetEnumerator](./getenumerator/)() override | คืนค่า enumerator ที่ทำการวนซ้ำคอลเลกชัน |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) เปิดใช้งานการแฮชของอ็อบเจกต์ที่กำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์ คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextAnimation](../itextanimation/)\> [idx_get](./idx_get/)(**int32_t**) override | คืนค่าองค์ประกอบตามดัชนี |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextAnimation](../itextanimation/)\>\> [idx_get](./idx_get/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\>) override | คืนค่าองค์ประกอบทั้งหมด |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType คล้ายกับโอเปอเรเตอร์ 'is' ของ C# |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | นำฟังก์ชันสะสมไปใช้กับลำดับ |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | ตรวจสอบว่าองค์ประกอบทั้งหมดของลำดับตรงตามเงื่อนไข |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | ตรวจสอบว่าลำดับมีองค์ประกอบใดๆ หรือไม่ |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | ตรวจสอบว่ามีองค์ประกอบใดของลำดับที่มีอยู่หรือทำตามเงื่อนไข |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | คำนวณค่าเฉลี่ยของลำดับค่าตัวเลข |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | คำนวณค่าเฉลี่ยของลำดับค่าที่ได้โดยเรียกฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับอินพุต |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | แปลงประเภทขององค์ประกอบเป็นประเภทที่ระบุ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | ต่อสองลำดับเข้าด้วยกัน |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | ตรวจสอบว่าลำดับมีค่าที่ระบุหรือไม่ |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | คืนค่าจำนวนองค์ประกอบในลำดับ (คำนวณโดยการนับโดยตรง) |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | คืนค่าจำนวนองค์ประกอบในลำดับที่ตรงตามเงื่อนไขที่ระบุ |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | คืนค่าองค์ประกอบที่ตำแหน่งดัชนีที่ระบุในลำดับ |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | คืนค่าองค์ประกอบที่ตำแหน่งดัชนีที่ระบุในลำดับ |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | คืนค่าองค์ประกอบแรกของลำดับ |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | คืนค่าองค์ประกอบแรกของลำดับที่ตรงตามเงื่อนไขที่ระบุ |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | คืนค่าองค์ประกอบแรกของลำดับ หรือค่าดีฟอลต์หากลำดับว่างเปล่า |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | คืนค่าองค์ประกอบแรกของลำดับที่ตรงตามเงื่อนไข หรือค่าดีฟอลต์หากไม่พบ |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | จัดกลุ่มองค์ประกอบของลำดับ |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | จัดกลุ่มองค์ประกอบของลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | คืนค่าองค์ประกอบสุดท้ายของลำดับ |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | คืนค่าองค์ประกอบสุดท้ายของลำดับ หรือค่าดีฟอลต์หากลำดับว่างเปล่า |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับทั่วไปและคืนค่าผลลัพธ์สูงสุด |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับทั่วไปและคืนค่าผลลัพธ์ต่ำสุด |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | กรององค์ประกอบของลำดับตามประเภทที่ระบุ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | เรียงลำดับองค์ประกอบของลำดับในลำดับจากน้อยไปมากตามค่ากุญแจที่เลือกโดย keySelector |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | เรียงลำดับองค์ประกอบของลำดับในลำดับจากมากไปน้อยตามค่ากุญแจที่เลือกโดย keySelector |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | กลับลำดับขององค์ประกอบในลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | แปลงองค์ประกอบของลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | แปลงแต่ละองค์ประกอบของลำดับเป็นรูปแบบใหม่โดยรวมดัชนีขององค์ประกอบ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | โพรเจกต์แต่ละองค์ประกอบของลำดับและรวมลำดับที่ได้เป็นลำดับเดียว |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | ข้ามจำนวนองค์ประกอบต่อเนื่องที่ระบุจากจุดเริ่มต้นของลำดับและคืนส่วนที่เหลือ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | คืนจำนวนองค์ประกอบต่อเนื่องที่ระบุจากจุดเริ่มต้นของลำดับ |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | สร้างอาเรย์จากลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | สร้าง List<T> จากลำดับ |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | กรองลำดับตามเงื่อนไขที่ระบุ |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) เปิดใช้งานการคล cloning ของประเภทที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริงๆ เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกในซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์มอบหมาย ไม่ได้คัดลอกอะไรจริงๆ เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกในซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์ตามการอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์ตามการอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่ากับ nullptr ด้วยการอ้างอิง |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทน shared) อนุญาตสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แชร์ ควรไม่เรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงที่แชร์และคืนค่า ควรไม่เรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
|  [TextAnimationCollection](./textanimationcollection/)() |  |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/) เปิดใช้งานการแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตาม construct typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | รับอิเทอเรเตอร์ที่ชี้ไปที่องค์ประกอบแรก (ถ้ามี) ของอินสแตนซ์ที่มีคุณลักษณะ const ของคอลเลกชัน |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | รับอิเทอเรเตอร์ที่ชี้ไปที่องค์ประกอบแรก (ถ้ามี) ของคอลเลกชัน |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | รับอิเทอเรเตอร์ที่ชี้หลังจากองค์ประกอบสุดท้าย (ถ้ามี)ของอินสแตนซ์ที่มีคุณลักษณะ const ของคอลเลกชัน |
| [virtualized_iterator](./virtualized_iterator/) * [virtualizeEndIterator](./virtualizeenditerator/)() override | รับอิเทอเรเตอร์ที่ชี้หลังจากองค์ประกอบสุดท้าย (ถ้ามี) ของคอลเลกชัน |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak ควรไม่เรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak ควรไม่เรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## การนิยามประเภท

| Typedef | คำอธิบาย |
| --- | --- |
| [iterator_holder_type](./iterator_holder_type/) | ชนิดคอลเลกชันที่ประเภทอิเทอเรเตอร์ของมันถูกใช้เป็นประเภทอิเทอเรเตอร์ในคอลเลกชันปัจจุบัน |
| [iterator](./iterator/) | ประเภทอิเทอเรเตอร์ |
| [const_iterator](./const_iterator/) | ประเภทอิเทอเรเตอร์คอนสท์ |
| [virtualized_iterator_element](./virtualized_iterator_element/) | ประเภทองค์ประกอบที่เวอร์ชวลไลส์ |
| [virtualized_iterator](./virtualized_iterator/) | ประเภทที่เวอร์ชวลไลส์ |

## ดูเพิ่มเติม

* คลาส [ITextAnimationCollection](../itextanimationcollection/)
* เนมสเปซ [Aspose::Slides::Animation](../)
* ไลบรารี [Aspose.Slides](../../)