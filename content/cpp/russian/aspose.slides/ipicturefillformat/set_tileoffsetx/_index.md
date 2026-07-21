---
title: set_TileOffsetX()
second_title: Aspose.Slides для C++ справочник API
description: Устанавливает горизонтальное смещение текстуры от начала формы в пунктах. Положительное значение смещает текстуру вправо, а отрицательное — влево. Записать float.
type: docs
weight: 287
url: /ru/aspose.slides/ipicturefillformat/set_tileoffsetx/
---
## IPictureFillFormat::set_TileOffsetX(float) метод


Устанавливает горизонтальное смещение текстуры от начала формы в пунктах. Положительное значение смещает текстуру вправо, а отрицательное — влево. Записать **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetX(float value)=0
```

## Примечания



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Получает формат заливки изображением формы
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Устанавливает режим заливки изображением в Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Устанавливает горизонтальное смещение текстуры на 20 пунктов
pictureFillFormat->set_TileOffsetX(20.0f);
```

## Смотрите также

* Класс [IPictureFillFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)