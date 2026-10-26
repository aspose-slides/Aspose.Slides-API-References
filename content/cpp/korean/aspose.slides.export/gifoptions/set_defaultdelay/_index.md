---
title: set_DefaultDelay()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "기본 지연 시간 [ms]을 설정합니다. 이 값은 ISlideShowTransition::set_AdvanceAfterTime() 메서드가 호출되지 않은 경우에 사용됩니다. 기본값은 1000입니다."
type: docs
weight: 92
url: /ko/aspose.slides.export/gifoptions/set_defaultdelay/
---
## GifOptions::set_DefaultDelay(int32_t) 메서드

기본 지연 시간 [ms]을 설정합니다. 이 값은 [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) 메서드가 호출되지 않은 경우에 사용됩니다. 기본값은 1000입니다.

```cpp
void Aspose::Slides::Export::GifOptions::set_DefaultDelay(int32_t value) override
```

## 비고

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## 참고

* 클래스 [GifOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)