---
title: get_DisableFontLigatures()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 텍스트가 리가처를 사용하지 않고 렌더링되는지 여부를 나타내는 값을 가져옵니다. true 로 설정하면 렌더링된 출력에서 리가처가 비활성화됩니다. 기본적으로 이 속성은 false 로 설정됩니다.
type: docs
weight: 40
url: /ko/aspose.slides.export/irenderingoptions/get_disablefontligatures/
---
## IRenderingOptions::get_DisableFontLigatures() 메서드


텍스트가 리가처를 사용하지 않고 렌더링되는지 여부를 나타내는 값을 가져옵니다. **true** 로 설정하면 렌더링된 출력에서 리가처가 비활성화됩니다. 기본적으로 이 속성은 **false** 로 설정되어 있습니다.

```cpp
virtual bool Aspose::Slides::Export::IRenderingOptions::get_DisableFontLigatures()=0
```

## 비고


예시: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // 텍스트 렌더링에서 리가처를 비활성화합니다

System::ArrayPtr<System::SharedPtr<IImage>> renderedSlides = pres->GetImages(options);
for (int32_t index = 0; index < renderedSlides->get_Length(); index++)
{
    auto slideImage = renderedSlides[index];
    slideImage->Save(System::String::Format(u"slide-{0}.png", index));
}
```

## 참고

* 클래스 [IRenderingOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)