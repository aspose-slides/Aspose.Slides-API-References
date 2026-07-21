---
title: DeletePictureCroppedAreas()
second_title: Aspose.Slides для C++ справочник API
description: Удалить обрезанные области заливки Picture.
type: docs
weight: 430
url: /ru/aspose.slides/picturefillformat/deletepicturecroppedareas/
---
## PictureFillFormat::DeletePictureCroppedAreas() метод


Удалить обрезанные области заливки [Picture](../../picture/).

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::PictureFillFormat::DeletePictureCroppedAreas() override
```


### Возвращаемое значение

Обрезанное изображение или исходное изображение, если обрезка не требуется.

## Примечания


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

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IPPImage](../../ippimage/)
* Класс [PictureFillFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)