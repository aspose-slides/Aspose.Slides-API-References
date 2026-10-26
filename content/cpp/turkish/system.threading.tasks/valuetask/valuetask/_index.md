---
title: ValueTask()
second_title: Aspose.Slides for C++ API Referansı
description: Boş, başlatılmamış bir ValueTask oluşturur.
type: docs
weight: 1
url: /tr/system.threading.tasks/valuetask/valuetask/
---
## ValueTask::ValueTask() yapıcı


Boş, başlatılmamış bir [ValueTask](../) oluşturur.

```cpp
System::Threading::Tasks::ValueTask::ValueTask()
```

## Açıklamalar



Görev tamamlanmadı ve herhangi bir sonuç içermiyor. Sonucu almaya çalışmak bir istisna fırlatır.

## ValueTask::ValueTask(const TaskPtr\&) yapıcı


[Task](../../task/)'ye ortak bir işaretçiden bir [ValueTask](../) oluşturur.

```cpp
System::Threading::Tasks::ValueTask::ValueTask(const TaskPtr &task)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| task | const [TaskPtr](../../../system/taskptr/)\& | Sarmalanacak görev. Boş bir görev için null olabilir. |

## Açıklamalar



[ValueTask](../) sağlanan görevin durumunu temsil edecektir.

## Ayrıca Bakınız

* Typedef [TaskPtr](../../../system/taskptr/)
* Sınıf [ValueTask](../)
* İsim Alanı [System::Threading::Tasks](../../)
* Kütüphane [Aspose.Slides](../../../)