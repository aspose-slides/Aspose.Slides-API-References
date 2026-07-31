---
title: Change()
second_title: Referensi API Aspose.Slides untuk C++
description: Menjadwalkan ulang atau membatalkan timer.
type: docs
weight: 14
url: /id/system.threading/timer/change/
---
## Timer::Change(int64_t, int64_t) metode


Menjadwalkan ulang atau membatalkan timer.

```cpp
bool System::Threading::Timer::Change(int64_t dueTime, int64_t period)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dueTime | **int64_t** | [Timeout](../../timeout/) sebelum pemanggilan berikutnya fungsi callback, dalam milidetik; nilai negatif membatalkan timer bahkan jika telah dijadwalkan. |
| period | **int64_t** | [Timeout](../../timeout/) antara pemanggilan berurutan fungsi callback, dalam milidetik; nilai non-positif berarti timer hanya harus dijalankan satu kali. |

## Timer::Change(System::TimeSpan, System::TimeSpan) metode


Menjadwalkan ulang atau membatalkan timer.

```cpp
bool System::Threading::Timer::Change(System::TimeSpan dueTime, System::TimeSpan period)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) sebelum pemanggilan berikutnya fungsi callback; nilai negatif membatalkan timer bahkan jika telah dijadwalkan. |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) antara pemanggilan berurutan fungsi callback; nilai non-positif berarti timer hanya harus dijalankan satu kali. |

## Lihat Juga

* Kelas [Timer](../)
* Kelas [TimeSpan](../../../system/timespan/)
* Namespace [System::Threading](../../)
* Perpustakaan [Aspose.Slides](../../../)