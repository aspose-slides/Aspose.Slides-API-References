---
title: CancellationToken
second_title: Aspose.Slides for C++ API 참조
description: 작업이 취소되어야 함을 알리는 알림을 전파합니다. 이 클래스는 스레드 간 협력적 취소 메커니즘을 제공하여 하나의 스레드가 다른 스레드에 작업 취소를 알릴 수 있게 합니다.
type: docs
weight: 14
url: /ko/system.threading/cancellationtoken/
---
## CancellationToken 클래스

Propagates notification that operations should be canceled. This class provides a mechanism for cooperative cancellation between threads, allowing one thread to notify others that an operation should be canceled.

```cpp
class CancellationToken : public System::Details::BoxableObjectBase
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [CancellationToken](./cancellationtoken/)() | 기본 생성자. |
| **bool** [get_CanBeCanceled](./get_canbecanceled/)() const | 이 토큰이 취소된 상태가 될 수 있는지 여부를 가져옵니다. |
| **bool** [get_IsCancellationRequested](./get_iscancellationrequested/)() const | 이 토큰에 대해 취소가 요청되었는지 여부를 가져옵니다. |
| static [CancellationToken](./) [get_None](./get_none/)() | 빈 [System::Threading::CancellationToken](./) 값을 반환합니다. |
| [CancellationTokenRegistration](../cancellationtokenregistration/) [Register](./register/)(const [Action](../../system/action/)<>\&) const | 취소가 요청될 때 호출되는 콜백을 등록합니다. |
| void [ThrowIfCancellationRequested](./throwifcancellationrequested/)() const | 취소가 요청된 경우 OperationCanceledException을 발생시킵니다. |

## 비고

[CancellationToken](./)은(는) 연결된 [CancellationTokenSource](../cancellationtokensource/)를 통해서만 취소될 수 있습니다.

## 참고

* 네임스페이스 [System::Threading](../)
* 라이브러리 [Aspose.Slides](../../)