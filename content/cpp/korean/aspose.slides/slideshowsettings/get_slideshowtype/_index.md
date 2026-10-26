---
title: get_SlideShowType()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "슬라이드 쇼 유형을 가져옵니다. 다음 SlideShowType 조상: BrowsedAtKiosk, PresentedBySpeaker 및 BrowsedByIndividual에 의해 표시됩니다."
type: docs
weight: 1
url: /ko/aspose.slides/slideshowsettings/get_slideshowtype/
---
## SlideShowSettings::get_SlideShowType() 메서드

슬라이드 쇼 유형을 가져옵니다. 다음 [SlideShowType](../../slideshowtype/) 조상: [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) 및 [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
System::SharedPtr<Aspose::Slides::SlideShowType> Aspose::Slides::SlideShowSettings::get_SlideShowType()
```

## 비고

```cpp
auto pres = System::MakeObject<Presentation>();

// "Browsed at a kiosk (full screen)" 유형을 설정
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// "Browsed by individual (window)" 유형을 설정
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// "Presented by a speaker (full screen)" 유형을 설정
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [SlideShowType](../../slideshowtype/)
* 클래스 [SlideShowSettings](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)