---
title: TimerQueue
second_title: Aspose.Slides for C++ API 레퍼런스
description: Timer 객체를 처리하는 큐입니다. 이것은 단지 구현일 뿐입니다. Timer 객체는 스스로 등록되므로 이를 사용하기 위해 직접 등록할 필요가 없습니다 - 대신 Timer 클래스 API를 사용하십시오. 이는 액세스 함수(들)를 통해 메모리 관리가 이루어지는 싱글톤 유형입니다. 직접 인스턴스를 생성해서는 안 됩니다.
type: docs
weight: 261
url: /ko/system.threading/timerqueue/
---
## TimerQueue 클래스


큐는 [Timer](../timer/) 객체를 처리합니다. 이것은 단지 구현일 뿐입니다. [Timer](../timer/) 객체는 스스로 등록되므로 이를 사용하기 위해 직접 등록할 필요가 없습니다 - 대신 [Timer](../timer/) 클래스 API를 사용하십시오. 이는 액세스 함수(들)로 메모리 관리가 이루어지는 싱글톤 유형입니다. 직접 인스턴스를 생성해서는 안 됩니다.

```cpp
class TimerQueue
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| **bool** [Add](./add/)([Timer](../timer/) *) | 큐에 타이머를 등록합니다. |
| **bool** [Delete](./delete/)([Timer](../timer/) *) | 큐에서 타이머를 삭제합니다. |
| static [TimerQueue](./)\& [GetInstance](./getinstance/)() | 구현 싱글톤. |
| static void [JoinWorkerThread](./joinworkerthread/)() | 워커 스레드에 조인합니다. 필요한 경우 무한히 대기합니다. |
| void [operator=](./operator_equal/)(const [TimerQueue](./)\&) | 복사되지 않습니다. |
|  [TimerQueue](./timerqueue/)(const [TimerQueue](./)\&) | 복사되지 않습니다. |
## 참고

* 네임스페이스 [System::Threading](../)
* 라이브러리 [Aspose.Slides](../../)