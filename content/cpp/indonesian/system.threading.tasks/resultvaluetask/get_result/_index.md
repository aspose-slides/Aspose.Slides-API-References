---
title: get_Result()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan hasil dari tugas yang telah selesai.
type: docs
weight: 66
url: /id/system.threading.tasks/resultvaluetask/get_result/
---
## ResultValueTask::get_Result() metode

Mendapatkan hasil dari tugas yang telah selesai.

```cpp
T System::Threading::Tasks::ResultValueTask<T>::get_Result()
```

### Nilai Kembalian

T Nilai hasil.

## Catatan

Jika tugas ditopang oleh ResultTask<T>, metode ini akan menunggu hasilnya dan menyimpannya dalam cache. Panggilan berikutnya akan mengembalikan nilai yang telah di-cache tanpa menunggu.

## Lihat Juga

* Kelas [ResultValueTask](../)
* Ruang Nama [System::Threading::Tasks](../../)
* Perpustakaan [Aspose.Slides](../../../)