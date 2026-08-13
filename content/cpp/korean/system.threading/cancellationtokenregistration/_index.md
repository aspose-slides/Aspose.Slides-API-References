---
title: CancellationTokenRegistration
second_title: Aspose.Slides for C++ API 참조
description: 취소 토큰 콜백에 대한 등록을 나타냅니다.
type: docs
weight: 27
url: /ko/system.threading/cancellationtokenregistration/
---
## CancellationTokenRegistration 클래스

취소 토큰 콜백에 대한 등록을 나타냅니다.

```cpp
class CancellationTokenRegistration
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| void [Dispose](./dispose/)() | 등록을 해제하고 연관된 [CancellationTokenSource](../cancellationtokensource/)에서 콜백을 제거합니다. 이 메서드를 호출한 후에는 연관된 [CancellationTokenSource](../cancellationtokensource/)가 취소될 때 등록된 콜백이 더 이상 호출되지 않습니다. |
## 비고

이 클래스는 취소 토큰에서 콜백을 등록 해제할 수 있게 해 줍니다. 해제될 경우 연관된 [CancellationTokenSource](../cancellationtokensource/)에서 콜백을 제거합니다.  
이 클래스를 직접 생성해서는 안 되며, [CancellationToken](../cancellationtoken/) 등록 메서드가 반환합니다. 

## 참조

* 네임스페이스 [System::Threading](../)
* 라이브러리 [Aspose.Slides](../../)