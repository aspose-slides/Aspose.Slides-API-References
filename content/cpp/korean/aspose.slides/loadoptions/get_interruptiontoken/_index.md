---
title: get_InterruptionToken()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 중단 요청을 모니터링하기 위한 토큰입니다.
type: docs
weight: 235
url: /ko/aspose.slides/loadoptions/get_interruptiontoken/
---
## LoadOptions::get_InterruptionToken() 메서드

이 토큰은 중단 요청을 모니터링하기 위한 토큰입니다.

```cpp
System::SharedPtr<IInterruptionToken> Aspose::Slides::LoadOptions::get_InterruptionToken() override
```

## 비고

이 토큰은 전체 [IPresentation](../../ipresentation/) 인스턴스 수명을 관리합니다. 프레젠테이션의 로드 또는 저장과 같은 장기 실행 작업은 [InterruptionTokenSource](../../interruptiontokensource/)의 [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) 메서드를 호출함으로써 중단됩니다.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IInterruptionToken](../../iinterruptiontoken/)
* Class [LoadOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)