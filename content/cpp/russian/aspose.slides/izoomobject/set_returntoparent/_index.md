---
title: set_ReturnToParent()
second_title: Aspose.Slides для C++ API справка
description: "Устанавливает поведение навигации в слайд-шоу. Запишите bool. Значение по умолчанию: false"
type: docs
weight: 40
url: /ru/aspose.slides/izoomobject/set_returntoparent/
---
## IZoomObject::set_ReturnToParent(bool) метод


Устанавливает поведение навигации в слайд-шоу. Запишите **bool**. Значение по умолчанию: false

```cpp
virtual void Aspose::Slides::IZoomObject::set_ReturnToParent(bool value)=0
```

## Примечания


Значение true свойства определяет поведение возврата к родительскому элементу в слайд-шоу. 

Пример: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Смотрите также

* Класс [IZoomObject](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)