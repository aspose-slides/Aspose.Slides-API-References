---
title: Default()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vrací referenci na jedinou výchozí konstrukci instance typu výjimky.
type: docs
weight: 2224
url: /cs/system/default/
---
## System::Default() funkce

Vrací referenci na jedinou výchozí konstrukci instance typu výjimky.

```cpp
template<typename T> std::enable_if<IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ, jehož instance je vrácena |

## System::Default() funkce

Vrací referenci na jedinou výchozí konstrukci instance ne-výjimečného typu.

```cpp
template<typename T> std::enable_if<!IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ, jehož instance je vrácena |

## Viz také

* Struct [IsExceptionWrapper](../isexceptionwrapper/)
* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)