---
title: Wait()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 객체에 대한 잠금을 해제하고 현재 스레드가 잠금을 다시 획득할 때까지 차단합니다. 지정된 제한 시간이 경과하면 스레드는 준비 큐에 들어갑니다. 대기하기 전에 동기화 컨텍스트의 동기화 도메인을 나갔다가 이후에 다시 도메인을 획득할 수 있습니다. 구현되지 않음.
type: docs
weight: 53
url: /ko/system.threading/monitor/wait/
---
## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t, bool) 메서드


객체에 대한 잠금을 해제하고 현재 스레드가 잠금을 다시 획득할 때까지 차단합니다. 지정된 제한 시간이 경과하면 스레드는 준비 큐에 들어갑니다. 옵션으로 대기하기 전 동기화 컨텍스트의 동기화 도메인을 나가고 이후에 도메인을 다시 획득합니다. 구현되지 않음.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool exitContext)
```


## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan, bool) 메서드


객체에 대한 잠금을 해제하고 현재 스레드가 잠금을 다시 획득할 때까지 차단합니다. 지정된 제한 시간이 경과하면 스레드는 준비 큐에 들어갑니다. 옵션으로 대기하기 전 동기화 컨텍스트의 동기화 도메인을 나가고 이후에 도메인을 다시 획득합니다. 구현되지 않음.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout, bool exitContext)
```


## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t) 메서드


객체에 대한 잠금을 해제하고 현재 스레드가 잠금을 다시 획득할 때까지 차단합니다. 지정된 제한 시간이 경과하면 스레드는 준비 큐에 들어갑니다. 구현되지 않음.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```


## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan) 메서드


객체에 대한 잠금을 해제하고 현재 스레드가 잠금을 다시 획득할 때까지 차단합니다. 지정된 제한 시간이 경과하면 스레드는 준비 큐에 들어갑니다. 구현되지 않음.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout)
```


## Monitor::Wait(const SharedPtr\<Object\>\&) 메서드


객체에 대한 잠금을 해제하고 현재 스레드가 잠금을 다시 획득할 때까지 차단합니다 구현되지 않음.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj)
```


## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [Monitor](../)
* 클래스 [TimeSpan](../../../system/timespan/)
* 네임스페이스 [System::Threading](../../)
* Library [Aspose.Slides](../../../)