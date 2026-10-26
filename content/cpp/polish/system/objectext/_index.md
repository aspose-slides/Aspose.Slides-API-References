---
title: ObjectExt
second_title: Aspose.Slides dla C++ – odniesienie API
description: Udostępnia statyczne metody, które emulują metody Object z C# wywoływane dla typów C++ nie-obiektowych (łańcuchy znaków, liczby itp.). Jest to typ statyczny bez usług instancji. Nie należy nigdy tworzyć jego instancji w żaden sposób.
type: docs
weight: 1145
url: /pl/system/objectext/
---
## ObjectExt klasa

Udostępnia statyczne metody, które emulują metody C# [Object](../object/) wywoływane dla typów C++ nie-obiektowych (ciągi znaków, liczby itd.). To jest typ statyczny bez usług instancji. Nie powinieneś nigdy tworzyć jego instancji w żaden sposób.

```cpp
class ObjectExt : public System::ObjectType
```

## Metody

| Metoda | Opis |
| --- | --- |
| static std::enable_if<(std::is_fundamental\<To\>::value), std::array\<To, sizeof...(From)>\>::type [ArrayInitializerCast](./arrayinitializercast/)(From ...) | Konwertuje podstawowe wartości tablicowe (które C# robi domyślnie, ale C++ najwyraźniej nie robi). |
| static std::enable_if\<std::is_enum\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Opakowuje typy wartościowe w celu konwersji do [Object](../object/). Implementacja dla typów wyliczeniowych. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Opakowuje typy wartościowe w celu konwersji do [Object](../object/). Implementacja dla typów nie-wyliczeniowych. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Opakowuje typy [Nullable](../nullable/) w celu konwersji do [Object](../object/). |
| static [SmartPtr](../smartptr/)\<[Object](../object/)\> [Box](./box/)(const [String](../string/)\&) | Opakowuje wartości łańcuchów znaków. |
| static [SmartPtr](../smartptr/)\<[System::BoxedValueBase](../boxedvaluebase/)\> [BoxEnum](./boxenum/)(T) | Opakowuje typy wyliczeniowe, aby były propagowane jako [Object](../object/). |
| static [SmartPtr](../smartptr/)\<[System::Collections::IList](../../system.collections/ilist/)\> [CastToIList](./casttoilist/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) |  |
| static auto [Coalesce](./coalesce/)(T0, T1) | Implementacja tłumaczenia operatora '??' dla typów nie-nullable. |
| static T0 [Coalesce](./coalesce/)([System::Nullable](../nullable/)\<T0\>, T1) | Implementacja tłumaczenia operatora '??' dla typów nullable. |
| static auto [CoalesceAssign](./coalesceassign/)(T0\&, T1) | Implementacja tłumaczenia operatora '??=' . |
| static std::conditional\<std::is_convertible\<RT2, RT1\>::value, RT1, RT2\>::type [CoalesceInternal](./coalesceinternal/)(RT1, F) | Implementacja tłumaczenia operatora '??' dla typów nie-nullable. Przeciążenie na wypadek, gdy RT2 jest konwertowalne do RT1. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) |  |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | Zastąpienie wywołań C# [Object.Equals](../object/equals/) działających dla dowolnego typu w C++. Przeciążenie dla typów inteligentnych wskaźników. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(T, const T2\&) | Zastąpienie wywołań C# [Object.Equals](../object/equals/) działających dla dowolnego typu w C++. Przeciążenie dla typów struktur. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | Zastąpienie wywołań C# [Object.Equals](../object/equals/) działających dla dowolnego typu w C++. Przeciążenie dla typów skalarów. |
| static **bool** [Equals](./equals/)(const char_t(&), [String](../string/)) | Zastąpienie wywołań C# [Object.Equals](../object/equals/) działających dla dowolnego typu w C++. Przeciążenie dla literału łańcucha z porównaniem łańcuchów. |
| static **bool** [Equals](./equals/)(const **float**\&, const **float**\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| static **bool** [Equals](./equals/)(const **double**\&, const **double**\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static std::enable_if\<[System::IsSmartPtr](../issmartptr/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static int [GetHashCode](./gethashcode/)(const T\&) | Implementuje wywołania [GetHashCode()](./gethashcode/); działa zarówno na podklasach [Object](../object/), jak i na typach niepowiązanych. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Implementuje tłumaczenie typeof(). Przeciążenie dla inteligentnych wskaźników. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Implementuje tłumaczenie typeof(). Przeciążenie dla struktur. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Implementuje tłumaczenie typeof(). Przeciążenie dla wyjątków. |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | Implementuje tłumaczenie typeof(). Przeciążenie dla typów pierwotnych. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | Implementuje tłumaczenie typeof(). Przeciążenie dla typów [Nullable](../nullable/). |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementuje tłumaczenie typeof(). Przeciążenie dla typów pierwotnych. |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementuje tłumaczenie typeof(). Przeciążenie dla typów wyliczeniowych. |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementuje tłumaczenie typeof(). Przeciążenie dla struktur i wskaźników. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementuje tłumaczenie typeof(). Przeciążenie dla [Nullable](../nullable/). |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementuje tłumaczenie typeof(). Przeciążenie dla MulticastDelegate. |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implementuje tłumaczenie typeof(). Przeciążenie dla struktur i wskaźników. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)(const [String](../string/)\&) | Implementuje tłumaczenie typeof(). Przeciążenie dla typu łańcucha znaków. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementuje tłumaczenie typeof(). Przeciążenie dla **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementuje tłumaczenie typeof(). Przeciążenie dla **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementuje tłumaczenie typeof(). Przeciążenie dla **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementuje tłumaczenie typeof(). Przeciążenie dla **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementuje tłumaczenie typeof(). Przeciążenie dla **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implementuje tłumaczenie typeof(). Przeciążenie dla **uint8_t**. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, **bool**\>::type [Is](./is/)(const T\&) | Implementuje tłumaczenie operatora 'is'. Specjalizacja dla typów pakowalnych (wartościowych), które dokładnie są tym, czym są. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | Implementuje tłumaczenie operatora 'is'. Specjalizacja dla typów wskaźnikowych zoptymalizowanych dla klas 'final'. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&\!std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | Implementuje tłumaczenie operatora 'is'. Specjalizacja dla typów wskaźnikowych. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | Implementuje tłumaczenie operatora 'is'. Specjalizacja dla typów wartościowych. |
| static std::enable_if<\!std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | Implementuje tłumaczenie operatora 'is'. Specjalizacja dla typów niekonwertowalnych. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | Implementuje tłumaczenie operatora 'is'. Specjalizacja dla typów wskaźnikowych. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Is](./is/)(const [ExceptionWrapper](../exceptionwrapper/)\<U\>\&) | Implementuje tłumaczenie operatora 'is'. Specjalizacja dla typów opakowujących wyjątki. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Implementuje tłumaczenie operatora 'is'. Specjalizacja dla typów nullable. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Implementuje tłumaczenie operatora 'is'. Specjalizacja dla typów pakowalnych z zdefiniowanym operatorem ==. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Implementuje tłumaczenie operatora 'is'. Specjalizacja dla typów pakowalnych bez zdefiniowanego operatora ==. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!std::is_same\<V, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<V\>\&) | Implementuje tłumaczenie operatora 'is'. Specjalizacja typów wartościowych opakowanych w interfejsy. |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | Implementuje tłumaczenie operatora 'is'. Specjalizacja dla typów wyliczeniowych. |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [WeakPtr](../weakptr/)\<U\>\&) | Implementuje tłumaczenie operatora 'is'. Specjalizacja dla typów wyliczeniowych w stosunku do słabych wskaźników. |
| static **bool** [Is](./is/)(const [Nullable](../nullable/)\<U\>\&) | Implementuje tłumaczenie operatora 'is'. Specjalizacja dla [Nullable](../nullable/) typu. |
| static **bool** [Is](./is/)(const char16_t *) | Implementuje tłumaczenie operatora 'is'. Specjalizacja dla literału łańcucha znaków. |
| static **bool** [Is](./is/)(**int32_t**) | Implementuje tłumaczenie operatora 'is'. Specjalizacja dla literału liczby całkowitej. |
| static **bool** [IsBoxedValue](./isboxedvalue/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Sprawdza, czy obiekt jest wartością opakowaną. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | Konwertuje [Object](../object/) na nieznany typ, obsługując zarówno typ inteligentnego wskaźnika, jak i sytuacje bpxed wartości. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | Konwertuje [Object](../object/) na nieznany typ, obsługując zarówno typ inteligentnego wskaźnika, jak i sytuacje wartości opakowanej. |
| static [String](../string/) [ToString](./tostring/)(const char_t *) | Zastąpienie metody C# ToString, aby działała na dowolnym typie C++. |
| static [String](../string/) [ToString](./tostring/)(const [Nullable](../nullable/)\<T\>\&) | Zastąpienie metody C# ToString, aby działała na dowolnym typie C++. |
| static std::enable_if\<std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Zastąpienie metody C# ToString, aby działała na dowolnym typie C++. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Zastąpienie metody C# ToString, aby działała na dowolnym typie C++. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value||std::is_pointer\<T\>::value||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Zastąpienie metody C# ToString, aby działała na dowolnym typie C++. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Zastąpienie metody C# ToString, aby działała na dowolnym typie C++. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | Zastąpienie metody C# ToString, aby działała na dowolnym typie C++. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Zastąpienie metody C# ToString, aby działała na dowolnym typie C++. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Zastąpienie metody C# ToString, aby działała na dowolnym typie C++. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_reference\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | Zastąpienie metody C# ToString, aby działała na dowolnym typie C++. |
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
## Zobacz także

* Klasa [ObjectType](../objecttype/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)