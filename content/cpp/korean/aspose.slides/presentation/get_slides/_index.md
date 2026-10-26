---
title: get_Slides()
second_title: Aspose.Slides for C++ API 참조
description: 프레젠테이션에 정의된 모든 슬라이드의 목록을 반환합니다. 읽기 전용 ISlideCollection.
type: docs
weight: 53
url: /ko/aspose.slides/presentation/get_slides/
---
## Presentation::get_Slides() 메서드

프레젠테이션에 정의된 모든 슬라이드의 목록을 반환합니다. 읽기 전용 [ISlideCollection](../../islidecollection/).

```cpp
System::SharedPtr<ISlideCollection> Aspose::Slides::Presentation::get_Slides() override
```

## 비고

다음 예시는 PowerPoint [Presentation](../)의 슬라이드 배경 색을 설정하는 방법을 보여줍니다. 
```cpp
// 프레젠테이션 파일을 나타내는 Presentation 클래스를 인스턴스화합니다
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Set the background color of the first ISlide to Blue
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Solid);
slide->get_Background()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Blue());
pres->Save(u"ContentBG_out.pptx", SaveFormat::Pptx);
```
다음 예시는 PowerPoint [Presentation](../)의 슬라이드 배경 이미지를 설정하는 방법을 보여줍니다. 
```cpp
// 프레젠테이션 파일을 나타내는 Presentation 클래스를 인스턴스화합니다
auto pres = System::MakeObject<Presentation>(u"SetImageAsBackground.pptx");
auto slide = pres->get_Slides()->idx_get(0);

// 이미지로 배경을 설정합니다
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Picture);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);
// 그림을 설정합니다
auto img = System::ExplicitCast<System::Drawing::Image>(System::MakeObject<System::Drawing::Bitmap>(dataDir + u"Tulips.jpg"));
// 프레젠테이션의 이미지 컬렉션에 이미지를 추가합니다
auto imgx = pres->get_Images()->AddImage(img);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(imgx);
// 프레젠테이션을 디스크에 저장합니다
pres->Save(u"ContentBG_Img_out.pptx", SaveFormat::Pptx);
```
다음 예시는 슬라이드 전환을 추가하는 방법을 보여줍니다 [Presentation](../). 
```cpp
// 소스 프레젠테이션 파일을 로드하기 위해 Presentation 클래스를 인스턴스화합니다
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// 슬라이드 1에 원형 전환을 적용합니다
presentation->get_Slides()->idx_get(0)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// 슬라이드 2에 콤 전환을 적용합니다
presentation->get_Slides()->idx_get(1)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// 프레젠테이션을 디스크에 저장합니다
presentation->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```
다음 예시는 고급 슬라이드 전환을 추가하는 방법을 보여줍니다. 
```cpp
// 프레젠테이션 파일을 나타내는 Presentation 클래스를 인스턴스화합니다
auto pres = System::MakeObject<Presentation>(u"BetterSlideTransitions.pptx");

auto slide1 = pres->get_Slides()->idx_get(0);
auto slide2 = pres->get_Slides()->idx_get(1);
auto slide3 = pres->get_Slides()->idx_get(2);

// 슬라이드 1에 원형 전환을 적용합니다
slide1->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// 전환 시간을 3초로 설정합니다
slide1->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide1->get_SlideShowTransition()->set_AdvanceAfterTime(3000);
// 슬라이드 2에 콤 전환을 적용합니다
slide2->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// 전환 시간을 5초로 설정합니다
slide2->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide2->get_SlideShowTransition()->set_AdvanceAfterTime(5000);
// 슬라이드 3에 확대 전환을 적용합니다
slide3->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Zoom);
// 전환 시간을 7초로 설정합니다
slide3->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide3->get_SlideShowTransition()->set_AdvanceAfterTime(7000);
// 프레젠테이션을 디스크에 저장합니다
pres->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [ISlideCollection](../../islidecollection/)
* 클래스 [Presentation](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)