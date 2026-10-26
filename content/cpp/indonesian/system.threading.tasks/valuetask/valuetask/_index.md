---
title: ValueTask()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat ValueTask yang kosong dan belum diinisialisasi.
type: docs
weight: 1
url: /id/system.threading.tasks/valuetask/valuetask/
---
## ValueTask::ValueTask() konstruktor


Membuat [ValueTask](../) kosong yang belum diinisialisasi.

```cpp
System::Threading::Tasks::ValueTask::ValueTask()
```

## Catatan



Tugas belum selesai dan tidak berisi hasil. Mencoba mendapatkan hasil akan melemparkan pengecualian. 

## ValueTask::ValueTask(const TaskPtr\&) konstruktor


Membuat [ValueTask](../) dari pointer bersama ke [Task](../../task/).

```cpp
System::Threading::Tasks::ValueTask::ValueTask(const TaskPtr &task)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| task | const [TaskPtr](../../../system/taskptr/)\& | Tugas yang akan dibungkus. Dapat bernilai null untuk tugas kosong. |
## Catatan



[ValueTask](../) akan mewakili keadaan tugas yang diberikan. 

## Lihat Juga

* Typedef [TaskPtr](../../../system/taskptr/)
* Kelas [ValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Pustaka [Aspose.Slides](../../../)