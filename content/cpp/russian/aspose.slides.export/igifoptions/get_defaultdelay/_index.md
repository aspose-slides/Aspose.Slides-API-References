---
title: get_DefaultDelay()
second_title: Aspose.Slides для C++ справочник API
description: "Получает время задержки по умолчанию [ms]. Это значение будет использоваться, если метод ISlideShowTransition::set_AdvanceAfterTime() не был вызван. Значение по умолчанию равно 1000."
type: docs
weight: 79
url: /ru/aspose.slides.export/igifoptions/get_defaultdelay/
---
## IGifOptions::get_DefaultDelay() method


Получает время задержки по умолчанию [ms]. Это значение будет использоваться, если метод [ISlideShowTransition::set_AdvanceAfterTime()](../../../aspose.slides/islideshowtransition/set_advanceaftertime/) не был вызван. Значение по умолчанию равно 1000.

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_DefaultDelay()=0
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
* Пространство имен [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)