---
title: IsBoxable
second_title: Aspose.Slides pro C++ API Reference
description: Predikát šablony, který kontroluje, zda je pro zadaný typ podporováno boxing.
type: docs
weight: 1665
url: /cs/system/isboxable/
---
## IsBoxable struct

Predikát šablony, který kontroluje, zda je pro zadaný typ podporováno boxing.

```cpp
template<typename T>class IsBoxable : public std::integral_constant<bool, std::is_base_of<Details::BoxableObjectBase, T>::value||std::is_arithmetic<T>::value||std::is_enum<T>::value>
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ, který se má zkontrolovat |

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)