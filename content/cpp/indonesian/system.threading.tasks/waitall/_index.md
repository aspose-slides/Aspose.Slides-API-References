---
title: WaitAll()
second_title: Referensi API Aspose.Slides untuk C++
description: Menunggu semua objek Task yang disediakan selesai dieksekusi.
type: docs
weight: 170
url: /id/system.threading.tasks/waitall/
---
## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) function

Menunggu semua objek [Task](../task/) yang disediakan hingga selesai dieksekusi.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Sebuah array berisi instance [Task](../task/) yang akan ditunggu. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Sebuah [CancellationToken](../../system.threading/cancellationtoken/) untuk dipantau saat menunggu tugas selesai. |

## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&) function

Menunggu semua objek [Task](../task/) yang disediakan hingga selesai dieksekusi.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Sebuah array berisi instance [Task](../task/) yang akan ditunggu. |

## See Also

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)