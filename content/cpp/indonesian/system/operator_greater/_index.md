---
title: operator>()
second_title: Referensi API Aspose.Slides untuk C++
description: 
type: docs
weight: 2120
url: /id/system/operator_greater/
---
## System::operator>(std::nullptr_t, DateTime) fungsi




```cpp
constexpr bool System::operator>(std::nullptr_t, DateTime)
```

## System::operator>(std::nullptr_t, const DateTimeOffset\&) fungsi




```cpp
constexpr bool System::operator>(std::nullptr_t, const DateTimeOffset &)
```

## System::operator>(std::nullptr_t, const Nullable\<T\>\&) fungsi


Selalu mengembalikan false.

```cpp
template<typename T> bool System::operator>(std::nullptr_t, const Nullable<T> &)
```

## System::operator>(const T1\&, const Nullable\<T2\>\&) fungsi


Menentukan apakah nilai yang ditentukan lebih besar daripada nilai yang diwakili oleh objek [Nullable](../nullable/) yang ditentukan dengan menerapkan [operator>()](./) pada nilai-nilai ini.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator>(const T1 &some, const Nullable<T2> &other)
```


### Parameter Template

| Parameter | Deskripsi |
| --- | --- |
| T1 | Tipe nilai perbandingan pertama |
| T2 | Tipe dasar dari objek [Nullable](../nullable/) yang mewakili nilai perbandingan kedua |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| some | const T1\& | Referensi konstan ke nilai yang akan digunakan sebagai perbandingan pertama |
| other | const [Nullable](../nullable/)\<T2\>\& | Referensi konstan ke objek [Nullable](../nullable/) yang nilai yang diwakilinya akan digunakan sebagai perbandingan kedua |

### Nilai Kembalian

True jika perbandingan pertama lebih besar daripada perbandingan kedua, jika tidak - false

## System::operator>(std::nullptr_t, TimeSpan) fungsi




```cpp
constexpr bool System::operator>(std::nullptr_t, TimeSpan)
```

## Lihat Juga

* Kelas [DateTime](../datetime/)
* Kelas [DateTimeOffset](../datetimeoffset/)
* Kelas [Nullable](../nullable/)
* Kelas [TimeSpan](../timespan/)
* Struktur [IsNullable](../isnullable/)
* Ruang Nama [System](../)
* Perpustakaan [Aspose.Slides](../../)