---
title: set_TransitionFps()
second_title: Справка API Aspose.Slides для C++
description: Устанавливает FPS перехода [frames/sec]. Значение по умолчанию — 25.
type: docs
weight: 66
url: /ru/aspose.slides.export/gifoptions/set_transitionfps/
---
## GifOptions::set_TransitionFps(int32_t) метод


Устанавливает FPS перехода [frames/sec]. Значение по умолчанию — 25.

```cpp
void Aspose::Slides::Export::GifOptions::set_TransitionFps(int32_t value) override
```

## Примечания



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## См. также

* Класс [GifOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)