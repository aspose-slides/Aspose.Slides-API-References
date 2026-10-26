---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 숨겨진 슬라이드가 내보내질지 여부를 결정합니다. 기본값은 false입니다.
type: docs
weight: 27
url: /ko/aspose.slides.export/igifoptions/get_exporthiddenslides/
---
## IGifOptions::get_ExportHiddenSlides() 메서드


숨겨진 슬라이드가 내보내질지 여부를 결정합니다. 기본값은 false입니다.

```cpp
virtual bool Aspose::Slides::Export::IGifOptions::get_ExportHiddenSlides()=0
```

## 비고



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## 참고

* 클래스 [IGifOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)