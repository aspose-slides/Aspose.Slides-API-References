---
title: set_SlideShowType()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "슬라이드 쇼 유형을 설정합니다. 다음 SlideShowType 조상: BrowsedAtKiosk, PresentedBySpeaker 및 BrowsedByIndividual"
type: docs
weight: 14
url: /ko/aspose.slides/slideshowsettings/set_slideshowtype/
---
## SlideShowSettings::set_SlideShowType(System::SharedPtr\<Aspose::Slides::SlideShowType\>) 메서드

슬라이드 쇼 유형을 설정합니다. 다음 [SlideShowType](../../slideshowtype/) 조상: [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) 및 [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
void Aspose::Slides::SlideShowSettings::set_SlideShowType(System::SharedPtr<Aspose::Slides::SlideShowType> value)
```

## 비고

```cpp
auto pres = System::MakeObject<Presentation>();

// "Browsed at a kiosk (full screen)" 유형을 설정합니다
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// "Browsed by individual (window)" 유형을 설정합니다
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// "Presented by a speaker (full screen)" 유형을 설정합니다
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## 또한 보기

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [SlideShowType](../../slideshowtype/)
* 클래스 [SlideShowSettings](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)