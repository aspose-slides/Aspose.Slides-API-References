---
title: ForEach()
second_title: Справочник API Aspose.Slides для C++
description: Выполняет операцию foreach над IEnumerable, в которой итерации могут выполняться параллельно.
type: docs
weight: 1
url: /ru/system.threading.tasks/parallel/foreach/
---
## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const SharedPtr\<ParallelOptions\>\&, const Action\<TSource\>\&) метод

Выполняет операцию foreach над IEnumerable, в которой итерации могут запускаться параллельно.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const SharedPtr<ParallelOptions> &parallelOptions, const Action<TSource> &body)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TSource | Тип данных в источнике. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | Перечислимый источник данных. |
| parallelOptions | const [SharedPtr](../../../system/sharedptr/)\<[ParallelOptions](../../paralleloptions/)\>\& | Объект, который задаёт поведение этой операции. |
| body | const [Action](../../../system/action/)\<TSource\>\& | Делегат, вызываемый один раз за каждую итерацию. |

### Возвращаемое значение

Структура [ParallelLoopResult](../../parallelloopresult/), содержащая информацию о том, какая часть цикла выполнена.

## Примечания

Этот метод разбивает исходный перечислимый объект и выполняет делегат body на нескольких потоках одновременно.

## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const Action\<TSource\>\&) метод

Выполняет операцию foreach над IEnumerable, в которой итерации могут запускаться параллельно.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const Action<TSource> &body)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TSource | Тип данных в источнике. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | Перечислимый источник данных. |
| body | const [Action](../../../system/action/)\<TSource\>\& | Делегат, вызываемый один раз за каждую итерацию. |

### Возвращаемое значение

Структура [ParallelLoopResult](../../parallelloopresult/), содержащая информацию о том, какая часть цикла выполнена.

## Примечания

Использует [ParallelOptions](../../paralleloptions/) по умолчанию с неограниченным параллелизмом и без отмены.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* Класс [ParallelLoopResult](../../parallelloopresult/)
* Класс [IEnumerable](../../../system.collections.generic/ienumerable/)
* Класс [ParallelOptions](../../paralleloptions/)
* Класс [Parallel](../)
* Пространство имён [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)