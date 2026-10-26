---
title: get_Sections()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 프레젠테이션에 정의된 모든 슬라이드 섹션의 목록을 반환합니다. 읽기 전용 ISectionCollection.
type: docs
weight: 66
url: /ko/aspose.slides/presentation/get_sections/
---
## Presentation::get_Sections() 메서드

프레젠테이션에 정의된 모든 슬라이드 섹션의 목록을 반환합니다. 읽기 전용 [ISectionCollection](../../isectioncollection/).

```cpp
System::SharedPtr<ISectionCollection> Aspose::Slides::Presentation::get_Sections() override
```

## 비고

다음 예제는 PowerPoint [Presentation](../)에서 섹션을 만드는 방법을 보여줍니다.  
```cpp
auto pres = System::MakeObject<Presentation>();

auto defaultSlide = pres->get_Slides()->idx_get(0);
auto layoutSlide = pres->get_LayoutSlides()->idx_get(0);
auto newSlide1 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide2 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide3 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide4 = pres->get_Slides()->AddEmptySlide(layoutSlide);

System::SharedPtr<ISection> section1 = pres->get_Sections()->AddSection(u"Section 1", newSlide1);
// section1은 newSlide2에서 종료되고 그 뒤에 section2가 시작됩니다.
System::SharedPtr<ISection> section2 = pres->get_Sections()->AddSection(u"Section 2", newSlide3);

pres->Save(u"pres-sections.pptx", SaveFormat::Pptx);
pres->get_Sections()->ReorderSectionWithSlides(section2, 0);
pres->Save(u"pres-sections-moved.pptx", SaveFormat::Pptx);
pres->get_Sections()->RemoveSectionWithSlides(section2);
pres->get_Sections()->AppendEmptySection(u"Last empty section");
pres->Save(u"pres-section-with-empty.pptx", SaveFormat::Pptx);
```
다음 예제는 섹션 이름을 변경하는 방법을 보여줍니다.  
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<ISection> section = pres->get_Sections()->idx_get(0);
section->set_Name(u"My section");
```

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [ISectionCollection](../../isectioncollection/)
* 클래스 [Presentation](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)