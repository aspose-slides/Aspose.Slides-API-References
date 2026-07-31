---
title: ContinueWith()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat kelanjutan yang dijalankan ketika tugas selesai.
type: docs
weight: 118
url: /id/system.threading.tasks/task/continuewith/
---
## Task::ContinueWith(const Action\<TaskPtr\>\&) method


Membuat kelanjutan yang dijalankan ketika tugas selesai.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | Aksi yang akan dijalankan ketika tugas ini selesai |

### Nilai Kembalian

TaskPtr Tugas baru yang mewakili kelanjutan

## Task::ContinueWith(const Func\<TaskPtr, TResult\>\&) method


Membuat kelanjutan yang dijalankan ketika tugas selesai.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TResult | Sebuah tipe hasil tugas |

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
* Class [Task](../)
* Class [Func](../../../system/func/)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)