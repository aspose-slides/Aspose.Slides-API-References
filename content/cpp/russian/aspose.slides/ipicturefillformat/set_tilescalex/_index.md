---
title: set_TileScaleX()
second_title: Aspose.Slides для C++ справочник API
description: Устанавливает горизонтальный масштаб заливки текстурой в процентах. Запишите float.
type: docs
weight: 339
url: /ru/aspose.slides/ipicturefillformat/set_tilescalex/
---
## IPictureFillFormat::set_TileScaleX(float) метод


Устанавливает горизонтальный масштаб заливки текстурой в процентах. Запишите **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileScaleX(float value)=0
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
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)