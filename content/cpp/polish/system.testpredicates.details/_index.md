---
title: "System::TestPredicates::Details"
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: 
type: docs
weight: 937
url: /pl/system.testpredicates.details/
---
## Funkcje

| Funkcja | Opis |
| --- | --- |
| std::enable_if_t<\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | Wypisuje obiekt do ciągu znaków, wybierając odpowiednią funkcję serializatora. |
| std::enable_if_t\<[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | Wypisuje kontenery typu ICollection do ciągu znaków, wypisując ich elementy (nie więcej niż 32). |
| std::string [PrintToString](./printtostring/)(std::nullptr_t) | Wypisuje nullptr do ciągu znaków. |
| std::string [PrintToString](./printtostring/)(const [Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<**bool**\>\&) | Wypisuje [IEnumerable<bool>](../system.collections.generic/ienumerable/) kolekcje do ciągu znaków, wypisując ich elementy (nie więcej niż 32). |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, long long) | Wypisuje podklasę [System::Object](../system/object/) do ciągu znaków, używając metody ToString(). |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [WeakPtr](../system/weakptr/)\<T\>\&, long long) | Wypisuje podklasę [System::Object](../system/object/) do ciągu znaków, używając metody ToString(). |
| std::enable_if<\![TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Wypisuje obiekt do ciągu znaków, używając metody ToString(). |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Wypisuje obiekt do ciągu znaków, używając metody PrintTo. |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Wypisuje obiekt do ciągu znaków, używając metody PrintTo. |
| std::string [PrintToStringImpl](./printtostringimpl/)(const std::pair\<T1, T2\>\&, long long) | Wypisuje parę do ciągu znaków. |
| std::string [PrintToStringImpl](./printtostringimpl/)(const [Collections::Generic::KeyValuePair](../system.collections.generic/keyvaluepair/)\<T1, T2\>\&, long long) | Wypisuje parę do ciągu znaków. |
| std::enable_if\<[TypeTraits::IsCppContainer](../system.testpredicates.typetraits/iscppcontainer/)\<T\>::value\&&\!std::is_base_of\<[Object](../system/object/), T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Wypisuje kontenery w stylu STL do ciągu znaków, wypisując ich elementy (nie więcej niż 32). |
| std::string [PrintToStringImpl](./printtostringimpl/)(const T\&, int) | Wypisuje inne typy do ciągu znaków, używając funkcji dostarczonych przez gtest. |
| testing::AssertionResult [EqFailure](./eqfailure/)(const char *, const char *, T1\&, T2\&) | Formatuje niepowodzenie asercji == do wyjścia. |
| testing::AssertionResult [NotEqFailure](./noteqfailure/)(const char *, const char *, T1\&, T2\&) | Formatuje niepowodzenie asercji != do wyjścia. |
| testing::AssertionResult [SameFailure](./samefailure/)(const char *, const char *, T1\&, T2\&) | Formatuje niepowodzenie asercji 'same' do wyjścia. |
| testing::AssertionResult [NotSameFailure](./notsamefailure/)(const char *, const char *, T1\&, T2\&) | Formatuje niepowodzenie asercji 'not same' do wyjścia. |