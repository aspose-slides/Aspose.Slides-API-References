---
title: ContinueWith()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 결과 작업이 완료될 때 실행되는 연속 작업을 생성합니다.
type: docs
weight: 40
url: /ko/system.threading.tasks/resulttask/continuewith/
---
## ResultTask::ContinueWith(const Action\<RTaskPtr\<T\>\>\&) 메서드


Creates a continuation that executes when the result task completes.

```cpp
TaskPtr System::Threading::Tasks::ResultTask<T>::ContinueWith(const Action<RTaskPtr<T>> &continuationAction)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>\>\& | 이 작업이 완료될 때 실행되는 작업이며, 이 결과 작업을 받습니다 |

### 반환값

TaskPtr 연속 작업을 나타내는 새로운 작업
## 비고



연속 작업은 결과 값을 접근하기 위해 이 [ResultTask](../)를 받습니다 

## ResultTask::ContinueWith(const Func\<RTaskPtr\<T\>, TNewResult\>\&) 메서드


Creates a continuation that executes when the result task completes.

```cpp
template<typename TNewResult> RTaskPtr<TNewResult> System::Threading::Tasks::ResultTask<T>::ContinueWith(const Func<RTaskPtr<T>, TNewResult> &continuationFunction)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TNewResult | 작업 연속의 결과 유형 |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>, TNewResult\>\& | 이 작업이 완료될 때 연속 결과를 가져오고, 이 결과 작업을 받는 함수 |

### 반환값

RTaskPtr 연속 작업을 나타내는 새로운 작업
## 비고



연속 함수는 결과 값을 접근하기 위해 이 [ResultTask](../)를 받습니다 

## ResultTask::ContinueWith(const Action\<TaskPtr\>\&) 메서드


Creates a continuation that executes when the task completes.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | 이 작업이 완료될 때 실행되는 작업 |

### 반환값

TaskPtr 연속 작업을 나타내는 새로운 작업

## ResultTask::ContinueWith(const Func\<TaskPtr, TResult\>\&) 메서드


Creates a continuation that executes when the task completes.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TResult | 작업 결과의 유형 |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | 이 작업이 완료될 때 결과를 가져오는 함수 |

### 반환값

RTaskPtr 연속 작업을 나타내는 새로운 작업

## 참조

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* 클래스 [ResultTask](../)
* 클래스 [Func](../../../system/func/)
* 네임스페이스 [System::Threading::Tasks](../../)
* 라이브러리 [Aspose.Slides](../../../)