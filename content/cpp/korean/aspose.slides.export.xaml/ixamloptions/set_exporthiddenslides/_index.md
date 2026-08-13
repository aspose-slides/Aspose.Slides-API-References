---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides for C++ API 참조
description: 숨겨진 슬라이드가 내보내어질지 여부를 결정합니다.
type: docs
weight: 14
url: /ko/aspose.slides.export.xaml/ixamloptions/set_exporthiddenslides/
---
## IXamlOptions::set_ExportHiddenSlides(bool) 메서드


숨겨진 슬라이드가 내보내어질지 여부를 결정합니다.

```cpp
virtual void Aspose::Slides::Export::Xaml::IXamlOptions::set_ExportHiddenSlides(bool value)=0
```

## 비고



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## 참조

* 클래스 [IXamlOptions](../)
* 네임스페이스 [Aspose::Slides::Export::Xaml](../../)
* 라이브러리 [Aspose.Slides](../../../)