---
title: Join()
second_title: Aspose.Slides for C++ API 참조
description: 관리되는 스레드를 조인합니다. 필요 시 무제한 대기를 수행합니다.
type: docs
weight: 196
url: /ko/system.threading/thread/join/
---
## Thread::Join() 메서드


관리되는 스레드를 조인합니다. 필요 시 무제한 대기를 수행합니다.

```cpp
void System::Threading::Thread::Join()
```

## Thread::Join(int) 메서드


관리되는 스레드를 조인합니다. 제한된 대기를 수행합니다.

```cpp
bool System::Threading::Thread::Join(int millisecondsTimeout)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| millisecondsTimeout | int | 밀리초 단위의 대기 제한 시간. |

### 반환 값

스레드가 성공적으로 조인된 경우 true, 제한 시간을 초과한 경우 false.

## Thread::Join(TimeSpan) 메서드


관리되는 스레드를 조인합니다. 제한된 대기를 수행합니다.

```cpp
bool System::Threading::Thread::Join(TimeSpan timeout)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | [TimeSpan](../../../system/timespan/)은(는) 스레드가 종료될 때까지 기다리는 시간 양으로 설정됩니다. |

### 반환 값

스레드가 성공적으로 조인된 경우 true, 제한 시간을 초과한 경우 false.

## 참조

* 클래스 [Thread](../)
* 클래스 [TimeSpan](../../../system/timespan/)
* 네임스페이스 [System::Threading](../../)
* 라이브러리 [Aspose.Slides](../../../)