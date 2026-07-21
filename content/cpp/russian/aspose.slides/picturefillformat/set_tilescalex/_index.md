---
title: set_TileScaleX()
second_title: Справочник API Aspose.Slides для C++
description: Устанавливает горизонтальный масштаб текстурной заливки в процентах. Запишите float.
type: docs
weight: 339
url: /ru/aspose.slides/picturefillformat/set_tilescalex/
---
## PictureFillFormat::set_TileScaleX(float) метод


Устанавливает горизонтальный масштаб текстурной заливки в процентах. Запишите **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleX(float value) override
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

## Смотрите также

* Класс [PictureFillFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)