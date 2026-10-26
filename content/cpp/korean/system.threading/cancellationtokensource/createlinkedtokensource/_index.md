---
title: CreateLinkedTokenSource()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 제공된 토큰 중 하나라도 취소되면 취소되는 연결된 토큰 소스를 생성합니다.
type: docs
weight: 66
url: /ko/system.threading/cancellationtokensource/createlinkedtokensource/
---
## CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken\&, const CancellationToken\&) 메서드

제공된 토큰 중 하나라도 취소되면 취소되는 연결된 토큰 소스를 생성합니다.

```cpp
static SharedPtr<CancellationTokenSource> System::Threading::CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken &token1, const CancellationToken &token2)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| token1 | const [CancellationToken](../../cancellationtoken/)\& | 모니터링할 첫 번째 취소 토큰. |
| token2 | const [CancellationToken](../../cancellationtoken/)\& | 모니터링할 두 번째 취소 토큰. |

### 반환 값

입력 토큰 중 하나가 취소될 때 취소되는 새 토큰 소스.

## 비고

반환된 소스는 입력 토큰 중 하나가 이미 취소된 경우 즉시 취소됩니다. 

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [CancellationTokenSource](../)
* 클래스 [CancellationToken](../../cancellationtoken/)
* 네임스페이스 [System::Threading](../../)
* Library [Aspose.Slides](../../../)