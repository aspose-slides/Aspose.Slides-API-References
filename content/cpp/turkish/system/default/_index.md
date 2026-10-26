---
title: Default()
second_title: Aspose.Slides for C++ API Referansı
description: İstisna tipinin tek varsayılan oluşturulmuş örneğine referansı döndürür.
type: docs
weight: 2224
url: /tr/system/default/
---
## System::Default() fonksiyonu

İstisna tipinin tek varsayılan oluşturulmuş örneğine referansı döndürür.

```cpp
template<typename T> std::enable_if<IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Örneği döndürülen tip |

## System::Default() fonksiyonu

İstisna olmayan tipin tek varsayılan oluşturulmuş örneğine referansı döndürür.

```cpp
template<typename T> std::enable_if<!IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Örneği döndürülen tip |

## Ayrıca Bakınız

* Struct [IsExceptionWrapper](../isexceptionwrapper/)
* Namespace [System](../)
* Kütüphane [Aspose.Slides](../../)