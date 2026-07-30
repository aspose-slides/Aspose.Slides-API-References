---
title: WhenAll()
second_title: Aspose.Slides pro C++ referenci API
description: Vytvoří úlohu, která bude dokončena, až budou dokončeny všechny zadané úlohy.
type: docs
weight: 196
url: /cs/system.threading.tasks/whenall/
---
## System::Threading::Tasks::WhenAll(const ArrayPtr\<TaskPtr\>\&) function


Vytvoří úlohu, která bude dokončena, až budou dokončeny všechny zadané úlohy.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const ArrayPtr<TaskPtr> &tasks)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Úlohy, na které se má čekat, dokud nedojde k jejich dokončení. |

### Návratová hodnota

Úloha představující dokončení všech zadaných úloh.

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) function


Vytvoří úlohu, která bude dokončena, až budou dokončeny všechny zadané úlohy.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | Úlohy, na které se má čekat, dokud nedojde k jejich dokončení. |

### Návratová hodnota

Úloha představující dokončení všech zadaných úloh.

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) function


Vytvoří úlohu, která bude dokončena, až budou dokončeny všechny zadané úlohy.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```


### Parametry šablony

| Parameter | Description |
| --- | --- |
| TResult | Typ výsledků dokončených úloh. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | Úlohy, na které se má čekat, dokud nedojde k jejich dokončení. |

### Návratová hodnota

Úloha, která vrací pole všech výsledků po dokončení všech úloh.

## System::Threading::Tasks::WhenAll(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) function


Vytvoří úlohu, která bude dokončena, až budou dokončeny všechny zadané úlohy.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```


### Parametry šablony

| Parameter | Description |
| --- | --- |
| TResult | Typ výsledků dokončených úloh. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | Úlohy, na které se má čekat, dokud nedojde k jejich dokončení. |

### Návratová hodnota

Úloha, která vrací pole všech výsledků po dokončení všech úloh.

## Viz také

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Třída [IEnumerable](../../system.collections.generic/ienumerable/)
* Jmenný prostor [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)