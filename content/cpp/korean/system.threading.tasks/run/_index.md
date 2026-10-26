---
title: Run()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 작업을 스레드 풀에서 실행하도록 큐에 넣고 해당 작업에 대한 Task 핸들을 반환합니다.
type: docs
weight: 157
url: /ko/system.threading.tasks/run/
---
## System::Threading::Tasks::Run(const Action<>\&) function

지정된 작업을 스레드 풀에서 실행하도록 큐에 넣고 해당 작업에 대한 [Task](../task/) 핸들을 반환합니다.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | 비동기적으로 실행할 작업. |

### 반환 값

스레드 풀에서 실행하도록 큐에 넣은 작업을 나타내는 [Task](../task/).

## System::Threading::Tasks::Run(const Action<>\&, const CancellationToken\&) function

지정된 작업을 스레드 풀에서 실행하도록 큐에 넣고 해당 작업에 대한 [Task](../task/) 핸들을 반환합니다.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action, const CancellationToken &cancellationToken)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | 비동기적으로 실행할 작업. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | 작업이 아직 시작되지 않은 경우 작업을 취소하는 데 사용할 수 있는 취소 토큰. |

### 반환 값

스레드 풀에서 실행하도록 큐에 넣은 작업을 나타내는 [Task](../task/).

## System::Threading::Tasks::Run(const Func\<TaskPtr\>\&) function

지정된 작업을 스레드 풀에서 실행하도록 큐에 넣고 함수가 반환한 [Task](../task/)에 대한 프록시를 반환합니다.

```cpp
TaskPtr System::Threading::Tasks::Run(const Func<TaskPtr> &function)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/)\>\& | 비동기적으로 실행될 작업으로, [Task](../task/)을(를) 반환합니다. |

### 반환 값

함수가 반환한 [Task](../task/)에 대한 프록시를 나타내는 [Task](../task/).

## System::Threading::Tasks::Run(const Func\<TResult\>\&) function

지정된 작업을 스레드 풀에서 실행하도록 큐에 넣고 해당 작업에 대한 Task<TResult> 핸들을 반환합니다.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Run(const Func<TResult> &function)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TResult | 작업이 반환하는 결과의 형식. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<TResult\>\& | 비동기적으로 실행될 작업. |

### 반환 값

스레드 풀에서 실행하도록 큐에 넣은 작업을 나타내는 Task<TResult>.

## 참고

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Action](../../system/action/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* 클래스 [CancellationToken](../../system.threading/cancellationtoken/)
* 클래스 [Func](../../system/func/)
* 네임스페이스 [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)