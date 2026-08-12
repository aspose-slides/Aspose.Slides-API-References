---
title: X509ExtensionCollection
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "คอลเลคชันของอ็อบเจ็กต์ส่วนขยาย. อ็อบเจ็กต์ของคลาสนี้ควรสร้างขึ้นโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้โอเปอเรเตอร์ new, เนื่องจากจะทำให้เกิดข้อผิดพลาดระหว่างการทำงานและ/หรือข้อผิดพลาดการอ้างอิง. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 157
url: /th/system.security.cryptography.x509certificates/x509extensioncollection/
---
## X509ExtensionCollection คลาส

คอลเล็กชันของอ็อบเจ็กต์ส่วนขยาย. อ็อบเจ็กต์ของคลาสนี้ควรจัดสรรด้วยฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new, เนื่องจากจะทำให้เกิดข้อผิดพลาดเวลาเรียกใช้งานและ/หรือการตรวจสอบความถูกต้อง. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) และใช้พอยน์เตอร์นี้ส่งเป็นอากิวเมนต์ให้กับฟังก์ชัน.

```cpp
class X509ExtensionCollection : public System::Collections::Generic::List<SharedPtr<X509Extension>>
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| void [_add_range](../../system.collections.generic/list/_add_range/)(std::initializer_list\<T\>) | เฉพาะ C++. |
| void [Add](../../system.collections.generic/list/add/)(const T\&) override | เพิ่มอิลิเมนต์ไปยังท้ายของลิสต์. |
| void [AddInitializer](../../system.collections.generic/list/addinitializer/)(int, const T *) | เพิ่มอิลิเมนต์ไปยังลิสต์; ใช้เมื่อตีความค่าเริ่มต้น. |
| void [AddRange](../../system.collections.generic/list/addrange/)([IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | เพิ่มอิลิเมนต์ทั้งหมดจากคอลเล็กชัน (หรือจากตัวเอง) ไปยังท้ายของลิสต์ปัจจุบัน. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](../../system.collections.generic/list/asreadonly/)() | รับอ้างอิงแบบอ่านอย่างเดียวต่อคอลเล็กชันนี้. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/list/begin/)() | รับอิเทอเรเตอร์ไปยังอิลิเมนต์แรกของคอลเล็กชัน. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/list/begin/)() const | รับอิเทอเรเตอร์ไปยังอิลิเมนต์แรกของคอลเล็กชันที่กำหนดเป็น const. |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(const T\&) const | ค้นหารายการในลิสต์ที่เรียงลำดับ. |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) const | ค้นหารายการในลิสต์ที่เรียงลำดับ. |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) const | ค้นหารายการในลิสต์ที่เรียงลำดับ. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/list/cbegin/)() const | รับอิเทอเรเตอร์ไปยังอิลิเมนต์แรกที่กำหนดเป็น const ของคอลเล็กชัน. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/list/cend/)() const | รับอิเทอเรเตอร์สำหรับอิลิเมนต์ const ที่ไม่มีอยู่หลังจบของคอลเล็กชัน. |
| void [Clear](../../system.collections.generic/list/clear/)() override | ลบอิลิเมนต์ทั้งหมด. |
| **bool** [Contains](../../system.collections.generic/list/contains/)(const T\&) const override | ตรวจสอบว่ารายการมีอยู่ในลิสต์หรือไม่. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<OutputType\>\> [ConvertAll](../../system.collections.generic/list/convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | สร้างลิสต์ของอิลิเมนต์ที่แปลงเป็นประเภทอื่น. |
| void [CopyTo](../../system.collections.generic/list/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | คัดลอกอิลิเมนต์ของลิสต์ลงในอาร์เรย์ที่มีอยู่. |
| void [CopyTo](../../system.collections.generic/list/copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | คัดลอกอิลิเมนต์ทั้งหมดลงในอาร์เรย์ที่มีอยู่. |
| void [CopyTo](../../system.collections.generic/list/copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | คัดลอกอิลิเมนต์ตั้งแต่ดัชนีที่ระบุลงในอาร์เรย์ที่มีอยู่. |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [crbegin](../../system.collections.generic/list/crbegin/)() const | รับอิเทอเรเตอร์ย้อนกลับไปยังอิลิเมนต์ const ตัวสุดท้ายของคอลเล็กชัน (อิลิเมนต์แรกเมื่อย้อนกลับ). |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [crend](../../system.collections.generic/list/crend/)() const | รับอิเทอเรเตอร์ย้อนกลับสำหรับอิลิเมนต์ const ที่ไม่มีอยู่ก่อนจุดเริ่มต้นของคอลเล็กชัน. |
| [vector_t](../../system.collections.generic/list/vector_t/)\& [data](../../system.collections.generic/list/data/)() | ฟังก์ชันเข้าถึงโครงสร้างข้อมูลพื้นฐาน. |
| const [vector_t](../../system.collections.generic/list/vector_t/)\& [data](../../system.collections.generic/list/data/)() const | ฟังก์ชันเข้าถึงโครงสร้างข้อมูลพื้นฐาน. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/list/end/)() | รับอิเทอเรเตอร์สำหรับอิลิเมนต์ที่ไม่มีอยู่หลังจบของคอลเล็กชัน. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/list/end/)() const | รับอิเทอเรเตอร์สำหรับอิลิเมนต์ที่ไม่มีอยู่หลังจบของคอลเล็กชันที่กำหนดเป็น const. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบออบเจ็กต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจ็กต์ประเภทอ้างอิงในรูปแบบ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจ็กต์ประเภทค่าในรูปแบบ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่า floating-point แบบ C# ซึ่ง NaN สองค่าถูกถือว่าเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่า floating-point แบบ C# ซึ่ง NaN สองค่าถูกถือว่าเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| **bool** [Exists](../../system.collections.generic/list/exists/)([System::Predicate](../../system/predicate/)\<T\>) | ตรวจสอบว่ามีอิลิเมนต์ที่ตรงกับเงื่อนไขเฉพาะในลิสต์หรือไม่. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| T [Find](../../system.collections.generic/list/find/)([System::Predicate](../../system/predicate/)\<T\>) | ค้นหาอิลิเมนต์ที่ตรงกับเงื่อนไขเฉพาะ. |
| [ListPtr](../../system.collections.generic/listptr/)\<T\> [FindAll](../../system.collections.generic/list/findall/)([System::Predicate](../../system/predicate/)\<T\>) | ค้นหาอิลิเมนต์ที่ตรงกับเงื่อนไขเฉพาะ. |
| int [FindIndex](../../system.collections.generic/list/findindex/)([System::Predicate](../../system/predicate/)\<T\>) | ค้นหาอิลิเมนต์ที่ตรงกับเงื่อนไขเฉพาะ. |
| int [FindIndex](../../system.collections.generic/list/findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | ค้นหาอิลิเมนต์ที่ตรงกับเงื่อนไขเฉพาะ. |
| int [FindIndex](../../system.collections.generic/list/findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | ค้นหาอิลิเมนต์ที่ตรงกับเงื่อนไขเฉพาะ. |
| T [FindLast](../../system.collections.generic/list/findlast/)([System::Predicate](../../system/predicate/)\<T\>) | ค้นหาอิลิเมนต์สุดท้ายที่ตรงกับเงื่อนไขเฉพาะ. |
| void [ForEach](../../system.collections.generic/list/foreach/)([System::Action](../../system/action/)\<T\>) | นำการกระทำไปใช้กับอิลิเมนต์ทั้งหมดในลิสต์. |
| int [get_Capacity](../../system.collections.generic/list/get_capacity/)() const | รับความจุปัจจุบันของลิสต์. |
| int [get_Count](../../system.collections.generic/list/get_count/)() const override | รับจำนวนอิลิเมนต์ในลิสต์ปัจจุบัน. |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | ตรวจสอบว่าคอลเล็กชันมีขนาดคงที่หรือไม่. |
| virtual **bool** [get_IsReadOnly](../../system.collections.generic/icollection/get_isreadonly/)() const | ตรวจสอบว่าคอลเล็กชันเป็นแบบอ่านอย่างเดียวหรือไม่. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | รับออบเจ็กต์ที่คอลเล็กชันทำการซิงโครไนซ์ผ่าน. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับออบเจ็กต์. |
| [IEnumeratorPtr](../../system.collections.generic/list/ienumeratorptr/) [GetEnumerator](../../system.collections.generic/list/getenumerator/)() override | รับอีแนมอเรเตอร์เพื่อวนผ่านอิลิเมนต์ของลิสต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของออบเจ็กต์ที่กำหนดเอง. |
| **ThisPtr** [GetRange](../../system.collections.generic/list/getrange/)(int, int) | สร้างสไลซ์ของลิสต์. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของออบเจ็กต์. คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICollection](../../system.collections.generic/icollection/icollection/)() | คอนสตรัคเตอร์เริ่มต้น. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | คอนสตรัคเตอร์คัดลอก. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | คอนสตรัคเตอร์ย้าย. |
| [SharedPtr](../../system/sharedptr/)\<[X509Extension](../x509extension/)\> [idx_get](./idx_get/)(const [String](../../system/string/)\&) const | ตัวเข้าถึง. ยังไม่ได้ทำการ implement. |
| T [idx_get](../../system.collections.generic/list/idx_get/)(int) const override | รับอิลิเมนต์ที่ตำแหน่งเฉพาะ. |
| void [idx_set](../../system.collections.generic/list/idx_set/)(int, T) override | ตั้งค่าอิลิเมนต์ที่ตำแหน่งเฉพาะ. |
| int [IndexOf](../../system.collections.generic/list/indexof/)(const T\&) const override | รับดัชนีแรกของอิลิเมนต์เฉพาะ. |
| int [IndexOf](../../system.collections.generic/list/indexof/)(const T\&, int) const | ค้นหาอิลิเมนต์เฉพาะในลิสต์. |
| void [Insert](../../system.collections.generic/list/insert/)(int, const T\&) override | แทรกอิลิเมนต์ที่ตำแหน่งที่ระบุ. |
| void [InsertRange](../../system.collections.generic/list/insertrange/)(int, [IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | แทรกช่วงข้อมูลที่ตำแหน่งเฉพาะ. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าออบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. คล้ายกับโอเปอเรเตอร์ 'is' ของ C#. |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&) const | ค้นหาออบเจ็กต์ที่ระบุและคืนค่าดัชนีเริ่มจากศูนย์ของการปรากฏครั้งสุดท้ายในลิสต์ทั้งหมด. |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&, **int32_t**) const | ค้นหาออบเจ็กต์ที่ระบุและคืนค่าดัชนีเริ่มจากศูนย์ของการปรากฏครั้งสุดท้ายในช่วงของอิลิเมนต์ใน [List](../../system.collections.generic/list/) ที่เริ่มจากอิลิเมนต์แรกจนถึงดัชนีที่ระบุ. |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&, **int32_t**, **int32_t**) const | ค้นหาออบเจ็กต์ที่ระบุและคืนค่าดัชนีเริ่มจากศูนย์ของการปรากฏครั้งสุดท้ายในช่วงของอิลิเมนต์ใน [List](../../system.collections.generic/list/) ที่มีจำนวนอิลิเมนต์ที่ระบุและจบที่ดัชนีที่ระบุ. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | ใช้ฟังก์ชัน accumulator บนลำดับ. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | กำหนดว่าทุกอิลิเมนต์ในลำดับทั้งหมดตรงตามเงื่อนไขหรือไม่. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | กำหนดว่าลำดับมีอิลิเมนต์ใด ๆ หรือไม่. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | กำหนดว่ามีอิลิเมนต์ใดในลำดับที่มีอยู่หรือทำตามเงื่อนไขหรือไม่. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | คำนวณค่าเฉลี่ยของลำดับของค่าตัวเลข. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | คำนวณค่าเฉลี่ยของลำดับของค่าที่ได้จากการเรียกใช้ฟังก์ชันแปลงบนแต่ละอิลิเมนต์ของลำดับอินพุต. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | แคสท์อิลิเมนต์เป็นประเภทที่ระบุ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | ต่อสองลำดับต่อกัน. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | กำหนดว่าลำดับมีค่าที่ระบุหรือไม่. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | คืนจำนวนอิลิเมนต์ในลำดับ (คำนวณโดยการนับโดยตรง). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | คืนจำนวนอิลิเมนต์ในลำดับที่ตรงตามเงื่อนไขที่ระบุ. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | คืนอิลิเมนต์ที่ดัชนีที่ระบุในลำดับ. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | คืนอิลิเมนต์ที่ดัชนีที่ระบุในลำดับ. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | คืนอิลิเมนต์แรกของลำดับ. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | คืนอิลิเมนต์แรกของลำดับที่ตรงตามเงื่อนไขที่ระบุ. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | คืนอิลิเมนต์แรกของลำดับ, หรือค่าตั้งต้นหากลำดับว่าง. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | คืนอิลิเมนต์แรกของลำดับที่ตรงตามเงื่อนไขหรือค่าตั้งต้นหากไม่พบอิลิเมนต์ดังกล่าว. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | จัดกลุ่มอิลิเมนต์ของลำดับ. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | จัดกลุ่มอิลิเมนต์ของลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | คืนอิลิเมนต์สุดท้ายของลำดับ. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | คืนอิลิเมนต์สุดท้ายของลำดับ, หรือค่าตั้งต้นหากลำดับว่าง. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกฟังก์ชันแปลงบนแต่ละอิลิเมนต์ของลำดับทั่วไปและคืนค่าผลลัพธ์สูงสุด. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกฟังก์ชันแปลงบนแต่ละอิลิเมนต์ของลำดับทั่วไปและคืนค่าผลลัพธ์ต่ำสุด. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | กรองอิลิเมนต์ของลำดับตามประเภทที่ระบุ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | จัดเรียงอิลิเมนต์ของลำดับในลำดับจากน้อยไปมากตามค่ากุญแจที่เลือกโดย keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | จัดเรียงอิลิเมนต์ของลำดับในลำดับจากมากไปน้อยตามค่ากุญแจที่เลือกโดย keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | ย้อนลำดับของอิลิเมนต์ในลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | แปลงอิลิเมนต์ของลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | แปลงแต่ละอิลิเมนต์ของลำดับเป็นรูปแบบใหม่โดยรวมดัชนีของอิลิเมนต์. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | โปรเจ็กต์อิลิเมนต์แต่ละตัวของลำดับและรวมลำดับผลลัพธ์เป็นลำดับเดียว. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | ข้ามจำนวนอิลิเมนต์ต่อเนื่องที่ระบุจากจุดเริ่มต้นของลำดับและคืนส่วนที่เหลือ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | คืนจำนวนอิลิเมนต์ต่อเนื่องที่ระบุจากจุดเริ่มต้นของลำดับ. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | สร้างอาร์เรย์จากลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | สร้าง List<T> จากลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | กรองลำดับโดยใช้เงื่อนไขที่ระบุ. |
|  [List](../../system.collections.generic/list/list/)() | สร้างลิสต์เปล่า. |
|  [List](../../system.collections.generic/list/list/)(int) | สร้างลิสต์พร้อมความจุก่อนกำหนด. |
|  [List](../../system.collections.generic/list/list/)([IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | คอนสตรัคเตอร์คัดลอก. |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการคล clones ชนิดที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างออบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. ไม่ได้คัดลอกอะไรจริงๆ เพียงเริ่มต้นออบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. ไม่ได้คัดลอกอะไรจริงๆ เพียงเริ่มต้นออบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกซับคลาส. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | โอเปอเรเตอร์การย้ายค่ากำหนด. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | โอเปอเรเตอร์การย้ายค่ากำหนด. |
| vector_t::reference [operator[]](../../system.collections.generic/list/operator[]/)(int) | ฟังก์ชันเข้าถึง. |
| vector_t::const_reference [operator[]](../../system.collections.generic/list/operator[]/)(int) const | ฟังก์ชันเข้าถึง. |
| [reverse_iterator](../../system.collections.generic/list/reverse_iterator/) [rbegin](../../system.collections.generic/list/rbegin/)() | รับอิเทอเรเตอร์ย้อนกลับไปยังอิลิเมนต์สุดท้ายของคอลเล็กชัน (อิลิเมนต์แรกเมื่อย้อนกลับ). |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [rbegin](../../system.collections.generic/list/rbegin/)() const | รับอิเทอเรเตอร์ย้อนกลับไปยังอิลิเมนต์สุดท้ายของคอลเล็กชันที่กำหนดเป็น const (อิลิเมนต์แรกเมื่อย้อนกลับ). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบออบเจ็กต์ตามอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบออบเจ็กต์ตามอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจ็กต์ประเภทค่ากับ nullptr ตามอ้างอิง. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริง. |
| **bool** [Remove](../../system.collections.generic/list/remove/)(const T\&) override | ลบอินสแตนซ์แรกของอิลิเมนต์เฉพาะจากลิสต์. |
| int [RemoveAll](../../system.collections.generic/list/removeall/)([Predicate](../../system/predicate/)\<T\>) | ลบอิลิเมนต์ทั้งหมดที่ตรงกับเงื่อนไขเฉพาะ. |
| void [RemoveAt](../../system.collections.generic/list/removeat/)(int) override | ลบอิลิเมนต์ที่ตำแหน่งที่ระบุ. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| void [RemoveRange](../../system.collections.generic/list/removerange/)(int, int) | ลบส่วนของลิสต์. |
| [reverse_iterator](../../system.collections.generic/list/reverse_iterator/) [rend](../../system.collections.generic/list/rend/)() | รับอิเทอเรเตอร์ย้อนกลับสำหรับอิลิเมนต์ที่ไม่มีอยู่ก่อนจุดเริ่มต้นของคอลเล็กชัน. |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [rend](../../system.collections.generic/list/rend/)() const | รับอิเทอเรเตอร์ย้อนกลับสำหรับอิลิเมนต์ที่ไม่มีอยู่ก่อนจุดเริ่มต้นของคอลเล็กชันที่กำหนดเป็น const. |
| void [Reverse](../../system.collections.generic/list/reverse/)() | ย้อนลำดับอิลิเมนต์ของลิสต์ทั้งหมด. |
| void [Reverse](../../system.collections.generic/list/reverse/)(int, int) | ย้อนลำดับอิลิเมนต์ของส่วนลิสต์. |
| void [set_Capacity](../../system.collections.generic/list/set_capacity/)(int) | ตั้งค่าความจูลิสต์. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้เปลี่ยนพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| void [Sort](../../system.collections.generic/list/sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) | จัดเรียงอิลิเมนต์ในลิสต์. |
| void [Sort](../../system.collections.generic/list/sort/)() | จัดเรียงอิลิเมนต์ในลิสต์โดยใช้ comparator เริ่มต้น. |
| void [Sort](../../system.collections.generic/list/sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>) | จัดเรียงอิลิเมนต์ในส่วนของลิสต์. |
| void [Sort](../../system.collections.generic/list/sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | จัดเรียงอิลิเมนต์ในลิสต์. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](../../system.collections.generic/list/toarray/)() const | แปลงลิสต์เป็นอาร์เรย์. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงออบเจ็กต์ที่กำหนดเองเป็นสตริง. |
| void [TrimExcess](../../system.collections.generic/list/trimexcess/)() | ทำให้ความจูลิสต์พอกับขนาดของมัน. |
| **bool** [TrueForAll](../../system.collections.generic/list/trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | กำหนดว่าทุกอิลิเมนต์ในคอลเล็กชันตรงกับเงื่อนไขที่กำหนดโดยเงื่อนไขที่ระบุหรือไม่. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการโครงสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](../../system.collections.generic/list/virtualizebeginconstiterator/)() const override | รับการดำเนินการของ begin const iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](../../system.collections.generic/list/virtualizebeginiterator/)() override | รับการดำเนินการของ begin iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](../../system.collections.generic/list/virtualizeendconstiterator/)() const override | รับการดำเนินการของ end const iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](../../system.collections.generic/list/virtualizeenditerator/)() override | รับการดำเนินการของ end iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
|  [X509ExtensionCollection](./x509extensioncollection/)() | สร้างคอลเล็กชันเปล่า. |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | ทำลายออบเจ็กต์. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายออบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [List](../../system.collections.generic/list/)
* เนมสเปซ [System::Security::Cryptography::X509Certificates](../)
* ไลบรารี [Aspose.Slides](../../)