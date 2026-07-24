---
title: DateTimeOffset()
second_title: Aspose.Slides for C++ API Referansı
description: Varsayılan yapıcı.
type: docs
weight: 1
url: /tr/system/datetimeoffset/datetimeoffset/
---
## DateTimeOffset::DateTimeOffset() yapıcı

Varsayılan yapıcı.

```cpp
constexpr System::DateTimeOffset::DateTimeOffset()=default
```

## DateTimeOffset::DateTimeOffset(DateTime) yapıcı

Yapıcı.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Tarih ve saat. |

## DateTimeOffset::DateTimeOffset(int64_t, TimeSpan) yapıcı

Yapıcı.

```cpp
System::DateTimeOffset::DateTimeOffset(int64_t ticks, TimeSpan offset)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ticks | **int64_t** | Tik sayısı. |
| offset | [TimeSpan](../../timespan/) | UTC'den zaman farkı. |

## DateTimeOffset::DateTimeOffset(DateTime, TimeSpan) yapıcı

Yapıcı.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time, TimeSpan offset)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Tarih ve saat. |
| offset | [TimeSpan](../../timespan/) | UTC'den zaman farkı. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, TimeSpan) yapıcı

Yapıcı.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, TimeSpan offset)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| year | int | Yıl (1 ile 9999 arasında). |
| month | int | Ay (1 ile 12 arasında). |
| day | int | Gün (1 ile ayın gün sayısı arasında). |
| hour | int | Saat (0 ile 23 arasında). |
| minute | int | Dakika (0 ile 59 arasında). |
| second | int | Saniye (0 ile 59 arasında). |
| offset | [TimeSpan](../../timespan/) | UTC'den zaman farkı. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, TimeSpan) yapıcı

Yapıcı.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, TimeSpan offset)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| year | int | Yıl (1 ile 9999 arasında). |
| month | int | Ay (1 ile 12 arasında). |
| day | int | Gün (1 ile ayın gün sayısı arasında). |
| hour | int | Saat (0 ile 23 arasında). |
| minute | int | Dakika (0 ile 59 arasında). |
| second | int | Saniye (0 ile 59 arasında). |
| millisecond | int | Milisaniye (0 ile 999 arasında). |
| offset | [TimeSpan](../../timespan/) | UTC'den zaman farkı. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, TimeSpan) yapıcı

Yapıcı.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, TimeSpan offset)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| year | int | Yıl. |
| month | int | Ay (1 ile 12 arasında). |
| day | int | Gün (1 ile ayın gün sayısı arasında). |
| hour | int | Saat (0 ile 23 arasında). |
| minute | int | Dakika (0 ile 59 arasında). |
| second | int | Saniye (0 ile 59 arasında). |
| millisecond | int | Milisaniye (0 ile 999 arasında). |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Yıl, ay ve günü yorumlamak için kullanılan takvim. |
| offset | [TimeSpan](../../timespan/) | UTC'den zaman farkı. |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [DateTimeOffset](../)
* Sınıf [DateTime](../../datetime/)
* Sınıf [TimeSpan](../../timespan/)
* Sınıf [Calendar](../../../system.globalization/calendar/)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)