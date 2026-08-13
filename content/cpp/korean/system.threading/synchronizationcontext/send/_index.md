---
title: Send()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 콜백을 동기식으로 실행합니다.
type: docs
weight: 27
url: /ko/system.threading/synchronizationcontext/send/
---
## SynchronizationContext::Send(SendOrPostCallback, SharedPtr\<Object\>) 메서드

콜백을 동기식으로 실행합니다.

```cpp
virtual void System::Threading::SynchronizationContext::Send(SendOrPostCallback d, SharedPtr<Object> state)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| d | [SendOrPostCallback](../../sendorpostcallback/) | 실행할 콜백. |
| state | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/)을(를) 콜백 인수로 전달합니다. |

## 비고

구현되지 않음.

## 참고

* 타입정의 [SendOrPostCallback](../../sendorpostcallback/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [SynchronizationContext](../)
* 네임스페이스 [System::Threading](../../)
* 라이브러리 [Aspose.Slides](../../../)