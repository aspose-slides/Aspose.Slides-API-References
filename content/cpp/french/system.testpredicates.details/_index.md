---
title: "System::TestPredicates::Details"
second_title: Référence de l'API Aspose.Slides pour C++
description: 
type: docs
weight: 937
url: /fr/system.testpredicates.details/
---
## Fonctions

| Fonction | Description |
| --- | --- |
| std::enable_if_t<\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | Convertit l'objet en chaîne en sélectionnant la fonction de sérialisation appropriée. |
| std::enable_if_t\<[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | Convertit les conteneurs de type ICollection en chaîne en affichant leurs éléments (pas plus de 32). |
| std::string [PrintToString](./printtostring/)(std::nullptr_t) | Convertit nullptr en chaîne. |
| std::string [PrintToString](./printtostring/)(const [Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<**bool**\>\&) | Convertit les collections [IEnumerable<bool>](../system.collections.generic/ienumerable/) en chaîne en affichant leurs éléments (pas plus de 32). |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, long long) | Convertit la sous-classe [System::Object](../system/object/) en chaîne en utilisant la méthode ToString(). |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [WeakPtr](../system/weakptr/)\<T\>\&, long long) | Convertit la sous-classe [System::Object](../system/object/) en chaîne en utilisant la méthode ToString(). |
| std::enable_if<\![TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Convertit l'objet en chaîne en utilisant la méthode ToString(). |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Convertit l'objet en chaîne en utilisant la méthode PrintTo. |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Convertit l'objet en chaîne en utilisant la méthode PrintTo. |
| std::string [PrintToStringImpl](./printtostringimpl/)(const std::pair\<T1, T2\>\&, long long) | Convertit une paire en chaîne. |
| std::string [PrintToStringImpl](./printtostringimpl/)(const [Collections::Generic::KeyValuePair](../system.collections.generic/keyvaluepair/)\<T1, T2\>\&, long long) | Convertit une paire en chaîne. |
| std::enable_if\<[TypeTraits::IsCppContainer](../system.testpredicates.typetraits/iscppcontainer/)\<T\>::value\&&\!std::is_base_of\<[Object](../system/object/), T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Convertit les conteneurs de style STL en chaîne en affichant leurs éléments (pas plus de 32). |
| std::string [PrintToStringImpl](./printtostringimpl/)(const T\&, int) | Convertit d'autres types en chaîne en utilisant les fonctions fournies par gtest. |
| testing::AssertionResult [EqFailure](./eqfailure/)(const char *, const char *, T1\&, T2\&) | Formate l'échec d'assertion == pour la sortie. |
| testing::AssertionResult [NotEqFailure](./noteqfailure/)(const char *, const char *, T1\&, T2\&) | Formate l'échec d'assertion != pour la sortie. |
| testing::AssertionResult [SameFailure](./samefailure/)(const char *, const char *, T1\&, T2\&) | Formate l'échec d'assertion 'same' pour la sortie. |
| testing::AssertionResult [NotSameFailure](./notsamefailure/)(const char *, const char *, T1\&, T2\&) | Formate l'échec d'assertion 'not same' pour la sortie. |