---
title: operator>=()
second_title: Aspose.Slides for C++ API Referansı
description: 
type: docs
weight: 2133
url: /tr/system/operator_greater_equal/
---
## System::operator>=(std::nullptr_t, DateTime) fonksiyon




```cpp
constexpr bool System::operator>=(std::nullptr_t, DateTime)
```

## System::operator>=(std::nullptr_t, const DateTimeOffset\&) fonksiyon




```cpp
constexpr bool System::operator>=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator>=(std::nullptr_t, const Nullable\<T\>\&) fonksiyon


Her zaman false döner.

```cpp
template<typename T> bool System::operator>=(std::nullptr_t, const Nullable<T> &)
```

## System::operator>=(const T1\&, const Nullable\<T2\>\&) fonksiyon


Belirtilen [Nullable](../nullable/) nesnesi tarafından temsil edilen değere, bu değerlere [operator>=()](./) uygulanarak, belirtilen değerin büyük veya eşit olup olmadığını belirler.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator>=(const T1 &some, const Nullable<T2> &other)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | İlk karşılaştırma değerinin tipi |
| T2 | [Nullable](../nullable/) nesnesinin temel tipi; bu nesne ikinci karşılaştırma değerini temsil eder |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| some | const T1\& | İlk karşılaştırma olarak kullanılacak değere sabit referans |
| other | const [Nullable](../nullable/)\<T2\>\& | [Nullable](../nullable/) nesnesine sabit referans; temsil edilen değer ikinci karşılaştırma olarak kullanılacak |

### Dönüş Değeri

İlk karşılaştırma değeri ikinci karşılaştırma değerine büyük veya eşit ise true, aksi takdirde false

## System::operator>=(std::nullptr_t, TimeSpan) fonksiyon




```cpp
constexpr bool System::operator>=(std::nullptr_t, TimeSpan)
```

## Ayrıca Bakınız

* Sınıf [DateTime](../datetime/)
* Sınıf [DateTimeOffset](../datetimeoffset/)
* Sınıf [Nullable](../nullable/)
* Sınıf [TimeSpan](../timespan/)
* Yapı [IsNullable](../isnullable/)
* Ad Alanı [System](../)
* Kütüphane [Aspose.Slides](../../)