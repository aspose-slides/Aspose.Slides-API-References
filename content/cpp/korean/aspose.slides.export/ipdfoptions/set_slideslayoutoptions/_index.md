---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 ISlidesLayoutOptions로 설정합니다.
type: docs
weight: 378
url: /ko/aspose.slides.export/ipdfoptions/set_slideslayoutoptions/
---
## IPdfOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) 메서드

프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 설정합니다 [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value)=0
```

## 비고

예: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [ISlidesLayoutOptions](../../islideslayoutoptions/)
* 클래스 [IPdfOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)