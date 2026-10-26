---
title: "System::TestPredicates::Details"
second_title: Referensi API Aspose.Slides untuk C++
description: 
type: docs
weight: 937
url: /id/system.testpredicates.details/
---
## Fungsi

| Fungsi | Deskripsi |
| --- | --- |
| std::enable_if_t<\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | Mencetak objek ke string dengan memilih fungsi serializer yang tepat. |
| std::enable_if_t\<[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | Mencetak kontainer gaya ICollection ke string dengan mencetak elemennya (tidak lebih dari 32). |
| std::string [PrintToString](./printtostring/)(std::nullptr_t) | Mencetak nullptr ke string. |
| std::string [PrintToString](./printtostring/)(const [Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<**bool**\>\&) | Mencetak koleksi [IEnumerable<bool>](../system.collections.generic/ienumerable/) ke string dengan mencetak elemennya (tidak lebih dari 32). |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, long long) | Mencetak subclass [System::Object](../system/object/) ke string menggunakan metode ToString(). |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [WeakPtr](../system/weakptr/)\<T\>\&, long long) | Mencetak subclass [System::Object](../system/object/) ke string menggunakan metode ToString(). |
| std::enable_if<\![TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Mencetak objek ke string menggunakan metode ToString(). |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Mencetak objek ke string menggunakan metode PrintTo. |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Mencetak objek ke string menggunakan metode PrintTo. |
| std::string [PrintToStringImpl](./printtostringimpl/)(const std::pair\<T1, T2\>\&, long long) | Mencetak pasangan ke string. |
| std::string [PrintToStringImpl](./printtostringimpl/)(const [Collections::Generic::KeyValuePair](../system.collections.generic/keyvaluepair/)\<T1, T2\>\&, long long) | Mencetak pasangan ke string. |
| std::enable_if\<[TypeTraits::IsCppContainer](../system.testpredicates.typetraits/iscppcontainer/)\<T\>::value\&&\!std::is_base_of\<[Object](../system/object/), T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Mencetak kontainer gaya STL ke string dengan mencetak elemennya (tidak lebih dari 32). |
| std::string [PrintToStringImpl](./printtostringimpl/)(const T\&, int) | Mencetak tipe lain ke string dengan menggunakan fungsi yang disediakan oleh gtest. |
| testing::AssertionResult [EqFailure](./eqfailure/)(const char *, const char *, T1\&, T2\&) | Memformat kegagalan asersi == untuk output. |
| testing::AssertionResult [NotEqFailure](./noteqfailure/)(const char *, const char *, T1\&, T2\&) | Memformat kegagalan asersi != untuk output. |
| testing::AssertionResult [SameFailure](./samefailure/)(const char *, const char *, T1\&, T2\&) | Memformat kegagalan asersi 'same' untuk output. |
| testing::AssertionResult [NotSameFailure](./notsamefailure/)(const char *, const char *, T1\&, T2\&) | Memformat kegagalan asersi 'not same' untuk output. |