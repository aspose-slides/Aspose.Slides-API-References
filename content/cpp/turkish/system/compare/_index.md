---
title: Compare()
second_title: Aspose.Slides for C++ API Referansı
description: İki değeri karşılaştırır.
type: docs
weight: 2731
url: /tr/system/compare/
---
## System::Compare(const TA\&, const TB\&) fonksiyon

İki değeri karşılaştırır.

```cpp
template<typename TA,typename TB> std::enable_if_t<!std::is_floating_point<TA>::value &&!std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TA | İlk karşılaştırılanın tipi |
| TB | İkinci karşılaştırılanın tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | const TA\& | İlk karşılaştırılan |
| b | const TB\& | İkinci karşılaştırılan |

### Dönüş Değeri

- 1 eğer **a** **b**'den daha az karşılaştırıyorsa; 0 eğer değerler eşitse; 1 eğer **a** **b**'den daha büyük karşılaştırıyorsa

## System::Compare(const TA\&, const TB\&) fonksiyon

İki kayan nokta değerini karşılaştırır.

```cpp
template<typename TA,typename TB> std::enable_if_t<std::is_floating_point<TA>::value &&std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TA | İlk karşılaştırılanın tipi |
| TB | İkinci karşılaştırılanın tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | const TA\& | İlk karşılaştırılan |
| b | const TB\& | İkinci karşılaştırılan |

### Dönüş Değeri

- 1 eğer **a** **b**'den daha az karşılaştırıyorsa; 0 eğer değerler eşitse; 1 eğer **a** **b**'den daha büyük karşılaştırıyorsa

## Bakınız

* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)