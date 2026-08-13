---
title: ContinueWith()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 작업이 완료될 때 실행되는 연속 작업을 생성합니다.
type: docs
weight: 118
url: /ko/system.threading.tasks/task/continuewith/
---
## Task::ContinueWith(const Action\<TaskPtr\>\&) 메서드

작업이 완료될 때 실행되는 연속 작업을 생성합니다.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | 이 작업이 완료될 때 실행할 Action |

### 반환 값

TaskPtr 연속 작업을 나타내는 새 작업

## Task::ContinueWith(const Func\<TaskPtr, TResult\>\&) 메서드

작업이 완료될 때 실행되는 연속 작업을 생성합니다.

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

### 반환 값

RTaskPtr 연속 작업을 나타내는 새 작업

## 또 보기

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* 클래스 [Task](../)
* 클래스 [Func](../../../system/func/)
* 네임스페이스 [System::Threading::Tasks](../../)
* 라이브러리 [Aspose.Slides](../../../)