---
title: Parallel
second_title: Aspose.Slides для C++ справочник API
description: Обеспечивает поддержку параллельных циклов и областей.
type: docs
weight: 1
url: /ru/system.threading.tasks/parallel/
---
## Parallel класс

Предоставляет поддержку параллельных циклов и областей.

```cpp
class Parallel
```
## Методы

| Метод | Описание |
| --- | --- |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[ParallelOptions](../paralleloptions/)\>\&, const [Action](../../system/action/)\<TSource\>\&) | Выполняет операцию foreach над IEnumerable, в которой итерации могут выполняться параллельно. |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [Action](../../system/action/)\<TSource\>\&) | Выполняет операцию foreach над IEnumerable, в которой итерации могут выполняться параллельно. |
## Замечания

Этот класс предоставляет методы для параллельного выполнения циклов и операций. 
## См. также

* пространство имён [System::Threading::Tasks](../)
* библиотека [Aspose.Slides](../../)