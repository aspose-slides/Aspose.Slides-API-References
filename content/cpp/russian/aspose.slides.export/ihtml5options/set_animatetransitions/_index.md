---
title: set_AnimateTransitions()
second_title: Aspose.Slides для C++ справочник API
description: Устанавливает параметр анимации переходов. Записывает bool.
type: docs
weight: 14
url: /ru/aspose.slides.export/ihtml5options/set_animatetransitions/
---
## IHtml5Options::set_AnimateTransitions(bool) метод


Устанавливает опцию анимации переходов. Записывает **bool**.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_AnimateTransitions(bool value)=0
```

## Примечания


Пример: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-transitions.html", SaveFormat::Html5, options);
```




## См. также

* Класс [IHtml5Options](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)