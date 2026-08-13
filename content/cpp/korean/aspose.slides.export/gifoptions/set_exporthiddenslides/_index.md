---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 숨겨진 슬라이드가 내보내지는지 여부를 결정합니다. 기본값은 false입니다.
type: docs
weight: 40
url: /ko/aspose.slides.export/gifoptions/set_exporthiddenslides/
---
## GifOptions::set_ExportHiddenSlides(bool) 메서드


숨겨진 슬라이드가 내보내지는지 여부를 결정합니다. 기본값은 false입니다.

```cpp
void Aspose::Slides::Export::GifOptions::set_ExportHiddenSlides(bool value) override
```

## 비고



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## 참조

* 클래스 [GifOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)