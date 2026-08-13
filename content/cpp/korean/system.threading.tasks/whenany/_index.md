---
title: WhenAny()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 제공된 작업 중 어느 하나가 완료될 때 완료되는 작업을 생성합니다.
type: docs
weight: 209
url: /ko/system.threading.tasks/whenany/
---
## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) function


제공된 작업 중 어느 하나가 완료될 때 완료되는 작업을 생성합니다.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | 완료를 기다릴 작업들. |

### 반환 값

제공된 작업 중 하나의 완료를 나타내는 작업입니다.

## System::Threading::Tasks::WhenAny(const ArrayPtr\<TaskPtr\>\&) function


제공된 작업 중 어느 하나가 완료될 때 완료되는 작업을 생성합니다.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const ArrayPtr<TaskPtr> &tasks)
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | 완료를 기다릴 작업들. |

### 반환 값

제공된 작업 중 하나의 완료를 나타내는 작업입니다.

## System::Threading::Tasks::WhenAny(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) function


제공된 작업 중 어느 하나가 완료될 때 완료되는 작업을 생성합니다.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```


### 템플릿 매개 변수

| Parameter | Description |
| --- | --- |
| TResult | 완료된 작업 결과의 형식. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | 완료를 기다릴 작업들. |

### 반환 값

어떤 작업이 완료될 때 첫 번째로 완료된 작업을 반환하는 작업입니다.

## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) function


제공된 작업 중 어느 하나가 완료될 때 완료되는 작업을 생성합니다.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```


### 템플릿 매개 변수

| Parameter | Description |
| --- | --- |
| TResult | 완료된 작업 결과의 형식. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | 완료를 기다릴 작업들. |

### 반환 값

어떤 작업이 완료될 때 첫 번째로 완료된 작업을 반환하는 작업입니다.

## 또 보기

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)