---
title: TimeSpan()
second_title: Aspose.Slides için C++ API Referansı
description: Sıfır zaman aralığını temsil eden bir TimeSpan nesnesi oluşturur.
type: docs
weight: 1
url: /tr/system/timespan/timespan/
---
## TimeSpan::TimeSpan() yapıcı

Sıfır zaman aralığını temsil eden bir [TimeSpan](../) nesnesi oluşturur.

```cpp
constexpr System::TimeSpan::TimeSpan()
```

## TimeSpan::TimeSpan(int64_t) yapıcı

[TimeSpan](../) sınıfının belirtilen zaman aralığını temsil eden bir örneğini oluşturur.

```cpp
constexpr System::TimeSpan::TimeSpan(int64_t ticks)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ticks | **int64_t** | Yapılandırılan örnek tarafından temsil edilecek zaman aralığı, 100-nanosaneye eşit aralıkların sayısı olarak ifade edilir. |

## TimeSpan::TimeSpan(int, int, int) yapıcı

[TimeSpan](../) sınıfının saat, dakika ve saniye bileşenlerinin toplamına eşit bir zaman aralığını temsil eden bir örneğini oluşturur.

```cpp
System::TimeSpan::TimeSpan(int hours, int minutes, int seconds)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hours | int | Yapılandırılan örnek tarafından temsil edilecek zaman aralığının saat bileşenindeki saat sayısı |
| minutes | int | Yapılandırılan örnek tarafından temsil edilecek zaman aralığının dakika bileşenindeki dakika sayısı |
| seconds | int | Yapılandırılan örnek tarafından temsil edilecek zaman aralığının saniye bileşenindeki saniye sayısı |

## TimeSpan::TimeSpan(int, int, int, int, int) yapıcı

[TimeSpan](../) sınıfının saat, dakika, saniye ve milisaniye bileşenlerinin toplamına eşit bir zaman aralığını temsil eden bir örneğini oluşturur.

```cpp
System::TimeSpan::TimeSpan(int days, int hours, int minutes, int seconds, int milliseconds=0)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| days | int | Yapılandırılan örnek tarafından temsil edilecek zaman aralığının gün bileşenindeki gün sayısı |
| hours | int | Yapılandırılan örnek tarafından temsil edilecek zaman aralığının saat bileşenindeki saat sayısı |
| minutes | int | Yapılandırılan örnek tarafından temsil edilecek zaman aralığının dakika bileşenindeki dakika sayısı |
| seconds | int | Yapılandırılan örnek tarafından temsil edilecek zaman aralığının saniye bileşenindeki saniye sayısı |
| milliseconds | int | Yapılandırılan örnek tarafından temsil edilecek zaman aralığının milisaniye bileşenindeki milisaniye sayısı |

## TimeSpan::TimeSpan(const TimeSpan\&) yapıcı

[TimeSpan](../) nesnesi, belirtilen [TimeSpan](../) nesnesi tarafından temsil edilen zaman aralığına eşit bir zaman aralığını temsil eder.

```cpp
constexpr System::TimeSpan::TimeSpan(const TimeSpan &)=default
```

## İlgili

* Sınıf [TimeSpan](../)
* İsim Uzayı [System](../../)
* Kütüphane [Aspose.Slides](../../../)