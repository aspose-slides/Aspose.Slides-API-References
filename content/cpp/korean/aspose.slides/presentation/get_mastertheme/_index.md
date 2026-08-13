---
title: get_MasterTheme()
second_title: Aspose.Slides for C++ API 참조
description: "마스터 테마를 반환합니다. 읽기 전용 Theme::IMasterTheme."
type: docs
weight: 404
url: /ko/aspose.slides/presentation/get_mastertheme/
---
## Presentation::get_MasterTheme() 메서드

마스터 테마를 반환합니다. 읽기 전용 [Theme::IMasterTheme](../../../aspose.slides.theme/imastertheme/).

```cpp
System::SharedPtr<Theme::IMasterTheme> Aspose::Slides::Presentation::get_MasterTheme() override
```

## 비고

다음 예제는 PowerPoint [Presentation](../) 요소의 일부를 변경하여 테마 효과를 변경하는 방법을 보여줍니다.
```cpp
// 프레젠테이션 파일을 나타내는 프레젠테이션 객체를 인스턴스화합니다
auto pres = System::MakeObject<Presentation>(u"Subtle_Moderate_Intense.pptx");
auto masterTheme = pres->get_MasterTheme();
auto formatScheme = masterTheme->get_FormatScheme();

formatScheme->get_LineStyles()->idx_get(0)->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
formatScheme->get_FillStyles()->idx_get(2)->set_FillType(FillType::Solid);
formatScheme->get_FillStyles()->idx_get(2)->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
formatScheme->get_EffectStyles()->idx_get(2)->get_EffectFormat()->get_OuterShadowEffect()->set_Distance(10.0f);
pres->Save(u"Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat::Pptx);
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMasterTheme](../../../aspose.slides.theme/imastertheme/)
* 클래스 [Presentation](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)