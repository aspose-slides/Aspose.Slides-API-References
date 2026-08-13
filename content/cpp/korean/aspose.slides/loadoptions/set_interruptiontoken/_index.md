---
title: set_InterruptionToken()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 중단 요청을 모니터링하는 토큰입니다.
type: docs
weight: 248
url: /ko/aspose.slides/loadoptions/set_interruptiontoken/
---
## LoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) 메서드


중단 요청을 모니터링하는 토큰입니다.

```cpp
void Aspose::Slides::LoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value) override
```

## 비고


이 토큰은 전체 [IPresentation](../../ipresentation/) 인스턴스 수명을 관리합니다. 프레젠테이션을 로드하거나 저장하는 등 장시간 실행되는 작업은 [InterruptionTokenSource](../../interruptiontokensource/)의 [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) 메서드를 호출하여 중단됩니다. 
## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IInterruptionToken](../../iinterruptiontoken/)
* 클래스 [LoadOptions](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)