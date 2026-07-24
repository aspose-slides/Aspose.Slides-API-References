---
title: "System::TestPredicates::Details"
second_title: Aspose.Slides für C++ API-Referenz
description: 
type: docs
weight: 937
url: /de/system.testpredicates.details/
---
## Funktionen

| Funktion | Beschreibung |
| --- | --- |
| std::enable_if_t<\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | Gibt Objekt als Zeichenkette aus, indem die passende Serialisierungsfunktion ausgewählt wird. |
| std::enable_if_t\<[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | Gibt ICollection-artige Container als Zeichenkette aus, indem deren Elemente (höchstens 32) ausgegeben werden. |
| std::string [PrintToString](./printtostring/)(std::nullptr_t) | Gibt nullptr als Zeichenkette aus. |
| std::string [PrintToString](./printtostring/)(const [Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<**bool**\>\&) | Gibt [IEnumerable<bool>](../system.collections.generic/ienumerable/) Sammlungen als Zeichenkette aus, indem deren Elemente (höchstens 32) ausgegeben werden. |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, long long) | Gibt [System::Object](../system/object/) Unterklasse als Zeichenkette aus, indem die ToString()-Methode verwendet wird. |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [WeakPtr](../system/weakptr/)\<T\>\&, long long) | Gibt [System::Object](../system/object/) Unterklasse als Zeichenkette aus, indem die ToString()-Methode verwendet wird. |
| std::enable_if<\![TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Gibt Objekt als Zeichenkette aus, indem die ToString()-Methode verwendet wird. |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Gibt Objekt als Zeichenkette aus, indem die PrintTo-Methode verwendet wird. |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Gibt Objekt als Zeichenkette aus, indem die PrintTo-Methode verwendet wird. |
| std::string [PrintToStringImpl](./printtostringimpl/)(const std::pair\<T1, T2\>\&, long long) | Gibt Paar als Zeichenkette aus. |
| std::string [PrintToStringImpl](./printtostringimpl/)(const [Collections::Generic::KeyValuePair](../system.collections.generic/keyvaluepair/)\<T1, T2\>\&, long long) | Gibt Paar als Zeichenkette aus. |
| std::enable_if\<[TypeTraits::IsCppContainer](../system.testpredicates.typetraits/iscppcontainer/)\<T\>::value\&&\!std::is_base_of\<[Object](../system/object/), T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Gibt STL-artige Container als Zeichenkette aus, indem deren Elemente (höchstens 32) ausgegeben werden. |
| std::string [PrintToStringImpl](./printtostringimpl/)(const T\&, int) | Gibt andere Typen als Zeichenkette aus, indem gtest-bereitgestellte Funktionen verwendet werden. |
| testing::AssertionResult [EqFailure](./eqfailure/)(const char *, const char *, T1\&, T2\&) | Formatiert ==-Assertion-Fehler für die Ausgabe. |
| testing::AssertionResult [NotEqFailure](./noteqfailure/)(const char *, const char *, T1\&, T2\&) | Formatiert !=-Assertion-Fehler für die Ausgabe. |
| testing::AssertionResult [SameFailure](./samefailure/)(const char *, const char *, T1\&, T2\&) | Formatiert 'same'-Assertion-Fehler für die Ausgabe. |
| testing::AssertionResult [NotSameFailure](./notsamefailure/)(const char *, const char *, T1\&, T2\&) | Formatiert 'not same'-Assertion-Fehler für die Ausgabe. |