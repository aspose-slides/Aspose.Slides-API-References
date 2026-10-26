---
title: HasOperatorEqualsHelper()
second_title: Aspose.Slides for C++ API Referansı
description: Belirli bir sınıfın operator == içerip içermediğini belirlemek için yardımcı işlev.
type: docs
weight: 235
url: /tr/system.collections.generic.details/hasoperatorequalshelper/
---
## System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *) fonksiyon

Belirli bir sınıfın operator == içerip içermediğini belirlemek için yardımcı işlev.

```cpp
template<class T,typename Dummy> std::true_type System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Kontrol edilecek tip. |
| Dummy | SFINAE sihri için sahte argüman. |

### Dönüş Değeri

Operator == mevcutsa std::true_type değeri, aksi takdirde false.

## System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *) fonksiyon

Belirli bir sınıfın operator == içerip içermediğini belirlemek için yardımcı işlev.

```cpp
std::false_type System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *)
```

### Dönüş Değeri

Operator == mevcutsa std::true_type değeri, aksi takdirde false.

## Ayrıca Bakınız

* Ad alanı [System::Collections::Generic::Details](../)
* Kütüphane [Aspose.Slides](../../)