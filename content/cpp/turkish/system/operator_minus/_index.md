---
title: operator-()
second_title: Aspose.Slides for C++ API Referansı
description: İki hafta günü arasındaki gün sayısını hesaplar.
type: docs
weight: 2172
url: /tr/system/operator_minus/
---
## System::operator-(DayOfWeek, DayOfWeek) fonksiyon


İki hafta gününün arasındaki gün sayısını hesaplar.

```cpp
auto System::operator-(DayOfWeek a, DayOfWeek b)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [DayOfWeek](../dayofweek/) | The minuend |
| b | [DayOfWeek](../dayofweek/) | The subtrahend |

### Dönüş Değeri

Hafta içi **a** ve **b** arasındaki gün sayısı; dönüş değeri *goes* sonrasında **** negatif bir sayıdır.

## System::operator-(const T\&, const Decimal\&) fonksiyon


Belirtilen değerden belirtilen [Decimal](../decimal/) nesnesiyle temsil edilen değerin çıkarılması sonucunda elde edilen bir değeri temsil eden yeni bir [Decimal](../decimal/) sınıfı örneği döndürür.

```cpp
template<typename T,typename _> Decimal System::operator-(const T &x, const Decimal &d)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | const T\& | Çıkarmak için değer |
| d | const [Decimal](../decimal/)\& | [Decimal](../decimal/) nesnesi, çıkarılan değeri temsil eder |

### Dönüş Değeri

**x**'den **d** tarafından temsil edilen değerin çıkarılması sonucunda elde edilen bir değeri temsil eden yeni bir [Decimal](../decimal/) sınıfı örneği.

## System::operator-(MulticastDelegate\<T\>, MulticastDelegate\<T\>) fonksiyon


Sağ el temsilcisindeki tüm geri çağrıları, sol el temsilcisinin geri çağrı listesinin sonundan ayırır.

```cpp
template<typename T> MulticastDelegate<T> System::operator-(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | Geri çağrıların kaldırılacağı temsilci. |
| rhv | MulticastDelegate\<T\> | Geri çağrıları kaldırılacak temsilci. |

### Dönüş Değeri

Sol el değerinin geri çağrılarını içeren, ancak sağ el değerinin geri çağrıları olmadan bir temsilci döndürür.

## System::operator-(const T1\&, const Nullable\<T2\>\&) fonksiyon


Null olmayan ve null olabilen değerleri çıkarır.

```cpp
template<typename T1,typename T2,typename> auto System::operator-(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some - other.get_Value())>
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | Sol operand tipi. |
| T2 | Sağ operand tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| some | const T1\& | Sol operand. |
| other | const [Nullable](../nullable/)\<T2\>\& | Sağ operand. |

### Dönüş Değeri

Çıkarma sonucu.

## Ayrıca Bakınız

* Enum [DayOfWeek](../dayofweek/)
* Sınıf [Decimal](../decimal/)
* Sınıf [Nullable](../nullable/)
* İsimAlanı [System](../)
* Kütüphane [Aspose.Slides](../../)