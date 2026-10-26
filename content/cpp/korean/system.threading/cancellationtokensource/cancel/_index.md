---
title: Cancel()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 취소 요청을 전달합니다.
type: docs
weight: 40
url: /ko/system.threading/cancellationtokensource/cancel/
---
## CancellationTokenSource::Cancel() 메서드


취소 요청을 전달합니다.

```cpp
void System::Threading::CancellationTokenSource::Cancel()
```

## 비고



모든 등록된 콜백이 호출됩니다.

그 이후 [get_IsCancellationRequested()](../get_iscancellationrequested/)에 대한 호출은 true를 반환합니다.

콜백은 이 호출 동안 동기식으로 실행됩니다.

## 참조

* 클래스 [CancellationTokenSource](../)
* 네임스페이스 [System::Threading](../../)
* 라이브러리 [Aspose.Slides](../../../)