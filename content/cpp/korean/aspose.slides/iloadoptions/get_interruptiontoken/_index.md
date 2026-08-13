---
title: get_InterruptionToken()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 중단 요청을 모니터링하기 위한 토큰입니다.
type: docs
weight: 235
url: /ko/aspose.slides/iloadoptions/get_interruptiontoken/
---
## ILoadOptions::get_InterruptionToken() 메서드


중단 요청을 모니터링하기 위한 토큰입니다.

```cpp
virtual System::SharedPtr<IInterruptionToken> Aspose::Slides::ILoadOptions::get_InterruptionToken()=0
```

## 비고


이 토큰은 전체 [IPresentation](../../ipresentation/) 인스턴스 수명을 관리합니다. 프레젠테이션 로드 또는 저장과 같은 장시간 실행되는 작업은 [IInterruptionTokenSource](../../iinterruptiontokensource/)의 [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) 메서드를 호출함으로써 중단됩니다. 
## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IInterruptionToken](../../iinterruptiontoken/)
* 클래스 [ILoadOptions](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)