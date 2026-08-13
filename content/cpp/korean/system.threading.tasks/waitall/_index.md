---
title: WaitAll()
second_title: Aspose.Slides for C++ API 참조
description: 제공된 Task 객체가 모두 실행을 완료할 때까지 대기합니다.
type: docs
weight: 170
url: /ko/system.threading.tasks/waitall/
---
## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) 함수

제공된 [Task](../task/) 객체가 모두 실행을 완료할 때까지 대기합니다.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | 대기할 [Task](../task/) 인스턴스들의 배열. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | 작업이 완료될 때까지 관찰할 [CancellationToken](../../system.threading/cancellationtoken/). |

## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&) 함수

제공된 [Task](../task/) 객체가 모두 실행을 완료할 때까지 대기합니다.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | 대기할 [Task](../task/) 인스턴스들의 배열. |

## 참조

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* 클래스 [CancellationToken](../../system.threading/cancellationtoken/)
* 네임스페이스 [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)