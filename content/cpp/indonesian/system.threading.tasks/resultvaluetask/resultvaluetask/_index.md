---
title: ResultValueTask()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat ResultValueTask yang kosong dan belum diinisialisasi.
type: docs
weight: 1
url: /id/system.threading.tasks/resultvaluetask/resultvaluetask/
---
## ResultValueTask::ResultValueTask() constructor

Membuat [ResultValueTask](../) kosong dan belum diinisialisasi.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask()
```

## Catatan

Tugas belum selesai dan tidak berisi hasil. Mencoba mengambil hasil akan melempar pengecualian.

## ResultValueTask::ResultValueTask(const T\&) constructor

Membuat [ResultValueTask](../) yang selesai dengan hasil yang ditentukan.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const T &result)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| result | const T\& | Nilai hasil untuk dibungkus dalam tugas yang selesai. |

## Catatan

Ini membuat tugas yang berhasil selesai yang langsung mengembalikan nilai.

## ResultValueTask::ResultValueTask(const RTaskPtr\<T\>\&) constructor

Membuat [ResultValueTask](../) dari shared pointer ke ResultTask<T>.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const RTaskPtr<T> &task)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| task | const [RTaskPtr](../../../system/rtaskptr/)\<T\>\& | Tugas yang akan dibungkus. Dapat bernilai null untuk tugas kosong. |

## Catatan

[ResultValueTask](../) akan mewakili status dan hasil dari tugas yang diberikan.

## Lihat Juga

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Kelas [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Pustaka [Aspose.Slides](../../../)