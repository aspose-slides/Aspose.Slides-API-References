---
title: get_TileFlip()
second_title: Справочник API Aspose.Slides для C++
description: "Переворачивает плитку текстуры вокруг её горизонтальной, вертикальной или обеих осей. См. Slides::TileFlip."
type: docs
weight: 404
url: /ru/aspose.slides/picturefillformat/get_tileflip/
---
## PictureFillFormat::get_TileFlip() метод

Переворачивает плитку текстуры вокруг её горизонтальной, вертикальной или обеих осей. См. [Slides::TileFlip](../../tileflip/).

```cpp
Aspose::Slides::TileFlip Aspose::Slides::PictureFillFormat::get_TileFlip() override
```

## Примечания


По умолчанию [TileFlip::NoFlip](../../tileflip/). 

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Получает формат заливки изображением фигуры
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Устанавливает режим заливки изображением в режим Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Поворачивает плитку текстуры вокруг её вертикальной оси.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## См. также

* Enum [TileFlip](../../tileflip/)
* Класс [PictureFillFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)