---
title: Run()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengantri pekerjaan yang ditentukan untuk dijalankan pada thread pool dan mengembalikan sebuah handle Task untuk pekerjaan tersebut.
type: docs
weight: 157
url: /id/system.threading.tasks/run/
---
## System::Threading::Tasks::Run(const Action<>\&) fungsi

Mengantri pekerjaan yang ditentukan untuk dijalankan pada thread pool dan mengembalikan sebuah [Task](../task/) handle untuk pekerjaan tersebut.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | The work to execute asynchronously. |

### Nilai Kembali

Sebuah [Task](../task/) yang mewakili pekerjaan yang diantrikan untuk dieksekusi dalam thread pool.

## System::Threading::Tasks::Run(const Action<>\&, const CancellationToken\&) fungsi

Mengantri pekerjaan yang ditentukan untuk dijalankan pada thread pool dan mengembalikan sebuah [Task](../task/) handle untuk pekerjaan tersebut.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action, const CancellationToken &cancellationToken)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | The work to execute asynchronously. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | A cancellation token that can be used to cancel the work if it has not yet started. |

### Nilai Kembali

Sebuah [Task](../task/) yang mewakili pekerjaan yang diantrikan untuk dieksekusi dalam thread pool.

## System::Threading::Tasks::Run(const Func\<TaskPtr\>\&) fungsi

Mengantri pekerjaan yang ditentukan untuk dijalankan pada thread pool dan mengembalikan proxy untuk [Task](../task/) yang dikembalikan oleh fungsi.

```cpp
TaskPtr System::Threading::Tasks::Run(const Func<TaskPtr> &function)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/)\>\& | Pekerjaan yang akan dieksekusi secara asynchronous, yang mengembalikan sebuah [Task](../task/). |

### Nilai Kembali

Sebuah [Task](../task/) yang mewakili proxy untuk [Task](../task/) yang dikembalikan oleh fungsi.

## System::Threading::Tasks::Run(const Func\<TResult\>\&) fungsi

Mengantri pekerjaan yang ditentukan untuk dijalankan pada thread pool dan mengembalikan handle Task<TResult> untuk pekerjaan tersebut.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Run(const Func<TResult> &function)
```

### Parameter template

| Parameter | Deskripsi |
| --- | --- |
| TResult | Tipe hasil yang dikembalikan oleh tugas. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<TResult\>\& | Pekerjaan yang akan dieksekusi secara asynchronous. |

### Nilai Kembali

Sebuah Task<TResult> yang mewakili pekerjaan yang diantrikan untuk dieksekusi dalam thread pool.

## Lihat Juga

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Action](../../system/action/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Kelas [CancellationToken](../../system.threading/cancellationtoken/)
* Kelas [Func](../../system/func/)
* Namespace [System::Threading::Tasks](../)
* Perpustakaan [Aspose.Slides](../../)