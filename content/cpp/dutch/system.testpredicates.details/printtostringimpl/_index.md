---
title: PrintToStringImpl()
second_title: Aspose.Slides voor C++ API Referentie
description: "Print een System::Object subklasse naar een string met behulp van de ToString()-methode."
type: docs
weight: 14
url: /nl/system.testpredicates.details/printtostringimpl/
---
## System::TestPredicates::Details::PrintToStringImpl(const SharedPtr\<T\>\&, long long) function

Print de [System::Object](../../system/object/) subklasse naar een string met behulp van de ToString()-methode.

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const SharedPtr<T> &value, long long s)
```

### Template parameters

| Parameter | Beschrijving |
| --- | --- |
| T | Final class type. |

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Pointer to object to print. |
| s | long long | Een serviceparameter die dient als selector voor functie-overloads op basis van het type van deze parameter; de waarde van de parameter wordt genegeerd |

### Retourwaarde

[String](../../system/string/) representation of object passed or \"nullptr\", if **value** is null.

## System::TestPredicates::Details::PrintToStringImpl(const WeakPtr\<T\>\&, long long) function

Print de [System::Object](../../system/object/) subklasse naar een string met behulp van de ToString()-methode.

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const WeakPtr<T> &value, long long s)
```

### Template parameters

| Parameter | Beschrijving |
| --- | --- |
| T | Final class type. |

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [WeakPtr](../../system/weakptr/)\<T\>\& | Pointer to object to print. |
| s | long long | Een serviceparameter die dient als selector voor functie-overloads op basis van het type van deze parameter; de waarde van de parameter wordt genegeerd |

### Retourwaarde

[String](../../system/string/) representation of object passed or \"nullptr\", if **value** is null.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) function

Print een object naar een string met behulp van de ToString()-methode.

```cpp
template<typename T> std::enable_if<!TypeTraits::has_print_to_method<T>::value &&System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### Template parameters

| Parameter | Beschrijving |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) om te printen. |
| s | long long | Een serviceparameter die dient als selector voor functie-overloads op basis van het type van deze parameter; de waarde van de parameter wordt genegeerd |

### Retourwaarde

[String](../../system/string/) representation of object passed.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) function

Print een object naar een string met behulp van de PrintTo-methode.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&!TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### Template parameters

| Parameter | Beschrijving |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) om te printen. |
| s | long long | Een serviceparameter die dient als selector voor functie-overloads op basis van het type van deze parameter; de waarde van de parameter wordt genegeerd |

### Retourwaarde

[String](../../system/string/) representatie van het doorgegeven object.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) function

Print een object naar een string met behulp van de PrintTo-methode.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### Template parameters

| Parameter | Beschrijving |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) om te printen. |
| s | long long | Een serviceparameter die dient als selector voor functie-overloads op basis van het type van deze parameter; de waarde van de parameter wordt genegeerd |

### Retourwaarde

[String](../../system/string/) representatie van het doorgegeven object.

## System::TestPredicates::Details::PrintToStringImpl(const std::pair\<T1, T2\>\&, long long) function

Print een paar naar een string.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const std::pair<T1, T2> &value, long long s)
```

### Template parameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | Eerste type-argument van het paar. |
| T2 | Tweede type-argument van het paar. |

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const std::pair\<T1, T2\>\& | [Object](../../system/object/) om te printen. |
| s | long long | Een serviceparameter die dient als selector voor functie-overloads op basis van het type van deze parameter; de waarde van de parameter wordt genegeerd |

### Retourwaarde

Samengevoegde stringrepresentaties van zowel het eerste als het tweede paar-component.

## System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair\<T1, T2\>\&, long long) function

Print een paar naar een string.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair<T1, T2> &value, long long s)
```

### Template parameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | Eerste type-argument van het paar. |
| T2 | Tweede type-argument van het paar. |

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<T1, T2\>\& | [Object](../../system/object/) om te printen. |
| s | long long | Een serviceparameter die dient als selector voor functie-overloads op basis van het type van deze parameter; de waarde van de parameter wordt genegeerd |

### Retourwaarde

Samengevoegde stringrepresentaties van zowel het eerste als het tweede paar-component.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) function

Print STL-achtige containers naar een string door hun elementen af te drukken (maximaal 32).

```cpp
template<typename T> std::enable_if<TypeTraits::IsCppContainer<T>::value &&!std::is_base_of<Object, T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &container, long long s)
```

### Template parameters

| Parameter | Beschrijving |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| container | const T\& | [Object](../../system/object/) om te printen. |
| s | long long | Een serviceparameter die dient als selector voor functie-overloads op basis van het type van deze parameter; de waarde van de parameter wordt genegeerd |

### Retourwaarde

Samengevoegde stringrepresentaties van de bevatte elementen.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, int) function

Print andere typen naar een string met behulp van door gtest geleverde functies.

```cpp
template<typename T> std::string System::TestPredicates::Details::PrintToStringImpl(const T &value, int s)
```

### Template parameters

| Parameter | Beschrijving |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) om te printen. |
| s | int | Een serviceparameter die dient als selector voor functie-overloads op basis van het type van deze parameter; de waarde van de parameter wordt genegeerd |

### Retourwaarde

[String](../../system/string/) representaties van het doorgegeven object.

## Zie ook

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [WeakPtr](../../system/weakptr/)
* Class [KeyValuePair](../../system.collections.generic/keyvaluepair/)
* Class [Object](../../system/object/)
* Struct [has_print_to_method](../../system.testpredicates.typetraits/has_print_to_method/)
* Struct [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* Struct [IsCppContainer](../../system.testpredicates.typetraits/iscppcontainer/)
* Namespace [System::TestPredicates::Details](../)
* Library [Aspose.Slides](../../)