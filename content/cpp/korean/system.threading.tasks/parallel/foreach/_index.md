---
title: ForEach()
second_title: Aspose.Slides for C++ API 참조
description: 반복이 병렬로 실행될 수 있는 IEnumerable에 대해 foreach 작업을 수행합니다.
type: docs
weight: 1
url: /ko/system.threading.tasks/parallel/foreach/
---
## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const SharedPtr\<ParallelOptions\>\&, const Action\<TSource\>\&) method

반복이 병렬로 실행될 수 있는 IEnumerable에 대해 foreach 작업을 수행합니다.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const SharedPtr<ParallelOptions> &parallelOptions, const Action<TSource> &body)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TSource | 소스에 있는 데이터의 유형입니다. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | 열거 가능한 데이터 소스입니다. |
| parallelOptions | const [SharedPtr](../../../system/sharedptr/)\<[ParallelOptions](../../paralleloptions/)\>\& | 이 작업의 동작을 구성하는 객체입니다. |
| body | const [Action](../../../system/action/)\<TSource\>\& | 각 반복마다 호출되는 대리자입니다. |

### 반환값

[ParallelLoopResult](../../parallelloopresult/) 구조체는 루프가 완료된 부분에 대한 정보를 포함합니다.

## 비고

이 메서드는 소스 열거자를 분할하고 여러 스레드에서 동시에 본문 대리자를 실행합니다.

## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const Action\<TSource\>\&) method

반복이 병렬로 실행될 수 있는 IEnumerable에 대해 foreach 작업을 수행합니다.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const Action<TSource> &body)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TSource | 소스에 있는 데이터의 유형입니다. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | 열거 가능한 데이터 소스입니다. |
| body | const [Action](../../../system/action/)\<TSource\>\& | 각 반복마다 호출되는 대리자입니다. |

### 반환값

[ParallelLoopResult](../../parallelloopresult/) 구조체는 루프가 완료된 부분에 대한 정보를 포함합니다.

## 비고

무제한 병렬성과 취소 없이 기본 [ParallelOptions](../../paralleloptions/)을 사용합니다.

## 참조

* typedef [SharedPtr](../../../system/sharedptr/)
* typedef [Action](../../../system/action/)
* 클래스 [ParallelLoopResult](../../parallelloopresult/)
* 클래스 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 클래스 [ParallelOptions](../../paralleloptions/)
* 클래스 [Parallel](../)
* 네임스페이스 [System::Threading::Tasks](../../)
* 라이브러리 [Aspose.Slides](../../../)