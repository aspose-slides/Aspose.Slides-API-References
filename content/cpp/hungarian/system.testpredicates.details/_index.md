---
title: "System::TestPredicates::Details"
second_title: Aspose.Slides C++ API referencia
description: 
type: docs
weight: 937
url: /hu/system.testpredicates.details/
---
## Funkciók

| Függvény | Leírás |
| --- | --- |
| std::enable_if_t<\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | Az objektumot karakterláncra írja ki a megfelelő sorosító függvény kiválasztásával. |
| std::enable_if_t\<[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | Az ICollection-stílusú konténereket karakterláncra írja ki az elemeik (legfeljebb 32) kiíratásával. |
| std::string [PrintToString](./printtostring/)(std::nullptr_t) | A nullptr értéket karakterláncra írja ki. |
| std::string [PrintToString](./printtostring/)(const [Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<**bool**\>\&) | A [IEnumerable<bool>](../system.collections.generic/ienumerable/) gyűjteményeket karakterláncra írja ki az elemeik (legfeljebb 32) kiíratásával. |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, long long) | A [System::Object](../system/object/) alosztályt karakterláncra írja ki a ToString() metódus használatával. |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [WeakPtr](../system/weakptr/)\<T\>\&, long long) | A [System::Object](../system/object/) alosztályt karakterláncra írja ki a ToString() metódus használatával. |
| std::enable_if<\![TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Az objektumot karakterláncra írja ki a ToString() metódus használatával. |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Az objektumot karakterláncra írja ki a PrintTo metódus használatával. |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Az objektumot karakterláncra írja ki a PrintTo metódus használatával. |
| std::string [PrintToStringImpl](./printtostringimpl/)(const std::pair\<T1, T2\>\&, long long) | A párost karakterláncra írja ki. |
| std::string [PrintToStringImpl](./printtostringimpl/)(const [Collections::Generic::KeyValuePair](../system.collections.generic/keyvaluepair/)\<T1, T2\>\&, long long) | A párost karakterláncra írja ki. |
| std::enable_if\<[TypeTraits::IsCppContainer](../system.testpredicates.typetraits/iscppcontainer/)\<T\>::value\&&\!std::is_base_of\<[Object](../system/object/), T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Az STL-stílusú konténereket karakterláncra írja ki az elemeik (legfeljebb 32) kiíratásával. |
| std::string [PrintToStringImpl](./printtostringimpl/)(const T\&, int) | A többi típust karakterláncra írja ki a gtest által biztosított függvények használatával. |
| testing::AssertionResult [EqFailure](./eqfailure/)(const char *, const char *, T1\&, T2\&) | Formázza a == állításkiesést a kimenethez. |
| testing::AssertionResult [NotEqFailure](./noteqfailure/)(const char *, const char *, T1\&, T2\&) | Formázza a != állításkiesést a kimenethez. |
| testing::AssertionResult [SameFailure](./samefailure/)(const char *, const char *, T1\&, T2\&) | Formázza a 'azonos' állításkiesést a kimenethez. |
| testing::AssertionResult [NotSameFailure](./notsamefailure/)(const char *, const char *, T1\&, T2\&) | Formázza a 'nem azonos' állításkiesést a kimenethez. |