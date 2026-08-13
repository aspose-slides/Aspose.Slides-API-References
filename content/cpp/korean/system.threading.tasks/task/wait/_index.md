---
title: Wait()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 취소 지원과 함께 작업이 완료될 때까지 기다립니다.
type: docs
weight: 183
url: /ko/system.threading.tasks/task/wait/
---
## Task::Wait(const CancellationToken\&) 메서드

작업이 취소 지원과 함께 완료될 때까지 대기합니다.

```cpp
void System::Threading::Tasks::Task::Wait(const CancellationToken &cancellationToken)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | 대기 중에 취소를 감시하는 토큰 |

## Task::Wait() 메서드

작업이 완료될 때까지 대기합니다.

```cpp
void System::Threading::Tasks::Task::Wait()
```

## 참고

* 클래스 [CancellationToken](../../../system.threading/cancellationtoken/)
* 클래스 [Task](../)
* 네임스페이스 [System::Threading::Tasks](../../)
* 라이브러리 [Aspose.Slides](../../../)