---
title: ResultValueTask()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 빈, 초기화되지 않은 ResultValueTask를 생성합니다.
type: docs
weight: 1
url: /ko/system.threading.tasks/resultvaluetask/resultvaluetask/
---
## ResultValueTask::ResultValueTask() 생성자

빈, 초기화되지 않은 [ResultValueTask](../)을 생성합니다.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask()
```

## 비고

작업이 완료되지 않았으며 결과를 포함하고 있지 않습니다. 결과를 가져오려 시도하면 예외가 발생합니다.

## ResultValueTask::ResultValueTask(const T\&) 생성자

지정된 결과와 함께 완료된 [ResultValueTask](../)을 생성합니다.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const T &result)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| result | const T\& | 완료된 작업에 래핑할 결과 값. |

## 비고

이 작업은 값을 즉시 반환하는 성공적으로 완료된 작업을 생성합니다.

## ResultValueTask::ResultValueTask(const RTaskPtr\<T\>\&) 생성자

ResultTask<T>에 대한 공유 포인터에서 [ResultValueTask](../)을 생성합니다.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const RTaskPtr<T> &task)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| task | const [RTaskPtr](../../../system/rtaskptr/)\<T\>\& | 래핑할 작업입니다. 빈 작업의 경우 null일 수 있습니다. |

## 비고

[ResultValueTask](../)은 제공된 작업의 상태와 결과를 나타냅니다.

## 참조

* typedef [RTaskPtr](../../../system/rtaskptr/)
* 클래스 [ResultValueTask](../)
* 네임스페이스 [System::Threading::Tasks](../../)
* 라이브러리 [Aspose.Slides](../../../)