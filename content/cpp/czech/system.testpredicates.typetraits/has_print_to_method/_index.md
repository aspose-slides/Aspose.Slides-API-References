---
title: has_print_to_method
second_title: Aspose.Slides pro C++ referenční příručku API
description: "Kontroluje přetížení funkce PrintTo, která přijímá daný typ jako první argument. Pokud přetížení existuje, dědí std::true_type, jinak dědí std::false_type."
type: docs
weight: 27
url: /cs/system.testpredicates.typetraits/has_print_to_method/
---
## has_print_to_method struct

Kontroluje přetížení funkce PrintTo, která přijímá daný typ jako první argument. Pokud přetížení existuje, dědí std::true_type, jinak dědí std::false_type.

```cpp
template<typename T,typename Enable>class has_print_to_method : public std::false_type
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ, který se má zkontrolovat. |
| Enable | Formální argument pro fungování SFINAE. |

## Viz také

* jmenný prostor [System::TestPredicates::TypeTraits](../)
* Knihovna [Aspose.Slides](../../)