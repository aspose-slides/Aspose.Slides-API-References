---
title: WhenAll()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sebuah tugas yang akan selesai ketika semua tugas yang diberikan telah selesai.
type: docs
weight: 196
url: /id/system.threading.tasks/whenall/
---
## System::Threading::Tasks::WhenAll(const ArrayPtr\<TaskPtr\>\&) fungsi

Membuat sebuah tugas yang akan selesai ketika semua tugas yang diberikan telah selesai.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const ArrayPtr<TaskPtr> &tasks)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Tugas-tugas yang harus ditunggu hingga selesai. |

### Nilai Kembalian

Sebuah tugas yang mewakili selesainya semua tugas yang diberikan.

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) fungsi

Membuat sebuah tugas yang akan selesai ketika semua tugas yang diberikan telah selesai.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | Tugas-tugas yang harus ditunggu hingga selesai. |

### Nilai Kembalian

Sebuah tugas yang mewakili selesainya semua tugas yang diberikan.

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) fungsi

Membuat sebuah tugas yang akan selesai ketika semua tugas yang diberikan telah selesai.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```

### Parameter Template

| Parameter | Deskripsi |
| --- | --- |
| TResult | Tipe hasil tugas yang selesai. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | Tugas-tugas yang harus ditunggu hingga selesai. |

### Nilai Kembalian

Sebuah tugas yang mengembalikan array semua hasil ketika semua tugas selesai.

## System::Threading::Tasks::WhenAll(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) fungsi

Membuat sebuah tugas yang akan selesai ketika semua tugas yang diberikan telah selesai.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```

### Parameter Template

| Parameter | Deskripsi |
| --- | --- |
| TResult | Tipe hasil tugas yang selesai. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | Tugas-tugas yang harus ditunggu hingga selesai. |

### Nilai Kembalian

Sebuah tugas yang mengembalikan array semua hasil ketika semua tugas selesai.

## Lihat Juga

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)