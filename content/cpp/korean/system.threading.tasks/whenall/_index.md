---
title: WhenAll()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 제공된 모든 작업이 완료될 때 완료되는 작업을 생성합니다.
type: docs
weight: 196
url: /ko/system.threading.tasks/whenall/
---
## System::Threading::Tasks::WhenAll(const ArrayPtr\<TaskPtr\>\&) 함수

모든 제공된 작업이 완료될 때 완료되는 작업을 생성합니다.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const ArrayPtr<TaskPtr> &tasks)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | 완료될 때까지 기다릴 작업들. |

### 반환 값

제공된 모든 작업의 완료를 나타내는 작업.

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) 함수

모든 제공된 작업이 완료될 때 완료되는 작업을 생성합니다.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | 완료될 때까지 기다릴 작업들. |

### 반환 값

제공된 모든 작업의 완료를 나타내는 작업.

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) 함수

모든 제공된 작업이 완료될 때 완료되는 작업을 생성합니다.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TResult | 완료된 작업 결과의 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | 완료될 때까지 기다릴 작업들. |

### 반환 값

모든 작업이 완료될 때 모든 결과의 배열을 반환하는 작업.

## System::Threading::Tasks::WhenAll(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) 함수

모든 제공된 작업이 완료될 때 완료되는 작업을 생성합니다.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TResult | 완료된 작업 결과의 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | 완료될 때까지 기다릴 작업들. |

### 반환 값

모든 작업이 완료될 때 모든 결과의 배열을 반환하는 작업.

## 또 보기

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)