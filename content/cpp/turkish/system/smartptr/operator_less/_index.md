---
title: operator<()
second_title: Aspose.Slides for C++ API Referansı
description: SmartPtr sınıfı için daha az karşılaştırma semantiği sağlar.
type: docs
weight: 235
url: /tr/system/smartptr/operator_less/
---
## SmartPtr::operator<(Y *) const metod

[SmartPtr](../) sınıfı için daha az karşılaştırma semantiği sağlar.

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(Y *p) const
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Y | Mevcut işaretçi ile karşılaştırılacak işaretçi türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| p | Y * | Mevcut işaretçi ile karşılaştırılacak işaretçi. |

### Dönüş Değeri

Doğru, [SmartPtr](../) tarafından referans verilen nesne p'den 'daha az' ise ve aksi takdirde yanlış.

## SmartPtr::operator<(SmartPtr\<Y\> const\&) const metod

[SmartPtr](../) sınıfı için daha az karşılaştırma semantiği sağlar.

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(SmartPtr<Y> const &x) const
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Y | Mevcut işaretçi ile karşılaştırılacak işaretçi türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | [SmartPtr](../)\<Y\> const\& | Mevcut işaretçi ile karşılaştırılacak işaretçi. |

### Dönüş Değeri

Doğru, [SmartPtr](../) tarafından referans verilen nesne x'ten 'daha az' ise ve aksi takdirde yanlış.

## Bakınız

* Sınıf [SmartPtr](../)
* İsim alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)