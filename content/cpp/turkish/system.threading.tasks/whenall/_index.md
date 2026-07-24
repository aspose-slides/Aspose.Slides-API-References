---
title: WhenAll()
second_title: Aspose.Slides for C++ API Referansı
description: Sağlanan tüm görevler tamamlandığında gerçekleşecek bir görev oluşturur.
type: docs
weight: 196
url: /tr/system.threading.tasks/whenall/
---
## System::Threading::Tasks::WhenAll(const ArrayPtr\<TaskPtr\>\&) function

Sağlanan tüm görevler tamamlandığında gerçekleşecek bir görev oluşturur.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const ArrayPtr<TaskPtr> &tasks)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Tamamlanması için beklenen görevler. |

### Dönüş Değeri

Sağlanan tüm görevlerin tamamlanmasını temsil eden bir görev.

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) function

Sağlanan tüm görevler tamamlandığında gerçekleşecek bir görev oluşturur.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | Tamamlanması için beklenen görevler. |

### Dönüş Değeri

Sağlanan tüm görevlerin tamamlanmasını temsil eden bir görev.

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) function

Sağlanan tüm görevler tamamlandığında gerçekleşecek bir görev oluşturur.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TResult | Tamamlanmış görevlerin sonuçlarının türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | Tamamlanması için beklenen görevler. |

### Dönüş Değeri

Tüm görevler tamamlandığında tüm sonuçların bir dizisini döndüren bir görev.

## System::Threading::Tasks::WhenAll(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) function

Sağlanan tüm görevler tamamlandığında gerçekleşecek bir görev oluşturur.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TResult | Tamamlanmış görevlerin sonuçlarının türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | Tamamlanması için beklenen görevler. |

### Dönüş Değeri

Tüm görevler tamamlandığında tüm sonuçların bir dizisini döndüren bir görev.

## İlgili

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)