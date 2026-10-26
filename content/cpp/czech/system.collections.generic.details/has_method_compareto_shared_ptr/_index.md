---
title: has_method_compareto_shared_ptr
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Kontroluje, zda metoda CompareTo(SharedPtr<T>) existuje v určeném typu. Pokud ano, dědí std::true_type, jinak dědí std::false_type. Lze použít ve std::enable_if."
type: docs
weight: 183
url: /cs/system.collections.generic.details/has_method_compareto_shared_ptr/
---
## has_method_compareto_shared_ptr struct


Zjišťuje, zda metoda CompareTo(SharedPtr<T>) existuje ve zadaném typu. Pokud ano, dědí std::true_type, jinak dědí std::false_type. Lze použít v std::enable_if.

```cpp
template<typename T,typename Sfinae>class has_method_compareto_shared_ptr : public std::false_type
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ, u kterého se kontroluje existence metody Equals. |
| Sfinae | Formální argument šablony pro fungování SFINAE. |

## Viz také

* Namespace [System::Collections::Generic::Details](../)
* Library [Aspose.Slides](../../)