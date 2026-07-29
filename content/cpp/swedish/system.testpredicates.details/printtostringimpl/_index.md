---
title: PrintToStringImpl()
second_title: Aspose.Slides för C++ API-referens
description: "Skriver ut System::Object underklass till en sträng med metoden ToString()."
type: docs
weight: 14
url: /sv/system.testpredicates.details/printtostringimpl/
---
## System::TestPredicates::Details::PrintToStringImpl(const SharedPtr\<T\>\&, long long) funktion


Skriver ut [System::Object](../../system/object/) underklass till en sträng med metoden ToString().

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const SharedPtr<T> &value, long long s)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Slutlig klasstyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Pekare till objekt som ska skrivas ut. |
| s | long long | En serviceparameter som fungerar som en selektor för funktionsöverladdning baserat på typen av denna parameter; parametervärdet ignoreras |

### Returvärde

[String](../../system/string/) representation av det skickade objektet eller "nullptr", om **value** är null.

## System::TestPredicates::Details::PrintToStringImpl(const WeakPtr\<T\>\&, long long) funktion


Skriver ut [System::Object](../../system/object/) underklass till en sträng med metoden ToString().

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const WeakPtr<T> &value, long long s)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Slutlig klasstyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [WeakPtr](../../system/weakptr/)\<T\>\& | Pekare till objekt som ska skrivas ut. |
| s | long long | En serviceparameter som fungerar som en selektor för funktionsöverladdning baserat på typen av denna parameter; parametervärdet ignoreras |

### Returvärde

[String](../../system/string/) representation av det skickade objektet eller "nullptr", om **value** är null.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) funktion


Skriver ut objekt till en sträng med metoden ToString().

```cpp
template<typename T> std::enable_if<!TypeTraits::has_print_to_method<T>::value &&System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) att skriva ut. |
| s | long long | En serviceparameter som fungerar som en selektor för funktionsöverladdning baserat på typen av denna parameter; parametervärdet ignoreras |

### Returvärde

[String](../../system/string/) representation av det skickade objektet.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) funktion


Skriver ut objekt till en sträng med metoden PrintTo.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&!TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) att skriva ut. |
| s | long long | En serviceparameter som fungerar som en selektor för funktionsöverladdning baserat på typen av denna parameter; parametervärdet ignoreras |

### Returvärde

[String](../../system/string/) representation av det skickade objektet.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) funktion


Skriver ut objekt till en sträng med metoden PrintTo.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) att skriva ut. |
| s | long long | En serviceparameter som fungerar som en selektor för funktionsöverladdning baserat på typen av denna parameter; parametervärdet ignoreras |

### Returvärde

[String](../../system/string/) representation av det skickade objektet.

## System::TestPredicates::Details::PrintToStringImpl(const std::pair\<T1, T2\>\&, long long) funktion


Skriver ut par till en sträng.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const std::pair<T1, T2> &value, long long s)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | Första typargumentet för paret. |
| T2 | Andra typargumentet för paret. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const std::pair\<T1, T2\>\& | [Object](../../system/object/) att skriva ut. |
| s | long long | En serviceparameter som fungerar som en selektor för funktionsöverladdning baserat på typen av denna parameter; parametervärdet ignoreras |

### Returvärde

Gemensamma strängrepresentationer av både första och andra parkomponenterna.

## System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair\<T1, T2\>\&, long long) funktion


Skriver ut par till en sträng.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair<T1, T2> &value, long long s)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | Första typargumentet för paret. |
| T2 | Andra typargumentet för paret. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<T1, T2\>\& | [Object](../../system/object/) att skriva ut. |
| s | long long | En serviceparameter som fungerar som en selektor för funktionsöverladdning baserat på typen av denna parameter; parametervärdet ignoreras |

### Returvärde

Gemensamma strängrepresentationer av både första och andra parkomponenterna.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) funktion


Skriver ut STL-liknande behållare till en sträng genom att skriva ut deras element (maximalt 32).

```cpp
template<typename T> std::enable_if<TypeTraits::IsCppContainer<T>::value &&!std::is_base_of<Object, T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &container, long long s)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| container | const T\& | [Object](../../system/object/) att skriva ut. |
| s | long long | En serviceparameter som fungerar som en selektor för funktionsöverladdning baserat på typen av denna parameter; parametervärdet ignoreras |

### Returvärde

Gemensamma strängrepresentationer av de innehållna elementen.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, int) funktion


Skriver ut andra typer till en sträng genom att använda gtest-funktioner.

```cpp
template<typename T> std::string System::TestPredicates::Details::PrintToStringImpl(const T &value, int s)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) att skriva ut. |
| s | int | En serviceparameter som fungerar som en selektor för funktionsöverladdning baserat på typen av denna parameter; parametervärdet ignoreras |

### Returvärde

[String](../../system/string/) representationer av det skickade objektet.

## Se även

* Typdefinition [SharedPtr](../../system/sharedptr/)
* Klass [WeakPtr](../../system/weakptr/)
* Klass [KeyValuePair](../../system.collections.generic/keyvaluepair/)
* Klass [Object](../../system/object/)
* Struktur [has_print_to_method](../../system.testpredicates.typetraits/has_print_to_method/)
* Struktur [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* Struktur [IsCppContainer](../../system.testpredicates.typetraits/iscppcontainer/)
* Namnrymd [System::TestPredicates::Details](../)
* Bibliotek [Aspose.Slides](../../)