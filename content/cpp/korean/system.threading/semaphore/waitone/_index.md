---
title: WaitOne()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 세마포어를 잠급니다. 필요하면 무제한 대기를 수행합니다.
type: docs
weight: 40
url: /ko/system.threading/semaphore/waitone/
---
## Semaphore::WaitOne() 메서드

세마포어를 잠급니다. 필요하다면 무제한 대기를 수행합니다.

```cpp
virtual bool System::Threading::Semaphore::WaitOne() override
```

### 반환 값

세마포어가 잠길 때까지 반환되지 않으므로 항상 true를 반환합니다.

## Semaphore::WaitOne(int) 메서드

세마포어를 잠급니다. 필요하다면 대기를 수행합니다.

```cpp
virtual bool System::Threading::Semaphore::WaitOne(int millisecondsTimeout) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| millisecondsTimeout | int | 밀리초 단위의 대기 시간 제한. |

### 반환 값

세마포어가 잠겼다면 true를, 시간 초과가 발생하면 false를 반환합니다.

## 참고

* 클래스 [Semaphore](../)
* 네임스페이스 [System::Threading](../../)
* 라이브러리 [Aspose.Slides](../../../)