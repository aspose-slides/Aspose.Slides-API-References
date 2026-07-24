---
title: operator<=()
second_title: Aspose.Slides for C++ API Referansı
description: 
type: docs
weight: 2107
url: /tr/system/operator_less_equal/
---
## System::operator<=(std::nullptr_t, DateTime) fonksiyon




```cpp
constexpr bool System::operator<=(std::nullptr_t, DateTime)
```

## System::operator<=(std::nullptr_t, const DateTimeOffset\&) fonksiyon




```cpp
constexpr bool System::operator<=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator<=(std::nullptr_t, const Nullable\<T\>\&) fonksiyon


Her zaman false döndürür.

```cpp
template<typename T> bool System::operator<=(std::nullptr_t, const Nullable<T> &)
```

## System::operator<=(const T1\&, const Nullable\<T2\>\&) fonksiyon


Belirtilen [Nullable](../nullable/) nesnesi tarafından temsil edilen değere, bu değerlere [operator<=()](./) uygulanarak, belirtilen değerin daha az veya eşit olup olmadığını belirler.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator<=(const T1 &some, const Nullable<T2> &other)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | İlk karşılaştırılan değerin türü |
| T2 | [Nullable](../nullable/) nesnesi tarafından temsil edilen ikinci karşılaştırılan değerin temel türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| some | const T1\& | İlk karşılaştırılan değer olarak kullanılacak değerin sabit referansı |
| other | const [Nullable](../nullable/)\<T2\>\& | [Nullable](../nullable/) nesnesinin temsil ettiği değerin ikinci karşılaştırılan olarak kullanılacak sabit referansı |

### Dönüş Değeri

İlk karşılaştırılan değer ikinci karşılaştırılan değere eşit veya daha az ise true, aksi takdirde - false

## System::operator<=(std::nullptr_t, TimeSpan) fonksiyon




```cpp
constexpr bool System::operator<=(std::nullptr_t, TimeSpan)
```

## İlgili

* Sınıf [DateTime](../datetime/)
* Sınıf [DateTimeOffset](../datetimeoffset/)
* Sınıf [Nullable](../nullable/)
* Sınıf [TimeSpan](../timespan/)
* Yapı [IsNullable](../isnullable/)
* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)