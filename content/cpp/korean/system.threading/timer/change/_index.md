---
title: Change()
second_title: Aspose.Slides for C++ API 참조
description: 타이머를 다시 예약하거나 취소합니다.
type: docs
weight: 14
url: /ko/system.threading/timer/change/
---
## Timer::Change(int64_t, int64_t) 메서드

타이머를 다시 예약하거나 취소합니다.

```cpp
bool System::Threading::Timer::Change(int64_t dueTime, int64_t period)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dueTime | **int64_t** | [Timeout](../../timeout/) 다음 콜백 함수 호출 이전, 밀리초 단위; 음수 값은 예약되어 있더라도 타이머를 취소합니다. |
| period | **int64_t** | [Timeout](../../timeout/) 연속적인 콜백 함수 호출 사이, 밀리초 단위; 0 이하 값은 타이머가 한 번만 실행되어야 함을 의미합니다. |

## Timer::Change(System::TimeSpan, System::TimeSpan) 메서드

타이머를 다시 예약하거나 취소합니다.

```cpp
bool System::Threading::Timer::Change(System::TimeSpan dueTime, System::TimeSpan period)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) 다음 콜백 함수 호출 이전; 음수 값은 예약되어 있더라도 타이머를 취소합니다. |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) 연속적인 콜백 함수 호출 사이; 0 이하 값은 타이머가 한 번만 실행되어야 함을 의미합니다. |

## 참고

* 클래스 [Timer](../)
* 클래스 [TimeSpan](../../../system/timespan/)
* 네임스페이스 [System::Threading](../../)
* 라이브러리 [Aspose.Slides](../../../)