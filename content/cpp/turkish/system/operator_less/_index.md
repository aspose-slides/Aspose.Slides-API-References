---
title: operator<()
second_title: Aspose.Slides for C++ API Referansı
description: 
type: docs
weight: 2094
url: /tr/system/operator_less/
---
## System::operator<(std::nullptr_t, DateTime) fonksiyon




```cpp
constexpr bool System::operator<(std::nullptr_t, DateTime)
```

## System::operator<(std::nullptr_t, const DateTimeOffset\&) fonksiyon




```cpp
constexpr bool System::operator<(std::nullptr_t, const DateTimeOffset &)
```

## System::operator<(std::nullptr_t, const Nullable\<T\>\&) fonksiyon


Her zaman false döndürür.

```cpp
template<typename T> bool System::operator<(std::nullptr_t, const Nullable<T> &)
```

## System::operator<(const T1\&, const Nullable\<T2\>\&) fonksiyon


Belirtilen değerin, belirtilen [Nullable](../nullable/) nesnesi tarafından temsil edilen değerden daha küçük olup olmadığını, bu değerlere [operator<()](./) uygulayarak belirler.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator<(const T1 &some, const Nullable<T2> &other)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | The type of the first comparand value |
| T2 | The underlying type of the [Nullable](../nullable/) object that represents the second comparand value |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| some | const T1\& | A constant reference to the value that is to be used as the first comparand |
| other | const [Nullable](../nullable/)\<T2\>\& | A constant reference to the [Nullable](../nullable/) object the represented value of which is to be used as the second comparand |

### Dönüş değeri

True if the first comparand is less than the second comparand, otherwise - false

## System::operator<(std::nullptr_t, TimeSpan) fonksiyon




```cpp
constexpr bool System::operator<(std::nullptr_t, TimeSpan)
```

## Ayrıca bakınız

* Sınıf [DateTime](../datetime/)
* Sınıf [DateTimeOffset](../datetimeoffset/)
* Sınıf [Nullable](../nullable/)
* Sınıf [TimeSpan](../timespan/)
* Yapı [IsNullable](../isnullable/)
* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)