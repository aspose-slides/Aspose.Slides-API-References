---
title: get_Masters()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 프레젠테이션에 정의된 모든 마스터 슬라이드의 목록을 반환합니다. 읽기 전용 IMasterSlideCollection.
type: docs
weight: 118
url: /ko/aspose.slides/presentation/get_masters/
---
## Presentation::get_Masters() 메서드

프레젠테이션에 정의된 모든 마스터 슬라이드의 목록을 반환합니다. 읽기 전용 [IMasterSlideCollection](../../imasterslidecollection/).

```cpp
System::SharedPtr<IMasterSlideCollection> Aspose::Slides::Presentation::get_Masters() override
```

## 비고

다음 예제는 PowerPoint [Presentation](../)의 마스터 [Slides](../../)에 [Images](../../images/)를 추가하는 방법을 보여줍니다.
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto masterSlide = slide->get_LayoutSlide()->get_MasterSlide();

auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
masterSlide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
다음 예제는 PowerPoint [Presentation](../)의 마스터 슬라이드 배경 색을 변경하는 방법을 보여줍니다.
```cpp
// 프레젠테이션 파일을 나타내는 Presentation 클래스를 인스턴스화합니다
auto pres = System::MakeObject<Presentation>();

// 마스터 ISlide의 배경 색을 포레스트 그린으로 설정합니다
auto masterSlide = pres->get_Masters()->idx_get(0);
auto background = masterSlide->get_Background();
background->set_Type(BackgroundType::OwnBackground);
background->get_FillFormat()->set_FillType(FillType::Solid);
background->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
// 프레젠테이션을 디스크에 저장합니다
pres->Save(u"SetSlideBackgroundMaster_out.pptx", SaveFormat::Pptx);
```
다음 예제는 PowerPoint [Presentation](../)에 슬라이드 레이아웃을 추가하는 방법을 보여줍니다.
```cpp
// 프레젠테이션 파일을 나타내는 Presentation 클래스를 인스턴스화합니다
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// 레이아웃 슬라이드 유형으로 검색 시도
auto layoutSlides = presentation->get_Masters()->idx_get(0)->get_LayoutSlides();
auto layoutSlide = System::ObjectExt::Coalesce(
    layoutSlides->GetByType(SlideLayoutType::TitleAndObject),
    [&](){ return layoutSlides->GetByType(SlideLayoutType::Title); });

if (layoutSlide == nullptr)
{
    // 프레젠테이션에 특정 유형의 레이아웃이 포함되지 않은 경우.
    // 프레젠테이션 파일은 Blank와 Custom 레이아웃 유형만 포함합니다.
    // 하지만 Custom 유형의 레이아웃 슬라이드는 서로 다른 슬라이드 이름을 가집니다,
    // 예: "Title", "Title and Content" 등. 이러한 이름을 레이아웃 슬라이드 선택에 사용할 수 있습니다.
    // 또한 자리표시자 형태 유형 집합을 사용할 수 있습니다. 예를 들어,
    // Title 슬라이드는 Title 자리표시자 유형만 가져야 합니다 등.
    for (auto&& titleAndObjectLayoutSlide : layoutSlides)
    {
        if (titleAndObjectLayoutSlide->get_Name() == u"Title and Object")
        {
            layoutSlide = titleAndObjectLayoutSlide;
            break;
        }
    }

    if (layoutSlide == nullptr)
    {
        for (auto&& titleLayoutSlide : layoutSlides)
        {
            if (titleLayoutSlide->get_Name() == u"Title")
            {
                layoutSlide = titleLayoutSlide;
                break;
            }
        }

        if (layoutSlide == nullptr)
        {
            layoutSlide = layoutSlides->GetByType(SlideLayoutType::Blank);
            if (layoutSlide == nullptr)
            {
                layoutSlide = layoutSlides->Add(SlideLayoutType::TitleAndObject, u"Title and Object");
            }
        }
    }
}

// 추가된 레이아웃 슬라이드를 사용하여 빈 슬라이드 삽입
presentation->get_Slides()->InsertEmptySlide(0, layoutSlide);
// 프레젠테이션 저장
presentation->Save(u"AddLayoutSlides_out.pptx", SaveFormat::Pptx);
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMasterSlideCollection](../../imasterslidecollection/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)