---
title: get_TransitionFps()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 전환 FPS [frames/sec]를 가져옵니다. 기본값은 25입니다.
type: docs
weight: 53
url: /ko/aspose.slides.export/gifoptions/get_transitionfps/
---
## GifOptions::get_TransitionFps() 메서드


전환 FPS [frames/sec]를 가져옵니다. 기본값은 25입니다.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_TransitionFps() override
```

## 비고



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## 관련 보기

* 클래스 [GifOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)