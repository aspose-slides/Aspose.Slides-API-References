---
title: PrintToString()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vytiskne objekt do řetězce výběrem vhodné funkce serializátoru.
type: docs
weight: 1
url: /cs/system.testpredicates.details/printtostring/
---
## System::TestPredicates::Details::PrintToString(const T\&) funkce

Vytiskne objekt do řetězce výběrem vhodné funkce serializátoru.

```cpp
template<typename T> std::enable_if_t<!TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) k vytištění. |

### Návratová hodnota

[String](../../system/string/) reprezentace předaného objektu.

## System::TestPredicates::Details::PrintToString(const T\&) funkce

Vytiskne kontejnery ve stylu ICollection do řetězce vytištěním jejich prvků (ne více než 32).

```cpp
template<typename T> std::enable_if_t<TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) k vytištění. |

### Návratová hodnota

Společný řetězcový představování obsažených prvků.

## System::TestPredicates::Details::PrintToString(std::nullptr_t) funkce

Vytiskne nullptr do řetězce.

```cpp
std::string System::TestPredicates::Details::PrintToString(std::nullptr_t)
```

### Návratová hodnota

"nullptr" řetězec.

## System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable\<bool\>\&) funkce

Vytiskne [IEnumerable<bool>](../../system.collections.generic/ienumerable/) kolekce do řetězce vytištěním jejich prvků (ne více než 32).

```cpp
std::string System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable<bool> &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Object](../../system/object/) typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<**bool**\>\& | [Object](../../system/object/) k vytištění. |

### Návratová hodnota

Společné řetězcové reprezentace obsažených prvků.

## Viz také

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Struct [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* Namespace [System::TestPredicates::Details](../)
* Library [Aspose.Slides](../../)