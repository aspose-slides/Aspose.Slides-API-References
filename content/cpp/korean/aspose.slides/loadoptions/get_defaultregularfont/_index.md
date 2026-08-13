---
title: get_DefaultRegularFont()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "소스 글꼴을 찾을 수 없는 경우 사용되는 Regular 글꼴을 반환합니다. System::String을 읽으십시오."
type: docs
weight: 27
url: /ko/aspose.slides/loadoptions/get_defaultregularfont/
---
## LoadOptions::get_DefaultRegularFont() 메서드

소스 글꼴을 찾을 수 없는 경우 사용되는 Regular 글꼴을 반환합니다. [System::String](../../../system/string/) 를 읽으십시오.

```cpp
System::String Aspose::Slides::LoadOptions::get_DefaultRegularFont() override
```

## 비고

다음 예제는 PowerPoint [Presentation](../../presentation/) 렌더링을 위한 기본 글꼴을 설정하는 방법을 보여줍니다.
```cpp
// 로드 옵션을 사용하여 기본 일반 및 아시아 글꼴을 정의합니다.
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// 프레젠테이션을 로드합니다.
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// 슬라이드 썸네일을 생성합니다.
auto slide = pptx->get_Slides()->idx_get(0);
slide->GetThumbnail(1.0f, 1.0f)->Save(u"output_out.png", System::Drawing::Imaging::ImageFormat::get_Png());

// PDF를 생성합니다.
pptx->Save(u"output_out.pdf", SaveFormat::Pdf);
// XPS를 생성합니다.
pptx->Save(u"output_out.xps", SaveFormat::Xps);
```

## 관련 항목

* 클래스 [String](../../../system/string/)
* 클래스 [LoadOptions](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)