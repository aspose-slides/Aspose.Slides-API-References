---
title: WaitAny()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 제공된 Task 객체가 실행을 완료할 때까지 대기합니다.
type: docs
weight: 183
url: /ko/system.threading.tasks/waitany/
---
## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) function

제공된 [Task](../task/) 객체가 실행을 완료할 때까지 대기합니다.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | 대기할 [Task](../task/) 인스턴스들의 배열. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | 작업이 완료될 때까지 대기하면서 관찰할 [CancellationToken](../../system.threading/cancellationtoken/). |

### 반환 값

작업 배열에서 완료된 작업의 인덱스.

## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&) function

제공된 [Task](../task/) 객체가 실행을 완료할 때까지 대기합니다.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | 대기할 [Task](../task/) 인스턴스들의 배열. |

### 반환 값

작업 배열에서 완료된 작업의 인덱스.

## 참고

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* 클래스 [CancellationToken](../../system.threading/cancellationtoken/)
* 네임스페이스 [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)