---
title: operator&=()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen değeri sağ taraf argümanı olarak kullanarak, mevcut nesne tarafından temsil edilen değere operator&=() uygular.
type: docs
weight: 274
url: /tr/system/nullable/operator_and_equal/
---
## Nullable::operator&=(bool) metot


[operator&=()](./) öğesini, mevcut nesne tarafından temsil edilen değere, belirtilen değeri sağ taraf argümanı olarak kullanarak uygular.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator&=(bool other)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | SFINAE'nin çalışmasını sağlamak için şablon parametresi. |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| other | **bool** | Mevcut nesne tarafından temsil edilen değere uygulanan [operator&=()](./)'nin sağ taraf değeri olarak kullanılan bir Boolean değerdir. |

### Dönüş Değeri

Kendisine bir referans.

## Bakınız

* Sınıf [Nullable](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)