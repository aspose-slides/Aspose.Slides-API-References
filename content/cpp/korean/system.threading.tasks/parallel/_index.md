---
title: Parallel
second_title: Aspose.Slides for C++ API 참조
description: 병렬 루프와 영역에 대한 지원을 제공합니다.
type: docs
weight: 1
url: /ko/system.threading.tasks/parallel/
---
## Parallel 클래스

Provides support for parallel loops and regions.

```cpp
class Parallel
```

## Methods

| Method | Description |
| --- | --- |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[ParallelOptions](../paralleloptions/)\>\&, const [Action](../../system/action/)\<TSource\>\&) | 반복이 병렬로 실행될 수 있는 IEnumerable에 대해 foreach 작업을 실행합니다. |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [Action](../../system/action/)\<TSource\>\&) | 반복이 병렬로 실행될 수 있는 IEnumerable에 대해 foreach 작업을 실행합니다. |
## 비고

이 클래스는 루프와 연산을 병렬로 실행하는 메서드를 제공합니다.

## 참고

* 네임스페이스 [System::Threading::Tasks](../)
* 라이브러리 [Aspose.Slides](../../)