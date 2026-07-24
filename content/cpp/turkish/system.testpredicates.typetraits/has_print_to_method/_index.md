---
title: has_print_to_method
second_title: Aspose.Slides for C++ API Referansı
description: "PrintTo işlevinin verilen tipi ilk argüman olarak kabul eden bir aşırı yüklendiğini kontrol eder. Eğer bir aşırı yükleme varsa, std::true_type miras alır, aksi takdirde std::false_type miras alır."
type: docs
weight: 27
url: /tr/system.testpredicates.typetraits/has_print_to_method/
---
## has_print_to_method struct

Checks for overload of PrintTo function that accepts given type as first argument. If an overload exists, inherits std::true_type, otherwise inheirts std::false_type.

```cpp
template<typename T,typename Enable>class has_print_to_method : public std::false_type
```

### Şablon parametreleri

| Parameter | Description |
| --- | --- |
| T | Kontrol edilecek tür. |
| Enable | SFINAE'nin çalışması için resmi argüman. |

## İlgili

* Ad alanı [System::TestPredicates::TypeTraits](../)
* Kütüphane [Aspose.Slides](../../)