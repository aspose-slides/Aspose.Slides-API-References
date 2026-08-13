---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API 참조
description: 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 설정합니다 ISlidesLayoutOptions.
type: docs
weight: 222
url: /ko/aspose.slides.export/ihtmloptions/set_slideslayoutoptions/
---
## IHtmlOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) 메서드

프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 방식을 설정합니다 [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual void Aspose::Slides::Export::IHtmlOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value)=0
```

## 비고

예:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.html", SaveFormat::Html, options);
```

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [ISlidesLayoutOptions](../../islideslayoutoptions/)
* 클래스 [IHtmlOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)