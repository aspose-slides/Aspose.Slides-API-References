---
title: IsBoxable
second_title: Aspose.Slides C++ API referencia
description: Sablonpredikátum, amely ellenőrzi, hogy a megadott típus dobozolása támogatott-e.
type: docs
weight: 1665
url: /hu/system/isboxable/
---
## IsBoxable struct

Sablonpredikátum, amely ellenőrzi, hogy a megadott típus dobozolása támogatott-e.

```cpp
template<typename T>class IsBoxable : public std::integral_constant<bool, std::is_base_of<Details::BoxableObjectBase, T>::value||std::is_arithmetic<T>::value||std::is_enum<T>::value>
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az ellenőrzendő típus |

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)