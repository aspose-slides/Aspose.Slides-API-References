---
title: ObjectExt
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: ให้เมธอดสถิติที่จำลองเมธอด Object ของ C# ที่เรียกใช้สำหรับประเภท C++ ที่ไม่ใช่ Object (สตริง, ตัวเลข ฯลฯ) นี่เป็นประเภทสถิติที่ไม่มีบริการของอินสแตนซ์ คุณไม่ควรสร้างอินสแตนซ์ของมันด้วยวิธีใด ๆ
type: docs
weight: 1145
url: /th/system/objectext/
---
## ObjectExt คลาส


ให้เมธอดสถิติเช่นเดียวกับเมธอด C# [Object](../object/) ที่เรียกใช้สำหรับประเภท C++ ที่ไม่ใช่ Object (สตริง, ตัวเลข, เป็นต้น) สิ่งนี้เป็นประเภทสถิติที่ไม่มีบริการของอินสแตนซ์ คุณไม่ควรสร้างอินสแตนซ์ของมันโดยวิธีใด ๆ

```cpp
class ObjectExt : public System::ObjectType
```

## เมธอด

| Method | Description |
| --- | --- |
| static std::enable_if<(std::is_fundamental\<To\>::value), std::array\<To, sizeof...(From)>\>::type [ArrayInitializerCast](./arrayinitializercast/)(From ...) | ทำการแปลงค่าพื้นฐานของอาเรย์ (ซึ่ง C# ทำโดยอัตโนมัติแต่ C++ ดูเหมือนว่าจะไม่ได้ทำ) |
| static std::enable_if\<std::is_enum\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | ทำการบรรจุประเภทค่าเพื่อแปลงเป็น [Object](../object/). การทำงานสำหรับประเภท enum |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | ทำการบรรจุประเภทค่าเพื่อแปลงเป็น [Object](../object/). การทำงานสำหรับประเภทที่ไม่ใช่ enum |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | ทำการบรรจุประเภท [Nullable](../nullable/) เพื่อแปลงเป็น [Object](../object/) |
| static [SmartPtr](../smartptr/)\<[Object](../object/)\> [Box](./box/)(const [String](../string/)\&) | ทำการบรรจุค่า string |
| static [SmartPtr](../smartptr/)\<[System::BoxedValueBase](../boxedvaluebase/)\> [BoxEnum](./boxenum/)(T) | ทำการบรรจุประเภท enum เพื่อถูกส่งต่อเป็น [Object](../object/) |
| static [SmartPtr](../smartptr/)\<[System::Collections::IList](../../system.collections/ilist/)\> [CastToIList](./casttoilist/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) |  |
| static auto [Coalesce](./coalesce/)(T0, T1) | การทำงานของการแปลโอเปอเรเตอร์ '??' สำหรับประเภทที่ไม่เป็น nullable |
| static T0 [Coalesce](./coalesce/)([System::Nullable](../nullable/)\<T0\>, T1) | การทำงานของการแปลโอเปอเรเตอร์ '??' สำหรับประเภท nullable |
| static auto [CoalesceAssign](./coalesceassign/)(T0\&, T1) | การทำงานของการแปลโอเปอเรเตอร์ '??=' |
| static std::conditional\<std::is_convertible\<RT2, RT1\>::value, RT1, RT2\>::type [CoalesceInternal](./coalesceinternal/)(RT1, F) | การทำงานของการแปลโอเปอเรเตอร์ '??' สำหรับประเภทที่ไม่เป็น nullable. การโอเวอร์โหลดสำหรับกรณีที่ RT2 สามารถแปลงเป็น RT1 |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) |  |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | การทดแทนการเรียก [Object.Equals](../object/equals/) ของ C# ที่ทำงานกับประเภทใดก็ได้ใน C++. การโอเวอร์โหลดสำหรับประเภท smart pointer |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(T, const T2\&) | การทดแทนการเรียก [Object.Equals](../object/equals/) ของ C# ที่ทำงานกับประเภทใดก็ได้ใน C++. การโอเวอร์โหลดสำหรับประเภทโครงสร้าง |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | การทดแทนการเรียก [Object.Equals](../object/equals/) ของ C# ที่ทำงานกับประเภทใดก็ได้ใน C++. การโอเวอร์โหลดสำหรับประเภทสเกลาร์ |
| static **bool** [Equals](./equals/)(const char_t(&), [String](../string/)) | การทดแทนการเรียก [Object.Equals](../object/equals/) ของ C# ที่ทำงานกับประเภทใดก็ได้ใน C++. การโอเวอร์โหลดสำหรับสตริงลิเทรัลโดยใช้การเปรียบเทียบสตริง |
| static **bool** [Equals](./equals/)(const **float**\&, const **float**\&) | จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C# ที่ NaN สองค่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](./equals/)(const **double**\&, const **double**\&) | จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C# ที่ NaN สองค่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static std::enable_if\<[System::IsSmartPtr](../issmartptr/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static int [GetHashCode](./gethashcode/)(const T\&) | ทำการทำงานของการเรียก [GetHashCode()](./gethashcode/); ทำงานได้กับทั้ง subclass ของ [Object](../object/) และประเภทที่ไม่เกี่ยวข้อง |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | ทำการแปล typeof() . การโอเวอร์โหลดสำหรับ smart pointer |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | ทำการแปล typeof() . การโอเวอร์โหลดสำหรับโครงสร้าง |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | ทำการแปล typeof() . การโอเวอร์โหลดสำหรับข้อยกเว้น |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | ทำการแปล typeof() . การโอเวอร์โหลดสำหรับประเภทพื้นฐาน |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | ทำการแปล typeof() . การโอเวอร์โหลดสำหรับประเภท [Nullable](../nullable/) |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | ทำการแปล typeof() . การโอเวอร์โหลดสำหรับประเภทพื้นฐาน |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | ทำการแปล typeof() . การโอเวอร์โหลดสำหรับประเภท enum |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | ทำการแปล typeof() . การโอเวอร์โหลดสำหรับโครงสร้างและพอยน์เตอร์ |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | ทำการแปล typeof() . การโอเวอร์โหลดสำหรับ [Nullable](../nullable/) |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | ทำการแปล typeof() . การโอเวอร์โหลดสำหรับ MutlicastDelegate |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | ทำการแปล typeof() . การโอเวอร์โหลดสำหรับโครงสร้างและพอยน์เตอร์ |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)(const [String](../string/)\&) | ทำการแปล typeof() . การโอเวอร์โหลดสำหรับประเภทสตริง |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | ทำการแปล typeof() . การโอเวอร์โหลดสำหรับ **uint8_t** |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | ทำการแปล typeof() . การโอเวอร์โหลดสำหรับ **uint8_t** |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | ทำการแปล typeof() . การโอเวอร์โหลดสำหรับ **uint8_t** |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | ทำการแปล typeof() . การโอเวอร์โหลดสำหรับ **uint8_t** |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | ทำการแปล typeof() . การโอเวอร์โหลดสำหรับ **uint8_t** |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | ทำการแปล typeof() . การโอเวอร์โหลดสำหรับ **uint8_t** |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, **bool**\>::type [Is](./is/)(const T\&) | ทำการแปลโอเปอเรเตอร์ 'is'. การเจาะจงสำหรับประเภทที่สามารถบรรจุ (value) ซึ่งจริง ๆ แล้วคือประเภทนั้น |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | ทำการแปลโอเปอเรเตอร์ 'is'. การเจาะจงสำหรับประเภทพอยน์เตอร์ที่ถูกปรับให้เหมาะกับคลาส 'final' |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&\!std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | ทำการแปลโอเปอเรเตอร์ 'is'. การเจาะจงสำหรับประเภทพอยน์เตอร์ |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | ทำการแปลโอเปอเรเตอร์ 'is'. การเจาะจงสำหรับประเภท value |
| static std::enable_if<\!std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | ทำการแปลโอเปอเรเตอร์ 'is'. การเจาะจงสำหรับประเภทที่ไม่สามารถแปลงได้ |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | ทำการแปลโอเปอเรเตอร์ 'is'. การเจาะจงสำหรับประเภทพอยน์เตอร์ |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Is](./is/)(const [ExceptionWrapper](../exceptionwrapper/)\<U\>\&) | ทำการแปลโอเปอเรเตอร์ 'is'. การเจาะจงสำหรับประเภท wrapper ของข้อยกเว้น |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | ทำการแปลโอเปอเรเตอร์ 'is'. การเจาะจงสำหรับประเภท nullable |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | ทำการแปลโอเปอเรเตอร์ 'is'. การเจาะจงสำหรับประเภทที่สามารถบรรจุที่มีการกำหนดโอเปอเรเตอร์ == |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | ทำการแปลโอเปอเรเตอร์ 'is'. การเจาะจงสำหรับประเภทที่สามารถบรรจุที่ไม่มีการกำหนด == |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!std::is_same\<V, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<V\>\&) | ทำการแปลโอเปอเรเตอร์ 'is'. การเจาะจงสำหรับประเภท value ที่บรรจุเป็นอินเทอร์เฟซ |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | ทำการแปลโอเปอเรเตอร์ 'is'. การเจาะจงสำหรับประเภท enum |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [WeakPtr](../weakptr/)\<U\>\&) | ทำการแปลโอเปอเรเตอร์ 'is'. การเจาะจงสำหรับประเภท enum กับ weak pointer |
| static **bool** [Is](./is/)(const [Nullable](../nullable/)\<U\>\&) | ทำการแปลโอเปอเรเตอร์ 'is'. การเจาะจงสำหรับประเภท [Nullable](../nullable/) |
| static **bool** [Is](./is/)(const char16_t *) | ทำการแปลโอเปอเรเตอร์ 'is'. การเจาะจงสำหรับสตริงลิเทรัล |
| static **bool** [Is](./is/)(**int32_t**) | ทำการแปลโอเปอเรเตอร์ 'is'. การเจาะจงสำหรับจำนวนเต็มลิเทรัล |
| static **bool** [IsBoxedValue](./isboxedvalue/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | ตรวจสอบว่าอ็อบเจกต์เป็นค่าแบบบรรจุหรือไม่ |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | แปลง [Object](../object/) เป็นประเภทที่ไม่ทราบค่า, โดยจัดการทั้งประเภท smart pointer และสถานการณ์ค่าที่บรรจุ |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | แปลง [Object](../object/) เป็นประเภทที่ไม่ทราบค่า, โดยจัดการทั้งประเภท smart pointer และสถานการณ์ค่าที่บรรจุ |
| static [String](../string/) [ToString](./tostring/)(const char_t *) | การทดแทนเมธอด C# ToString เพื่อทำงานกับประเภท C++ ใด ๆ |
| static [String](../string/) [ToString](./tostring/)(const [Nullable](../nullable/)\<T\>\&) | การทดแทนเมธอด C# ToString เพื่อทำงานกับประเภท C++ ใด ๆ |
| static std::enable_if\<std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | การทดแทนเมธอด C# ToString เพื่อทำงานกับประเภท C++ ใด ๆ |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | การทดแทนเมธอด C# ToString เพื่อทำงานกับประเภท C++ ใด ๆ |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value||std::is_pointer\<T\>::value||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | การทดแทนเมธอด C# ToString เพื่อทำงานกับประเภท C++ ใด ๆ |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | การทดแทนเมธอด C# ToString เพื่อทำงานกับประเภท C++ ใด ๆ |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | การทดแทนเมธอด C# ToString เพื่อทำงานกับประเภท C++ ใด ๆ |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | การทดแทนเมธอด C# ToString เพื่อทำงานกับประเภท C++ ใด ๆ |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | การทดแทนเมธอด C# ToString เพื่อทำงานกับประเภท C++ ใด ๆ |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_reference\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | การทดแทนเมธอด C# ToString เพื่อทำงานกับประเภท C++ ใด ๆ |
| static std::enable_if\<std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | แยกบรรจุประเภท value หลังจากแปลงเป็น [Object](../object/). การทำงานสำหรับประเภท enum |
| static std::enable_if<\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | แยกบรรจุประเภท value หลังจากแปลงเป็น [Object](../object/). การทำงานสำหรับประเภทที่ไม่ใช่ enum & ไม่เป็น nullable |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | แยกบรรจุประเภท value หลังจากแปลงเป็น [Object](../object/). การทำงานสำหรับประเภทที่ไม่ใช่ enum & ไม่เป็น nullable |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::numeric_limits\<T\>::is_integer, T\>::type [Unbox](./unbox/)(E) | แยกบรรจุประเภท enum เป็นจำนวนเต็ม |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(E) | แปลงประเภท enum |
| static [String](../string/) [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | แยกบรรจุค่า string |
| static [String](../string/) [UnboxStringSafe](./unboxstringsafe/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | แยกบรรจุ string จากค่าแบบบรรจุ |
| static [Nullable](../nullable/)\<T\> [UnboxToNullable](./unboxtonullable/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | แยกบรรจุอ็อบเจกต์เป็นประเภท nullable |
| static std::enable_if<\!std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | ตรวจสอบว่าอ็อบเจกต์ประเภทที่ไม่ทราบค่ามีค่า nullptr หรือไม่ (สำหรับประเภทที่ไม่เป็นสเกลาร์) |
| static std::enable_if\<std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | ตรวจสอบว่าอ็อบเจกต์ประเภทที่ไม่ทราบค่ามีค่า nullptr หรือไม่ (สำหรับประเภทสเกลาร์) |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(T) | แปลงประเภทที่ไม่ทราบค่าเป็น [Object](../object/), โดยจัดการทั้งประเภท smart pointer และประเภท value |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(const T\&) | แปลงประเภทที่ไม่ทราบค่าเป็น [Object](../object/), โดยจัดการทั้งประเภท smart pointer และประเภท value |

## ดูเพิ่มเติม

* คลาส [ObjectType](../objecttype/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)