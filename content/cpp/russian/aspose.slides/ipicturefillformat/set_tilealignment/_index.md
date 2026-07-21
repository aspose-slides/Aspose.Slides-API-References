---
title: set_TileAlignment()
second_title: Aspose.Slides для C++ справочник API
description: Устанавливает, как текстура выравнивается внутри фигуры. Эта настройка контролирует начальную точку шаблона текстуры и то, как она повторяется по всей фигуре. Укажите RectangleAlignment.
type: docs
weight: 391
url: /ru/aspose.slides/ipicturefillformat/set_tilealignment/
---
## IPictureFillFormat::set_TileAlignment(RectangleAlignment) метод

Устанавливает, как текстура выравнивается внутри формы. Эта настройка контролирует начальную точку шаблона текстуры и то, как она повторяется по всей форме. Запишите [RectangleAlignment](../../rectanglealignment/).

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileAlignment(RectangleAlignment value)=0
```

## Примечания

По умолчанию [RectangleAlignment::TopLeft](../../rectanglealignment/). 

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Получает формат заливки изображения формы
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Устанавливает режим заливки изображения в Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Устанавливает выравнивание плитки в правый нижний угол
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## См. также

* Перечисление [RectangleAlignment](../../rectanglealignment/)
* Класс [IPictureFillFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)