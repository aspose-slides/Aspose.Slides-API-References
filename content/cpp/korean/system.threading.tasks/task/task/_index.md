---
title: Task()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 실행할 액션과 함께 Task를 생성합니다.
type: docs
weight: 1
url: /ko/system.threading.tasks/task/task/
---
## Task::Task(const Action<>\&) 생성자

실행할 액션과 함께 [Task](../)를 생성합니다.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | 비동기적으로 실행할 액션 |

## Task::Task(const Action<>\&, const CancellationToken\&) 생성자

액션 및 취소 토큰과 함께 [Task](../)를 생성합니다.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action, const CancellationToken &cancellationToken)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | 비동기적으로 실행할 액션 |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | 취소 요청을 모니터링하는 토큰 |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&) 생성자

상태를 보유하는 액션 및 상태 객체와 함께 [Task](../)를 생성합니다.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | 상태 객체를 받는 액션 |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 액션에 전달되는 사용자 정의 상태 객체 |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&, const CancellationToken\&) 생성자

상태를 보유하는 액션, 상태 및 취소 토큰과 함께 [Task](../)를 생성합니다.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state, const CancellationToken &cancellationToken)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | 상태 객체를 받는 액션 |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 액션에 전달되는 사용자 정의 상태 객체 |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | 취소 요청을 모니터링하는 토큰 |

## Task::Task() 생성자

초기화되지 않은 작업을 만들기 위한 내부 생성자.

```cpp
System::Threading::Tasks::Task::Task()
```

## 참조

* Typedef [Action](../../../system/action/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Task](../)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [Object](../../../system/object/)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)