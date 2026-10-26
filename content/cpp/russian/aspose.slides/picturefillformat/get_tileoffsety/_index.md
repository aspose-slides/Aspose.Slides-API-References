---
title: get_TileOffsetY()
second_title: Aspose.Slides для справочника API C++
description: Возвращает вертикальное смещение текстуры от начала формы в пунктах. Положительное значение перемещает текстуру вниз, а отрицательное — вверх. Читайте float.
type: docs
weight: 300
url: /ru/aspose.slides/picturefillformat/get_tileoffsety/
---
## PictureFillFormat::get_TileOffsetY() метод

Возвращает вертикальное смещение текстуры от начала формы в пунктах. Положительное значение перемещает текстуру вниз, а отрицательное — вверх. Читать **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileOffsetY() override
```

## Примечания



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Получает формат заливки картинкой формы
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Устанавливает режим заливки картинкой в Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Устанавливает вертикальное смещение текстуры в -50 пунктов
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## См. также

* Класс [PictureFillFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)