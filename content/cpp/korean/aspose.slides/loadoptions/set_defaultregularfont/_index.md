---
title: set_DefaultRegularFont()
second_title: Aspose.Slides for C++ API 참조
description: "소스 글꼴을 찾을 수 없을 경우 사용되는 일반 글꼴을 설정합니다. System::String을 씁니다."
type: docs
weight: 40
url: /ko/aspose.slides/loadoptions/set_defaultregularfont/
---
## LoadOptions::set_DefaultRegularFont(System::String) 메서드

원본 글꼴을 찾을 수 없을 때 사용되는 보통 글꼴을 설정합니다. [System::String](../../../system/string/)을 씁니다.

```cpp
void Aspose::Slides::LoadOptions::set_DefaultRegularFont(System::String value) override
```

## 비고

다음 예제는 PowerPoint [Presentation](../../presentation/) 렌더링을 위한 기본 글꼴 설정 방법을 보여 줍니다.

```cpp
// 로드 옵션을 사용하여 기본 일반 및 아시아 글꼴을 정의합니다
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// Load the presentation
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// Generate slide thumbnail
auto slide = pptx->get_Slides()->idx_get(0);
slide->GetThumbnail(1.0f, 1.0f)->Save(u"output_out.png", System::Drawing::Imaging::ImageFormat::get_Png());

// Generate PDF
pptx->Save(u"output_out.pdf", SaveFormat::Pdf);
// Generate XPS
pptx->Save(u"output_out.xps", SaveFormat::Xps);
```

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [LoadOptions](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)