---
title: get_TileAlignment()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает, как текстура выравнивается внутри фигуры. Эта настройка определяет начальную точку шаблона текстуры и то, как она повторяется по фигуре. См. RectangleAlignment.
type: docs
weight: 378
url: /ru/aspose.slides/picturefillformat/get_tilealignment/
---
## PictureFillFormat::get_TileAlignment() метод


Возвращает, как текстура выравнивается внутри фигуры. Эта настройка определяет начальную точку шаблона текстуры и то, как она повторяется по фигуре. См. [RectangleAlignment](../../rectanglealignment/).

```cpp
RectangleAlignment Aspose::Slides::PictureFillFormat::get_TileAlignment() override
```

## Примечания


По умолчанию [RectangleAlignment::TopLeft](../../rectanglealignment/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Получает формат заливки картинкой фигуры
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Устанавливает режим заливки картинки в Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Устанавливает выравнивание тайлинга в BottomRight
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Смотрите также

* Перечисление [RectangleAlignment](../../rectanglealignment/)
* Класс [PictureFillFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)