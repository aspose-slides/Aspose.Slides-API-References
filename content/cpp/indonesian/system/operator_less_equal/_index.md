---
title: operator<=()
second_title: Aspose.Slides untuk Referensi API C++
description: 
type: docs
weight: 2107
url: /id/system/operator_less_equal/
---
## System::operator<=(std::nullptr_t, DateTime) fungsi




```cpp
constexpr bool System::operator<=(std::nullptr_t, DateTime)
```

## System::operator<=(std::nullptr_t, const DateTimeOffset\&) fungsi




```cpp
constexpr bool System::operator<=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator<=(std::nullptr_t, const Nullable\<T\>\&) fungsi


Selalu mengembalikan false.

```cpp
template<typename T> bool System::operator<=(std::nullptr_t, const Nullable<T> &)
```

## System::operator<=(const T1\&, const Nullable\<T2\>\&) fungsi


Menentukan apakah nilai yang ditentukan kurang atau sama dengan nilai yang direpresentasikan oleh objek [Nullable](../nullable/) yang ditentukan dengan menerapkan [operator<=()](./) pada nilai-nilai ini.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator<=(const T1 &some, const Nullable<T2> &other)
```


### Parameter templat

| Parameter | Description |
| --- | --- |
| T1 | The type of the first comparand value |
| T2 | The underlying type of the [Nullable](../nullable/) object that represents the second comparand value |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| some | const T1\& | A constant reference to the value that is to be used as the first comparand |
| other | const [Nullable](../nullable/)\<T2\>\& | A constant reference to the [Nullable](../nullable/) object the represented value of which is to be used as the second comparand |

### Nilai Kembalian

True if the first comparand is less or equal to the second comparand, otherwise - false

## System::operator<=(std::nullptr_t, TimeSpan) fungsi




```cpp
constexpr bool System::operator<=(std::nullptr_t, TimeSpan)
```

## Lihat Juga

* Kelas [DateTime](../datetime/)
* Kelas [DateTimeOffset](../datetimeoffset/)
* Kelas [Nullable](../nullable/)
* Kelas [TimeSpan](../timespan/)
* Struktur [IsNullable](../isnullable/)
* Ruang nama [System](../)
* Perpustakaan [Aspose.Slides](../../)