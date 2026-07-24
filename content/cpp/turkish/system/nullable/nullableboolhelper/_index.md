---
title: NullableBoolHelper()
second_title: Aspose.Slides için C++ API Referansı
description: Bu ve other'in ikisinin de null olmadığı durumları kontrol eden ve öyleyse bir lambda çağıran yardımcı fonksiyon. implementation.s içinde kullanılır.
type: docs
weight: 105
url: /tr/system/nullable/nullableboolhelper/
---
## Nullable::NullableBoolHelper(const T1\&, const std::function\<bool()>\&, bool) const metodu

Bu ve **other** değerlerinin ikisinin de null olmadığını kontrol eden ve böyleyse bir lambda çağıran yardımcı fonksiyon. Uygulamalarda kullanılır.

```cpp
template<typename T1> bool System::Nullable<T>::NullableBoolHelper(const T1 &other, const std::function<bool()> &f, bool default_if_both_are_null=false) const
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | Diğer null olabilen tip. |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| other | const T1\& | Karşılaştırılacak diğer null olabilen değer. |
| f | const std::function\<**bool**()>\& | Hem **this** hem de **other** null değilse çağrılacak lambda. |
| default_if_both_are_null | **bool** | Her iki değer de null ise döndürülecek değer. |

### Dönüş Değeri

Eğer **this** veya **other** null ise false; her ikisi de null ise **default_if_both_are_null**; ikisi de null değilse **f** çağrısının sonucu.

## Ayrıca Bakınız

* Sınıf [Nullable](../)
* İsim Alanı [System](../../)
* Kitaplık [Aspose.Slides](../../../)