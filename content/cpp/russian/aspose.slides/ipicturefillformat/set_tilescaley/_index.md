---
title: set_TileScaleY()
second_title: Aspose.Slides для справки API C++
description: Устанавливает вертикальный масштаб текстурного заполнения в процентах. Запишите float.
type: docs
weight: 365
url: /ru/aspose.slides/ipicturefillformat/set_tilescaley/
---
## IPictureFillFormat::set_TileScaleY(float) method


Устанавливает вертикальный масштаб текстурного заливки в процентах. Запишите **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileScaleY(float value)=0
```

## Примечания



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Получает формат заливки изображения формы
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Устанавливает режим заливки изображения в Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Устанавливает вертикальный масштаб текстуры в 120 процентов
pictureFillFormat->set_TileScaleY(120.0f);
```

## Смотрите также

* Класс [IPictureFillFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)