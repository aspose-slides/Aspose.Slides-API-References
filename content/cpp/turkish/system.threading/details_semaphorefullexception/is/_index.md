---
title: Is()
second_title: Aspose.Slides için C++ API Referansı
description: 
type: docs
weight: 27
url: /tr/system.threading/details_semaphorefullexception/is/
---
## Ayrıntılar_SemaphoreFullException::Is(const System::TypeInfo\&) const yöntem

```cpp
bool System::Threading::Details_SemaphoreFullException::Is(const System::TypeInfo &target) const override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) yapısı, geçerli nesneyi test etmek için kullanılacak türü tanımlar. |

### Dönüş Değeri

Nesne işaretli türde veya onun alt sınıfındaysa True, aksi takdirde false.

## Açıklamalar

Nesnenin targetType tarafından tanımlanan türe ait bir örnek olup olmadığını kontrol eder. C# 'is' operatörünün benzeri.

## Ayrıca

* Sınıf [TypeInfo](../../../system/typeinfo/)
* Sınıf [Details_SemaphoreFullException](../)
* AdAlanı [System::Threading](../../)
* Kütüphane [Aspose.Slides](../../../)