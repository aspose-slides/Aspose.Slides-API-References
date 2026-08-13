---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API 참조
description: 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 ISlidesLayoutOptions에서 가져옵니다.
type: docs
weight: 157
url: /ko/aspose.slides.export/itiffoptions/get_slideslayoutoptions/
---
## ITiffOptions::get_SlidesLayoutOptions() 메서드

프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져옵니다 [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::ITiffOptions::get_SlidesLayoutOptions()=0
```

## 비고

예:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<TiffOptions> options = System::MakeObject<TiffOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.tiff", SaveFormat::Tiff, options);
```

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [ISlidesLayoutOptions](../../islideslayoutoptions/)
* 클래스 [ITiffOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)