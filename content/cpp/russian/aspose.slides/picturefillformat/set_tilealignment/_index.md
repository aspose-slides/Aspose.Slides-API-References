---
title: set_TileAlignment()
second_title: Справочник API Aspose.Slides для C++
description: Устанавливает, как текстура выравнивается внутри фигуры. Эта настройка контролирует начальную точку шаблона текстуры и то, как она повторяется по фигуре. Запишите RectangleAlignment.
type: docs
weight: 391
url: /ru/aspose.slides/picturefillformat/set_tilealignment/
---

## PictureFillFormat::set_TileAlignment(RectangleAlignment) метод

Устанавливает, как текстура выравнивается внутри фигуры. Эта настройка контролирует начальную точку шаблона текстуры и то, как она повторяется по фигуре. Запишите [RectangleAlignment](../../rectanglealignment/).

```cpp
void Aspose::Slides::PictureFillFormat::set_TileAlignment(RectangleAlignment value) override
```

## Примечания

По умолчанию [RectangleAlignment::TopLeft](../../rectanglealignment/).

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Получает формат заливки картинки формы
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Устанавливает режим заливки картинки в Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Устанавливает выравнивание плитки в правый нижний угол
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## См. также

* Перечисление [RectangleAlignment](../../rectanglealignment/)
* Класс [PictureFillFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)