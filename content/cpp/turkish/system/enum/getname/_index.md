---
title: GetName()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen değere sahip enum sabitinin adını döndürür.
type: docs
weight: 40
url: /tr/system/enum/getname/
---
## Enum::GetName(T) metod

Belirtilen değere sahip enum sabitının adını döndürür.

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetName(T value)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | T | Adı döndürülecek enum sabitinin değeri |

### Dönüş Değeri

Belirtilen enum sabitinin adı

## Ayrıca Bakınız

* Typedef [UnderlyingType](../underlyingtype/)
* Sınıf [String](../../string/)
* Yapı [Enum](../)
* AdAlanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)