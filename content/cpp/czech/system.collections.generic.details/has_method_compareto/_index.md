---
title: has_method_compareto
second_title: Aspose.Slides pro C++ referenční příručka API
description: "Kontroluje, zda metoda CompareTo existuje v určeném typu. Pokud ano, dědí std::true_type, jinak dědí std::false_type. Lze použít ve std::enable_if."
type: docs
weight: 170
url: /cs/system.collections.generic.details/has_method_compareto/
---
## has_method_compareto struct

Kontroluje, zda metoda CompareTo existuje ve zadaném typu. Pokud ano, dědí std::true_type, jinak dědí std::false_type. Lze použít ve std::enable_if.

```cpp
template<typename T,typename Sfinae>class has_method_compareto : public std::false_type
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ, jehož existence metody Equals se kontroluje. |
| Sfinae | Formální argument šablony pro fungování SFINAE. |

## Viz také

* Jmenný prostor [System::Collections::Generic::Details](../)
* Knihovna [Aspose.Slides](../../)