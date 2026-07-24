---
title: WaitAll()
second_title: Aspose.Slides için C++ API Referansı
description: Sağlanan tüm Task nesnelerinin yürütmeyi tamamlamasını bekler.
type: docs
weight: 170
url: /tr/system.threading.tasks/waitall/
---
## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) fonksiyon

Sağlanan tüm [Task](../task/) nesnelerinin yürütmeyi tamamlamasını bekler.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Beklenilecek [Task](../task/) örneklerinden oluşan bir dizi. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Görevlerin tamamlanmasını beklerken gözlemlenecek bir [CancellationToken](../../system.threading/cancellationtoken/). |

## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&) fonksiyon

Sağlanan tüm [Task](../task/) nesnelerinin yürütmeyi tamamlamasını bekler.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Beklenilecek [Task](../task/) örneklerinden oluşan bir dizi. |

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)