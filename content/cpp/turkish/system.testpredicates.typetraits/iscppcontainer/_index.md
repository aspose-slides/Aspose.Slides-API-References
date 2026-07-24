---
title: IsCppContainer
second_title: Aspose.Slides için C++ API Referansı
description: "Belirli bir tipin STL tarzı konteyner olup olmadığını denetler. Bunu yapmak için iterator ve const_iterator üye tiplerinin varlığı kontrol edilir. İkisi de mevcutsa std::true_type miras alınır, aksi takdirde std::false_type miras alınır."
type: docs
weight: 40
url: /tr/system.testpredicates.typetraits/iscppcontainer/
---
## IsCppContainer struct

Belirli bir tipin STL-stil konteyner olup olmadığını denetler. Bunu yapmak için iterator ve const_iterator üye tiplerinin varlığı kontrol edilir. İkisi de mevcutsa std::true_type miras alınır, aksi takdirde std::false_type miras alınır.

```cpp
template<typename T,typename Enable>class IsCppContainer : public std::false_type
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Kontrol edilecek tip. |
| Enable | SFINAE'in çalışması için formal argüman. |

## Diğer Bağlantılar

* Ad Alanı [System::TestPredicates::TypeTraits](../)
* Kütüphane [Aspose.Slides](../../)