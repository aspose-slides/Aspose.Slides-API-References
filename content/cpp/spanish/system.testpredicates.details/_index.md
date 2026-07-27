---
title: "System::TestPredicates::Details"
second_title: Referencia de API de Aspose.Slides para C++
description: 
type: docs
weight: 937
url: /es/system.testpredicates.details/
---
## Funciones

| Función | Descripción |
| --- | --- |
| std::enable_if_t<\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | Imprime el objeto a cadena seleccionando la función de serializador adecuada. |
| std::enable_if_t\<[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | Imprime contenedores de estilo ICollection a cadena imprimiendo sus elementos (no más de 32). |
| std::string [PrintToString](./printtostring/)(std::nullptr_t) | Imprime nullptr a cadena. |
| std::string [PrintToString](./printtostring/)(const [Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<**bool**\>\&) | Imprime colecciones [IEnumerable<bool>](../system.collections.generic/ienumerable/) a cadena imprimiendo sus elementos (no más de 32). |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, long long) | Imprime la subclase [System::Object](../system/object/) a cadena usando el método ToString(). |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [WeakPtr](../system/weakptr/)\<T\>\&, long long) | Imprime la subclase [System::Object](../system/object/) a cadena usando el método ToString(). |
| std::enable_if<\![TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Imprime el objeto a cadena usando el método ToString(). |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Imprime el objeto a cadena usando el método PrintTo. |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Imprime el objeto a cadena usando el método PrintTo. |
| std::string [PrintToStringImpl](./printtostringimpl/)(const std::pair\<T1, T2\>\&, long long) | Imprime el par a cadena. |
| std::string [PrintToStringImpl](./printtostringimpl/)(const [Collections::Generic::KeyValuePair](../system.collections.generic/keyvaluepair/)\<T1, T2\>\&, long long) | Imprime el par a cadena. |
| std::enable_if\<[TypeTraits::IsCppContainer](../system.testpredicates.typetraits/iscppcontainer/)\<T\>::value\&&\!std::is_base_of\<[Object](../system/object/), T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Imprime contenedores de estilo STL a cadena imprimiendo sus elementos (no más de 32). |
| std::string [PrintToStringImpl](./printtostringimpl/)(const T\&, int) | Imprime otros tipos a cadena usando funciones proporcionadas por gtest. |
| testing::AssertionResult [EqFailure](./eqfailure/)(const char *, const char *, T1\&, T2\&) | Formatea el fallo de aserción == para la salida. |
| testing::AssertionResult [NotEqFailure](./noteqfailure/)(const char *, const char *, T1\&, T2\&) | Formatea el fallo de aserción != para la salida. |
| testing::AssertionResult [SameFailure](./samefailure/)(const char *, const char *, T1\&, T2\&) | Formatea el fallo de aserción 'same' para la salida. |
| testing::AssertionResult [NotSameFailure](./notsamefailure/)(const char *, const char *, T1\&, T2\&) | Formatea el fallo de aserción 'not same' para la salida. |