---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 프레젠테이션을 내보낼 때 페이지에 슬라이드가 배치되는 모드를 ISlidesLayoutOptions에서 가져옵니다.
type: docs
weight: 157
url: /ko/aspose.slides.export/ihtml5options/get_slideslayoutoptions/
---
## IHtml5Options::get_SlidesLayoutOptions() 메서드

프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져옵니다 [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::IHtml5Options::get_SlidesLayoutOptions()=0
```

## 비고

예시: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> slidesLayoutOptions = System::MakeObject<HandoutLayoutingOptions>();
slidesLayoutOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.html", SaveFormat::Html5, options);
```

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [ISlidesLayoutOptions](../../islideslayoutoptions/)
* 클래스 [IHtml5Options](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)