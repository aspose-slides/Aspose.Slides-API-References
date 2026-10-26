---
title: MakeSharedPtr()
second_title: Aspose.Slides for C++ API Referansı
description: Ham işaretçiyi akıllı işaretçiye dönüştürür.
type: docs
weight: 2900
url: /tr/system/makesharedptr/
---
## System::MakeSharedPtr(X *) fonksiyon

Ham işaretçiyi akıllı işaretçiye dönüştürür.

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(X *p)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| X | İşaret edilen tip. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| p | X * | Nesneye ait ham işaretçi. |

### Dönüş Değeri

Nesneye ait paylaşımlı akıllı işaretçi.

## System::MakeSharedPtr(const X *) fonksiyon

Ham işaretçiyi akıllı işaretçiye dönüştürür. Const işaretçiler için aşırı yük. Örneğin C# metodlarında 'this' değişkeni const olarak çevrildiğinde yararlıdır.

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(const X *p)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| X | İşaret edilen tip. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| p | const X * | Nesneye ait ham işaretçi. |

### Dönüş Değeri

Nesneye ait paylaşımlı akıllı işaretçi.

## Ayrıca Bakınız

* Sınıf [SmartPtr](../smartptr/)
* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)