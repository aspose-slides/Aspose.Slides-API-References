---
title: Post()
second_title: Aspose.Slides for C++ API 참조
description: 콜백을 비동기적으로 실행합니다.
type: docs
weight: 14
url: /ko/system.threading/synchronizationcontext/post/
---
## SynchronizationContext::Post(SendOrPostCallback, SharedPtr\<Object\>) 메서드


콜백을 비동기적으로 실행합니다.

```cpp
virtual void System::Threading::SynchronizationContext::Post(SendOrPostCallback d, SharedPtr<Object> state)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| d | [SendOrPostCallback](../../sendorpostcallback/) | 실행할 콜백. |
| state | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | [Object](../../../system/object/) 콜백 인자로 전달하기 위해. |

## 참고

* 타입정의 [SendOrPostCallback](../../sendorpostcallback/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [SynchronizationContext](../)
* 네임스페이스 [System::Threading](../../)
* 라이브러리 [Aspose.Slides](../../../)