---
title: DateTime()
second_title: Aspose.Slides for C++ API Referansı
description: En küçük olası tarih ve saat değerini, MinValue'a eşit olacak şekilde temsil eden bir örnek oluşturur.
type: docs
weight: 1
url: /tr/system/datetime/datetime/
---
## DateTime::DateTime() yapıcı

En küçük olası tarih ve saat değerini, MinValue'a eşit olacak şekilde temsil eden bir örnek oluşturur.

```cpp
constexpr System::DateTime::DateTime()
```

## DateTime::DateTime(int, int, int) yapıcı

Belirli bir yıl, ay ve gün olarak belirtilen tarih ve saat değerini temsil eden bir örnek oluşturur.

```cpp
System::DateTime::DateTime(int year, int month, int day)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| year | int | Oluşturulan örnek tarafından temsil edilecek **year**. |
| month | int | Oluşturulan örnek tarafından temsil edilecek **year**'ın **month**'ı. |
| day | int | Oluşturulan örnek tarafından temsil edilecek **month**'ın **day**'ı. |

## DateTime::DateTime(int, int, int, const SharedPtr\<Globalization::Calendar\>\&) yapıcı

Belirtilen takvimde belirli bir yıl, ay ve gün olarak belirtilen tarih ve saat değerini temsil eden bir örnek oluşturur.

```cpp
System::DateTime::DateTime(int year, int month, int day, const SharedPtr<Globalization::Calendar> &calendar)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| year | int | Oluşturulan örnek tarafından temsil edilecek **year**. |
| month | int | Oluşturulan örnek tarafından temsil edilecek **year**'ın **month**'ı. |
| day | int | Oluşturulan örnek tarafından temsil edilecek **month**'ın **day**'ı. |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Belirtilen **year**, **month** ve **day** değerlerini yorumlamak için kullanılan takvim. |

## DateTime::DateTime(int, int, int, int, int, int) yapıcı

Belirli bir yıl, ay, gün, saat, dakika ve saniye olarak belirtilen tarih ve saat değerini temsil eden bir örnek oluşturur.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| year | int | Oluşturulan örnek tarafından temsil edilecek **year**. |
| month | int | Oluşturulan örnek tarafından temsil edilecek **year**'ın **month**'ı. |
| day | int | Oluşturulan örnek tarafından temsil edilecek **month**'ın **day**'ı. |
| hour | int | Oluşturulan örnek tarafından temsil edilecek **day**'ın **hour**'ı. |
| minute | int | Oluşturulan örnek tarafından temsil edilecek **hour**'ın **minute**'ı. |
| second | int | Oluşturulan örnek tarafından temsil edilecek **minute**'ın **second**'ı. |

## DateTime::DateTime(int, int, int, int, int, int, DateTimeKind) yapıcı

Belirli bir yıl, ay, gün, saat, dakika ve saniye olarak belirtilen tarih ve saat değerini temsil eden bir örnek oluşturur.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, DateTimeKind kind)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| year | int | Oluşturulan örnek tarafından temsil edilecek **year**. |
| month | int | Oluşturulan örnek tarafından temsil edilecek **year**'ın **month**'ı. |
| day | int | Oluşturulan örnek tarafından temsil edilecek **month**'ın **day**'ı. |
| hour | int | Oluşturulan örnek tarafından temsil edilecek **day**'ın **hour**'ı. |
| minute | int | Oluşturulan örnek tarafından temsil edilecek **hour**'ın **minute**'ı. |
| second | int | Oluşturulan örnek tarafından temsil edilecek **minute**'ın **second**'ı. |
| kind | [DateTimeKind](../../datetimekind/) | Sağlanan tarih ve saat parametrelerinin yerel zaman, UTC zamanı ya da hiçbiri olduğunu gösteren değer. |

## DateTime::DateTime(int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&) yapıcı

Belirli bir yıl, ay, gün, saat, dakika ve saniye olarak belirtilen tarih ve saat değerini belirtilen takvimde temsil eden bir örnek oluşturur.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, const SharedPtr<Globalization::Calendar> &calendar)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| year | int | Oluşturulan örnek tarafından temsil edilecek **year**. |
| month | int | Oluşturulan örnek tarafından temsil edilecek **year**'ın **month**'ı. |
| day | int | Oluşturulan örnek tarafından temsil edilecek **month**'ın **day**'ı. |
| hour | int | Oluşturulan örnek tarafından temsil edilecek **day**'ın **hour**'ı. |
| minute | int | Oluşturulan örnek tarafından temsil edilecek **hour**'ın **minute**'ı. |
| second | int | Oluşturulan örnek tarafından temsil edilecek **minute**'ın **second**'ı. |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Belirtilen **year**, **month** ve **day** değerlerini yorumlamak için kullanılan takvim. |

## DateTime::DateTime(int, int, int, int, int, int, int, DateTimeKind) yapıcı

Belirli bir yıl, ay, gün, saat, dakika, saniye ve milisaniye olarak belirtilen tarih ve saat değerini temsil eden bir örnek oluşturur.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, DateTimeKind kind=DateTimeKind::Unspecified)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| year | int | Oluşturulan örnek tarafından temsil edilecek **year**. |
| month | int | Oluşturulan örnek tarafından temsil edilecek **year**'ın **month**'ı. |
| day | int | Oluşturulan örnek tarafından temsil edilecek **month**'ın **day**'ı. |
| hour | int | Oluşturulan örnek tarafından temsil edilecek **day**'ın **hour**'ı. |
| minute | int | Oluşturulan örnek tarafından temsil edilecek **hour**'ın **minute**'ı. |
| second | int | Oluşturulan örnek tarafından temsil edilecek **minute**'ın **second**'ı. |
| millisecond | int | Oluşturulan örnek tarafından temsil edilecek **second**'ın **millisecond**'ı. |
| kind | [DateTimeKind](../../datetimekind/) | Sağlanan tarih ve saat parametrelerinin yerel zaman, UTC zamanı ya da hiçbiri olduğunu gösteren değer. |

## DateTime::DateTime(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, DateTimeKind) yapıcı

Belirli bir yıl, ay, gün, saat, dakika, saniye ve milisaniye olarak belirtilen tarih ve saat değerini belirtilen takvimde temsil eden bir örnek oluşturur.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, DateTimeKind kind=DateTimeKind::Unspecified)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| year | int | Oluşturulan örnek tarafından temsil edilecek **year**. |
| month | int | Oluşturulan örnek tarafından temsil edilecek **year**'ın **month**'ı. |
| day | int | Oluşturulan örnek tarafından temsil edilecek **month**'ın **day**'ı. |
| hour | int | Oluşturulan örnek tarafından temsil edilecek **day**'ın **hour**'ı. |
| minute | int | Oluşturulan örnek tarafından temsil edilecek **hour**'ın **minute**'ı. |
| second | int | Oluşturulan örnek tarafından temsil edilecek **minute**'ın **second**'ı. |
| millisecond | int | Oluşturulan örnek tarafından temsil edilecek **second**'ın **millisecond**'ı. |
| kind | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Sağlanan tarih ve saat parametrelerinin yerel zaman, UTC zamanı ya da hiçbiri olduğunu gösteren değer. |
| calendar | [DateTimeKind](../../datetimekind/) | Belirtilen **year**, **month** ve **day** değerlerini yorumlamak için kullanılan takvim. |

## DateTime::DateTime(int64_t, DateTimeKind) yapıcı

Bir takvim tik sayısı olarak belirtilen tarih ve saat değerini temsil eden bir örnek oluşturur.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind=DateTimeKind::Unspecified)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ticks | **int64_t** | Georgian takvimine göre 0001 yılının 1 Ocak 00:00:00.000 tarihinden itibaren geçen 100 ns aralıkların sayısı. |
| kind | [DateTimeKind](../../datetimekind/) | **ticks** parametresinin yerel zaman, UTC zamanı ya da hiçbiri olduğunu gösteren değer. |

## DateTime::DateTime(int64_t, DateTimeKind, bool) yapıcı

Bir takvim tik sayısı olarak belirtilen tarih ve saat değerini temsil eden bir örnek oluşturur. FOR INTERNAL USE.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind, bool is_ambiguous_local_dst)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ticks | **int64_t** | Georgian takvimine göre 0001 yılının 1 Ocak 00:00:00.000 tarihinden itibaren geçen 100 ns aralıkların sayısı. |
| kind | [DateTimeKind](../../datetimekind/) | **ticks** parametresinin yerel zaman, UTC zamanı ya da hiçbiri olduğunu gösteren değer. |
| is_ambiguous_local_dst | **bool** | Belirtilen tarih ve saat belirsiz ise ve birçok UTC zamanına eşlenebiliyorsa doğru. |

## DateTime::DateTime(const DateTime\&) yapıcı

Bir örnek kopyalar.

```cpp
System::DateTime::DateTime(const DateTime &dt)=default
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dt | const [DateTime](../)\& | [DateTime](../) sınıfının temsil edilen tarih ve saat değerini kopyalamak için bir örnek. |

## Ayrıca Bakınız

* Enum [DateTimeKind](../../datetimekind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTime](../)
* Class [Calendar](../../../system.globalization/calendar/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)