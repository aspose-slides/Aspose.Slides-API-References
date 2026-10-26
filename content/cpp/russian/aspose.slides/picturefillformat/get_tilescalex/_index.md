---
title: get_TileScaleX()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает горизонтальный масштаб для текстурной заливки в виде процента. Чтение float.
type: docs
weight: 326
url: /ru/aspose.slides/picturefillformat/get_tilescalex/
---
## PictureFillFormat::get_TileScaleX() метод


Возвращает горизонтальный масштаб для текстурной заливки в виде процента. Чтение **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleX() override
```

## Примечания



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Получает формат заливки изображением формы
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Устанавливает режим заливки изображением в Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Устанавливает горизонтальный масштаб текстуры в 120 процентов
pictureFillFormat->set_TileScaleX(120.0f);
```

## См. также

* Класс [PictureFillFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)