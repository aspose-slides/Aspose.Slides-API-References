---
title: get_AnimateTransitions()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает параметр анимации переходов. Читает bool.
type: docs
weight: 1
url: /ru/aspose.slides.export/html5options/get_animatetransitions/
---
## Html5Options::get_AnimateTransitions() метод


Возвращает параметр анимации переходов. Читает **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateTransitions() override
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

* Класс [Html5Options](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)