---
title: GetDescription()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen değere sahip enum sabitinin adını döndürür.
type: docs
weight: 53
url: /tr/system/enum/getdescription/
---
## Enum::GetDescription(T) metodu

Belirtilen değere sahip enum sabitinin adını döndürür.

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetDescription(T value)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | T | Adı döndürülecek enum sabitinin değeri |

### Dönüş Değeri

Belirtilen enum sabitinin adı

## Ayrıca Bakınız

* Tip Tanımı [UnderlyingType](../underlyingtype/)
* Sınıf [String](../../string/)
* Yapı [Enum](../)
* Ad Alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)