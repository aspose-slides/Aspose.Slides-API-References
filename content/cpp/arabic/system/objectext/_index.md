---
title: ObjectExt
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يوفر طرقًا ثابتة تحاكي طرق C# Object التي تُستدعى لأنواع C++ غير الكائن (السلاسل، الأعداد، إلخ). هذا نوع ثابت لا يحتوي على خدمات مثيل. يجب ألا تقوم بإنشاء مثيلات له بأي وسيلة.
type: docs
weight: 1145
url: /ar/system/objectext/
---
## فئة ObjectExt

توفر طرقًا ثابتة تحاكي طرق C# [Object](../object/) التي تُستدعى لأنواع C++ غير-الكائن (السلاسل، الأعداد، إلخ). هذا نوع ثابت لا يملك خدمات مثيل. يجب ألا تقوم بإنشاء مثيلات له بأي وسيلة.

```cpp
class ObjectExt : public System::ObjectType
```

## طرق

| الطريقة | الوصف |
| --- | --- |
| static std::enable_if<(std::is_fundamental\<To\>::value), std::array\<To, sizeof...(From)>\>::type [ArrayInitializerCast](./arrayinitializercast/)(From ...) | يحوِّل قيم أساسية للمصفوفة (التي يقوم C# بتحويلها ضمنيًا لكن C++ لا يبدو أنه يفعل ذلك). |
| static std::enable_if\<std::is_enum\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | يُغلف الأنواع القيمية لتحويلها إلى [Object](../object/). تنفيذ لأنواع التعداد. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | يُغلف الأنواع القيمية لتحويلها إلى [Object](../object/). تنفيذ للأنواع غير التعددية. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | يُغلف الأنواع [Nullable](../nullable/) لتحويلها إلى [Object](../object/). |
| static [SmartPtr](../smartptr/)\<[Object](../object/)\> [Box](./box/)(const [String](../string/)\&) | يُغلف قيم السلاسل. |
| static [SmartPtr](../smartptr/)\<[System::BoxedValueBase](../boxedvaluebase/)\> [BoxEnum](./boxenum/)(T) | يُغلف الأنواع التعددية لتُنشر كـ [Object](../object/). |
| static [SmartPtr](../smartptr/)\<[System::Collections::IList](../../system.collections/ilist/)\> [CastToIList](./casttoilist/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) |  |
| static auto [Coalesce](./coalesce/)(T0, T1) | تنفيذ ترجمة عامل '??' للأنواع غير القابلة للفراغ. |
| static T0 [Coalesce](./coalesce/)([System::Nullable](../nullable/)\<T0\>, T1) | تنفيذ ترجمة عامل '??' للأنواع القابلة للفراغ. |
| static auto [CoalesceAssign](./coalesceassign/)(T0\&, T1) | تنفيذ ترجمة عامل '??=' . |
| static std::conditional\<std::is_convertible\<RT2, RT1\>::value, RT1, RT2\>::type [CoalesceInternal](./coalesceinternal/)(RT1, F) | تنفيذ ترجمة عامل '??' للأنواع غير القابلة للفراغ. تحميل زائدة للحالة إذا كان RT2 قابلًا للتحويل إلى RT1. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) |  |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | استبدال لاستدعاءات C# [Object.Equals](../object/equals/) التي تعمل لأي نوع في C++. تحميل زائدة لأنواع المؤشرات الذكية. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(T, const T2\&) | استبدال لاستدعاءات C# [Object.Equals](../object/equals/) التي تعمل لأي نوع في C++. تحميل زائدة لأنواع البنى. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | استبدال لاستدعاءات C# [Object.Equals](../object/equals/) التي تعمل لأي نوع في C++. تحميل زائدة لأنواع القيم الأولية. |
| static **bool** [Equals](./equals/)(const char_t(&), [String](../string/)) | استبدال لاستدعاءات C# [Object.Equals](../object/equals/) التي تعمل لأي نوع في C++. تحميل زائدة للمتن الحرفي مع مقارنة السلاسل. |
| static **bool** [Equals](./equals/)(const **float**\&, const **float**\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث يُعتبر NaNانان متساويين رغم أن معيار IEC 60559:1989 ينص على أن NaN لا يساوي أي قيمة، بما فيها NaN. |
| static **bool** [Equals](./equals/)(const **double**\&, const **double**\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث يُعتبر NaNانان متساويين رغم أن معيار IEC 60559:1989 ينص على أن NaN لا يساوي أي قيمة، بما فيها NaN. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static std::enable_if\<[System::IsSmartPtr](../issmartptr/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static int [GetHashCode](./gethashcode/)(const T\&) | يُنفّذ استدعاءات [GetHashCode()](./gethashcode/)؛ يعمل على كل من الفئات الفرعية [Object](../object/) والأنواع غير المرتبطة. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | يُنفّذ ترجمة typeof(). تحميل زائدة للمؤشرات الذكية. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | يُنفّذ ترجمة typeof(). تحميل زائدة للبنى. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | يُنفّذ ترجمة typeof(). تحميل زائدة للاستثناءات. |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | يُنفّذ ترجمة typeof(). تحميل زائدة للأنواع الأولية. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | يُنفّذ ترجمة typeof(). تحميل زائدة لأنواع [Nullable](../nullable/). |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | يُنفّذ ترجمة typeof(). تحميل زائدة للأنواع الأولية. |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | يُنفّذ ترجمة typeof(). تحميل زائدة لأنواع التعداد. |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | يُنفّذ ترجمة typeof(). تحميل زائدة للبنى والمؤشرات. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | يُنفّذ ترجمة typeof(). تحميل زائدة لـ [Nullable](../nullable/). |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | يُنفّذ ترجمة typeof(). تحميل زائدة لـ MutlicastDelegate. |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | يُنفّذ ترجمة typeof(). تحميل زائدة للبنى والمؤشرات. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)(const [String](../string/)\&) | يُنفّذ ترجمة typeof(). تحميل زائدة لنوع السلسلة. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | يُنفّذ ترجمة typeof(). تحميل زائدة لنوع **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | يُنفّذ ترجمة typeof(). تحميل زائدة لنوع **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | يُنفّذ ترجمة typeof(). تحميل زائدة لنوع **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | يُنفّذ ترجمة typeof(). تحميل زائدة لنوع **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | يُنفّذ ترجمة typeof(). تحميل زائدة لنوع **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | يُنفّذ ترجمة typeof(). تحميل زائدة لنوع **uint8_t**. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, **bool**\>::type [Is](./is/)(const T\&) | Implements 'is' operator translation. Specialization for boxable (value) types which exactly is that they are. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | Implements 'is' operator translation. Specialization for pointer types optimized for 'final' classes. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&\!std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | Implements 'is' operator translation. Specialization for pointer types. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | Implements 'is' operator translation. Specialization for value types. |
| static std::enable_if<\!std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | Implements 'is' operator translation. Specialization for unconvertible types. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | Implements 'is' operator translation. Specialization for pointer types. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Is](./is/)(const [ExceptionWrapper](../exceptionwrapper/)\<U\>\&) | Implements 'is' operator translation. Specialization for exception wrapper types. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Implements 'is' operator translation. Specialization for nullable types. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Implements 'is' operator translation. Specialization for boxable types with == operator defined. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Implements 'is' operator translation. Specialization for boxable types without defined ==. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!std::is_same\<V, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<V\>\&) | Implements 'is' operator translation. Specialization value types boxed to interfaces. |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | Implements 'is' operator translation. Specialization for enum types. |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [WeakPtr](../weakptr/)\<U\>\&) | Implements 'is' operator translation. Specialization for enum types vs weak pointers. |
| static **bool** [Is](./is/)(const [Nullable](../nullable/)\<U\>\&) | Implements 'is' operator translation. Specialization for [Nullable](../nullable/) type. |
| static **bool** [Is](./is/)(const char16_t *) | Implements 'is' operator translation. Specialization for string literal. |
| static **bool** [Is](./is/)(**int32_t**) | Implements 'is' operator translation. Specialization for integer literal. |
| static **bool** [IsBoxedValue](./isboxedvalue/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Checks if object is a boxed value. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | محول [Object](../object/) إلى نوع غير معروف، مع معالجة كل من نوع المؤشر الذكي وحالات القيمة المغلفة. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | محول [Object](../object/) إلى نوع غير معروف، مع معالجة كل من نوع المؤشر الذكي وحالات القيمة المغلفة. |
| static [String](../string/) [ToString](./tostring/)(const char_t *) | استبدال لطريقة C# ToString لتعمل على أي نوع C++. |
| static [String](../string/) [ToString](./tostring/)(const [Nullable](../nullable/)\<T\>\&) | استبدال لطريقة C# ToString لتعمل على أي نوع C++. |
| static std::enable_if\<std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | استبدال لطريقة C# ToString لتعمل على أي نوع C++. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | استبدال لطريقة C# ToString لتعمل على أي نوع C++. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value||std::is_pointer\<T\>::value||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | استبدال لطريقة C# ToString لتعمل على أي نوع C++. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | استبدال لطريقة C# ToString لتعمل على أي نوع C++. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | استبدال لطريقة C# ToString لتعمل على أي نوع C++. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | استبدال لطريقة C# ToString لتعمل على أي نوع C++. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | استبدال لطريقة C# ToString لتعمل على أي نوع C++. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_reference\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | استبدال لطريقة C# ToString لتعمل على أي نوع C++. |
| static std::enable_if\<std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Unboxes value types after converting to [Object](../object/). Implementation for enum types. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Unboxes value types after converting to [Object](../object/). Implementation for non-enum & non-nullable types. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Unboxes value types after converting to [Object](../object/). Implementation for non-enum & non-nullable types. |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::numeric_limits\<T\>::is_integer, T\>::type [Unbox](./unbox/)(E) | Unboxes enum types to integer. |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(E) | Converts enum types. |
| static [String](../string/) [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Unboxes string values. |
| static [String](../string/) [UnboxStringSafe](./unboxstringsafe/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Unboxes string from boxed value. |
| static [Nullable](../nullable/)\<T\> [UnboxToNullable](./unboxtonullable/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | Unboxes object to nullable type. |
| static std::enable_if<\!std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | Checks whether unknown type object is nullptr. Overload for non-scalar types. |
| static std::enable_if\<std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | Checks whether unknown type object is nullptr. Overload for scalar types. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(T) | Converts unknown type to [Object](../object/), handling both smart pointer type and value type situations. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(const T\&) | Converts unknown type to [Object](../object/), handling both smart pointer type and value type situations. |
## راجع أيضًا

* فئة [ObjectType](../objecttype/)
* مساحة أسماء [System](../)
* مكتبة [Aspose.Slides](../../)