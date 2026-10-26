---
title: PrintToStringImpl()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Vytiskne podtřídu System::Object do řetězce pomocí metody ToString()."
type: docs
weight: 14
url: /cs/system.testpredicates.details/printtostringimpl/
---
## System::TestPredicates::Details::PrintToStringImpl(const SharedPtr\<T\>\&, long long) function

Vytiskne podtřídu [System::Object](../../system/object/) do řetězce pomocí metody ToString().

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const SharedPtr<T> &value, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Konečný typ třídy. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Ukazatel na objekt k vytištění. |
| s | long long | Služební parametr, který slouží jako selektor přetížení funkce na základě typu tohoto parametru; hodnota parametru je ignorována |

### Návratová hodnota

[String](../../system/string/) reprezentace předaného objektu nebo "nullptr", pokud je **value** null.

## System::TestPredicates::Details::PrintToStringImpl(const WeakPtr\<T\>\&, long long) function

Vytiskne podtřídu [System::Object](../../system/object/) do řetězce pomocí metody ToString().

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const WeakPtr<T> &value, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Konečný typ třídy. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [WeakPtr](../../system/weakptr/)\<T\>\& | Ukazatel na objekt k vytištění. |
| s | long long | Služební parametr, který slouží jako selektor přetížení funkce na základě typu tohoto parametru; hodnota parametru je ignorována |

### Návratová hodnota

[String](../../system/string/) reprezentace předaného objektu nebo "nullptr", pokud je **value** null.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) function

Vytiskne objekt do řetězce pomocí metody ToString().

```cpp
template<typename T> std::enable_if<!TypeTraits::has_print_to_method<T>::value &&System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) k vytištění. |
| s | long long | Služební parametr, který slouží jako selektor přetížení funkce na základě typu tohoto parametru; hodnota parametru je ignorována |

### Návratová hodnota

[String](../../system/string/) reprezentace předaného objektu.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) function

Vytiskne objekt do řetězce pomocí metody PrintTo.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&!TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) k vytištění. |
| s | long long | Služební parametr, který slouží jako selektor přetížení funkce na základě typu tohoto parametru; hodnota parametru je ignorována |

### Návratová hodnota

[String](../../system/string/) reprezentace předaného objektu.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) function

Vytiskne objekt do řetězce pomocí metody PrintTo.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) k vytištění. |
| s | long long | Služební parametr, který slouží jako selektor přetížení funkce na základě typu tohoto parametru; hodnota parametru je ignorována |

### Návratová hodnota

[String](../../system/string/) reprezentace předaného objektu.

## System::TestPredicates::Details::PrintToStringImpl(const std::pair\<T1, T2\>\&, long long) function

Vytiskne dvojici do řetězce.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const std::pair<T1, T2> &value, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | První typový argument dvojice. |
| T2 | Druhý typový argument dvojice. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const std::pair\<T1, T2\>\& | [Object](../../system/object/) k vytištění. |
| s | long long | Služební parametr, který slouží jako selektor přetížení funkce na základě typu tohoto parametru; hodnota parametru je ignorována |

### Návratová hodnota

Společná řetězcová reprezentace obou komponent první a druhé dvojice.

## System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair\<T1, T2\>\&, long long) function

Vytiskne dvojici do řetězce.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair<T1, T2> &value, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | První typový argument dvojice. |
| T2 | Druhý typový argument dvojice. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<T1, T2\>\& | [Object](../../system/object/) k vytištění. |
| s | long long | Služební parametr, který slouží jako selektor přetížení funkce na základě typu tohoto parametru; hodnota parametru je ignorována |

### Návratová hodnota

Společná řetězcová reprezentace obou komponent první a druhé dvojice.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) function

Vytiskne kontejnery ve stylu STL do řetězce tím, že vytiskne jejich prvky (maximálně 32).

```cpp
template<typename T> std::enable_if<TypeTraits::IsCppContainer<T>::value &&!std::is_base_of<Object, T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &container, long long s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| container | const T\& | [Object](../../system/object/) k vytištění. |
| s | long long | Služební parametr, který slouží jako selektor přetížení funkce na základě typu tohoto parametru; hodnota parametru je ignorována |

### Návratová hodnota

Společná řetězcová reprezentace obsažených prvků.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, int) function

Vytiskne jiné typy do řetězce pomocí funkcí poskytovaných gtestem.

```cpp
template<typename T> std::string System::TestPredicates::Details::PrintToStringImpl(const T &value, int s)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) k vytištění. |
| s | int | Služební parametr, který slouží jako selektor přetížení funkce na základě typu tohoto parametru; hodnota parametru je ignorována |

### Návratová hodnota

[String](../../system/string/) reprezentace předaného objektu.

## Viz také

* Typedef [SharedPtr](../../system/sharedptr/)
* Třída [WeakPtr](../../system/weakptr/)
* Třída [KeyValuePair](../../system.collections.generic/keyvaluepair/)
* Třída [Object](../../system/object/)
* Struct [has_print_to_method](../../system.testpredicates.typetraits/has_print_to_method/)
* Struct [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* Struct [IsCppContainer](../../system.testpredicates.typetraits/iscppcontainer/)
* Jmenný prostor [System::TestPredicates::Details](../)
* Library [Aspose.Slides](../../)