---
title: set_TileOffsetY()
second_title: Aspose.Slides для C++ справочник API
description: Устанавливает вертикальное смещение текстуры от начала формы в пунктах. Положительное значение перемещает текстуру вниз, отрицательное — вверх. Записывается float.
type: docs
weight: 313
url: /ru/aspose.slides/ipicturefillformat/set_tileoffsety/
---
## IPictureFillFormat::set_TileOffsetY(float) метод

Устанавливает вертикальное смещение текстуры от начала формы в пунктах. Положительное значение перемещает текстуру вниз, отрицательное — вверх. Записывается **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetY(float value)=0
```

## Примечания



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Получает формат заливки изображения формы
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Устанавливает режим заливки изображения в Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Устанавливает вертикальное смещение текстуры на -50 пунктов
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## См. также

* Класс [IPictureFillFormat](../)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)