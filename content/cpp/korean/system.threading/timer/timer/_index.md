---
title: Timer()
second_title: Aspose.Slides for C++ API 참조
description: 생성자.
type: docs
weight: 1
url: /ko/system.threading/timer/timer/
---
## Timer::Timer(TimerCallback) 생성자

생성자.

```cpp
System::Threading::Timer::Timer(TimerCallback callback)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | 타이머에 의해 호출되는 함수. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, int64_t, int64_t) 생성자

생성자.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, int64_t dueTime, int64_t period)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | 타이머에 의해 호출되는 함수. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | 콜백 함수 인수. |
| dueTime | **int64_t** | [Timeout](../../timeout/) 첫 번째 콜백 함수 호출 이전에, 밀리초 단위; 음수 값은 생성 후 타이머를 예약하지 않으므로 나중에 다시 예약할 수 있습니다. |
| period | **int64_t** | [Timeout](../../timeout/) 콜백 함수의 연속 호출 사이, 밀리초 단위; 0 이하 값은 타이머가 한 번만 실행되어야 함을 의미합니다. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, System::TimeSpan, System::TimeSpan) 생성자

생성자.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, System::TimeSpan dueTime, System::TimeSpan period)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | 타이머에 의해 호출되는 함수. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | 콜백 함수 인수. |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) 첫 번째 콜백 함수 호출 이전에; 음수 값은 생성 후 타이머를 예약하지 않으므로 나중에 다시 예약할 수 있습니다. |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) 콜백 함수의 연속 호출 사이; 0 이하 값은 타이머가 한 번만 실행되어야 함을 의미합니다. |

## 참고

* 타입정의 [TimerCallback](../../timercallback/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Timer](../)
* 클래스 [Object](../../../system/object/)
* 클래스 [TimeSpan](../../../system/timespan/)
* 네임스페이스 [System::Threading](../../)
* 라이브러리 [Aspose.Slides](../../../)