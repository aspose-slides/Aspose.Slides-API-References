---
title: set_TileOffsetY()
second_title: Справочник API Aspose.Slides для C++
description: Устанавливает вертикальное смещение текстуры от исходной точки фигуры в пунктах. Положительное значение перемещает текстуру вниз, отрицательное - вверх. Запишите float.
type: docs
weight: 313
url: /ru/aspose.slides/picturefillformat/set_tileoffsety/
---
## PictureFillFormat::set_TileOffsetY(float) метод


Устанавливает вертикальное смещение текстуры от исходной точки фигуры в пунктах. Положительное значение перемещает текстуру вниз, отрицательное — вверх. Запишите **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileOffsetY(float value) override
```

## Примечания



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Получает формат заполнения изображения формы
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Устанавливает режим заполнения изображения в режим Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Устанавливает вертикальное смещение текстуры на -50 пунктов
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## См. также

* Класс [PictureFillFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)