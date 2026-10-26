---
title: set_TransitionFps()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 전환 FPS [frames/sec]를 설정합니다. 기본값은 25입니다.
type: docs
weight: 66
url: /ko/aspose.slides.export/gifoptions/set_transitionfps/
---
## GifOptions::set_TransitionFps(int32_t) 메서드


전환 FPS [frames/sec]를 설정합니다. 기본값은 25입니다.

```cpp
void Aspose::Slides::Export::GifOptions::set_TransitionFps(int32_t value) override
```

## 비고



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## 관련 항목

* 클래스 [GifOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)