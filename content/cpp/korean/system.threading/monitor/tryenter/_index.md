---
title: TryEnter()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 객체에 대한 독점 잠금을 시도합니다. 구현되지 않음.
type: docs
weight: 27
url: /ko/system.threading/monitor/tryenter/
---
## Monitor::TryEnter(const SharedPtr\<Object\>\&) 메서드


지정된 객체에 대한 독점 잠금을 시도합니다. 구현되지 않음.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj)
```


## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, bool\&) 메서드


지정된 객체에 대한 독점 잠금을 시도하고, 잠금이 획득되었는지를 나타내는 값을 원자적으로 설정합니다.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## Monitor::TryEnter(const SharedPtr\<Object\>\&, int32_t) 메서드


지정된 밀리초 동안 지정된 객체에 대한 독점 잠금을 시도합니다. 구현되지 않음.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```


## Monitor::TryEnter(const SharedPtr\<Object\>\&, TimeSpan) 메서드


지정된 시간 동안 지정된 객체에 대한 독점 잠금을 시도합니다. 구현되지 않음.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, TimeSpan timeout)
```


## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, int32_t, bool\&) 메서드


지정된 시간 동안 지정된 객체에 대한 독점 잠금을 시도하고, 잠금이 획득되었는지를 나타내는 값을 원자적으로 설정합니다.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool &lockTaken)
```

## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, TimeSpan, bool\&) 메서드


지정된 시간 동안 지정된 객체에 대한 독점 잠금을 시도하고, 잠금이 획득되었는지를 나타내는 값을 원자적으로 설정합니다.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, TimeSpan timeout, bool &lockTaken)
```

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [Monitor](../)
* 클래스 [TimeSpan](../../../system/timespan/)
* 네임스페이스 [System::Threading](../../)
* 라이브러리 [Aspose.Slides](../../../)