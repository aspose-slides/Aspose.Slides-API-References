---
title: AsTask()
second_title: Aspose.Slides untuk C++ Referensi API
description: Mengonversi ResultValueTask ini menjadi pointer bersama ke ResultTask<T>.
type: docs
weight: 79
url: /id/system.threading.tasks/resultvaluetask/astask/
---
## ResultValueTask::AsTask() const metode


Mengonversi [ResultValueTask](../) ini menjadi pointer bersama ke ResultTask<T>.

```cpp
RTaskPtr<T> System::Threading::Tasks::ResultValueTask<T>::AsTask() const
```


### Nilai Kembali

RTaskPtr<T> Pointer bersama ke ResultTask<T> yang mewakili operasi ini.
## Catatan



Jika [ResultValueTask](../) berisi hasil langsung, membuat tugas yang selesai dengan hasil tersebut. Jika berisi tugas, mengembalikan pointer bersama ke tugas itu. 

## Lihat Juga

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Kelas [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Perpustakaan [Aspose.Slides](../../../)