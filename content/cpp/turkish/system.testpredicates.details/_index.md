---
title: "System::TestPredicates::Details"
second_title: Aspose.Slides için C++ API Referansı
description: 
type: docs
weight: 937
url: /tr/system.testpredicates.details/
---
## Fonksiyonlar

| Fonksiyon | Açıklama |
| --- | --- |
| std::enable_if_t<\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | Nesneyi uygun serileştirici fonksiyonunu seçerek dizeye yazdırır. |
| std::enable_if_t\<[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | ICollection tarzı kapsayıcıları elemanlarını (32'den fazla olmamak kaydıyla) yazarak dizeye yazdırır. |
| std::string [PrintToString](./printtostring/)(std::nullptr_t) | nullptr'ı dizeye yazdırır. |
| std::string [PrintToString](./printtostring/)(const [Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<**bool**\>\&) | [IEnumerable<bool>](../system.collections.generic/ienumerable/) koleksiyonlarını elemanlarını (32'den fazla olmamak kaydıyla) yazarak dizeye yazdırır. |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, long long) | [System::Object](../system/object/) alt sınıfını ToString() yöntemini kullanarak dizeye yazdırır. |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [WeakPtr](../system/weakptr/)\<T\>\&, long long) | [System::Object](../system/object/) alt sınıfını ToString() yöntemini kullanarak dizeye yazdırır. |
| std::enable_if<\![TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Nesneyi ToString() yöntemini kullanarak dizeye yazdırır. |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Nesneyi PrintTo yöntemiyle dizeye yazdırır. |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Nesneyi PrintTo yöntemiyle dizeye yazdırır. |
| std::string [PrintToStringImpl](./printtostringimpl/)(const std::pair\<T1, T2\>\&, long long) | Çifti dizeye yazdırır. |
| std::string [PrintToStringImpl](./printtostringimpl/)(const [Collections::Generic::KeyValuePair](../system.collections.generic/keyvaluepair/)\<T1, T2\>\&, long long) | Çifti dizeye yazdırır. |
| std::enable_if\<[TypeTraits::IsCppContainer](../system.testpredicates.typetraits/iscppcontainer/)\<T\>::value\&&\!std::is_base_of\<[Object](../system/object/), T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | STL tarzı kapsayıcıları elemanlarını (32'den fazla olmamak kaydıyla) yazarak dizeye yazdırır. |
| std::string [PrintToStringImpl](./printtostringimpl/)(const T\&, int) | gtest tarafından sağlanan fonksiyonları kullanarak diğer tipleri dizeye yazdırır. |
| testing::AssertionResult [EqFailure](./eqfailure/)(const char *, const char *, T1\&, T2\&) | Çıktı için == doğrulama hatasını biçimler. |
| testing::AssertionResult [NotEqFailure](./noteqfailure/)(const char *, const char *, T1\&, T2\&) | Çıktı için != doğrulama hatasını biçimler. |
| testing::AssertionResult [SameFailure](./samefailure/)(const char *, const char *, T1\&, T2\&) | Çıktı için 'same' doğrulama hatasını biçimler. |
| testing::AssertionResult [NotSameFailure](./notsamefailure/)(const char *, const char *, T1\&, T2\&) | Çıktı için 'not same' doğrulama hatasını biçimler. |