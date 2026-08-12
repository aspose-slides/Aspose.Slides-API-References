---
title: X509CertificateCollection
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "คอลเลกชันของอ็อบเจ็กต์ใบรับรอง X509. อ็อบเจ็กต์ของคลาสนี้ควรได้รับการจัดสรรโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new, เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการตรวจสอบความถูกต้อง. ควรห่อหุ้มคลาสนี้เป็นพอยเตอร์ System::SmartPtr และใช้พอยเตอร์นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 79
url: /th/system.security.cryptography.x509certificates/x509certificatecollection/
---
## X509CertificateCollection คลาส


คอลเลกชันของอ็อบเจ็กต์ใบรับรอง X509. อ็อบเจ็กต์ของคลาสนี้ควรได้รับการจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new, เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อหุ้มคลาสนี้เป็นพอยเตอร์ [System::SmartPtr](../../system/smartptr/) และใช้พอยเตอร์นี้เพื่อส่งผ่านให้กับฟังก์ชันเป็นอาร์กิวเมนต์.

```cpp
class X509CertificateCollection : public System::Collections::Generic::List<SharedPtr<X509Certificate>>
```

## วิธีการ

| Method | Description |
| --- | --- |
| void [_add_range](../../system.collections.generic/list/_add_range/)(std::initializer_list\<T\>) | เฉพาะ C++. |
| void [Add](../../system.collections.generic/list/add/)(const T\&) override | เพิ่มองค์ประกอบที่ท้ายรายการ. |
| void [AddInitializer](../../system.collections.generic/list/addinitializer/)(int, const T *) | เพิ่มองค์ประกอบหลายรายการไปยังรายการ; ใช้เมื่อต้องแปลตัวเริ่มต้น. |
| void [AddRange](../../system.collections.generic/list/addrange/)([IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | เพิ่มองค์ประกอบทั้งหมดจากคอลเลกชัน (หรือจากตัวเอง) ไปยังตอนท้ายของรายการปัจจุบัน. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](../../system.collections.generic/list/asreadonly/)() | ดึงอ้างอิงแบบอ่านอย่างเดียวของคอลเลกชันนี้. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/list/begin/)() | รับอิเทอเรเตอร์ไปยังองค์ประกอบแรกของคอลเลกชัน. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/list/begin/)() const | รับอิเทอเรเตอร์ไปยังองค์ประกอบแรกของคอลเลกชันที่มีคุณสมบัติ const. |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(const T\&) const | ค้นหารายการในรายการที่เรียงลำดับ. |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) const | ค้นหารายการในรายการที่เรียงลำดับ. |
| int [BinarySearch](../../system.collections.generic/list/binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) const | ค้นหารายการในรายการที่เรียงลำดับ. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/list/cbegin/)() const | รับอิเทอเรเตอร์ไปยังองค์ประกอบแรกที่มีคุณสมบัติ const ของคอลเลกชัน. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/list/cend/)() const | รับอิเทอเรเตอร์สำหรับองค์ประกอบที่ไม่มีอยู่และมีคุณสมบัติ const หลังจากจบของคอลเลกชัน. |
| void [Clear](../../system.collections.generic/list/clear/)() override | ลบองค์ประกอบทั้งหมด. |
| **bool** [Contains](../../system.collections.generic/list/contains/)(const T\&) const override | ตรวจสอบว่ารายการมีอยู่ในรายการหรือไม่. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<OutputType\>\> [ConvertAll](../../system.collections.generic/list/convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | สร้างรายการขององค์ประกอบที่แปลงเป็นประเภทที่ต่างกัน. |
| void [CopyTo](../../system.collections.generic/list/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | คัดลอกองค์ประกอบของรายการเข้าไปยังองค์ประกอบของอาเรย์ที่มีอยู่. |
| void [CopyTo](../../system.collections.generic/list/copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | คัดลอกองค์ประกอบทั้งหมดเข้าไปยังอาเรย์ที่มีอยู่. |
| void [CopyTo](../../system.collections.generic/list/copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | คัดลอกองค์ประกอบเริ่มจากดัชนีที่ระบุเข้าไปยังอาเรย์ที่มีอยู่. |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [crbegin](../../system.collections.generic/list/crbegin/)() const | รับอิเทอเรเตอร์ย้อนกลับไปยังองค์ประกอบสุดท้ายที่มีคุณสมบัติ const ของคอลเลกชัน (เป็นรายการแรกในลำดับย้อนกลับ). |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [crend](../../system.collections.generic/list/crend/)() const | รับอิเทอเรเตอร์ย้อนกลับสำหรับองค์ประกอบที่ไม่มีและมีคุณสมบัติ const ก่อนจุดเริ่มต้นของคอลเลกชัน. |
| [vector_t](../../system.collections.generic/list/vector_t/)\& [data](../../system.collections.generic/list/data/)() | ฟังก์ชันเข้าถึงโครงสร้างข้อมูลพื้นฐาน. |
| const [vector_t](../../system.collections.generic/list/vector_t/)\& [data](../../system.collections.generic/list/data/)() const | ฟังก์ชันเข้าถึงโครงสร้างข้อมูลพื้นฐาน. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/list/end/)() | รับอิเทอเรเตอร์สำหรับองค์ประกอบที่ไม่มีอยู่หลังจากจบของคอลเลกชัน. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/list/end/)() const | รับอิเทอเรเตอร์สำหรับองค์ประกอบที่ไม่มีอยู่หลังจากจบของคอลเลกชันที่มีคุณสมบัติ const. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| **bool** [Exists](../../system.collections.generic/list/exists/)([System::Predicate](../../system/predicate/)\<T\>) | ตรวจสอบว่ามีองค์ประกอบที่ตรงตามเงื่อนไขที่กำหนดในรายการหรือไม่. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| T [Find](../../system.collections.generic/list/find/)([System::Predicate](../../system/predicate/)\<T\>) | ค้นหาองค์ประกอบที่ตรงตามเงื่อนไขที่กำหนด. |
| [ListPtr](../../system.collections.generic/listptr/)\<T\> [FindAll](../../system.collections.generic/list/findall/)([System::Predicate](../../system/predicate/)\<T\>) | ค้นหาองค์ประกอบที่ตรงตามเงื่อนไขที่กำหนด. |
| int [FindIndex](../../system.collections.generic/list/findindex/)([System::Predicate](../../system/predicate/)\<T\>) | ค้นหาองค์ประกอบที่ตรงตามเงื่อนไขที่กำหนด. |
| int [FindIndex](../../system.collections.generic/list/findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | ค้นหาองค์ประกอบที่ตรงตามเงื่อนไขที่กำหนด. |
| int [FindIndex](../../system.collections.generic/list/findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | ค้นหาองค์ประกอบที่ตรงตามเงื่อนไขที่กำหนด. |
| T [FindLast](../../system.collections.generic/list/findlast/)([System::Predicate](../../system/predicate/)\<T\>) | ค้นหาองค์ประกอบสุดท้ายที่ตรงตามเงื่อนไขที่กำหนด. |
| void [ForEach](../../system.collections.generic/list/foreach/)([System::Action](../../system/action/)\<T\>) | ดำเนินการต่อทุกองค์ประกอบในรายการ. |
| int [get_Capacity](../../system.collections.generic/list/get_capacity/)() const | รับความจุปัจจุบันของรายการ. |
| int [get_Count](../../system.collections.generic/list/get_count/)() const override | รับจำนวนขององค์ประกอบในรายการปัจจุบัน. |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | ตรวจสอบว่าคอลเลกชันมีขนาดคงที่หรือไม่. |
| virtual **bool** [get_IsReadOnly](../../system.collections.generic/icollection/get_isreadonly/)() const | ตรวจสอบว่าคอลเลกชันเป็นแบบอ่านอย่างเดียวหรือไม่. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | รับอ็อบเจ็กต์ที่คอลเลกชันทำการซิงโครไนซ์ผ่าน. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลเคาน์เตอร์อ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| [IEnumeratorPtr](../../system.collections.generic/list/ienumeratorptr/) [GetEnumerator](../../system.collections.generic/list/getenumerator/)() override | รับตัวนับเพื่อวนซ้ำผ่านองค์ประกอบของรายการ. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เหมือนเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชอ็อบเจ็กต์ที่กำหนดเอง. |
| **ThisPtr** [GetRange](../../system.collections.generic/list/getrange/)(int, int) | สร้างส่วนของรายการ. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เหมือนการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICollection](../../system.collections.generic/icollection/icollection/)() | คอนสตรัคเตอร์เริ่มต้น. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | คอนสตรัคเตอร์คัดลอก. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | คอนสตรัคเตอร์ย้าย. |
| T [idx_get](../../system.collections.generic/list/idx_get/)(int) const override | รับองค์ประกอบที่ตำแหน่งเฉพาะ. |
| void [idx_set](../../system.collections.generic/list/idx_set/)(int, T) override | ตั้งค่าองค์ประกอบที่ตำแหน่งเฉพาะ. |
| int [IndexOf](../../system.collections.generic/list/indexof/)(const T\&) const override | รับดัชนีแรกของรายการที่ระบุ. |
| int [IndexOf](../../system.collections.generic/list/indexof/)(const T\&, int) const | ค้นหารายการที่ระบุในรายการ. |
| void [Insert](../../system.collections.generic/list/insert/)(int, const T\&) override | แทรกรายการที่ตำแหน่งที่ระบุ. |
| void [InsertRange](../../system.collections.generic/list/insertrange/)(int, [IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | แทรกช่วงข้อมูลที่ตำแหน่งที่ระบุ. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. เหมือนตัวดำเนินการ 'is' ของ C#. |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&) const | ค้นหาอ็อบเจ็กต์ที่ระบุและคืนค่าดัชนีเริ่มจากศูนย์ของการเกิดครั้งสุดท้ายในรายการทั้งหมด. |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&, **int32_t**) const | ค้นหาอ็อบเจ็กต์ที่ระบุและคืนค่าดัชนีเริ่มจากศูนย์ของการเกิดครั้งสุดท้ายในช่วงขององค์ประกอบใน [List](../../system.collections.generic/list/) ที่ขยายจากองค์ประกอบแรกถึงดัชนีที่ระบุ. |
| **int32_t** [LastIndexOf](../../system.collections.generic/list/lastindexof/)(const T\&, **int32_t**, **int32_t**) const | ค้นหาอ็อบเจ็กต์ที่ระบุและคืนค่าดัชนีเริ่มจากศูนย์ของการเกิดครั้งสุดท้ายในช่วงขององค์ประกอบใน [List](../../system.collections.generic/list/) ที่มีจำนวนองค์ประกอบที่ระบุและสิ้นสุดที่ดัชนีที่ระบุ. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | ใช้ฟังก์ชันสะสมบนลำดับ. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | ตรวจสอบว่าทุกองค์ประกอบของลำดับตรงตามเงื่อนไขหรือไม่. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | ตรวจสอบว่าลำดับมีองค์ประกอบใด ๆ หรือไม่. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | ตรวจสอบว่ามีองค์ประกอบใดในลำดับที่มีอยู่หรือที่ตรงตามเงื่อนไขหรือไม่. |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | คำนวณค่าเฉลี่ยของลำดับของค่าตัวเลข. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | คำนวณค่าเฉลี่ยของลำดับของค่าที่ได้จากการเรียกฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับอินพุต. |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | แคสต์องค์ประกอบเป็นประเภทที่ระบุ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | ต่อสองลำดับเข้าด้วยกัน. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | ตรวจสอบว่าลำดับมีค่าที่ระบุหรือไม่. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | คืนจำนวนขององค์ประกอบในลำดับ (คำนวณโดยการนับโดยตรง). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | คืนจำนวนขององค์ประกอบในลำดับที่ตรงตามเงื่อนไขที่ระบุ. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | คืนองค์ประกอบที่ดัชนีที่ระบุในลำดับ. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | คืนองค์ประกอบที่ดัชนีที่ระบุในลำดับ. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | คืนองค์ประกอบแรกของลำดับ. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | คืนองค์ประกอบแรกของลำดับที่ตรงตามเงื่อนไขที่ระบุ. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | คืนองค์ประกอบแรกของลำดับ, หรือค่าตั้งต้นหากลำดับว่าง. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | คืนองค์ประกอบแรกของลำดับที่ตรงตามเงื่อนไขหรือค่าตั้งต้นหากไม่พบ. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | จัดกลุ่มองค์ประกอบของลำดับ. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | จัดกลุ่มองค์ประกอบของลำดับ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | คืนองค์ประกอบสุดท้ายของลำดับ. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | คืนองค์ประกอบสุดท้ายของลำดับ, หรือค่าตั้งต้นหากลำดับว่าง. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับทั่วไปและคืนค่าสูงสุดที่ได้. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | เรียกฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับทั่วไปและคืนค่าต่ำสุดที่ได้. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | กรององค์ประกอบของลำดับตามประเภทที่ระบุ. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | เรียงลำดับองค์ประกอบของลำดับในลำดับเพิ่มตามค่ากุญแจที่เลือกโดย keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | เรียงลำดับองค์ประกอบของลำดับในลำดับลดตามค่ากุญแจที่เลือกโดย keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | พลิกลำดับขององค์ประกอบในลำดับ. |
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
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | กรองลำดับตามเงื่อนไขที่ระบุ. |
|  [List](../../system.collections.generic/list/list/)() | สร้างรายการว่าง. |
|  [List](../../system.collections.generic/list/list/)(int) | สร้างรายการด้วยความจุที่กำหนดล่วงหน้า. |
|  [List](../../system.collections.generic/list/list/)([IEnumerablePtr](../../system.collections.generic/list/ienumerableptr/)) | คอนสตรัคเตอร์คัดลอก. |
| void [Lock](../../system/object/lock/)() | ทำตามการล็อกของคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เหมือนเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทกำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. ไม่ได้คัดลอกอะไรเลย, เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมายค่า. ไม่ได้คัดลอกอะไรเลย, เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | ตัวดำเนินการมอบหมายค่าการย้าย. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | ตัวดำเนินการมอบหมายค่าการย้าย. |
| vector_t::reference [operator[]](../../system.collections.generic/list/operator[]/)(int) | ฟังก์ชันเข้าถึง. |
| vector_t::const_reference [operator[]](../../system.collections.generic/list/operator[]/)(int) const | ฟังก์ชันเข้าถึง. |
| [reverse_iterator](../../system.collections.generic/list/reverse_iterator/) [rbegin](../../system.collections.generic/list/rbegin/)() | รับอิเทอเรเตอร์ย้อนกลับไปยังองค์ประกอบสุดท้ายของคอลเลกชัน (เป็นแรกในลำดับย้อนกลับ). |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [rbegin](../../system.collections.generic/list/rbegin/)() const | รับอิเทอเรเตอร์ย้อนกลับไปยังองค์ประกอบสุดท้ายของคอลเลกชันที่มีคุณสมบัติ const (เป็นแรกในลำดับย้อนกลับ). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริง. |
| **bool** [Remove](../../system.collections.generic/list/remove/)(const T\&) override | ลบอินสแตนซ์แรกของรายการที่ระบุจากรายการ. |
| int [RemoveAll](../../system.collections.generic/list/removeall/)([Predicate](../../system/predicate/)\<T\>) | ลบทุกองค์ประกอบที่ตรงกับเงื่อนไขที่ระบุ. |
| void [RemoveAt](../../system.collections.generic/list/removeat/)(int) override | ลบรายการที่ตำแหน่งที่ระบุ. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| void [RemoveRange](../../system.collections.generic/list/removerange/)(int, int) | ลบส่วนของรายการ. |
| [reverse_iterator](../../system.collections.generic/list/reverse_iterator/) [rend](../../system.collections.generic/list/rend/)() | รับอิเทอเรเตอร์ย้อนกลับสำหรับองค์ประกอบที่ไม่มีก่อนจุดเริ่มต้นของคอลเลกชัน. |
| [const_reverse_iterator](../../system.collections.generic/list/const_reverse_iterator/) [rend](../../system.collections.generic/list/rend/)() const | รับอิเทอเรเตอร์ย้อนกลับสำหรับองค์ประกอบที่ไม่มีก่อนจุดเริ่มต้นของคอลเลกชันที่มีคุณสมบัติ const. |
| void [Reverse](../../system.collections.generic/list/reverse/)() | กลับลำดับขององค์ประกอบทั้งหมดของรายการ. |
| void [Reverse](../../system.collections.generic/list/reverse/)(int, int) | กลับลำดับขององค์ประกอบของส่วนของรายการ. |
| void [set_Capacity](../../system.collections.generic/list/set_capacity/)(int) | ตั้งค่าความจุของรายการ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทน shared). อนุญาตสลับพอยเตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของเคาน์เตอร์อ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยเตอร์หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยเตอร์หรือ ThisProtector. |
| void [Sort](../../system.collections.generic/list/sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) | เรียงลำดับองค์ประกอบในรายการ. |
| void [Sort](../../system.collections.generic/list/sort/)() | เรียงลำดับองค์ประกอบในรายการโดยใช้ตัวเปรียบเทียบเริ่มต้น. |
| void [Sort](../../system.collections.generic/list/sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>) | เรียงลำดับองค์ประกอบในส่วนของรายการ. |
| void [Sort](../../system.collections.generic/list/sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | เรียงลำดับองค์ประกอบในรายการ. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](../../system.collections.generic/list/toarray/)() const | แปลงรายการเป็นอาเรย์. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เหมือนเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์กำหนดเองเป็นสตริง. |
| void [TrimExcess](../../system.collections.generic/list/trimexcess/)() | ทำให้ความจุของรายการตรงกับขนาดของมัน. |
| **bool** [TrueForAll](../../system.collections.generic/list/trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | ตรวจสอบว่าทุกองค์ประกอบในคอลเลกชันตรงกับเงื่อนไขที่กำหนดโดยพรีดิเกตหรือไม่. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำตามโครงสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำตามการปลดล็อกของคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/). |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](../../system.collections.generic/list/virtualizebeginconstiterator/)() const override | รับการทำงานของ begin const iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](../../system.collections.generic/list/virtualizebeginiterator/)() override | รับการทำงานของ begin iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](../../system.collections.generic/list/virtualizeendconstiterator/)() const override | รับการทำงานของ end const iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](../../system.collections.generic/list/virtualizeenditerator/)() override | รับการทำงานของ end iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยเตอร์หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยเตอร์หรือ ThisProtector. |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | ทำลายวัตถุ. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [List](../../system.collections.generic/list/)
* เนมสเปซ [System::Security::Cryptography::X509Certificates](../)
* ไลบรารี [Aspose.Slides](../../)