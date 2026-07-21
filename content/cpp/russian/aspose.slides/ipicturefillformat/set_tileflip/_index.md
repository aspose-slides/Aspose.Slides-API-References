---
title: set_TileFlip()
second_title: Aspose.Slides для C++: справочник API
description: "Переворачивает тайл текстуры по горизонтальной, вертикальной или обеим осям. Запишите Slides::TileFlip."
type: docs
weight: 417
url: /ru/aspose.slides/ipicturefillformat/set_tileflip/
---
## IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) method


Переворачивает тайл текстуры по горизонтальной, вертикальной или обеим осям. Запишите [Slides::TileFlip](../../tileflip/).

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value)=0
```

## Remarks


По умолчанию [TileFlip::NoFlip](../../tileflip/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Получает формат заливки изображения формы
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Устанавливает режим заливки изображения в Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Отражает тайл текстуры относительно вертикальной оси.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## See Also

* Enum [TileFlip](../../tileflip/)
* Класс [IPictureFillFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)