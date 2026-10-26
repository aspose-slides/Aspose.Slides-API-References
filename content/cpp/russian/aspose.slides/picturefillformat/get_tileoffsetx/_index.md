---
title: get_TileOffsetX()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает горизонтальное смещение текстуры от начала формы в пунктах. Положительное значение перемещает текстуру вправо, а отрицательное — влево. Читает float.
type: docs
weight: 274
url: /ru/aspose.slides/picturefillformat/get_tileoffsetx/
---
## PictureFillFormat::get_TileOffsetX() метод

Возвращает горизонтальное смещение текстуры от начала формы в пунктах. Положительное значение перемещает текстуру вправо, а отрицательное — влево. Читает **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileOffsetX() override
```

## Примечания



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Получает формат заливки изображения формы
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Устанавливает режим заливки изображения в Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Устанавливает горизонтальное смещение текстуры в 20 пунктов
pictureFillFormat->set_TileOffsetX(20.0f);
```

## Смотрите также

* Класс [PictureFillFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)