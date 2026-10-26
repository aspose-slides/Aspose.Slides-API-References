---
title: has_method_compareto_shared_ptr
second_title: Aspose.Slides C++ API referencia
description: "Ellenőrzi, hogy a megadott típusban létezik-e a CompareTo(SharedPtr<T>) metódus. Ha igen, a std::true_type-ot örökli, ellenkező esetben a std::false_type-ot. Használható a std::enable_if-ben."
type: docs
weight: 183
url: /hu/system.collections.generic.details/has_method_compareto_shared_ptr/
---
## has_method_compareto_shared_ptr struct


Ellenőrzi, hogy a megadott típusban létezik-e a CompareTo(SharedPtr<T>) metódus. Ha igen, a std::true_type-ot örökli, ellenkező esetben a std::false_type-ot. Használható a std::enable_if-ben.

```cpp
template<typename T,typename Sfinae>class has_method_compareto_shared_ptr : public std::false_type
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Típus, amelynél ellenőrizni kell az Equals metódus létezését. |
| Sfinae | Formális sablonargumentum a SFINAE működéséhez. |

## Lásd még

* Névtér [System::Collections::Generic::Details](../)
* Könyvtár [Aspose.Slides](../../)