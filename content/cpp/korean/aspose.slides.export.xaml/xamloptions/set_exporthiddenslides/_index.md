---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides for C++ API 참조
description: 숨겨진 슬라이드를 내보낼지 여부를 결정합니다.
type: docs
weight: 14
url: /ko/aspose.slides.export.xaml/xamloptions/set_exporthiddenslides/
---
## XamlOptions::set_ExportHiddenSlides(bool) 메서드

숨겨진 슬라이드가 내보내질지 여부를 결정합니다.

```cpp
void Aspose::Slides::Export::Xaml::XamlOptions::set_ExportHiddenSlides(bool value) override
```

## 비고

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```


## 참고

* 클래스 [XamlOptions](../)
* 네임스페이스 [Aspose::Slides::Export::Xaml](../../)
* 라이브러리 [Aspose.Slides](../../../)