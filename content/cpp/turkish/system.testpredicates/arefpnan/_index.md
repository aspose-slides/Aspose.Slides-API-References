---
title: AreFPNaN()
second_title: Aspose.Slides için C++ API Referansı
description: ad alanı Details
type: docs
weight: 1
url: /tr/system.testpredicates/arefpnan/
---
## System::TestPredicates::AreFPNaN(T1, T2) fonksiyonu


ad alanı [Details](../../system.testpredicates.details/)

```cpp
template<typename T1,typename T2> std::enable_if<std::numeric_limits<T1>::has_quiet_NaN &&std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | İlk kayan nokta türü. |
| T2 | İkinci kayan nokta türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | T1 | İlk kayan nokta değeri. |
| rhs | T2 | İkinci kayan nokta değeri. |

### Dönüş Değeri

Her iki **lhs** ve **rhs** de kayan nokta değeri ise true, aksi takdirde false.
## Açıklamalar


İki kayan nokta değerinin her ikisinin de NaN olduğunu kontrol eder. Non-signalling NaN desteklendiğinde durumu ele alır. 
## System::TestPredicates::AreFPNaN(T1, T2) fonksiyonu


İki kayan nokta değerinin her ikisinin de NaN olduğunu kontrol eder. Non-signalling NaN desteklenmediğinde durumu ele alır.

```cpp
template<typename T1,typename T2> std::enable_if<!std::numeric_limits<T1>::has_quiet_NaN||!std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | İlk kayan nokta türü. |
| T2 | İkinci kayan nokta türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | T1 | İlk kayan nokta değeri. |
| rhs | T2 | İkinci kayan nokta değeri. |

### Dönüş Değeri

NaN değeri desteklenmediği için her zaman false döndürür.

## Ayrıca Bakınız

* Ad Alanı [System::TestPredicates](../)
* Kütüphane [Aspose.Slides](../../)