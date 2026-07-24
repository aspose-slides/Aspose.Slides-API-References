---
title: operator>()
second_title: Aspose.Slides için C++ API Referansı
description: 
type: docs
weight: 2120
url: /tr/system/operator_greater/
---
## System::operator>(std::nullptr_t, DateTime) fonksiyon




```cpp
constexpr bool System::operator>(std::nullptr_t, DateTime)
```

## System::operator>(std::nullptr_t, const DateTimeOffset\&) fonksiyon




```cpp
constexpr bool System::operator>(std::nullptr_t, const DateTimeOffset &)
```

## System::operator>(std::nullptr_t, const Nullable\<T\>\&) fonksiyon


Her zaman false döndürür.

```cpp
template<typename T> bool System::operator>(std::nullptr_t, const Nullable<T> &)
```

## System::operator>(const T1\&, const Nullable\<T2\>\&) fonksiyon


Belirtilen değerin, belirtilen [Nullable](../nullable/) nesnesi tarafından temsil edilen değerden büyük olup olmadığını, bu değerlere [operator>()](./) uygulayarak belirler.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator>(const T1 &some, const Nullable<T2> &other)
```


### Şablon parametreleri

| Parameter | Description |
| --- | --- |
| T1 | The type of the first comparand value |
| T2 | The underlying type of the [Nullable](../nullable/) object that represents the second comparand value |

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| some | const T1\& | A constant reference to the value that is to be used as the first comparand |
| other | const [Nullable](../nullable/)\<T2\>\& | A constant reference to the [Nullable](../nullable/) object the represented value of which is to be used as the second comparand |

### Dönüş Değeri

True, ilk karşılaştırma değeri ikinci karşılaştırma değerinden büyük olduğunda, aksi takdirde - false

## System::operator>(std::nullptr_t, TimeSpan) fonksiyon




```cpp
constexpr bool System::operator>(std::nullptr_t, TimeSpan)
```

## İlgili

* Sınıf [DateTime](../datetime/)
* Sınıf [DateTimeOffset](../datetimeoffset/)
* Sınıf [Nullable](../nullable/)
* Sınıf [TimeSpan](../timespan/)
* Yapı [IsNullable](../isnullable/)
* İsim Alanı [System](../)
* Kütüphane [Aspose.Slides](../../)