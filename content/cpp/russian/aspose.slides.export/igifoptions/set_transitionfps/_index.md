---
title: set_TransitionFps()
second_title: Aspose.Slides для справки по API C++
description: Устанавливает переход FPS [frames/sec] Значение по умолчанию — 25.
type: docs
weight: 66
url: /ru/aspose.slides.export/igifoptions/set_transitionfps/
---
## IGifOptions::set_TransitionFps(int32_t) метод

Устанавливает переход FPS [frames/sec]. Значение по умолчанию — 25.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_TransitionFps(int32_t value)=0
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