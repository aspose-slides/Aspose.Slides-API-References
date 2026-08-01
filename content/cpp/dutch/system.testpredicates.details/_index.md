---
title: "System::TestPredicates::Details"
second_title: Aspose.Slides voor C++ API-referentie
description: 
type: docs
weight: 937
url: /nl/system.testpredicates.details/
---
## Functies

| Functie | Beschrijving |
| --- | --- |
| std::enable_if_t<\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | Print een object naar string door de juiste serializer-functie te selecteren. |
| std::enable_if_t\<[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | Print ICollection-achtige containers naar string door hun elementen af te drukken (maximaal 32). |
| std::string [PrintToString](./printtostring/)(std::nullptr_t) | Print nullptr naar string. |
| std::string [PrintToString](./printtostring/)(const [Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<**bool**\>\&) | Print [IEnumerable<bool>](../system.collections.generic/ienumerable/) collecties naar string door hun elementen af te drukken (maximaal 32). |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, long long) | Print [System::Object](../system/object/) subklasse naar string met behulp van de ToString()-methode. |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [WeakPtr](../system/weakptr/)\<T\>\&, long long) | Print [System::Object](../system/object/) subklasse naar string met behulp van de ToString()-methode. |
| std::enable_if<\![TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Print een object naar string met behulp van de ToString()-methode. |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Print een object naar string met behulp van de PrintTo-methode. |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Print een object naar string met behulp van de PrintTo-methode. |
| std::string [PrintToStringImpl](./printtostringimpl/)(const std::pair\<T1, T2\>\&, long long) | Print een paar naar string. |
| std::string [PrintToStringImpl](./printtostringimpl/)(const [Collections::Generic::KeyValuePair](../system.collections.generic/keyvaluepair/)\<T1, T2\>\&, long long) | Print een paar naar string. |
| std::enable_if\<[TypeTraits::IsCppContainer](../system.testpredicates.typetraits/iscppcontainer/)\<T\>::value\&&\!std::is_base_of\<[Object](../system/object/), T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Print STL-achtige containers naar string door hun elementen af te drukken (maximaal 32). |
| std::string [PrintToStringImpl](./printtostringimpl/)(const T\&, int) | Print andere types naar string door gebruik te maken van gtest-voorzien functies. |
| testing::AssertionResult [EqFailure](./eqfailure/)(const char *, const char *, T1\&, T2\&) | Formatteert == assertiefout voor uitvoer. |
| testing::AssertionResult [NotEqFailure](./noteqfailure/)(const char *, const char *, T1\&, T2\&) | Formatteert != assertiefout voor uitvoer. |
| testing::AssertionResult [SameFailure](./samefailure/)(const char *, const char *, T1\&, T2\&) | Formatteert 'same' assertiefout voor uitvoer. |
| testing::AssertionResult [NotSameFailure](./notsamefailure/)(const char *, const char *, T1\&, T2\&) | Formatteert 'not same' assertiefout voor uitvoer. |