---
title: WaitAny()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 핸들 중 하나가 발생할 때까지 대기합니다.
type: docs
weight: 14
url: /ko/system.threading/waithandle/waitany/
---
## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) 메서드

핸들 중 하나가 발생할 때까지 기다립니다.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | 대기할 핸들. |
| millisecondsTimeout | int | [Timeout](../../timeout/)을(를) 밀리초 단위로 대기합니다; -1은 무한 대기, 0은 확인 후 반환, 양수 값은 제한 시간입니다. |

### 반환 값

핸들 중 하나가 발생하면 true, 제한 시간이 초과되면 false.

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) 메서드

핸들 중 하나가 발생할 때까지 기다립니다.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | 대기할 핸들. |
| timeout | [TimeSpan](../../../system/timespan/) | [System::TimeSpan](../../../system/timespan/)은(는) 대기할 밀리초 수를 나타내는 값이며, [System::TimeSpan](../../../system/timespan/)은(는) 무한히 대기하기 위해 -1 밀리초를 나타냅니다. |

### 반환 값

핸들 중 하나가 발생하면 true, 제한 시간이 초과되면 false.

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) 메서드

핸들 중 하나가 발생할 때까지 기다립니다.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | 대기할 핸들. |

### 반환 값

waitHandles의 모든 요소가 신호를 받은 경우 true, 그렇지 않으면 메서드는 절대 반환되지 않습니다.

## 참고

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [WaitHandle](../)
* 클래스 [TimeSpan](../../../system/timespan/)
* 네임스페이스 [System::Threading](../../)
* 라이브러리 [Aspose.Slides](../../../)