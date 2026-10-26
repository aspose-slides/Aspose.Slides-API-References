---
title: "System::TestPredicates::Details"
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 937
url: /sv/system.testpredicates.details/
---
## Funktioner

| Funktion | Beskrivning |
| --- | --- |
| std::enable_if_t<\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | Skriver ut objekt till sträng genom att välja rätt serialiseringsfunktion. |
| std::enable_if_t\<[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | Skriver ut ICollection-stilbehållare till sträng genom att skriva ut deras element (inte mer än 32). |
| std::string [PrintToString](./printtostring/)(std::nullptr_t) | Skriver ut nullptr till sträng. |
| std::string [PrintToString](./printtostring/)(const [Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<**bool**\>\&) | Skriver ut [IEnumerable<bool>](../system.collections.generic/ienumerable/) samlingar till sträng genom att skriva ut deras element (inte mer än 32). |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, long long) | Skriver ut [System::Object](../system/object/)-underklass till sträng med ToString()-metoden. |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [WeakPtr](../system/weakptr/)\<T\>\&, long long) | Skriver ut [System::Object](../system/object/)-underklass till sträng med ToString()-metoden. |
| std::enable_if<\![TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Skriver ut objekt till sträng med ToString()-metoden. |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Skriver ut objekt till sträng med PrintTo-metoden. |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Skriver ut objekt till sträng med PrintTo-metoden. |
| std::string [PrintToStringImpl](./printtostringimpl/)(const std::pair\<T1, T2\>\&, long long) | Skriver ut par till sträng. |
| std::string [PrintToStringImpl](./printtostringimpl/)(const [Collections::Generic::KeyValuePair](../system.collections.generic/keyvaluepair/)\<T1, T2\>\&, long long) | Skriver ut par till sträng. |
| std::enable_if\<[TypeTraits::IsCppContainer](../system.testpredicates.typetraits/iscppcontainer/)\<T\>::value\&&\!std::is_base_of\<[Object](../system/object/), T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Skriver ut STL-stilbehållare till sträng genom att skriva ut deras element (inte mer än 32). |
| std::string [PrintToStringImpl](./printtostringimpl/)(const T\&, int) | Skriver ut andra typer till sträng genom att använda gtest-tillhandahållna funktioner. |
| testing::AssertionResult [EqFailure](./eqfailure/)(const char *, const char *, T1\&, T2\&) | Formaterar ==-assertionfel för utskrift. |
| testing::AssertionResult [NotEqFailure](./noteqfailure/)(const char *, const char *, T1\&, T2\&) | Formaterar !=-assertionfel för utskrift. |
| testing::AssertionResult [SameFailure](./samefailure/)(const char *, const char *, T1\&, T2\&) | Formaterar 'same'-assertionfel för utskrift. |
| testing::AssertionResult [NotSameFailure](./notsamefailure/)(const char *, const char *, T1\&, T2\&) | Formaterar 'not same'-assertionfel för utskrift. |