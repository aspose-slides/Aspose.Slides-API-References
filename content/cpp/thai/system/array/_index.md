---
title: Array
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "คลาสที่แสดงโครงสร้างข้อมูลแบบอาเรย์ วัตถุของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน System::MakeArray() และ System::MakeObject() เท่านั้น ไม่ควรสร้างอินสแตนซ์ของชนิดนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr เสมอและใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้ฟังก์ชัน"
type: docs
weight: 14
url: /th/system/array/
---
## คลาส Array

คลาสที่เป็นตัวแทนของโครงสร้างข้อมูลแบบอาเรย์ อ็อบเจ็กต์ของคลาสนี้ควรจัดสรรด้วยการใช้ฟังก์ชัน [System::MakeArray()](../makearray/) และ [System::MakeObject()](../makeobject/) เท่านั้น ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือการตรวจสอบที่ล้มเหลว ควรหุ้มหรือแพกคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../smartptr/) เสมอและใช้พอยน์เตอร์นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน

```cpp
template<typename T>class Array : public System::ArrayBase,
                                  public System::Collections::Generic::IList<T>
```

### พารามิเตอร์ของเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบในอาเรย์ |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| void [Add](./add/)(const T\&) override | ไม่รองรับเนื่องจากอาเรย์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันเป็นแบบอ่านอย่างเดียว |
|  [Array](./array/)() | สร้างอาเรย์เปล่า |
|  [Array](./array/)(int, const T\&) | คอนสตรัคเตอร์เติมค่า |
|  [Array](./array/)(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](./valuetype/)\>::value\&&std::is_convertible\<[ValueType](./valuetype/), T\>::value, int\>::type, [ValueType](./valuetype/)) | คอนสตรัคเตอร์เติมค่า |
|  [Array](./array/)(int, const T) | คอนสตรัคเตอร์เติมค่า |
|  [Array](./array/)(**vector_t**\&&) | คอนสตรัคเตอร์ย้าย |
|  [Array](./array/)(const **vector_t**\&) | คอนสตรัคเตอร์คัดลอก |
|  [Array](./array/)(const std::vector\<Q\>\&) | สร้างอ็อบเจ็กต์ [Array](./) และเติมด้วยค่าโดยคัดลอกจากอ็อบเจ็กต์ std::vector ที่ชนิดค่าของมันเหมือนกับ **T** แต่ต่างจาก **UnderlyingType** |
|  [Array](./array/)(std::vector\<Q\>\&&) | สร้างอ็อบเจ็กต์ [Array](./) และเติมด้วยค่าที่ย้ายมาจากอ็อบเจ็กต์ std::vector ที่ชนิดค่าของมันเหมือนกับ **T** แต่ต่างจาก **UnderlyingType** |
|  [Array](./array/)(std::initializer_list\<[UnderlyingType](./underlyingtype/)\>) | สร้างอ็อบเจ็กต์ [Array](./) และเติมด้วยค่าจากลิสต์ initializer ที่ระบุซึ่งประกอบด้วยสมาชิกชนิด **UnderlyingType** |
|  [Array](./array/)(const std::array\<[UnderlyingType](./underlyingtype/), InitArraySize\>\&) | สร้างอ็อบเจ็กต์ [Array](./) และเติมด้วยค่าจากอาร์เรย์ที่ระบุซึ่งมีสมาชิกชนิด **UnderlyingType** |
|  [Array](./array/)(std::initializer_list\<**bool**\>, int) | สร้างอ็อบเจ็กต์ [Array](./) และเติมด้วยค่าจากลิสต์ initializer ที่ระบุซึ่งมีสมาชิกชนิด bool |
| static [SharedPtr](../sharedptr/)\<[Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)(const [SharedPtr](../sharedptr/)\<[Array](./)\<T\>\>\&) | แปลงอาเรย์เป็นคอลเลกชันแบบอ่านอย่างเดียว |
| [iterator](./iterator/) [begin](./begin/)() | คืนตัววนซ้ำไปยังสมาชิกแรกของคอนเทนเนอร์ ถ้าคอนเทนเนอร์ว่าง ตัววนซ้ำที่คืนค่าจะเท่ากับ [end()](./end/) |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | คืนตัววนซ้ำไปยังสมาชิกแรกของคอนเทนเนอร์ที่กำหนดเป็น const ถ้าคอนเทนเนอร์ว่าง ตัววนซ้ำที่คืนค่าจะเท่ากับ [end()](./end/) |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const T\&) | ทำการค้นหาแบบไบนารีในอาเรย์ที่เรียงลำดับแล้ว |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const Y\&, const [SharedPtr](../sharedptr/)\<[Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Z\>\>\&) | ยังไม่ได้ดำเนินการ |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | คืนตัววนซ้ำไปยังสมาชิกแรกที่กำหนดเป็น const ของคอนเทนเนอร์ ถ้าคอนเทนเนอร์ว่าง ตัววนซ้ำที่คืนค่าจะเท่ากับ [cend()](./cend/) |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | คืนตัววนซ้ำไปยังสมาชิกที่ตามหลังสมาชิกสุดท้ายของคอนเทนเนอร์ สมาชิกนี้ทำหน้าที่เป็นตัวแทน; การเข้าถึงจะทำให้เกิดพฤติกรรมไม่กำหนดผล |
| void [Clear](./clear/)() override | ไม่รองรับเนื่องจากอาเรย์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันเป็นแบบอ่านอย่างเดียว |
| static void [Clear](./clear/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | แทนที่ค่าจำนวน **count** เริ่มจากดัชนี **startIndex** ในอาเรย์ที่ระบุด้วยค่าตั้งต้น |
| [ArrayPtr](../arrayptr/)\<T\> [Clone](./clone/)() | คัดลอกอาเรย์ |
| static void [ConstrainedCopy](./constrainedcopy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | คัดลอกช่วงของสมาชิกจาก [System.Array](./) เริ่มจากแหล่งที่ระบุ |
| **bool** [Contains](./contains/)(const T\&) const override | ตรวจสอบว่ารายการที่ระบุอยู่ในอาเรย์หรือไม่ |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, [Converter](../converter/)\<InputType, OutputType\>) | สร้างอ็อบเจ็กต์ [Array](./) ใหม่และเติมด้วยสมาชิกของอาเรย์ที่ระบุโดยแปลงเป็นชนิด **OutputType** ด้วย delegate ตัวแปลงที่ระบุ |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, std::function\<OutputType(InputType)>) | สร้างอ็อบเจ็กต์ [Array](./) ใหม่และเติมด้วยสมาชิกของอาเรย์ที่ระบุโดยแปลงเป็นชนิด **OutputType** ด้วยฟังก์ชันออบเจ็กต์ตัวแปลงที่ระบุ |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | คัดลอกจำนวนสมาชิกที่ระบุจากอาเรย์ต้นฉบับไปยังอาเรย์ปลายทาง |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | คัดลอกจำนวนสมาชิกที่ระบุจากมุมมองอาเรย์ต้นฉบับไปยังอาเรย์ปลายทาง |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::ArrayView\<DstType\>, **int64_t**) | คัดลอกจำนวนสมาชิกที่ระบุจากอาเรย์ต้นฉบับไปยังมุมมองอาเรย์ปลายทาง |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, **int64_t**) | คัดลอกจำนวนสมาชิกที่ระบุจากมุมมองอาเรย์ต้นฉบับไปยังมุมมองอาเรย์ปลายทาง |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | คัดลอกจำนวนสมาชิกที่ระบุจากอาเรย์ต้นฉบับบนสแตกไปยังอาเรย์ปลายทาง |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, **int64_t**) | คัดลอกจำนวนสมาชิกที่ระบุจากอาเรย์ต้นฉบับไปยังอาเรย์ปลายทางบนสแตก |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, **int64_t**) | คัดลอกจำนวนสมาชิกที่ระบุจากอาเรย์ต้นฉบับบนสแตกไปยังอาเรย์ปลายทางบนสแตก |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | คัดลอกจำนวนสมาชิกที่ระบุจากอาเรย์ต้นฉบับเริ่มจากดัชนีที่ระบุไปยังตำแหน่งที่ระบุในอาเรย์ปลายทาง |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | คัดลอกจำนวนสมาชิกที่ระบุจากมุมมองอาเรย์ต้นฉบับเริ่มจากดัชนีที่ระบุไปยังตำแหน่งที่ระบุในอาเรย์ปลายทาง |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | คัดลอกจำนวนสมาชิกที่ระบุจากอาเรย์ต้นฉบับเริ่มจากดัชนีที่ระบุไปยังตำแหน่งที่ระบุในมุมมองอาเรย์ปลายทาง |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | คัดลอกจำนวนสมาชิกที่ระบุจากมุมมองอาเรย์ต้นฉบับเริ่มจากดัชนีที่ระบุไปยังตำแหน่งที่ระบุในมุมมองอาเรย์ปลายทาง |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | คัดลอกจำนวนสมาชิกที่ระบุจากอาเรย์ต้นฉบับบนสแตกเริ่มจากดัชนีที่ระบุไปยังตำแหน่งที่ระบุในอาเรย์ปลายทาง |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, N\>\&, **int64_t**, **int64_t**) | คัดลอกจำนวนสมาชิกที่ระบุจากอาเรย์ต้นฉบับเริ่มจากดัชนีที่ระบุไปยังตำแหน่งที่ระบุในอาเรย์ปลายทางบนสแตก |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | คัดลอกจำนวนสมาชิกที่ระบุจากอาเรย์ต้นฉบับบนสแตกเริ่มจากดัชนีที่ระบุไปยังตำแหน่งที่ระบุในอาเรย์ปลายทางบนสแตก |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | คัดลอกจำนวนสมาชิกที่ระบุจากมุมมองอาเรย์ต้นฉบับเริ่มจากดัชนีที่ระบุไปยังตำแหน่งที่ระบุในอาเรย์ปลายทางบนสแตก |
| void [CopyTo](./copyto/)([ArrayPtr](../arrayptr/)\<T\>, int) override | คัดลอกสมาชิกทั้งหมดของอาเรย์ปัจจุบันไปยังอาเรย์ปลายทางที่ระบุ สมาชิกจะถูกแทรกลงในอาเรย์ปลายทางเริ่มจากดัชนีที่ระบุโดยอาร์กิวเมนต์ arrayIndex |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) const | คัดลอกสมาชิกทั้งหมดของอาเรย์ปัจจุบันไปยังอาเรย์ปลายทางที่ระบุ สมาชิกจะถูกแทรกลงในอาเรย์ปลายทางเริ่มจากดัชนีที่ระบุโดยอาร์กิวเมนต์ dstIndex |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**) const | คัดลอกสมาชิกทั้งหมดของอาเรย์ปัจจุบันไปยังมุมมองอาเรย์ปลายทางที่ระบุ สมาชิกจะถูกแทรกลงในมุมมองอาเรย์ปลายทางเริ่มจากดัชนีที่ระบุโดยอาร์กิวเมนต์ dstIndex |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | คัดลอกจำนวนสมาชิกที่ระบุจากอาเรย์ปัจจุบันเริ่มจากตำแหน่งที่ระบุไปยังอาเรย์ปลายทางที่ระบุ สมาชิกจะถูกแทรกลงในอาเรย์ปลายทางเริ่มจากดัชนีที่ระบุโดยอาร์กิวเมนต์ dstIndex |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | คัดลอกจำนวนสมาชิกที่ระบุจากอาเรย์ปัจจุบันเริ่มจากตำแหน่งที่ระบุไปยังมุมมองอาเรย์ปลายทางที่ระบุ สมาชิกจะถูกแทรกลงในมุมมองอาเรย์ปลายทางเริ่มจากดัชนีที่ระบุโดยอาร์กิวเมนต์ dstIndex |
| int [Count](./count/)() const | คืนจำนวนที่แสดงถึงจำนวนสมาชิกทั้งหมดในทุกมิติของอาเรย์ |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | คืนตัววนซ้ำย้อนกลับไปยังสมาชิกแรกของคอนเทนเนอร์ที่ถูกย้อนกลับ ซึ่งสอดคล้องกับสมาชิกสุดท้ายของคอนเทนเนอร์ที่ไม่ถูกย้อนกลับ ถ้าคอนเทนเนอร์ว่าง ตัววนซ้ำที่คืนค่าจะเท่ากับ [crend()](./crend/) |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | คืนตัววนซ้ำย้อนกลับไปยังสมาชิกที่ตามหลังสมาชิกสุดท้ายของคอนเทนเนอร์ที่ถูกย้อนกลับ ซึ่งสอดคล้องกับสมาชิกก่อนหน้าสมาชิกแรกของคอนเทนเนอร์ที่ไม่ถูกย้อนกลับ สมาชิกนี้ทำหน้าที่เป็นตัวแทน; การเข้าถึงจะทำให้เกิดพฤติกรรมไม่กำหนดผล |
| **vector_t**\& [data](./data/)() | คืนการอ้างอิงไปยังโครงสร้างข้อมูลภายในที่ใช้เก็บสมาชิกอาเรย์ |
| const **vector_t**\& [data](./data/)() const | คืนการอ้างอิงแบบคงที่ไปยังโครงสร้างข้อมูลภายในที่ใช้เก็บสมาชิกอาเรย์ |
| vector_t::pointer [data_ptr](./data_ptr/)() | คืนพอยน์เตอร์แบบ raw ไปยังตำแหน่งเริ่มต้นของบัฟเฟอร์หน่วยความจำที่เก็บสมาชิกอาเรย์ |
| const [UnderlyingType](./underlyingtype/) * [data_ptr](./data_ptr/)() const | คืนพอยน์เตอร์ raw แบบคงที่ไปยังตำแหน่งเริ่มต้นของบัฟเฟอร์หน่วยความจำที่เก็บสมาชิกอาเรย์ |
| [iterator](./iterator/) [end](./end/)() | คืนตัววนซ้ำไปยังสมาชิกที่ตามหลังสมาชิกสุดท้ายของคอนเทนเนอร์ สมาชิกนี้ทำหน้าที่เป็นตัวแทน; การเข้าถึงจะทำให้เกิดพฤติกรรมไม่กำหนดผล |
| [const_iterator](./const_iterator/) [end](./end/)() const | คืนตัววนซ้ำไปยังสมาชิกที่ตามหลังสมาชิกสุดท้ายของคอนเทนเนอร์ที่กำหนดเป็น const สมาชิกนี้ทำหน้าที่เป็นตัวแทน; การเข้าถึงจะทำให้เกิดพฤติกรรมไม่กำหนดผล |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ semantics ของ C# [Object.Equals](../object/equals/) |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในรูปแบบ C# |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในรูปแบบ C# |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C# ที่ NaN ทั้งสองถือว่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบตัวเลขจุดลอยตามสไตล์ C# ซึ่ง NaN สองค่าได้รับการถือว่าเท่ากันแม้ว่า ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย |
| static **bool** [Exists](./exists/)([ArrayPtr](../arrayptr/)\<T\>, std::function\<**bool**(T)>) | กำหนดว่าวัตถุ [Array](./) ที่ระบุมีองค์ประกอบที่ตรงตามเงื่อนไขของตัวตรวจสอบที่ระบุหรือไม่ |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| static T [Find](./find/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | ค้นหาองค์ประกอบแรกในอาร์เรย์ที่ระบุซึ่งตรงตามเงื่อนไขของตัวตรวจสอบที่ระบุ |
| static [System::ArrayPtr](../arrayptr/)\<T\> [FindAll](./findall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | ดึงข้อมูลทุกองค์ประกอบที่ตรงกับเงื่อนไขที่กำหนดโดยตัวตรวจสอบที่ระบุ |
| static int [FindIndex](./findindex/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | ค้นหาองค์ประกอบแรกในอาร์เรย์ที่ระบุซึ่งตรงตามเงื่อนไขของตัวตรวจสอบที่ระบุ |
| static void [ForEach](./foreach/)(const [ArrayPtr](../arrayptr/)\<T\>\&, [System::Action](../action/)\<T\>) | ดำเนินการที่ระบุบนแต่ละองค์ประกอบของอาร์เรย์ที่ระบุ |
| int [get_Count](./get_count/)() const override | คืนค่าขนาดของอาร์เรย์ |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | ตรวจสอบว่าคอลเลกชันมีขนาดคงที่หรือไม่ |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const override | บ่งชี้ว่าอาร์เรย์เป็นแบบอ่านอย่างเดียวหรือไม่ |
| **int32_t** [get_Length](./get_length/)() const override | คืนค่าเต็ม 32 บิตที่แทนจำนวนทั้งหมดขององค์ประกอบในทุกมิติของอาร์เรย์ |
| **int64_t** [get_LongLength](./get_longlength/)() const | คืนค่าเต็ม 64 บิตที่แทนจำนวนทั้งหมดขององค์ประกอบในทุกมิติของอาร์เรย์ |
| **int32_t** [get_Rank](./get_rank/)() const | ยังไม่ได้ทำการใช้งาน |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | รับวัตถุที่คอลเลกชันกำลังซิงโครไนส์ผ่าน |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ |
| [EnumeratorPtr](./enumeratorptr/) [GetEnumerator](./getenumerator/)() override | คืนค่าตัวชี้ไปยังวัตถุ **Enumerator** ที่ให้ส่วนต่อประสาน IEnumerator กับองค์ประกอบของอาร์เรย์ที่แสดงโดยวัตถุปัจจุบัน |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../object/gethashcode/) ทำให้สามารถทำแฮชของวัตถุที่กำหนดเองได้ |
| int [GetLength](./getlength/)(int) | คืนค่าจำนวนองค์ประกอบในมิติที่ระบุ |
| **int64_t** [GetLongLength](./getlonglength/)(int) | คืนค่าจำนวนองค์ประกอบในมิติที่ระบุเป็นเลขเต็ม 64 บิต |
| int [GetLowerBound](./getlowerbound/)(int) const | คืนค่าขอบล่างของมิติที่ระบุ |
| size_t [GetSizeTLength](./getsizetlength/)() const | คืนค่าตัวแปร std::size_t ที่แทนจำนวนทั้งหมดขององค์ประกอบในทุกมิติของอาร์เรย์ |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | รับประเภทจริงของวัตถุ คล้ายกับการเรียก C# [System.Object.GetType()](../object/gettype/) |
| int [GetUpperBound](./getupperbound/)(int) | คืนค่าสูงสุดของมิติที่ระบุ |
|  [ICollection](../../system.collections.generic/icollection/icollection/)() | คอนสตรัคเตอร์เริ่มต้น |
|  [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | คอนสตรัคเตอร์คัดลอก |
|  [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | คอนสตรัคเตอร์ย้าย |
| T [idx_get](./idx_get/)(int) const override | คืนค่าสิ่งที่อยู่ที่ดัชนีที่ระบุ |
| void [idx_set](./idx_set/)(int, T) override | ตั้งค่าที่ระบุเป็นรายการของอาร์เรย์ที่ดัชนีที่ระบุ |
| int [IndexOf](./indexof/)(const T\&) const override | กำหนดดัชนีของการปรากฏครั้งแรกของรายการที่ระบุในอาร์เรย์ |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | กำหนดดัชนีของการปรากฏครั้งแรกของรายการที่ระบุในอาร์เรย์ |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | กำหนดดัชนีของการปรากฏครั้งแรกของรายการที่ระบุในอาร์เรย์โดยเริ่มจากดัชนีที่ระบุ |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | กำหนดดัชนีของการปรากฏครั้งแรกของรายการที่ระบุในช่วงของรายการในอาร์เรย์ที่กำหนดโดยดัชนีเริ่มต้นและจำนวนองค์ประกอบในช่วงนั้น |
| [ArrayPtr](../arrayptr/)\<T\> [Init](./init/)(const T) | เติมอาร์เรย์ที่แสดงโดยวัตถุปัจจุบันด้วยค่าจากอาร์เรย์ที่ระบุ |
| void [Initialize](./initialize/)() | เติมอาร์เรย์ด้วยออบเจ็กต์ที่สร้างโดยค่าเริ่มต้นของประเภท **T** |
| void [Insert](./insert/)(int, const T\&) override | ไม่รองรับเนื่องจากอาร์เรย์ที่แสดงโดยวัตถุปัจจุบันเป็นแบบอ่านอย่างเดียว |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ คล้ายกับโอเปอร์เตอร์ 'is' ของ C# |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | กำหนดดัชนีของการปรากฏครั้งสุดท้ายของรายการที่ระบุในช่วงของรายการในอาร์เรย์ที่กำหนดโดยดัชนีเริ่มต้นและจำนวนองค์ประกอบในช่วงนั้น |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | กำหนดดัชนีของการปรากฏครั้งสุดท้ายของรายการที่ระบุในอาร์เรย์โดยเริ่มจากดัชนีที่ระบุ |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | กำหนดดัชนีของการปรากฏครั้งสุดท้ายของรายการที่ระบุในอาร์เรย์ |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../func/)\<T, T, T\>\&) | ใช้ฟังก์ชันสะสมบนลำดับ |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | กำหนดว่าทุกรายการในลำดับตรงตามเงื่อนไขหรือไม่ |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | กำหนดว่าลำดับมีองค์ประกอบใด ๆ หรือไม่ |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | กำหนดว่ามีองค์ประกอบใดในลำดับที่มีอยู่หรือเป็นไปตามเงื่อนไขหรือไม่ |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | คำนวณค่าเฉลี่ยของลำดับค่าตัวเลข |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../func/)\<T, ResultType\>\&) | คำนวณค่าเฉลี่ยของลำดับค่าที่ได้จากการเรียกใช้ฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับอินพุต |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | แปลงประเภทขององค์ประกอบเป็นประเภทที่ระบุ |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | ต่อเนื่องสองลำดับเข้าด้วยกัน |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | กำหนดว่าลำดับมีค่าที่ระบุหรือไม่ |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | คืนค่าจำนวนองค์ประกอบในลำดับ (คำนวณโดยการนับโดยตรง) |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../func/)\<T, **bool**\>\&) | คืนค่าจำนวนองค์ประกอบในลำดับที่ตรงตามเงื่อนไขที่ระบุ |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | คืนค่ารายการที่ดัชนีที่ระบุในลำดับ |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | คืนค่ารายการที่ดัชนีที่ระบุในลำดับ |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | คืนค่ารายการแรกของลำดับ |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../func/)\<T, **bool**\>\&) | คืนค่ารายการแรกของลำดับที่ตรงตามเงื่อนไขที่ระบุ |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | คืนค่ารายการแรกของลำดับ หรือค่าตัวเริ่มต้นหากลำดับว่าง |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | คืนค่ารายการแรกของลำดับที่ตรงตามเงื่อนไข หรือค่าตัวเริ่มต้นหากไม่พบรายการที่ตรงเงื่อนไข |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>) | จัดกลุ่มองค์ประกอบของลำดับ |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>, [System::Func](../func/)\<T, Element\>) | จัดกลุ่มองค์ประกอบของลำดับ |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>, [System::Func](../func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | คืนค่ารายการสุดท้ายของลำดับ |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | คืนค่ารายการสุดท้ายของลำดับ หรือค่าตัวเริ่มต้นหากลำดับว่าง |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<T, ResultType\>\&) | เรียกใช้ฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับทั่วไปและคืนค่าผลลัพธ์สูงสุด |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<T, ResultType\>\&) | เรียกใช้ฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับทั่วไปและคืนค่าผลลัพธ์ต่ำสุด |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | กรององค์ประกอบของลำดับตามประเภทที่ระบุ |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<T, Key\>\&) | เรียงลำดับองค์ประกอบของลำดับในลำดับเพิ่มตามค่ากุญแจที่เลือกโดย keySelector |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<T, Key\>\&) | เรียงลำดับองค์ประกอบของลำดับในลำดับลดตามค่ากุญแจที่เลือกโดย keySelector |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | สลับลำดับขององค์ประกอบในลำดับ |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, ResultType\>\&) | แปลงองค์ประกอบของลำดับ |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, **int32_t**, ResultType\>\&) | แปลงแต่ละองค์ประกอบของลำดับเป็นรูปแบบใหม่โดยนำดัชนีขององค์ประกอบมาร่วม |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<T, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | โปรเจกต์แต่ละองค์ประกอบของลำดับและรวมลำดับผลลัพธ์เป็นหนึ่งลำดับ |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<Source, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | ข้ามจำนวนองค์ประกอบต่อเนื่องที่ระบุจากจุดเริ่มต้นของลำดับและคืนส่วนที่เหลือ |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | คืนจำนวนองค์ประกอบต่อเนื่องที่ระบุจากจุดเริ่มต้นของลำดับ |
| [System::ArrayPtr](../arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | สร้างอาร์เรย์จากลำดับ |
| [SharedPtr](../sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | สร้าง List<T> จากลำดับ |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | กรองลำดับตามตัวตรวจสอบที่ระบุ |
| void [Lock](../object/lock/)() | ใช้การล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ [LockContext](../lockcontext/) |
| [UnderlyingType](./underlyingtype/) [Max](./max/)() const | ค้นหาองค์ประกอบที่ใหญ่ที่สุดในอาร์เรย์โดยใช้ [operator<()](../operator_less/) เพื่อเปรียบเทียบองค์ประกอบ |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../object/memberwiseclone/) ทำให้สามารถโคลนประเภทที่กำหนดเองได้ |
| [UnderlyingType](./underlyingtype/) [Min](./min/)() const | ค้นหาองค์ประกอบที่เล็กที่สุดในอาร์เรย์โดยใช้ [operator<()](../operator_less/) เพื่อเปรียบเทียบองค์ประกอบ |
|  [Object](../object/object/)() | สร้างวัตถุ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../object/object/)([Object](../object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นออบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของคลาสย่อย |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | ตัวดำเนินการการกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นออบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของคลาสย่อย |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | ตัวดำเนินการการกำหนดค่าแบบย้าย |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | ตัวดำเนินการการกำหนดค่าแบบย้าย |
| [UnderlyingType](./underlyingtype/)\& [operator[]](./operator[]/)(int) | คืนค่าสิ่งที่อยู่ที่ดัชนีที่ระบุ |
| [UnderlyingType](./underlyingtype/) const\& [operator[]](./operator[]/)(int) const | คืนค่าสิ่งที่อยู่ที่ดัชนีที่ระบุ |
| void * [raw_data_ptr](./raw_data_ptr/)() override | คืนค่าตัวชี้ไปยังองค์ประกอบแรกของอาร์เรย์มิติเดียว สำหรับอาร์เรย์หลายมิตผลลัพธ์ไม่กำหนด |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | คืนค่าอิเทอเรเตอร์ย้อนกลับไปยังองค์ประกอบแรกของคอนเทนเนอร์ที่ถูกย้อนกลับ ซึ่งตรงกับองค์ประกอบสุดท้ายของคอนเทนเนอร์ปกติ หากคอนเทนเนอร์ว่างอิเทอเรเตอร์ที่คืนค่าจะเท่ากับ [rend()](./rend/) |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | คืนค่าอิตาเรเตอร์ย้อนกลับไปยังองค์ประกอบแรกของคอนเทนเนอร์ที่กลับด้าน ซึ่งสอดคล้องกับองค์ประกอบสุดท้ายของคอนเทนเนอร์ที่ไม่กลับด้าน หากคอนเทนเนอร์ว่าง อิตาเรเตอร์ที่คืนค่าจะเท่ากับ [rend()](./rend/). |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | เปรียบเทียบวัตถุตามการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุตามการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจ็กต์ชนิดค่าด้วยการอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | การกำหนดเฉพาะของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | การกำหนดเฉพาะของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริงหลายตัว. |
| **bool** [Remove](./remove/)(const T\&) override | ไม่รองรับเนื่องจากอาร์เรย์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันเป็นแบบอ่านอย่างเดียว. |
| void [RemoveAt](./removeat/)(int) override | ไม่รองรับเนื่องจากอาร์เรย์ที่แสดงโดยอ็อบเจ็กต์ปัจจุบันเป็นแบบอ่านอย่างเดียว. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | คืนค่าอิตาเรเตอร์ย้อนกลับไปยังองค์ประกอบที่อยู่ถัดจากองค์ประกอบสุดท้ายของคอนเทนเนอร์ที่กลับด้าน ซึ่งสอดคล้องกับองค์ประกอบที่มาก่อนองค์ประกอบแรกของคอนเทนเนอร์ที่ไม่กลับด้าน องค์ประกอบนี้ทำหน้าที่เป็นตัวแทนตำแหน่ง หากพยายามเข้าถึงจะทำให้เกิดพฤติกรรมที่ไม่ได้กำหนด. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | คืนค่าอิตาเรเตอร์ย้อนกลับไปยังองค์ประกอบที่อยู่ถัดจากองค์ประกอบสุดท้ายของคอนเทนเนอร์ที่กลับด้าน ซึ่งสอดคล้องกับองค์ประกอบที่มาก่อนองค์ประกอบแรกของคอนเทนเนอร์ที่ไม่กลับด้าน องค์ประกอบนี้ทำหน้าที่เป็นตัวแทนตำแหน่ง หากพยายามเข้าถึงจะทำให้เกิดพฤติกรรมที่ไม่ได้กำหนด. |
| static void [Resize](./resize/)([ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int) | เปลี่ยนขนาดของอาร์เรย์ที่ระบุเป็นค่าที่ระบุหรือสร้างอาร์เรย์ใหม่ด้วยขนาดที่ระบุ. |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | กลับลำดับขององค์ประกอบในอาร์เรย์ที่ระบุ. |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | กลับลำดับช่วงขององค์ประกอบในอาร์เรย์ที่ระบุ. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | ทำให้อาร์เรย์ถือว่าตัวชี้ที่เก็บเป็นแบบอ่อน (ถ้าใช้ได้). |
| void [SetValue](./setvalue/)(const T\&, int) | กำหนดค่าขององค์ประกอบที่ตำแหน่งที่ระบุ. |
| int [SharedCount](../object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แชร์ ควรไม่เรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงที่แชร์และคืนค่า ควรไม่เรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector แทน. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | จัดเรียงองค์ประกอบในอาร์เรย์ที่ระบุโดยใช้ตัวเปรียบเทียบค่าเริ่มต้น. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | จัดเรียงช่วงขององค์ประกอบในอาร์เรย์ที่ระบุโดยใช้ตัวเปรียบเทียบค่าเริ่มต้น. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) | จัดเรียบองค์ประกอบในอาร์เรย์ที่ระบุโดยใช้ตัวเปรียบเทียบที่ระบุ. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Y\>\>\&) | ยังไม่ได้ทำการใช้งาน. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [System::Comparison](../comparison/)\<T\>\&) | จัดเรียงองค์ประกอบในอาร์เรย์ที่ระบุโดยใช้การเปรียบเทียบที่ระบุ. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&) | จัดเรียงสองอาร์เรย์ หนึ่งอาร์เรย์ที่เก็บคีย์และอีกอาร์เรย์ที่เก็บรายการที่สอดคล้องกัน โดยอ้างอิงจากค่าของอาร์เรย์ที่เก็บคีย์ ซึ่งองค์ประกอบของอาร์เรย์นั้นจะถูกเปรียบเทียบโดยใช้ operator<. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&, int, int) | จัดเรียงสองอาร์เรย์ หนึ่งอาร์เรย์ที่เก็บคีย์และอีกอาร์เรย์ที่เก็บรายการที่สอดคล้องกัน โดยอ้างอิงจากค่าของอาร์เรย์ที่เก็บคีย์ ซึ่งองค์ประกอบของอาร์เรย์นั้นจะถูกเปรียบเทียบโดยใช้ตัวเปรียบเทียบค่าเริ่มต้น. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | เป็นอเนกแบบของเมธอด C# [Object.ToString()](../object/tostring/) ทำให้สามารถแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้. |
| static **bool** [TrueForAll](./trueforall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | กำหนดว่าทั้งหมดขององค์ประกอบในอาร์เรย์ที่ระบุเป็นไปตามเงื่อนไขที่กำหนดโดยพริดิกา (predicate) ที่ระบุหรือไม่. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | ทำหน้าที่เป็นการสร้าง typeof([System.Object](../object/)) trong C#. |
| void [Unlock](../object/unlock/)() | ทำการปลดล็อกคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/). |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | รับการทำงานของ begin const iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | รับการทำงานของ begin iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | รับการทำงานของ end const iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | รับการทำงานของ end iterator สำหรับคอนเทนเนอร์ปัจจุบัน. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบอ่อน ควรไม่เรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบอ่อน ควรไม่เรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector แทน. |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | ตัวทำลาย. |
| virtual  [~Object](../object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## การกำหนดชนิด

| การกำหนด | คำอธิบาย |
| --- | --- |
| [ValueType](./valuetype/) | นามแฝงสำหรับประเภทขององค์ประกอบของอาร์เรย์. |
| [UnderlyingType](./underlyingtype/) | นามแฝงสำหรับประเภทที่ใช้แทนแต่ละองค์ประกอบของอาร์เรย์. |
| [EnumerablePtr](./enumerableptr/) | นามแฝงสำหรับประเภท smart pointer ที่ชี้ไปยังอ็อบเจ็กต์ IEnumerable ที่บรรจุองค์ประกอบชนิด **T**. |
| [EnumeratorPtr](./enumeratorptr/) | นามแฝงสำหรับประเภท smart pointer ที่ชี้ไปยังอ็อบเจ็กต์ IEnumerator ที่บรรจุองค์ประกอบชนิด **T**. |
| [iterator](./iterator/) | ประเภทอิตาเรเตอร์. |
| [const_iterator](./const_iterator/) | ประเภทอิตาเรเตอร์แบบคงที่. |
| [reverse_iterator](./reverse_iterator/) | ประเภทอิตาเรเตอร์ย้อนกลับ. |
| [const_reverse_iterator](./const_reverse_iterator/) | ประเภทอิตาเรเตอร์ย้อนกลับแบบคงที่. |

## หมายเหตุ

```cpp
#include <system/array.h>
#include <system/smart_ptr.h>

using namespace System;

void Print(const SmartPtr<Array<int32_t>> &arrayPtr)
{
  for (auto item: arrayPtr)
  {
    std::cout << item << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // สร้างและเติมข้อมูลในอาเรย์.
  auto arrayPtr = MakeObject<Array<int32_t>>(5, 0);
  for (auto i = 0; i < arrayPtr->get_Length(); ++i)
  {
    arrayPtr[i] = 5 - i;
  }

  // พิมพ์รายการในอาเรย์.
  Print(arrayPtr);

  // เรียงลำดับรายการในอาเรย์จากน้อยไปมาก.
  Array<int32_t>::Sort(arrayPtr);

  // พิมพ์รายการในอาเรย์.
  Print(arrayPtr);

  // พิมพ์จำนวนรายการในอาเรย์.
  std::cout << arrayPtr->get_Length() << std::endl;

  // พิมพ์ดัชนีของรายการที่มีค่าเท่ากับ 4.
  std::cout << arrayPtr->IndexOf(4) << std::endl;

  // ปรับขนาดอาเรย์.
  Array<int32_t>::Resize(arrayPtr, 3);

  // พิมพ์รายการในอาเรย์.
  Print(arrayPtr);

  return 0;
}
/*
ตัวอย่างโค้ดนี้สร้างผลลัพธ์ต่อไปนี้:
5 4 3 2 1
1 2 3 4 5
5
3
1 2 3
*/
```

## ดูเพิ่มเติม

* คลาส [ArrayBase](../arraybase/)
* คลาส [IList](../../system.collections.generic/ilist/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)