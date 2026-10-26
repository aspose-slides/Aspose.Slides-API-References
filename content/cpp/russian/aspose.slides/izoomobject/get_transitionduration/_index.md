---
title: get_TransitionDuration()
second_title: Справочник API Aspose.Slides для C++
description: "Получает продолжительность перехода между Zoom и слайдом. Читает float. Значение по умолчанию: 1.0f"
type: docs
weight: 105
url: /ru/aspose.slides/izoomobject/get_transitionduration/
---
## IZoomObject::get_TransitionDuration() метод


Получает продолжительность перехода между Zoom и слайдом. Читает **float**. Значение по умолчанию: 1.0f

```cpp
virtual float Aspose::Slides::IZoomObject::get_TransitionDuration()=0
```

## Примечания


Если не указано (TransitionDur = 0), будет использовать переход целевого слайда и тайминги, связанные с этим переходом. 

пример демонстрирует изменение продолжительности перехода между Zoom и слайдом: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## См. также

* Класс [IZoomObject](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)