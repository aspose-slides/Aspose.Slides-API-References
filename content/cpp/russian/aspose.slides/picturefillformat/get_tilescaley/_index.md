---
title: get_TileScaleY()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает вертикальный масштаб заполнения текстурой в процентах. Читает float.
type: docs
weight: 352
url: /ru/aspose.slides/picturefillformat/get_tilescaley/
---
## PictureFillFormat::get_TileScaleY() метод

Возвращает вертикальный масштаб текстурного заполнения в процентах. Читает **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleY() override
```

## Примечания



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Получает формат заполнения рисунком формы
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Устанавливает режим заполнения рисунком в Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Устанавливает вертикальный масштаб текстуры в 120 процентов
pictureFillFormat->set_TileScaleY(120.0f);
```

## См. также

* Класс [PictureFillFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)