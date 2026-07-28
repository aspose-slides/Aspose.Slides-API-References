---
title: IsCppContainer
second_title: Aspose.Slides for C++ API referencia
description: "Ellenőrzi, hogy a megadott típus STL-stílusú tároló-e. Ehhez ellenőrzi az iterator és const_iterator tagság típusok meglétét. Ha mindkettő létezik, a std::true_type-ból örököl, különben a std::false_type-ból."
type: docs
weight: 40
url: /hu/system.testpredicates.typetraits/iscppcontainer/
---
## IsCppContainer struct

Ellenőrzi, hogy a megadott típus STL-stílusú tároló-e. Ehhez ellenőrzi, hogy léteznek-e az iterator és const_iterator tagság típusok. Ha mindkettő létezik, a std::true_type-ból örököl, ellenkező esetben a std::false_type-ból.

```cpp
template<typename T,typename Enable>class IsCppContainer : public std::false_type
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Ellenőrzendő típus. |
| Enable | Formális argumentum a SFINAE működéséhez. |

## Lásd még

* Névtere [System::TestPredicates::TypeTraits](../)
* Könyvtár [Aspose.Slides](../../)