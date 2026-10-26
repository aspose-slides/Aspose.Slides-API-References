---
title: operator|=()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen değeri sağ taraf argümanı olarak kullanarak, geçerli nesne tarafından temsil edilen değere operator|=() uygular.
type: docs
weight: 261
url: /tr/system/nullable/operator_or_equal/
---
## Nullable::operator|=(bool) yöntemi

[operator|=()](./) öğesini, belirtilen değeri sağ taraf argümanı olarak kullanarak geçerli nesne tarafından temsil edilen değere uygular.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator|=(bool other)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | SFINAE'in çalışmasını sağlamak için şablon parametresi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | **bool** | Geçerli nesne tarafından temsil edilen değere uygulanan [operator|=()](./)'nin sağ taraf değeri olarak kullanılan bir boolean değer. |

### Dönüş Değeri

Kendisine bir referans.

## İlgili

* Sınıf [Nullable](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)