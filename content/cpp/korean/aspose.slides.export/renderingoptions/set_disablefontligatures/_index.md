---
title: set_DisableFontLigatures()
second_title: Aspose.Slides for C++ API 참조
description: 텍스트가 리가처를 사용하지 않고 렌더링되는지 여부를 나타내는 값을 설정합니다. true로 설정하면 렌더링된 출력에서 리가처가 비활성화됩니다. 기본적으로 이 속성은 false로 설정됩니다.
type: docs
weight: 53
url: /ko/aspose.slides.export/renderingoptions/set_disablefontligatures/
---
## RenderingOptions::set_DisableFontLigatures(bool) 메서드

텍스트가 리가처를 사용하지 않고 렌더링되는지 여부를 나타내는 값을 설정합니다. **true**로 설정하면 렌더링된 출력에서 리가처가 비활성화됩니다. 기본적으로 이 속성은 **false**로 설정됩니다.

```cpp
void Aspose::Slides::Export::RenderingOptions::set_DisableFontLigatures(bool value) override
```

## 비고

예:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // 텍스트 렌더링에서 리가처 비활성화

System::ArrayPtr<System::SharedPtr<IImage>> renderedSlides = pres->GetImages(options);
for (int32_t index = 0; index < renderedSlides->get_Length(); index++)
{
    auto slideImage = renderedSlides[index];
    slideImage->Save(System::String::Format(u"slide-{0}.png", index));
}
```

## 참고

* 클래스 [RenderingOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)