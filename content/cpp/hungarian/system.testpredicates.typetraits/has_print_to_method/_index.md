---
title: has_print_to_method
second_title: Aspose.Slides C++ API referenciája
description: "Ellenőrzi, hogy létezik-e a PrintTo függvény túlterhelése, amely az adott típust első argumentumként fogadja. Ha van ilyen túlterhelés, a std::true_type-ból örököl, egyébként a std::false_type-ból."
type: docs
weight: 27
url: /hu/system.testpredicates.typetraits/has_print_to_method/
---
## has_print_to_method struct

Ellenőrzi, hogy létezik-e a PrintTo függvény túlterhelése, amely az adott típust első argumentumként fogadja. Ha van ilyen túlterhelés, a std::true_type-ból örököl, egyébként a std::false_type-ból.

```cpp
template<typename T,typename Enable>class has_print_to_method : public std::false_type
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | Ellenőrzendő típus. |
| Enable | Formális argumentum a SFINAE működéséhez. |

## Lásd még

* Névtér [System::TestPredicates::TypeTraits](../)
* Könyvtár [Aspose.Slides](../../)