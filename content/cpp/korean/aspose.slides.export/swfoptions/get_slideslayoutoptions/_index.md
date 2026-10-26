---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 ISlidesLayoutOptions로 가져옵니다. 이 속성은 HandoutLayoutingOptions 유형의 객체 할당을 지원하지 않습니다.
type: docs
weight: 391
url: /ko/aspose.slides.export/swfoptions/get_slideslayoutoptions/
---
## SwfOptions::get_SlidesLayoutOptions() 메서드


프레젠테이션을 내보낼 때 슬라이드가 페이지에 배치되는 모드를 가져옵니다 [ISlidesLayoutOptions](../../islideslayoutoptions/). 이 속성은 [HandoutLayoutingOptions](../../handoutlayoutingoptions/) 유형의 객체 할당을 지원하지 않습니다.

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::SwfOptions::get_SlidesLayoutOptions() override
```

## 비고


예제: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_CommentsPosition(CommentsPositions::Right);

System::SharedPtr<SwfOptions> options = System::MakeObject<SwfOptions>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.swf", SaveFormat::Swf, options);
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [ISlidesLayoutOptions](../../islideslayoutoptions/)
* 클래스 [SwfOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)