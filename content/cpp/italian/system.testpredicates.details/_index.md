---
title: "System::TestPredicates::Details"
second_title: Riferimento API Aspose.Slides per C++
description: 
type: docs
weight: 937
url: /it/system.testpredicates.details/
---
## Funzioni

| Funzione | Descrizione |
| --- | --- |
| std::enable_if_t<\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | Stampa l'oggetto in una stringa selezionando la funzione di serializzazione appropriata. |
| std::enable_if_t\<[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | Stampa contenitori in stile ICollection in una stringa stampando i loro elementi (non più di 32). |
| std::string [PrintToString](./printtostring/)(std::nullptr_t) | Stampa nullptr in una stringa. |
| std::string [PrintToString](./printtostring/)(const [Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<**bool**\>\&) | Stampa le collezioni [IEnumerable<bool>](../system.collections.generic/ienumerable/) in una stringa stampando i loro elementi (non più di 32). |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, long long) | Stampa la sottoclasse [System::Object](../system/object/) in una stringa usando il metodo ToString(). |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [WeakPtr](../system/weakptr/)\<T\>\&, long long) | Stampa la sottoclasse [System::Object](../system/object/) in una stringa usando il metodo ToString(). |
| std::enable_if<\![TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Stampa l'oggetto in una stringa usando il metodo ToString(). |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Stampa l'oggetto in una stringa usando il metodo PrintTo. |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Stampa l'oggetto in una stringa usando il metodo PrintTo. |
| std::string [PrintToStringImpl](./printtostringimpl/)(const std::pair\<T1, T2\>\&, long long) | Stampa una coppia in una stringa. |
| std::string [PrintToStringImpl](./printtostringimpl/)(const [Collections::Generic::KeyValuePair](../system.collections.generic/keyvaluepair/)\<T1, T2\>\&, long long) | Stampa una coppia in una stringa. |
| std::enable_if\<[TypeTraits::IsCppContainer](../system.testpredicates.typetraits/iscppcontainer/)\<T\>::value\&&\!std::is_base_of\<[Object](../system/object/), T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | Stampa contenitori in stile STL in una stringa stampando i loro elementi (non più di 32). |
| std::string [PrintToStringImpl](./printtostringimpl/)(const T\&, int) | Stampa altri tipi in una stringa usando le funzioni fornite da gtest. |
| testing::AssertionResult [EqFailure](./eqfailure/)(const char *, const char *, T1\&, T2\&) | Formatta il fallimento dell'asserzione == per l'output. |
| testing::AssertionResult [NotEqFailure](./noteqfailure/)(const char *, const char *, T1\&, T2\&) | Formatta il fallimento dell'asserzione != per l'output. |
| testing::AssertionResult [SameFailure](./samefailure/)(const char *, const char *, T1\&, T2\&) | Formatta il fallimento dell'asserzione 'same' per l'output. |
| testing::AssertionResult [NotSameFailure](./notsamefailure/)(const char *, const char *, T1\&, T2\&) | Formatta il fallimento dell'asserzione 'not same' per l'output. |