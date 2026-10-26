---
title: WaitAny()
second_title: Aspose.Slides için C++ API Referansı
description: Sağlanan Task nesnelerinden herhangi birinin yürütmesini tamamlamasını bekler.
type: docs
weight: 183
url: /tr/system.threading.tasks/waitany/
---
## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) fonksiyon


Sağlanan [Task](../task/) nesnelerinin herhangi birinin yürütmesini tamamlamasını bekler.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Beklenecek [Task](../task/) örneklerinden oluşan bir dizi. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Görevlerin tamamlanmasını beklerken gözlemlenecek bir [CancellationToken](../../system.threading/cancellationtoken/). |

### Dönüş Değeri

Görevler dizisindeki tamamlanan görevin dizin indeksi.

## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&) fonksiyon


Sağlanan [Task](../task/) nesnelerinin herhangi birinin yürütmesini tamamlamasını bekler.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Beklenecek [Task](../task/) örneklerinden oluşan bir dizi. |

### Dönüş Değeri

Görevler dizisindeki tamamlanan görevin dizin indeksi.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Sınıf [CancellationToken](../../system.threading/cancellationtoken/)
* Ad alanı [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)