---
title: Delay()
second_title: Aspose.Slides for C++ API 참조
description: 시간 지연 후에 완료되는 작업을 생성합니다.
type: docs
weight: 105
url: /ko/system.threading.tasks/delay/
---
## System::Threading::Tasks::Delay(int32_t) function

시간 지연 후에 완료되는 작업을 생성합니다.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | 반환된 작업이 완료되기까지 대기할 밀리초 수이며, 무한히 대기하려면 -1을 사용합니다. |

### 반환 값

시간 지연을 나타내는 작업입니다.

## System::Threading::Tasks::Delay(int32_t, const CancellationToken\&) function

시간 지연 후에 완료되고 취소할 수 있는 작업을 생성합니다.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay, const CancellationToken &cancellationToken)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | 반환된 작업이 완료되기까지 대기할 밀리초 수이며, 무한히 대기하려면 -1을 사용합니다. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | 지연을 취소하는 데 사용할 수 있는 취소 토큰입니다. |

### 반환 값

시간 지연을 나타내는 작업입니다.

## 또한 보기

* 타입정의 [TaskPtr](../../system/taskptr/)
* 클래스 [CancellationToken](../../system.threading/cancellationtoken/)
* 네임스페이스 [System::Threading::Tasks](../)
* 라이브러리 [Aspose.Slides](../../)