---
title: CompressImage()
second_title: Справочник API Aspose.Slides для C++
description: Сжимает изображение, уменьшая его размер в зависимости от размера формы и указанного разрешения. При необходимости также удаляет обрезанные области.
type: docs
weight: 443
url: /ru/aspose.slides/picturefillformat/compressimage/
---
## PictureFillFormat::CompressImage(bool, Export::PicturesCompression) метод

Сжимает изображение, уменьшая его размер в зависимости от размера фигуры и указанного разрешения. При необходимости также удаляет обрезанные области.

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Если true, метод удалит обрезанные области изображения, что может дополнительно уменьшить его размер. |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | Целевое разрешение для сжатия, указано как значение перечисления [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/). |

### Возвращаемое значение

Логическое значение **bool**, указывающее, было ли изображение успешно сжато. Возвращает ****true****

## Примечания

Этот метод изменяет размер и разрешение изображения аналогично функции PowerPoint "Picture Format -> Compress Pictures".

если изображение было изменено в размере или обрезано, иначе ****false****

. 

Следующий пример демонстрирует, как использовать метод **CompressImage** для уменьшения размера изображения в презентации, задав целевое разрешение и удалив обрезанные области: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// Сожмите изображение с целевым разрешением 150 DPI (веб-разрешение) и удалите обрезанные области
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## PictureFillFormat::CompressImage(bool, float) метод

Сжимает изображение, уменьшая его размер в зависимости от размера фигуры и указанного разрешения. При необходимости также удаляет обрезанные области.

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Если true, метод удалит обрезанные области изображения, что может дополнительно уменьшить его размер. |
| resolution | **float** | Целевое разрешение в DPI. Это значение должно быть положительным и определяет, как будет изменён размер изображения. |

### Возвращаемое значение

Логическое значение **bool**, указывающее, было ли изображение успешно сжато. Возвращает ****true****

## Примечания

Этот метод изменяет размер и разрешение изображения аналогично функции PowerPoint "Picture Format -> Compress Pictures".

если изображение было изменено в размере или обрезано, иначе ****false****

. 

Следующий пример демонстрирует, как использовать метод **CompressImage** для уменьшения размера изображения в презентации, задав целевое разрешение и удалив обрезанные области: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Получает PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Сжимает изображение с целевым разрешением 150 DPI (веб-разрешение) и удаляет обрезанные области
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // веб-разрешение
```

## См. также

* Enum [PicturesCompression](../../../aspose.slides.export/picturescompression/)
* Класс [PictureFillFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)