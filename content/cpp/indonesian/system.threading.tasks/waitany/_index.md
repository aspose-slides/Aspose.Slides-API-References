---
title: WaitAny()
second_title: Referensi API Aspose.Slides untuk C++
description: Menunggu salah satu objek Task yang disediakan untuk menyelesaikan eksekusi.
type: docs
weight: 183
url: /id/system.threading.tasks/waitany/
---
## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) fungsi


Menunggu salah satu objek [Task](../task/) yang disediakan untuk menyelesaikan eksekusi.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Sebuah array berisi instance [Task](../task/) yang akan ditunggu. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Sebuah [CancellationToken](../../system.threading/cancellationtoken/) yang dipantau saat menunggu tugas selesai. |

### Nilai Kembali

Indeks tugas yang selesai dalam array tugas.

## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&) fungsi


Menunggu salah satu objek [Task](../task/) yang disediakan untuk menyelesaikan eksekusi.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Sebuah array berisi instance [Task](../task/) yang akan ditunggu. |

### Nilai Kembali

Indeks tugas yang selesai dalam array tugas.

## Lihat Juga

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Kelas [CancellationToken](../../system.threading/cancellationtoken/)
* Ruang Nama [System::Threading::Tasks](../)
* Perpustakaan [Aspose.Slides](../../)