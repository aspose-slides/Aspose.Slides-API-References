---
title: get_TileScaleY()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает вертикальный масштаб для заполнения текстурой в процентах. Читается float.
type: docs
weight: 352
url: /ru/aspose.slides/ipicturefillformat/get_tilescaley/
---
## IPictureFillFormat::get_TileScaleY() метод


Возвращает вертикальный масштаб для заполнения текстурой в процентах. Читается **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileScaleY()=0
```

## Примечания



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Получает формат заполнения изображения формы
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Устанавливает режим заполнения изображения в Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Устанавливает вертикальный масштаб текстуры в 120 процентов
pictureFillFormat->set_TileScaleY(120.0f);
```

## Смотрите также

* Класс [IPictureFillFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)