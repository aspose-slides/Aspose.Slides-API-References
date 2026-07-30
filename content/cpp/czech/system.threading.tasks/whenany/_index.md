---
title: WhenAny()
second_title: Aspose.Slides pro C++ - reference API
description: Vytvoří úlohu, která bude dokončena, jakmile bude dokončena některá z dodaných úloh.
type: docs
weight: 209
url: /cs/system.threading.tasks/whenany/
---
## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) function


Vytvoří úlohu, která bude dokončena, jakmile bude dokončena některá z dodaných úloh.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | Úlohy, na které se čeká, dokud nedojde k dokončení. |

### Návratová hodnota

Úloha, která představuje dokončení jedné z dodaných úloh.

## System::Threading::Tasks::WhenAny(const ArrayPtr\<TaskPtr\>\&) function


Vytvoří úlohu, která bude dokončena, jakmile bude dokončena některá z dodaných úloh.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const ArrayPtr<TaskPtr> &tasks)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Úlohy, na které se čeká, dokud nedojde k dokončení. |

### Návratová hodnota

Úloha, která představuje dokončení jedné z dodaných úloh.

## System::Threading::Tasks::WhenAny(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) function


Vytvoří úlohu, která bude dokončena, jakmile bude dokončena některá z dodaných úloh.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TResult | Typ výsledku dokončené úlohy. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | Úlohy, na které se čeká, dokud nedojde k dokončení. |

### Návratová hodnota

Úloha, která vrací první dokončenou úlohu, když je dokončena jakákoli úloha.

## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) function


Vytvoří úlohu, která bude dokončena, jakmile bude dokončena některá z dodaných úloh.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TResult | Typ výsledku dokončené úlohy. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | Úlohy, na které se čeká, dokud nedojde k dokončení. |

### Návratová hodnota

Úloha, která vrací první dokončenou úlohu, když je dokončena jakákoli úloha.

## Viz také

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Třída [IEnumerable](../../system.collections.generic/ienumerable/)
* Jmenný prostor [System::Threading::Tasks](../)
* Knihovna [Aspose.Slides](../../)