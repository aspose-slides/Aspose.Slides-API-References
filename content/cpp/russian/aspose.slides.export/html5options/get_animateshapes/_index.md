---
title: get_AnimateShapes()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает параметр анимации фигур. Читает bool.
type: docs
weight: 27
url: /ru/aspose.slides.export/html5options/get_animateshapes/
---
## Html5Options::get_AnimateShapes() метод

Возвращает параметр анимации фигур. Читает **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateShapes() override
```

## Примечания

Пример: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```

## См. также

* Класс [Html5Options](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)