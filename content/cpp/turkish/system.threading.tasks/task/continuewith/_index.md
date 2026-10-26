---
title: ContinueWith()
second_title: Aspose.Slides için C++ API Referansı
description: Görev tamamlandığında yürütülen bir devam oluşturur.
type: docs
weight: 118
url: /tr/system.threading.tasks/task/continuewith/
---
## Task::ContinueWith(const Action\<TaskPtr\>\&) yöntemi


Görev tamamlandığında yürütülen bir devam oluşturur.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```


### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | Bu görev tamamlandığında yürütülecek eylem |

### Dönüş Değeri

TaskPtr Devamı temsil eden yeni bir görev

## Task::ContinueWith(const Func\<TaskPtr, TResult\>\&) yöntemi


Görev tamamlandığında yürütülen bir devam oluşturur.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```


### Şablon parametreleri

| Parameter | Description |
| --- | --- |
| TResult | Görev sonucunun bir türü |

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | Bu görev tamamlandığında sonucu almak için işlev |

### Dönüş Değeri

RTaskPtr Devamı temsil eden yeni bir görev

## Bunlara Bakın

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [Task](../)
* Class [Func](../../../system/func/)
* Namespace [System::Threading::Tasks](../../)
* Kütüphane [Aspose.Slides](../../../)