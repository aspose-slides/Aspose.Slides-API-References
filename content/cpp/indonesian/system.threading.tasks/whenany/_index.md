---
title: WhenAny()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sebuah tugas yang akan selesai ketika salah satu tugas yang diberikan telah selesai.
type: docs
weight: 209
url: /id/system.threading.tasks/whenany/
---
## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) fungsi

Membuat sebuah tugas yang akan selesai ketika salah satu tugas yang diberikan telah selesai.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | Tugas yang harus ditunggu hingga selesai. |

### Nilai Kembalian

Sebuah tugas yang mewakili penyelesaian salah satu tugas yang diberikan.

## System::Threading::Tasks::WhenAny(const ArrayPtr\<TaskPtr\>\&) fungsi


Membuat sebuah tugas yang akan selesai ketika salah satu tugas yang diberikan telah selesai.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const ArrayPtr<TaskPtr> &tasks)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Tugas yang harus ditunggu hingga selesai. |

### Nilai Kembalian

Sebuah tugas yang mewakili penyelesaian salah satu tugas yang diberikan.

## System::Threading::Tasks::WhenAny(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) fungsi


Membuat sebuah tugas yang akan selesai ketika salah satu tugas yang diberikan telah selesai.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```


### Parameter Template

| Parameter | Description |
| --- | --- |
| TResult | Tipe hasil tugas yang selesai. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | Tugas yang harus ditunggu hingga selesai. |

### Nilai Kembalian

Sebuah tugas yang mengembalikan tugas pertama yang selesai ketika tugas apa pun selesai.

## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) fungsi


Membuat sebuah tugas yang akan selesai ketika salah satu tugas yang diberikan telah selesai.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```


### Parameter Template

| Parameter | Description |
| --- | --- |
| TResult | Tipe hasil tugas yang selesai. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | Tugas yang harus ditunggu hingga selesai. |

### Nilai Kembalian

Sebuah tugas yang mengembalikan tugas pertama yang selesai ketika tugas apa pun selesai.

## Lihat Juga

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)