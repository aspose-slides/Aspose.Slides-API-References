---
title: ContinueWith()
second_title: Aspose.Slides for C++ API Referansı
description: Sonuç görevi tamamlandığında yürütülen bir devam işlemi oluşturur.
type: docs
weight: 40
url: /tr/system.threading.tasks/resulttask/continuewith/
---
## ResultTask::ContinueWith(const Action\<RTaskPtr\<T\>\>\&) yöntemi


Sonuç görevi tamamlandığında yürütülen bir devam işlemi oluşturur.

```cpp
TaskPtr System::Threading::Tasks::ResultTask<T>::ContinueWith(const Action<RTaskPtr<T>> &continuationAction)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>\>\& | Bu görev tamamlandığında yürütülecek eylem, bu sonuç görevini alır |

### Dönüş Değeri

TaskPtr Devamı temsil eden yeni bir görev

## Açıklamalar



Devam eylemi, sonuç değerine erişmek için bu [ResultTask](../) öğesini alır 

## ResultTask::ContinueWith(const Func\<RTaskPtr\<T\>, TNewResult\>\&) yöntemi


Sonuç görevi tamamlandığında yürütülen bir devam işlemi oluşturur.

```cpp
template<typename TNewResult> RTaskPtr<TNewResult> System::Threading::Tasks::ResultTask<T>::ContinueWith(const Func<RTaskPtr<T>, TNewResult> &continuationFunction)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TNewResult | Görev devamının sonuç tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>, TNewResult\>\& | Bu görev tamamlandığında devam sonucunu almak için fonksiyon, bu sonuç görevini alır |

### Dönüş Değeri

RTaskPtr Devamı temsil eden yeni bir görev
## Açıklamalar



Devam fonksiyonu, sonuç değerine erişmek için bu [ResultTask](../) öğesini alır 

## ResultTask::ContinueWith(const Action\<TaskPtr\>\&) yöntemi


Görev tamamlandığında yürütülen bir devam işlemi oluşturur.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | Bu görev tamamlandığında yürütülecek eylem |

### Dönüş Değeri

TaskPtr Devamı temsil eden yeni bir görev

## ResultTask::ContinueWith(const Func\<TaskPtr, TResult\>\&) yöntemi


Görev tamamlandığında yürütülen bir devam işlemi oluşturur.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TResult | Görev sonucunun bir tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | Bu görev tamamlandığında sonucu almak için fonksiyon |

### Dönüş Değeri

RTaskPtr Devamı temsil eden yeni bir görev

## Ayrıca Bakınız

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [ResultTask](../)
* Class [Func](../../../system/func/)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)