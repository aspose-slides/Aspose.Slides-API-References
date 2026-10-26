---
title: get_TileAlignment()
second_title: Aspose.Slides для C++ Справочник API
description: Возвращает, как текстура выравнивается внутри фигуры. Эта настройка задает начальную точку узора текстуры и то, как она повторяется по фигуре. См. RectangleAlignment.
type: docs
weight: 378
url: /ru/aspose.slides/ipicturefillformat/get_tilealignment/
---
## IPictureFillFormat::get_TileAlignment() метод

Возвращает, как текстура выравнивается внутри фигуры. Эта настройка задает начальную точку узора текстуры и то, как она повторяется по фигуре. См.[RectangleAlignment](../../rectanglealignment/).

```cpp
virtual RectangleAlignment Aspose::Slides::IPictureFillFormat::get_TileAlignment()=0
```

## Примечания

Значение по умолчанию [RectangleAlignment::TopLeft](../../rectanglealignment/).

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Получает формат заливки картинкой формы
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Устанавливает режим заливки картинкой в Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Устанавливает выравнивание тайлинга в BottomRight
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## См. также

* Перечисление [RectangleAlignment](../../rectanglealignment/)
* Класс [IPictureFillFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)