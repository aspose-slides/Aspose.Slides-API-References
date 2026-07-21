---
title: get_ReturnToParent()
second_title: Справочник API Aspose.Slides для C++
description: "Получает поведение навигации в слайд-шоу. Читает bool. Значение по умолчанию: false"
type: docs
weight: 27
url: /ru/aspose.slides/izoomobject/get_returntoparent/
---
## IZoomObject::get_ReturnToParent() метод

Получает поведение навигации в слайд-шоу. Читает **bool**. Значение по умолчанию: false

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ReturnToParent()=0
```

## Примечания

Значение true свойства указывает поведение возврата к родителю в слайд-шоу.

Пример:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## См. также

* Класс [IZoomObject](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)