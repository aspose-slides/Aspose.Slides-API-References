---
title: ValueTask()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 비어 있고 초기화되지 않은 ValueTask를 생성합니다.
type: docs
weight: 1
url: /ko/system.threading.tasks/valuetask/valuetask/
---
## ValueTask::ValueTask() 생성자

Constructs an empty, uninitialized [ValueTask](../).

```cpp
System::Threading::Tasks::ValueTask::ValueTask()
```

## 비고

The task is not completed and contains no result. Attempting to get the result will throw an exception. 

## ValueTask::ValueTask(const TaskPtr\&) 생성자

Constructs a [ValueTask](../) from a shared pointer to a [Task](../../task/).

```cpp
System::Threading::Tasks::ValueTask::ValueTask(const TaskPtr &task)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| task | const [TaskPtr](../../../system/taskptr/)\& | The task to wrap. Can be null for an empty task. |

## 비고

The [ValueTask](../) will represent the state of the provided task. 

## 참고

* typedef [TaskPtr](../../../system/taskptr/)
* 클래스 [ValueTask](../)
* 네임스페이스 [System::Threading::Tasks](../../)
* 라이브러리 [Aspose.Slides](../../../)