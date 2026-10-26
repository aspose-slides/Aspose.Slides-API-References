---
title: Start()
second_title: Aspose.Slides for C++ API 참조
description: 기본 스케줄러를 사용하여 작업 실행을 시작합니다.
type: docs
weight: 170
url: /ko/system.threading.tasks/task/start/
---
## Task::Start() 메서드

기본 스케줄러를 사용하여 작업 실행을 시작합니다.

```cpp
void System::Threading::Tasks::Task::Start()
```

## Task::Start(const SharedPtr\<TaskScheduler\>\&) 메서드

지정된 스케줄러를 사용하여 작업 실행을 시작합니다.

```cpp
void System::Threading::Tasks::Task::Start(const SharedPtr<TaskScheduler> &scheduler)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| scheduler | const [SharedPtr](../../../system/sharedptr/)\<[TaskScheduler](../../taskscheduler/)\>\& | 실행에 사용할 스케줄러 |

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Task](../)
* 클래스 [TaskScheduler](../../taskscheduler/)
* 네임스페이스 [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)