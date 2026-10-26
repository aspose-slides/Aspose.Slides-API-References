---
title: Register()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 취소가 요청될 때 호출되는 콜백을 등록합니다.
type: docs
weight: 40
url: /ko/system.threading/cancellationtoken/register/
---
## CancellationToken::Register(const Action<>\&) const method

취소가 요청될 때 호출되는 콜백을 등록합니다.

```cpp
CancellationTokenRegistration System::Threading::CancellationToken::Register(const Action<> &callback) const
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| callback | const [Action](../../../system/action/)<>\& | 취소가 요청될 때 실행할 Action<>입니다. |

### Return Value

[CancellationTokenRegistration](../../cancellationtokenregistration/) 객체를 반환하며, 콜백 등록을 해제하는 데 사용할 수 있습니다.

## 비고

취소가 이미 요청된 경우, 콜백은 즉시 호출됩니다.

콜백은 짧은 시간 안에 실행되고 차단되지 않아야 하며, [CancellationTokenSource](../../cancellationtokensource/)에서 Cancel()을 호출하는 스레드에서 실행됩니다.

## 참조

* 타입 정의 [Action](../../../system/action/)
* 클래스 [CancellationTokenRegistration](../../cancellationtokenregistration/)
* 클래스 [CancellationToken](../)
* 네임스페이스 [System::Threading](../../)
* 라이브러리 [Aspose.Slides](../../../)