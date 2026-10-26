---
title: set_DefaultDelay()
second_title: Aspose.Slides для C++ API Reference
description: "Устанавливает время задержки по умолчанию [ms]. Это значение будет использовано, если метод ISlideShowTransition::set_AdvanceAfterTime() не был вызван. Значение по умолчанию — 1000."
type: docs
weight: 92
url: /ru/aspose.slides.export/igifoptions/set_defaultdelay/
---
## IGifOptions::set_DefaultDelay(int32_t) метод

Устанавливает время задержки по умолчанию [мс]. Это значение будет использовано, если метод [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) не был вызван. Значение по умолчанию равно 1000.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_DefaultDelay(int32_t value)=0
```

## Примечания


```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_DefaultDelay(2000);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```



## См. также

* Класс [IGifOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)