---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API 참조
description: 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져옵니다 ISlidesLayoutOptions.
type: docs
weight: 1
url: /ko/aspose.slides.export/htmloptions/get_slideslayoutoptions/
---
## HtmlOptions::get_SlidesLayoutOptions() 메서드


프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져옵니다 [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::HtmlOptions::get_SlidesLayoutOptions() override
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

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [ISlidesLayoutOptions](../../islideslayoutoptions/)
* 클래스 [HtmlOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)