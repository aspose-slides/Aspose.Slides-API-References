---
title: get_DefaultDelay()
second_title: Справочник API Aspose.Slides для C++
description: "Получает значение задержки по умолчанию [мс]. Это значение будет использовано, если метод ISlideShowTransition::set_AdvanceAfterTime() не был вызван. Значение по умолчанию равно 1000."
type: docs
weight: 79
url: /ru/aspose.slides.export/gifoptions/get_defaultdelay/
---
## GifOptions::get_DefaultDelay() метод


Получает значение задержки по умолчанию [мс]. Это значение будет использовано, если метод [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) не был вызван. Значение по умолчанию равно 1000.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_DefaultDelay() override
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