---
title: get_TransitionFps()
second_title: Aspose.Slides для справочника API C++
description: Получает FPS перехода [frames/sec]. Значение по умолчанию — 25.
type: docs
weight: 53
url: /ru/aspose.slides.export/igifoptions/get_transitionfps/
---
## IGifOptions::get_TransitionFps() метод


Получает FPS перехода [frames/sec]. Значение по умолчанию — 25.

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_TransitionFps()=0
```

## Примечания



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## См. также

* Класс [IGifOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)