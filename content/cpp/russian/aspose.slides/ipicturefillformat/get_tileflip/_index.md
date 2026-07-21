---
title: get_TileFlip()
second_title: Aspose.Slides для C++ справочник API
description: "Переворачивает плитку текстуры по её горизонтальной, вертикальной или обеим осям. Смотрите Slides::TileFlip."
type: docs
weight: 404
url: /ru/aspose.slides/ipicturefillformat/get_tileflip/
---
## IPictureFillFormat::get_TileFlip() метод


Переворачивает плитку текстуры по её горизонтальной, вертикальной или обеим осям. Смотрите [Slides::TileFlip](../../tileflip/).

```cpp
virtual Aspose::Slides::TileFlip Aspose::Slides::IPictureFillFormat::get_TileFlip()=0
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

// Переворачивает плитку текстуры по её вертикальной оси.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## См. также

* Перечисление [TileFlip](../../tileflip/)
* Класс [IPictureFillFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)