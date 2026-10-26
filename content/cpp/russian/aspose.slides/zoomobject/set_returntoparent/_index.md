---
title: set_ReturnToParent()
second_title: Aspose.Slides для C++ справка по API
description: "Устанавливает поведение навигации в слайд-шоу. Записать bool. Значение по умолчанию: false"
type: docs
weight: 40
url: /ru/aspose.slides/zoomobject/set_returntoparent/
---
## ZoomObject::set_ReturnToParent(bool) метод


Устанавливает поведение навигации в слайд-шоу. Записать **bool**. Значение по умолчанию: false

```cpp
void Aspose::Slides::ZoomObject::set_ReturnToParent(bool value) override
```

## Примечания


Значение true свойства указывает поведение навигации возврата к родительскому элементу в слайд-шоу. 

Пример: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## См. также

* Класс [ZoomObject](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)