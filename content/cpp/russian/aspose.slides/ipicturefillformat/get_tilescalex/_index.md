---
title: get_TileScaleX()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает горизонтальный масштаб заливки текстурой в процентах. Читает float.
type: docs
weight: 326
url: /ru/aspose.slides/ipicturefillformat/get_tilescalex/
---
## IPictureFillFormat::get_TileScaleX() метод

Возвращает горизонтальный масштаб заливки текстурой в процентах. Читает **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileScaleX()=0
```

## Примечания

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Получает формат заливки изображения формы
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Устанавливает режим заливки изображения в Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Устанавливает горизонтальный масштаб текстуры в 120 процентов
pictureFillFormat->set_TileScaleX(120.0f);
```

## См. также

* Класс [IPictureFillFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)