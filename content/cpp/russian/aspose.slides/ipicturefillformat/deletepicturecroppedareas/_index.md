---
title: DeletePictureCroppedAreas()
second_title: Aspose.Slides для C++ справочник API
description: Удалить обрезанные области заливки Picture.
type: docs
weight: 430
url: /ru/aspose.slides/ipicturefillformat/deletepicturecroppedareas/
---
## IPictureFillFormat::DeletePictureCroppedAreas() метод


Удалить обрезанные области заливки [Picture](../../picture/).

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IPictureFillFormat::DeletePictureCroppedAreas()=0
```


### Возвращаемое значение

Обрезанное изображение или исходное изображение, если обрезка не требуется.
## Замечания


Этот метод преобразует метафайлы WMF/EMF в растровое PNG-изображение с обрезкой.



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Получает PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Удаляет обрезанные области изображения PictureFrame
System::SharedPtr<IPPImage> croppedImage = picFrame->get_PictureFormat()->DeletePictureCroppedAreas();
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IPPImage](../../ippimage/)
* Класс [IPictureFillFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)