---
title: ObjectExt
second_title: Справочник API Aspose.Slides для C++
description: Предоставляет статические методы, имитирующие методы C# Object, вызываемые для не-Object типов C++ (строки, числа и т.д.). Это статический тип без сервисов экземпляра. Вы никогда не должны создавать его экземпляры каким-либо способом.
type: docs
weight: 1132
url: /ru/system/objectext/
---
## ObjectExt класс

Предоставляет статические методы, которые имитируют методы C# [Object](../object/), вызываемые для не-Object типов C++ (строки, числа и т.д.). Это статический тип без сервисов экземпляра. Вы никогда не должны создавать его экземпляры каким-либо способом.

```cpp
class ObjectExt : public System::ObjectType
```

## Методы

| Метод | Описание |
| --- | --- |
| static std::enable_if<(std::is_fundamental\<To\>::value), std::array\<To, sizeof...(From)>\>::type [ArrayInitializerCast](./arrayinitializercast/)(From ...) | Преобразует фундаментальные значения массива (что C# делает неявно, но C++ очевидно нет). |
| static std::enable_if\<std::is_enum\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Упаковывает типы значений для преобразования в [Object](../object/). Реализация для перечислимых типов. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Упаковывает типы значений для преобразования в [Object](../object/). Реализация для неперечислимых типов. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Упаковывает типы [Nullable](../nullable/) для преобразования в [Object](../object/). |
| static [SmartPtr](../smartptr/)\<[Object](../object/)\> [Box](./box/)(const [String](../string/)\&) | Упаковывает строковые значения. |
| static [SmartPtr](../smartptr/)\<[System::BoxedValueBase](../boxedvaluebase/)\> [BoxEnum](./boxenum/)(T) | Упаковывает перечислимые типы для распространения как [Object](../object/). |
| static [SmartPtr](../smartptr/)\<[System::Collections::IList](../../system.collections/ilist/)\> [CastToIList](./casttoilist/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) |  |
| static auto [Coalesce](./coalesce/)(T0, T1) | Реализация перевода оператора '??' для типов, не допускающих null. |
| static T0 [Coalesce](./coalesce/)([System::Nullable](../nullable/)\<T0\>, T1) | Реализация перевода оператора '??' для nullable типов. |
| static auto [CoalesceAssign](./coalesceassign/)(T0\&, T1) | Реализация перевода оператора '??=' . |
| static std::conditional\<std::is_convertible\<RT2, RT1\>::value, RT1, RT2\>::type [CoalesceInternal](./coalesceinternal/)(RT1, F) | Реализация перевода оператора '??' для не-nullable типов. Перегрузка для случая, когда RT2 преобразуем к RT1. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) |  |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | Подстановка для вызовов C# [Object.Equals](../object/equals/), работающих с любым типом в C++. Перегрузка для типов умных указателей. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(T, const T2\&) | Подстановка для вызовов C# [Object.Equals](../object/equals/), работающих с любым типом в C++. Перегрузка для структурных типов. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | Подстановка для вызовов C# [Object.Equals](../object/equals/), работающих с любым типом в C++. Перегрузка для скалярных типов. |
| static **bool** [Equals](./equals/)(const char_t(&), [String](../string/)) | Подстановка для вызовов C# [Object.Equals](../object/equals/), работающих с любым типом в C++. Перегрузка для строковых литералов со строковым сравнением. |
| static **bool** [Equals](./equals/)(const **float**\&, const **float**\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](./equals/)(const **double**\&, const **double**\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static std::enable_if\<[System::IsSmartPtr](../issmartptr/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static int [GetHashCode](./gethashcode/)(const T\&) | Реализует вызовы [GetHashCode()](./gethashcode/); работает как с подклассами [Object](../object/), так и с несвязанными типами. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Реализует перевод typeof(). Перегрузка для умных указателей. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Реализует перевод typeof(). Перегрузка для структур. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Реализует перевод typeof(). Перегрузка для исключений. |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | Реализует перевод typeof(). Перегрузка для примитивных типов. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | Реализует перевод typeof(). Перегрузка для типов [Nullable](../nullable/). |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Реализует перевод typeof(). Перегрузка для примитивных типов. |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Реализует перевод typeof(). Перегрузка для перечислимых типов. |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Реализует перевод typeof(). Перегрузка для структур и указателей. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Реализует перевод typeof(). Перегрузка для [Nullable](../nullable/). |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Реализует перевод typeof(). Перегрузка для MutlicastDelegate. |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Реализует перевод typeof(). Перегрузка для структур и указателей. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)(const [String](../string/)\&) | Реализует перевод typeof(). Перегрузка для строкового типа. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Реализует перевод typeof(). Перегрузка для **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Реализует перевод typeof(). Перегрузка для **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Реализует перевод typeof(). Перегрузка для **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Реализует перевод typeof(). Перегрузка для **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Реализует перевод typeof(). Перегрузка для **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Реализует перевод typeof(). Перегрузка для **uint8_t**. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, **bool**\>::type [Is](./is/)(const T\&) | Реализует перевод оператора 'is'. Специализация для упаковываемых (value) типов, которые именно таковы. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | Реализует перевод оператора 'is'. Специализация для указательных типов, оптимизированных для классов 'final'. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&\!std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | Реализует перевод оператора 'is'. Специализация для указательных типов. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | Реализует перевод оператора 'is'. Специализация для значимых типов. |
| static std::enable_if<\!std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | Реализует перевод оператора 'is'. Специализация для неконвертируемых типов. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | Реализует перевод оператора 'is'. Специализация для указательных типов. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Is](./is/)(const [ExceptionWrapper](../exceptionwrapper/)\<U\>\&) | Реализует перевод оператора 'is'. Специализация для типов-оберток исключений. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Реализует перевод оператора 'is'. Специализация для nullable типов. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Реализует перевод оператора 'is'. Специализация для упаковываемых типов с определённым оператором ==. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Реализует перевод оператора 'is'. Специализация для упаковываемых типов без определённого оператора ==. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!std::is_same\<V, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<V\>\&) | Реализует перевод оператора 'is'. Специализация для упакованных значимых типов в интерфейсы. |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | Реализует перевод оператора 'is'. Специализация для перечислимых типов. |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [WeakPtr](../weakptr/)\<U\>\&) | Реализует перевод оператора 'is'. Специализация для перечислимых типов против слабых указателей. |
| static **bool** [Is](./is/)(const [Nullable](../nullable/)\<U\>\&) | Реализует перевод оператора 'is'. Специализация для типа [Nullable](../nullable/). |
| static **bool** [Is](./is/)(const char16_t *) | Реализует перевод оператора 'is'. Специализация для строкового литерала. |
| static **bool** [Is](./is/)(**int32_t**) | Реализует перевод оператора 'is'. Специализация для целочисленного литерала. |
| static **bool** [IsBoxedValue](./isboxedvalue/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Проверяет, является ли объект упакованным значением. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | Преобразует [Object](../object/) в неизвестный тип, обрабатывая как тип умного указателя, так и ситуации с упакованным значением. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | Преобразует [Object](../object/) в неизвестный тип, обрабатывая как тип умного указателя, так и ситуации с упакованным значением. |
| static [String](../string/) [ToString](./tostring/)(const char_t *) | Подстановка для метода C# ToString, работающего с любым типом C++. |
| static [String](../string/) [ToString](./tostring/)(const [Nullable](../nullable/)\<T\>\&) | Подстановка для метода C# ToString, работающего с любым типом C++. |
| static std::enable_if\<std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Подстановка для метода C# ToString, работающего с любым типом C++. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Подстановка для метода C# ToString, работающего с любым типом C++. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value||std::is_pointer\<T\>::value||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Подстановка для метода C# ToString, работающего с любым типом C++. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Подстановка для метода C# ToString, работающего с любым типом C++. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | Подстановка для метода C# ToString, работающего с любым типом C++. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Подстановка для метода C# ToString, работающего с любым типом C++. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Подстановка для метода C# ToString, работающего с любым типом C++. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_reference\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | Подстановка для метода C# ToString, работающего с любым типом C++. |
| static std::enable_if\<std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Разупаковывает типы значений после преобразования в [Object](../object/). Реализация для перечислимых типов. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Разупаковывает типы значений после преобразования в [Object](../object/). Реализация для неперечислимых и не nullable типов. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Разупаковывает типы значений после преобразования в [Object](../object/). Реализация для неперечислимых и не nullable типов. |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::numeric_limits\<T\>::is_integer, T\>::type [Unbox](./unbox/)(E) | Разупаковывает перечислимые типы в целое число. |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(E) | Преобразует перечислимые типы. |
| static [String](../string/) [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Разупаковывает строковые значения. |
| static [String](../string/) [UnboxStringSafe](./unboxstringsafe/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Разупаковывает строку из упакованного значения. |
| static [Nullable](../nullable/)\<T\> [UnboxToNullable](./unboxtonullable/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | Разупаковывает объект в nullable тип. |
| static std::enable_if<\!std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | Проверяет, является ли объект неизвестного типа nullptr. Перегрузка для нескалярных типов. |
| static std::enable_if\<std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | Проверяет, является ли объект неизвестного типа nullptr. Перегрузка для скалярных типов. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(T) | Преобразует неизвестный тип в [Object](../object/), обрабатывая как тип умного указателя, так и тип значения. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(const T\&) | Преобразует неизвестный тип в [Object](../object/), обрабатывая как тип умного указателя, так и тип значения. |

## Смотрите также

* Класс [ObjectType](../objecttype/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)