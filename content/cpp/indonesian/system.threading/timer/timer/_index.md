---
title: Timer()
second_title: Referensi API Aspose.Slides untuk C++
description: Konstruktor.
type: docs
weight: 1
url: /id/system.threading/timer/timer/
---
## Timer::Timer(TimerCallback) konstruktor

Konstruktor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Fungsi yang akan dipanggil oleh timer. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, int64_t, int64_t) konstruktor

Konstruktor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, int64_t dueTime, int64_t period)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Fungsi yang akan dipanggil oleh timer. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Argumen fungsi callback. |
| dueTime | **int64_t** | [Timeout](../../timeout/) sebelum pemanggilan pertama fungsi callback, dalam milidetik; nilai negatif tidak menjadwalkan timer setelah pembuatan sehingga dapat dijadwalkan ulang nanti. |
| period | **int64_t** | [Timeout](../../timeout/) antara pemanggilan berurutan fungsi callback, dalam milidetik; nilai non-positif berarti timer hanya harus dijalankan satu kali. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, System::TimeSpan, System::TimeSpan) konstruktor

Konstruktor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, System::TimeSpan dueTime, System::TimeSpan period)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Fungsi yang akan dipanggil oleh timer. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Argumen fungsi callback. |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) sebelum pemanggilan pertama fungsi callback; nilai negatif tidak menjadwalkan timer setelah pembuatan sehingga dapat dijadwalkan ulang nanti. |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) antara pemanggilan berurutan fungsi callback; nilai non-positif berarti timer hanya harus dijalankan satu kali. |

## Lihat Juga

* Typedef [TimerCallback](../../timercallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Timer](../)
* Class [Object](../../../system/object/)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)