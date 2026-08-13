---
title: get_Current()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 스레드의 동기화 컨텍스트를 가져옵니다.
type: docs
weight: 40
url: /ko/system.threading/synchronizationcontext/get_current/
---
## SynchronizationContext::get_Current() 메서드

현재 스레드에 대한 동기화 컨텍스트를 가져옵니다.

```cpp
static const SharedPtr<SynchronizationContext> & System::Threading::SynchronizationContext::get_Current()
```

### 반환값

SharedPtr<SynchronizationContext> 현재 스레드의 동기화 컨텍스트에 대한 공유 포인터.

## 비고

현재 스레드에 동기화 컨텍스트가 설정되지 않은 경우 null을 반환합니다.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [SynchronizationContext](../)
* 네임스페이스 [System::Threading](../../)
* 라이브러리 [Aspose.Slides](../../../)