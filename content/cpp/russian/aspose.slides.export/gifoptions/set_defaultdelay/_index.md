---
title: set_DefaultDelay()
second_title: Aspose.Slides для C++ справочник API
description: "Устанавливает время задержки по умолчанию [мс]. Это значение будет использовано, если метод ISlideShowTransition::set_AdvanceAfterTime() не был вызван. Значение по умолчанию — 1000."
type: docs
weight: 92
url: /ru/aspose.slides.export/gifoptions/set_defaultdelay/
---
## GifOptions::set_DefaultDelay(int32_t) метод

Устанавливает время задержки по умолчанию [мс]. Это значение будет использовано, если метод [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) не был вызван. Значение по умолчанию — 1000.

```cpp
void Aspose::Slides::Export::GifOptions::set_DefaultDelay(int32_t value) override
```
## Примечания

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```
## См. также

* Класс [GifOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)