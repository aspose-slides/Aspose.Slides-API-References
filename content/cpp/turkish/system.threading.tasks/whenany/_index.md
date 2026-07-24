---
title: WhenAny()
second_title: Aspose.Slides for C++ API Referansı
description: Sağlanan görevlerden herhangi biri tamamlandığında tamamlanacak bir görev oluşturur.
type: docs
weight: 209
url: /tr/system.threading.tasks/whenany/
---
## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) fonksiyonu

Sağlanan görevlerden herhangi biri tamamlandığında tamamlanacak bir görev oluşturur.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | Tamamlanma için beklenen görevler. |

### Dönüş Değeri

Sağlanan görevlerden birinin tamamlanmasını temsil eden bir görev.

## System::Threading::Tasks::WhenAny(const ArrayPtr\<TaskPtr\>\&) fonksiyonu

Sağlanan görevlerden herhangi biri tamamlandığında tamamlanacak bir görev oluşturur.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const ArrayPtr<TaskPtr> &tasks)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Tamamlanma için beklenen görevler. |

### Dönüş Değeri

Sağlanan görevlerden birinin tamamlanmasını temsil eden bir görev.

## System::Threading::Tasks::WhenAny(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) fonksiyonu

Sağlanan görevlerden herhangi biri tamamlandığında tamamlanacak bir görev oluşturur.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TResult | Tamamlanan görevin sonucunun türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | Tamamlanma için beklenen görevler. |

### Dönüş Değeri

Herhangi bir görev tamamlandığında ilk tamamlanan görevi döndüren bir görev.

## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) fonksiyonu

Sağlanan görevlerden herhangi biri tamamlandığında tamamlanacak bir görev oluşturur.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TResult | Tamamlanan görevin sonucunun türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | Tamamlanma için beklenen görevler. |

### Dönüş Değeri

Herhangi bir görev tamamlandığında ilk tamamlanan görevi döndüren bir görev.

## Ayrıca Bakınız

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)