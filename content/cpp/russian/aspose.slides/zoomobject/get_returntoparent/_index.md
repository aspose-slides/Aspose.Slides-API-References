---
title: get_ReturnToParent()
second_title: Aspose.Slides для справочника API C++
description: "Получает поведение навигации в слайд-шоу. Читается bool. Значение по умолчанию: false"
type: docs
weight: 27
url: /ru/aspose.slides/zoomobject/get_returntoparent/
---
## ZoomObject::get_ReturnToParent() метод

Получает поведение навигации в слайд-шоу. Читается **bool**. Значение по умолчанию: false

```cpp
bool Aspose::Slides::ZoomObject::get_ReturnToParent() override
```

## Примечания

Истинное значение свойства указывает поведение возврата к родителю в навигации слайд-шоу. 

Пример: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## См. также

* Класс [ZoomObject](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)