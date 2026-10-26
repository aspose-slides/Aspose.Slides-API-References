---
title: WaitAll()
second_title: Aspose.Slides for C++ API 참조
description: 모든 핸들이 발생할 때까지 기다립니다.
type: docs
weight: 1
url: /ko/system.threading/waithandle/waitall/
---
## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) method

모든 핸들이 발생할 때까지 대기합니다.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | 대기할 핸들. |
| millisecondsTimeout | int | [Timeout](../../timeout/) 대기 시간(밀리초); -1은 무한 대기를 의미하고, 0은 확인 후 반환, 양의 값은 제한 시간입니다. |

### 반환 값

모든 핸들이 발생하면 true, 제한 시간을 초과하면 false.

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) method

모든 핸들이 발생할 때까지 대기합니다.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | 대기할 핸들. |
| timeout | [TimeSpan](../../../system/timespan/) | [System::TimeSpan](../../../system/timespan/)는 대기할 밀리초 수를 나타내고, [System::TimeSpan](../../../system/timespan/)는 -1밀리초를 나타내어 무한히 대기함을 의미합니다. |

### 반환 값

모든 핸들이 발생하면 true, 제한 시간을 초과하면 false.

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) method

모든 핸들이 발생할 때까지 대기합니다.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | 대기할 핸들. |

### 반환 값

waitHandles의 모든 요소가 신호를 받으면 true; 그렇지 않으면 메서드는 반환되지 않습니다.

## 관련 항목

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [WaitHandle](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)