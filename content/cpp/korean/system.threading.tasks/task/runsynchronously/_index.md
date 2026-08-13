---
title: RunSynchronously()
second_title: Aspose.Slides for C++ API 참조
description: 현재 스레드에서 작업을 동기적으로 실행합니다.
type: docs
weight: 157
url: /ko/system.threading.tasks/task/runsynchronously/
---
## Task::RunSynchronously() 메서드

현재 스레드에서 작업을 동기적으로 실행합니다.

```cpp
void System::Threading::Tasks::Task::RunSynchronously()
```


## Task::RunSynchronously(const SharedPtr\<TaskScheduler\>\&) 메서드

지정된 스케줄러를 사용하여 작업을 동기적으로 실행합니다.

```cpp
void System::Threading::Tasks::Task::RunSynchronously(const SharedPtr<TaskScheduler> &scheduler)
```


### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| scheduler | const [SharedPtr](../../../system/sharedptr/)\<[TaskScheduler](../../taskscheduler/)\>\& | 실행에 사용할 스케줄러 |

## 참조

* typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Task](../)
* 클래스 [TaskScheduler](../../taskscheduler/)
* 네임스페이스 [System::Threading::Tasks](../../)
* 라이브러리 [Aspose.Slides](../../../)