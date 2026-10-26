---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides for C++ API 참조
description: 숨겨진 슬라이드가 내보내질지 여부를 결정합니다.
type: docs
weight: 1
url: /ko/aspose.slides.export.xaml/xamloptions/get_exporthiddenslides/
---
## XamlOptions::get_ExportHiddenSlides() 메서드

숨겨진 슬라이드가 내보내질지 여부를 결정합니다.

```cpp
bool Aspose::Slides::Export::Xaml::XamlOptions::get_ExportHiddenSlides() override
```

## 비고



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## 참조

* 클래스 [XamlOptions](../)
* 네임스페이스 [Aspose::Slides::Export::Xaml](../../)
* 라이브러리 [Aspose.Slides](../../../)