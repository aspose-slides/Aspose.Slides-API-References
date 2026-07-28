---
title: has_data_method
second_title: Aspose.Slides C++ API referencia
description: "Ellenőrzi, hogy egy típusnak van-e data() metódusa. Ha igen, a std::true_type-t örökli, ellenkező esetben a std::false_type-t örökli."
type: docs
weight: 1
url: /hu/system.testpredicates.typetraits/has_data_method/
---
## has_data_method struct

Ellenőrzi, hogy egy típusnak van-e data() metódusa. Ha igen, a std::true_type-t örökli, egyébként a std::false_type-t.

```cpp
template<typename T,typename Enable>class has_data_method : public std::false_type
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Ellenőrzendő típus. |
| Enable | Formális argumentum a SFINAE működéséhez. |

## Lásd még

* Névtér [System::TestPredicates::TypeTraits](../)
* Könyvtár [Aspose.Slides](../../)