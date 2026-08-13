---
title: Dispose()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 등록을 해제하고 연결된 CancellationTokenSource에서 콜백을 제거합니다. 이 메서드를 호출한 후에는 연결된 CancellationTokenSource가 취소될 때 등록된 콜백이 더 이상 호출되지 않습니다.
type: docs
weight: 1
url: /ko/system.threading/cancellationtokenregistration/dispose/
---
## CancellationTokenRegistration::Dispose() 메서드

등록을 해제하고 연결된 [CancellationTokenSource](../../cancellationtokensource/)에서 콜백을 제거합니다. 이 메서드를 호출한 후에는 연결된 [CancellationTokenSource](../../cancellationtokensource/)가 취소될 때 등록된 콜백이 더 이상 호출되지 않습니다.

```cpp
void System::Threading::CancellationTokenRegistration::Dispose()
```

## 비고

이 메서드를 여러 번 호출해도 안전합니다 - 이후 호출은 아무 영향도 미치지 않습니다.

## 참고

* 클래스 [CancellationTokenRegistration](../)
* 네임스페이스 [System::Threading](../../)
* 라이브러리 [Aspose.Slides](../../../)