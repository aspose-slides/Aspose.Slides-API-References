---
title: get_SlideSize()
second_title: Aspose.Slides C++ API 참조
description: 슬라이드 크기 객체를 반환합니다. 읽기 전용 ISlideSize.
type: docs
weight: 79
url: /ko/aspose.slides/presentation/get_slidesize/
---
## Presentation::get_SlideSize() 메서드


슬라이드 크기 객체를 반환합니다. 읽기 전용 [ISlideSize](../../islidesize/).

```cpp
System::SharedPtr<ISlideSize> Aspose::Slides::Presentation::get_SlideSize() override
```

## 비고


다음 예제는 PowerPoint [Presentation](../)에서 슬라이드 크기를 변경하는 방법을 보여줍니다. 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres-4x3-aspect-ratio.pptx");

pres->get_SlideSize()->SetSize(SlideSizeType::OnScreen16x9, SlideSizeScaleType::DoNotScale);
pres->Save(u"pres-4x3-aspect-ratio.pptx", SaveFormat::Pptx);
```
 다음 예제는 PowerPoint [Presentation](../)에 대한 콘텐츠 스케일링을 고려하여 슬라이드 크기를 설정하는 방법을 보여줍니다. 
```cpp
// 프레젠테이션 파일을 나타내는 Presentation 객체를 인스턴스화합니다
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto auxPresentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);

// 생성된 프레젠테이션의 슬라이드 크기를 원본과 동일하게 설정합니다
presentation->get_SlideSize()->SetSize(540.0f, 720.0f, SlideSizeScaleType::EnsureFit);

// SetSize 메서드는 콘텐츠를 스케일링하여 맞춤을 보장하면서 슬라이드 크기를 설정하는 데 사용됩니다
presentation->get_SlideSize()->SetSize(SlideSizeType::A4Paper, SlideSizeScaleType::Maximize);

// SetSize 메서드는 콘텐츠 크기를 최대화하면서 슬라이드 크기를 설정하는 데 사용됩니다
// 프레젠테이션을 디스크에 저장합니다
auxPresentation->Save(u"Set_Size_Type_out.pptx", SaveFormat::Pptx);
```
 다음 예제는 PowerPoint [Presentation](../)에서 사용자 정의 슬라이드 크기를 지정하는 방법을 보여줍니다. 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
pres->get_SlideSize()->SetSize(780.0f, 540.0f, SlideSizeScaleType::DoNotScale);

// A4 용지 크기
pres->Save(u"pres-a4-slide-size.pptx", SaveFormat::Pptx);
```

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [ISlideSize](../../islidesize/)
* 클래스 [Presentation](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)