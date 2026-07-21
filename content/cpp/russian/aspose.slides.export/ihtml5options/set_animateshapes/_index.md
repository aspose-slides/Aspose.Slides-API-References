---
title: set_AnimateShapes()
second_title: Aspose.Slides для C++ справочник API
description: Устанавливает опцию анимации фигур. Записывает bool.
type: docs
weight: 40
url: /ru/aspose.slides.export/ihtml5options/set_animateshapes/
---
## IHtml5Options::set_AnimateShapes(bool) метод


Устанавливает опцию анимации фигур. Записывает **bool**.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_AnimateShapes(bool value)=0
```

## Примечания


Пример: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```




## Смотрите также

* Класс [IHtml5Options](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)