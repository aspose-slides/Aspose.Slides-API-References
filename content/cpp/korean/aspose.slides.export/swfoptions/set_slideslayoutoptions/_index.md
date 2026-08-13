---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API 참조
description: 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 설정합니다 ISlidesLayoutOptions. 이 속성은 HandoutLayoutingOptions 유형의 객체 할당을 지원하지 않습니다.
type: docs
weight: 404
url: /ko/aspose.slides.export/swfoptions/set_slideslayoutoptions/
---
## SwfOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) 메서드


프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 설정합니다 [ISlidesLayoutOptions](../../islideslayoutoptions/). 이 속성은 유형 [HandoutLayoutingOptions](../../handoutlayoutingoptions/)의 객체 할당을 지원하지 않습니다.

```cpp
void Aspose::Slides::Export::SwfOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value) override
```

## 비고


예시: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_CommentsPosition(CommentsPositions::Right);

System::SharedPtr<SwfOptions> options = System::MakeObject<SwfOptions>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.swf", SaveFormat::Swf, options);
```

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [ISlidesLayoutOptions](../../islideslayoutoptions/)
* 클래스 [SwfOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)