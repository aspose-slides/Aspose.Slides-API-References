---
title: set_AnimateTransitions()
second_title: Aspose.Slides для C++ справочник API
description: Устанавливает параметр анимации переходов. Записывает bool.
type: docs
weight: 14
url: /ru/aspose.slides.export/html5options/set_animatetransitions/
---
## Html5Options::set_AnimateTransitions(bool) метод


Устанавливает параметр анимации переходов. Записывает **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_AnimateTransitions(bool value) override
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