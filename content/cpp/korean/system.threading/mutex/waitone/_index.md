---
title: WaitOne()
second_title: Aspose.Slides for C++ API 참조
description: 뮤텍스를 잠급니다. 필요에 따라 무제한 대기를 수행합니다.
type: docs
weight: 53
url: /ko/system.threading/mutex/waitone/
---
## Mutex::WaitOne() 메서드

뮤텍스를 잠급니다. 필요에 따라 무제한 대기를 수행합니다.

```cpp
virtual bool System::Threading::Mutex::WaitOne() override
```

### 반환값

뮤텍스가 잠길 때까지 반환되지 않으므로 항상 true를 반환합니다.

## Mutex::WaitOne(int) 메서드

뮤텍스를 잠급니다. 필요에 따라 대기를 수행합니다.

```cpp
virtual bool System::Threading::Mutex::WaitOne(int millisecondsTimeout) override
```

### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| millisecondsTimeout | int | 밀리초 단위의 대기 제한 시간. |

### 반환값

뮤텍스가 잠기면 true를 반환하고, 타임아웃이 초과되면 false를 반환합니다.

## Mutex::WaitOne(TimeSpan) 메서드

뮤텍스를 잠급니다. 필요에 따라 대기를 수행합니다.

```cpp
virtual bool System::Threading::Mutex::WaitOne(TimeSpan timeout) override
```

### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | [System::TimeSpan](../../../system/timespan/)은(는) 대기할 밀리초 수를 나타내고, [System::TimeSpan](../../../system/timespan/)은(는) -1 밀리초를 나타내어 무한히 대기합니다. |

### 반환값

뮤텍스가 잠기면 true를 반환하고, 타임아웃이 초과되면 false를 반환합니다.

## 관련 항목

* 클래스 [Mutex](../)
* 클래스 [TimeSpan](../../../system/timespan/)
* 네임스페이스 [System::Threading](../../)
* 라이브러리 [Aspose.Slides](../../../)