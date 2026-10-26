---
title: set_TileFlip()
second_title: Справочник API Aspose.Slides для C++
description: "Переворачивает текстурный тайл вокруг его горизонтальной, вертикальной или обеих осей. Запишите Slides::TileFlip."
type: docs
weight: 417
url: /ru/aspose.slides/picturefillformat/set_tileflip/
---
## PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) метод


Переворачивает текстурный тайл вокруг его горизонтальной, вертикальной или обеих осей. Запишите [Slides::TileFlip](../../tileflip/).

```cpp
void Aspose::Slides::PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value) override
```

## Примечания


По умолчанию [TileFlip::NoFlip](../../tileflip/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Получает формат заливки рисунком формы
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Устанавливает режим заливки изображения в Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Переворачивает текстурный тайл вокруг вертикальной оси.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## См. также

* Enum [TileFlip](../../tileflip/)
* Класс [PictureFillFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)