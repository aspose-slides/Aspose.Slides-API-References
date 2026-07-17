---
title: ObjectExt
second_title: Aspose.Slides for C++ API 参考
description: 提供静态方法，模拟对非 Object C++ 类型（字符串、数字等）的 C# Object 方法调用。这是一个没有实例服务的静态类型。无论何种方式都不应创建其实例。
type: docs
weight: 1132
url: /zh/system/objectext/
---
## ObjectExt 类

Provides static methods that emulate C# [Object](../object/) methods called for non-Object C++ types (strings, numbers, etc.). This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class ObjectExt : public System::ObjectType
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static std::enable_if<(std::is_fundamental\<To\>::value), std::array\<To, sizeof...(From)>\>::type [ArrayInitializerCast](./arrayinitializercast/)(From ...) | 将数组的基本值进行转换（C# 隐式执行，但 C++ 显然未执行）。 |
| static std::enable_if\<std::is_enum\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | 将值类型装箱以转换为 [Object](../object/)。针对枚举类型的实现。 |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | 将值类型装箱以转换为 [Object](../object/)。针对非枚举类型的实现。 |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | 将 [Nullable](../nullable/) 类型装箱以转换为 [Object](../object/)。 |
| static [SmartPtr](../smartptr/)\<[Object](../object/)\> [Box](./box/)(const [String](../string/)\&) | 装箱字符串值。 |
| static [SmartPtr](../smartptr/)\<[System::BoxedValueBase](../boxedvaluebase/)\> [BoxEnum](./boxenum/)(T) | 将枚举类型装箱以传播为 [Object](../object/)。 |
| static [SmartPtr](../smartptr/)\<[System::Collections::IList](../../system.collections/ilist/)\> [CastToIList](./casttoilist/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) |  |
| static auto [Coalesce](./coalesce/)(T0, T1) | 实现对非可空类型的 '??' 运算符翻译。 |
| static T0 [Coalesce](./coalesce/)([System::Nullable](../nullable/)\<T0\>, T1) | 实现对可空类型的 '??' 运算符翻译。 |
| static auto [CoalesceAssign](./coalesceassign/)(T0\&, T1) | 实现对 '??=' 运算符的翻译。 |
| static std::conditional\<std::is_convertible\<RT2, RT1\>::value, RT1, RT2\>::type [CoalesceInternal](./coalesceinternal/)(RT1, F) | 实现对非可空类型的 '??' 运算符翻译。针对 RT2 可转换为 RT1 的情况的重载。 |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) |  |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | 对 C# [Object.Equals](../object/equals/) 调用的替代，适用于 C++ 中的任何类型。针对智能指针类型的重载。 |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(T, const T2\&) | 对 C# [Object.Equals](../object/equals/) 调用的替代，适用于 C++ 中的任何类型。针对结构体类型的重载。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | 对 C# [Object.Equals](../object/equals/) 调用的替代，适用于 C++ 中的任何类型。针对标量类型的重载。 |
| static **bool** [Equals](./equals/)(const char_t(&), [String](../string/)) | 对 C# [Object.Equals](../object/equals/) 调用的替代，适用于 C++ 中的任何类型。针对使用字符串比较的字符串文字的重载。 |
| static **bool** [Equals](./equals/)(const **float**\&, const **float**\&) | 模拟 C# 式的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN 本身。 |
| static **bool** [Equals](./equals/)(const **double**\&, const **double**\&) | 模拟 C# 式的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN 本身。 |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static std::enable_if\<[System::IsSmartPtr](../issmartptr/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static int [GetHashCode](./gethashcode/)(const T\&) | 实现 [GetHashCode()](./gethashcode/) 调用；可用于 [Object](../object/) 子类以及不相关的类型。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | 实现 typeof() 的翻译。针对智能指针的重载。 |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | 实现 typeof() 的翻译。针对结构体的重载。 |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | 实现 typeof() 的翻译。针对异常的重载。 |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | 实现 typeof() 的翻译。针对原始类型的重载。 |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | 实现 typeof() 的翻译。针对 [Nullable](../nullable/) 类型的重载。 |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | 实现 typeof() 的翻译。针对原始类型的重载。 |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | 实现 typeof() 的翻译。针对枚举类型的重载。 |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | 实现 typeof() 的翻译。针对结构体和指针的重载。 |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | 实现 typeof() 的翻译。针对 [Nullable](../nullable/) 的重载。 |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | 实现 typeof() 的翻译。针对 MulticastDelegate 的重载。 |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | 实现 typeof() 的翻译。针对结构体和指针的重载。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)(const [String](../string/)\&) | 实现 typeof() 的翻译。针对字符串类型的重载。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | 实现 typeof() 的翻译。针对 **uint8_t** 的重载。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | 实现 typeof() 的翻译。针对 **uint8_t** 的重载。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | 实现 typeof() 的翻译。针对 **uint8_t** 的重载。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | 实现 typeof() 的翻译。针对 **uint8_t** 的重载。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | 实现 typeof() 的翻译。针对 **uint8_t** 的重载。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | 实现 typeof() 的翻译。针对 **uint8_t** 的重载。 |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, **bool**\>::type [Is](./is/)(const T\&) | 实现 'is' 运算符的翻译。针对可装箱（值）类型的特化，其正是它们本身。 |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | 实现 'is' 运算符的翻译。针对针对 'final' 类的指针类型的特化优化。 |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&\!std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | 实现 'is' 运算符的翻译。针对指针类型的特化。 |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | 实现 'is' 运算符的翻译。针对值类型的特化。 |
| static std::enable_if<\!std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | 实现 'is' 运算符的翻译。针对不可转换类型的特化。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | 实现 'is' 运算符的翻译。针对指针类型的特化。 |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Is](./is/)(const [ExceptionWrapper](../exceptionwrapper/)\<U\>\&) | 实现 'is' 运算符的翻译。针对异常包装类型的特化。 |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 实现 'is' 运算符的翻译。针对可空类型的特化。 |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 实现 'is' 运算符的翻译。针对已定义 == 运算符的可装箱类型的特化。 |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 实现 'is' 运算符的翻译。针对未定义 == 运算符的可装箱类型的特化。 |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!std::is_same\<V, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<V\>\&) | 实现 'is' 运算符的翻译。针对装箱为接口的值类型的特化。 |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | 实现 'is' 运算符的翻译。针对枚举类型的特化。 |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [WeakPtr](../weakptr/)\<U\>\&) | 实现 'is' 运算符的翻译。针对枚举类型与弱指针的特化。 |
| static **bool** [Is](./is/)(const [Nullable](../nullable/)\<U\>\&) | 实现 'is' 运算符的翻译。针对 [Nullable](../nullable/) 类型的特化。 |
| static **bool** [Is](./is/)(const char16_t *) | 实现 'is' 运算符的翻译。针对字符串文字的特化。 |
| static **bool** [Is](./is/)(**int32_t**) | 实现 'is' 运算符的翻译。针对整数文字的特化。 |
| static **bool** [IsBoxedValue](./isboxedvalue/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 检查对象是否为装箱值。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | 将 [Object](../object/) 转换为未知类型，处理智能指针类型和已装箱值的情况。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | 将 [Object](../object/) 转换为未知类型，处理智能指针类型和装箱值的情况。 |
| static [String](../string/) [ToString](./tostring/)(const char_t *) | 对 C# ToString 方法的替代，使其在任何 C++ 类型上工作。 |
| static [String](../string/) [ToString](./tostring/)(const [Nullable](../nullable/)\<T\>\&) | 对 C# ToString 方法的替代，使其在任何 C++ 类型上工作。 |
| static std::enable_if\<std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | 对 C# ToString 方法的替代，使其在任何 C++ 类型上工作。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | 对 C# ToString 方法的替代，使其在任何 C++ 类型上工作。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value||std::is_pointer\<T\>::value||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | 对 C# ToString 方法的替代，使其在任何 C++ 类型上工作。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | 对 C# ToString 方法的替代，使其在任何 C++ 类型上工作。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | 对 C# ToString 方法的替代，使其在任何 C++ 类型上工作。 |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | 对 C# ToString 方法的替代，使其在任何 C++ 类型上工作。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | 对 C# ToString 方法的替代，使其在任何 C++ 类型上工作。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_reference\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | 对 C# ToString 方法的替代，使其在任何 C++ 类型上工作。 |
| static std::enable_if\<std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 在转换为 [Object](../object/) 后解箱值类型。针对枚举类型的实现。 |
| static std::enable_if<\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 在转换为 [Object](../object/) 后解箱值类型。针对非枚举且非可空类型的实现。 |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 在转换为 [Object](../object/) 后解箱值类型。针对非枚举且非可空类型的实现。 |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::numeric_limits\<T\>::is_integer, T\>::type [Unbox](./unbox/)(E) | 将枚举类型解箱为整数。 |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(E) | 转换枚举类型。 |
| static [String](../string/) [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 解箱字符串值。 |
| static [String](../string/) [UnboxStringSafe](./unboxstringsafe/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 从装箱值中解箱字符串。 |
| static [Nullable](../nullable/)\<T\> [UnboxToNullable](./unboxtonullable/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | 将对象解箱为可空类型。 |
| static std::enable_if<\!std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | 检查未知类型对象是否为 nullptr。针对非标量类型的重载。 |
| static std::enable_if\<std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | 检查未知类型对象是否为 nullptr。针对标量类型的重载。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(T) | 将未知类型转换为 [Object](../object/)，同时处理智能指针类型和数值类型的情况。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(const T\&) | 将未知类型转换为 [Object](../object/)，同时处理智能指针类型和数值类型的情况。 |

## 另见

* 类 [ObjectType](../objecttype/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)