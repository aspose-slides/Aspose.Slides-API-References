---
title: set_InterruptionToken()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 중단 요청을 모니터링하기 위한 토큰입니다.
type: docs
weight: 248
url: /ko/aspose.slides/iloadoptions/set_interruptiontoken/
---
## ILoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) 메서드

중단 요청을 모니터링하기 위한 토큰입니다.

```cpp
virtual void Aspose::Slides::ILoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value)=0
```

## 비고

[IPresentation](../../ipresentation/) 인스턴스 전체 수명주기를 관리합니다. 프레젠테이션 로드 또는 저장과 같은 장기 실행 작업은 [IInterruptionTokenSource](../../iinterruptiontokensource/)의 [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) 메서드를 호출하여 중단됩니다.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IInterruptionToken](../../iinterruptiontoken/)
* 클래스 [ILoadOptions](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)