---
title: WaitOne()
second_title: Aspose.Slides for C++ API 참조
description: 핸들이 무제한 기간 동안 발생할 때까지 대기합니다.
type: docs
weight: 27
url: /ko/system.threading/waithandle/waitone/
---
## WaitHandle::WaitOne() 메서드


핸들이 무제한 기간 동안 발생할 때까지 대기합니다.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne()
```


### 반환 값

시간 초과가 발생하지 않으므로 항상 true를 반환합니다.

## WaitHandle::WaitOne(int) 메서드


핸들이 발생할 때까지 대기합니다.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout)
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) 대기 시간(밀리초); -1은 무한 대기를 의미하고, 0은 확인 후 반환, 양수 값은 제한 시간을 의미합니다. |

### 반환 값

핸들이 발생하면 true, 제한 시간이 초과되면 false를 반환합니다.

## WaitHandle::WaitOne(TimeSpan) 메서드


핸들이 발생할 때까지 대기합니다.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(TimeSpan timeout)
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | [System::TimeSpan](../../../system/timespan/)은(는) 대기할 밀리초 수를 나타내고, [System::TimeSpan](../../../system/timespan/)은(는) -1 밀리초를 나타내어 무기한 대기함을 의미합니다. |

### 반환 값

핸들이 발생하면 true, 제한 시간이 초과되면 false를 반환합니다.

## WaitHandle::WaitOne(int, bool) 메서드


핸들이 발생할 때까지 대기합니다.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout, bool exitContext)
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) 대기 시간(밀리초); -1은 무한 대기를 의미하고, 0은 확인 후 반환, 양수 값은 제한 시간을 의미합니다. |
| exitContext | **bool** | true이면, 대기하기 전에 핸들에 대한 잠금을 해제해야 합니다. |

### 반환 값

핸들이 발생하면 true, 제한 시간이 초과되면 false를 반환합니다.

## 관련 항목

* 클래스 [WaitHandle](../)
* 클래스 [TimeSpan](../../../system/timespan/)
* 네임스페이스 [System::Threading](../../)
* 라이브러리 [Aspose.Slides](../../../)