---
title: ThrowIfCancellationRequested()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 취소가 요청된 경우 OperationCanceledException을 발생시킵니다.
type: docs
weight: 53
url: /ko/system.threading/cancellationtoken/throwifcancellationrequested/
---
## CancellationToken::ThrowIfCancellationRequested() const 메서드

Throws a OperationCanceledException if cancellation has been requested.

```cpp
void System::Threading::CancellationToken::ThrowIfCancellationRequested() const
```

## 비고


This method provides a convenient way to check for cancellation at specific points in your code where it's safe to throw an exception.

## 참고

* 클래스 [CancellationToken](../)
* 네임스페이스 [System::Threading](../../)
* 라이브러리 [Aspose.Slides](../../../)