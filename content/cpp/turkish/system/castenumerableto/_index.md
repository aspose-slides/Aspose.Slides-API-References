---
title: CastEnumerableTo()
second_title: Aspose.Slides C++ API Referansı
description: Belirtilen enumerable nesnenin öğelerinin farklı bir tipe açıkça dönüştürülmesini gerçekleştirir.
type: docs
weight: 2965
url: /tr/system/castenumerableto/
---
## System::CastEnumerableTo(const From\&) function

Belirtilen enumerable nesnenin öğelerinin farklı bir tipe açıkça dönüştürülmesini gerçekleştirir.

```cpp
template<class To,class From> std::enable_if<!System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| To | Enumerable nesnesinin öğelerinin statik olarak dönüştürüleceği tip |
| From | Enumerable nesnenin tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| enumerable | const From\& | Dönüştürülecek öğeleri içeren enumerable nesne |

### Dönüş Değeri

**enumerable**'in öğelerine eşdeğer **To** tipinde olan yeni bir koleksiyona işaretçi

## System::CastEnumerableTo(const From\&) function

Belirtilen enumerable nesnenin öğelerinin farklı bir tipe açıkça dönüştürülmesini gerçekleştirir.

```cpp
template<class To,class From> std::enable_if<System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| To | Enumerable nesnesinin öğelerinin statik olarak dönüştürüleceği tip |
| From | Enumerable nesnenin tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| enumerable | const From\& | get_Count yöntemi tanımlı Enumerable nesnesinin türevi olup, dönüştürülecek öğeleri içerir |

### Dönüş Değeri

**enumerable**'in öğelerine eşdeğer **To** tipinde olan yeni bir koleksiyona işaretçi

## Ayrıca Bakınız

* Sınıf [ListPtr](../../system.collections.generic/listptr/)
* Ad Alanı [System](../)
* Kütüphane [Aspose.Slides](../../)