---
title: get_TileOffsetX()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает горизонтальное смещение текстуры от начала координат фигуры в пунктах. Положительное значение перемещает текстуру вправо, а отрицательное — влево. Читать float.
type: docs
weight: 274
url: /ru/aspose.slides/ipicturefillformat/get_tileoffsetx/
---
## IPictureFillFormat::get_TileOffsetX() метод


Возвращает горизонтальное смещение текстуры от начала координат фигуры в пунктах. Положительное значение перемещает текстуру вправо, а отрицательное — влево. Читать **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileOffsetX()=0
```

## Примечания



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Получает формат заливки рисунком фигуры
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Устанавливает режим заливки рисунком в Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Устанавливает горизонтальное смещение текстуры в 20 пунктов
pictureFillFormat->set_TileOffsetX(20.0f);
```

## Смотрите также

* Класс [IPictureFillFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)