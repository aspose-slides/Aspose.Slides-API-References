---
title: get_TileOffsetY()
second_title: Aspose.Slides для C++ справка API
description: Возвращает вертикальное смещение текстуры от начала координат фигуры в пунктах. Положительное значение перемещает текстуру вниз, а отрицательное — вверх. Читать float.
type: docs
weight: 300
url: /ru/aspose.slides/ipicturefillformat/get_tileoffsety/
---
## IPictureFillFormat::get_TileOffsetY() метод


Возвращает вертикальное смещение текстуры от начала координат фигуры в пунктах. Положительное значение перемещает текстуру вниз, а отрицательное — вверх. Читать **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileOffsetY()=0
```

## Примечания



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Получает формат заливки картинки формы
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Устанавливает режим заливки картинки в Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Устанавливает вертикальное смещение текстуры на -50 пунктов
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## См. также

* Класс [IPictureFillFormat](../)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)