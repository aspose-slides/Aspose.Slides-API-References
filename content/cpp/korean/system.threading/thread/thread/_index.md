---
title: Thread()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 생성자.
type: docs
weight: 1
url: /ko/system.threading/thread/thread/
---
## Thread::Thread() 생성자

생성자.

```cpp
System::Threading::Thread::Thread()
```

## Thread::Thread(ThreadStart) 생성자

생성자.

```cpp
System::Threading::Thread::Thread(ThreadStart thread_function)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| thread_function | [ThreadStart](../../threadstart/) | 스레드에서 실행될 함수. |

## Thread::Thread(ParameterizedThreadStart) 생성자

생성자.

```cpp
System::Threading::Thread::Thread(ParameterizedThreadStart thread_function)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| thread_function | [ParameterizedThreadStart](../../parameterizedthreadstart/) | 스레드에서 실행될 함수. |

## Thread::Thread(Thread\&) 생성자

복사 생성자.

```cpp
System::Threading::Thread::Thread(Thread &t)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| t | [Thread](../)\& | [Thread](../)에서 복사할 데이터. |

## 참조

* Typedef [ThreadStart](../../threadstart/)
* Typedef [ParameterizedThreadStart](../../parameterizedthreadstart/)
* 클래스 [Thread](../)
* 네임스페이스 [System::Threading](../../)
* 라이브러리 [Aspose.Slides](../../../)