---
title: ContinueWith()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat kelanjutan yang dijalankan ketika tugas hasil selesai.
type: docs
weight: 40
url: /id/system.threading.tasks/resulttask/continuewith/
---
## ResultTask::ContinueWith(const Action\<RTaskPtr\<T\>\>\&) method

Membuat kelanjutan yang dijalankan ketika tugas hasil selesai.

```cpp
TaskPtr System::Threading::Tasks::ResultTask<T>::ContinueWith(const Action<RTaskPtr<T>> &continuationAction)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>\>\& | Aksi yang dijalankan ketika tugas ini selesai, menerima tugas hasil ini |

### Nilai Kembalian

TaskPtr Tugas baru yang mewakili kelanjutan
## Catatan



Aksi kelanjutan menerima [ResultTask](../) ini untuk mengakses nilai hasil

## ResultTask::ContinueWith(const Func\<RTaskPtr\<T\>, TNewResult\>\&) method

Membuat kelanjutan yang dijalankan ketika tugas hasil selesai.

```cpp
template<typename TNewResult> RTaskPtr<TNewResult> System::Threading::Tasks::ResultTask<T>::ContinueWith(const Func<RTaskPtr<T>, TNewResult> &continuationFunction)
```

### Parameter template

| Parameter | Deskripsi |
| --- | --- |
| TNewResult | Tipe hasil dari kelanjutan tugas |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>, TNewResult\>\& | Fungsi untuk mendapatkan hasil kelanjutan ketika tugas ini selesai, menerima tugas hasil ini |

### Nilai Kembalian

RTaskPtr Tugas baru yang mewakili kelanjutan
## Catatan



Fungsi kelanjutan menerima [ResultTask](../) ini untuk mengakses nilai hasil

## ResultTask::ContinueWith(const Action\<TaskPtr\>\&) method

Membuat kelanjutan yang dijalankan ketika tugas selesai.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | Aksi yang dijalankan ketika tugas ini selesai |

### Nilai Kembalian

TaskPtr Tugas baru yang mewakili kelanjutan

## ResultTask::ContinueWith(const Func\<TaskPtr, TResult\>\&) method

Membuat kelanjutan yang dijalankan ketika tugas selesai.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```

### Parameter template

| Parameter | Deskripsi |
| --- | --- |
| TResult | Tipe hasil tugas |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | Fungsi untuk mendapatkan hasil ketika tugas ini selesai |

### Nilai Kembalian

RTaskPtr Tugas baru yang mewakili kelanjutan

## Lihat Juga

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Kelas [ResultTask](../)
* Kelas [Func](../../../system/func/)
* Ruang Nama [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)