---
title: get_TransitionFps()
second_title: Aspose.Slides для C++ справочник API
description: Получает FPS перехода [frames/sec]. Значение по умолчанию — 25.
type: docs
weight: 53
url: /ru/aspose.slides.export/gifoptions/get_transitionfps/
---
## GifOptions::get_TransitionFps() метод


Получает количество кадров перехода FPS [frames/sec] Значение по умолчанию — 25.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_TransitionFps() override
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