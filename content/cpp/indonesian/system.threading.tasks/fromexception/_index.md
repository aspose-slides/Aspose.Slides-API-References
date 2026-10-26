---
title: FromException()
second_title: Aspose.Slides untuk Referensi API C++
description: Membuat tugas yang telah selesai dengan pengecualian yang ditentukan.
type: docs
weight: 131
url: /id/system.threading.tasks/fromexception/
---
## System::Threading::Tasks::FromException(const Exception\&) fungsi


Membuat tugas yang telah selesai dengan pengecualian yang ditentukan.

```cpp
TaskPtr System::Threading::Tasks::FromException(const Exception &exception)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | Pengecualian yang digunakan untuk menyelesaikan tugas. |

### Nilai Kembalian

Tugas yang gagal.

## System::Threading::Tasks::FromException(const Exception\&) fungsi


Membuat tugas yang telah selesai dengan pengecualian yang ditentukan dan tipe hasil.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromException(const Exception &exception)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TResult | Tipe hasil tugas. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | Pengecualian yang digunakan untuk menyelesaikan tugas. |

### Nilai Kembalian

Tugas yang gagal dengan tipe hasil yang ditentukan.

## Lihat Juga

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Exception](../../system/exception/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)