---
title: set_TileScaleY()
second_title: Aspose.Slides для C++ справка по API
description: Устанавливает вертикальный масштаб для заливки текстурой в процентах. Записывает float.
type: docs
weight: 365
url: /ru/aspose.slides/picturefillformat/set_tilescaley/
---
## PictureFillFormat::set_TileScaleY(float) метод


Устанавливает вертикальный масштаб для заливки текстурой в процентах. Записывает **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleY(float value) override
```

## Примечание



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Получает формат заливки изображением формы
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Устанавливает режим заливки изображения в Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Устанавливает вертикальный масштаб текстуры на 120 процентов
pictureFillFormat->set_TileScaleY(120.0f);
```

## См. также

* Класс [PictureFillFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)