---
title: Delay()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat tugas yang selesai setelah penundaan waktu.
type: docs
weight: 105
url: /id/system.threading.tasks/delay/
---
## System::Threading::Tasks::Delay(int32_t) fungsi


Membuat tugas yang selesai setelah penundaan waktu.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | Jumlah milidetik yang harus ditunggu sebelum menyelesaikan tugas yang dikembalikan, atau -1 untuk menunggu tanpa batas. |

### Nilai Kembali

Sebuah tugas yang mewakili penundaan waktu.

## System::Threading::Tasks::Delay(int32_t, const CancellationToken\&) fungsi


Membuat tugas yang selesai setelah penundaan waktu dan dapat dibatalkan.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay, const CancellationToken &cancellationToken)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | Jumlah milidetik yang harus ditunggu sebelum menyelesaikan tugas yang dikembalikan, atau -1 untuk menunggu tanpa batas. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Token pembatalan yang dapat digunakan untuk membatalkan penundaan. |

### Nilai Kembali

Sebuah tugas yang mewakili penundaan waktu.

## Lihat Juga

* Typedef [TaskPtr](../../system/taskptr/)
* Kelas [CancellationToken](../../system.threading/cancellationtoken/)
* Ruang Nama [System::Threading::Tasks](../)
* Perpustakaan [Aspose.Slides](../../)