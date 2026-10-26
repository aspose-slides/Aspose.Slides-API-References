---
title: "System::TestPredicates::Details"
second_title: Aspose.Slides pro C++ - Referenční příručka API
description: 
type: docs
weight: 937
url: /cs/system.testpredicates.details/
---
## Funkce

| Funkce | Popis |
| --- | --- |
| std::enable_if_t<\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | Vytiskne objekt do řetězce výběrem správné funkce serializátoru. |
| std::enable_if_t\<[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | Vytiskne kontejnery ve stylu ICollection do řetězce výpisem jejich prvků (ne více než 32). |
| std::string [PrintToString](./printtostring/)(std::nullptr_t) | Vytiskne nullptr do řetězce. |
| std::string [PrintToString](./printtostring/)(const [Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<**bool**\>\&) | Vytiskne [IEnumerable<bool>](../system.collections.generic/ienumerable/) kolekce do řetězce výpisem jejich prvků (ne více než 32). |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, long long) | Vytiskne podtřídu [System::Object](../system/object/) do řetězce pomocí metody ToString(). |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [WeakPtr](../system/weakptr/)\<T\>\&, long long) | Vytiskne podtřídu [System::Object](../system/object/) do řetězce pomocí metody ToString(). |
| std::enable_if<\![TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Vytiskne objekt do řetězce pomocí metody ToString(). |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Vytiskne objekt do řetězce pomocí metody PrintTo. |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Vytiskne objekt do řetězce pomocí metody PrintTo. |
| std::string [PrintToStringImpl](./printtostringimpl/)(const std::pair\<T1, T2\>\&, long long) | Vytiskne dvojici do řetězce. |
| std::string [PrintToStringImpl](./printtostringimpl/)(const [Collections::Generic::KeyValuePair](../system.collections.generic/keyvaluepair/)\<T1, T2\>\&, long long) | Vytiskne dvojici do řetězce. |
| std::enable_if\<[TypeTraits::IsCppContainer](../system.testpredicates.typetraits/iscppcontainer/)\<T\>::value\&&\!std::is_base_of\<[Object](../system/object/), T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Vytiskne kontejnery ve stylu STL do řetězce výpisem jejich prvků (ne více než 32). |
| std::string [PrintToStringImpl](./printtostringimpl/)(const T\&, int) | Vytiskne jiné typy do řetězce pomocí funkcí poskytovaných gtest. |
| testing::AssertionResult [EqFailure](./eqfailure/)(const char *, const char *, T1\&, T2\&) | Formátuje selhání aserce == pro výstup. |
| testing::AssertionResult [NotEqFailure](./noteqfailure/)(const char *, const char *, T1\&, T2\&) | Formátuje selhání aserce != pro výstup. |
| testing::AssertionResult [SameFailure](./samefailure/)(const char *, const char *, T1\&, T2\&) | Formátuje selhání aserce 'same' pro výstup. |
| testing::AssertionResult [NotSameFailure](./notsamefailure/)(const char *, const char *, T1\&, T2\&) | Formátuje selhání aserce 'not same' pro výstup. |