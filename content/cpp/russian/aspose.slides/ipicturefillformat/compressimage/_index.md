---
title: CompressImage()
second_title: Справочник API Aspose.Slides для C++
description: Сжимает изображение, уменьшая его размер в зависимости от размера фигуры и указанного разрешения. При необходимости также удаляет обрезанные области.
type: docs
weight: 443
url: /ru/aspose.slides/ipicturefillformat/compressimage/
---
## IPictureFillFormat::CompressImage(bool, Export::PicturesCompression) метод


Сжимает изображение, уменьшая его размер в зависимости от размера фигуры и указанного разрешения. При необходимости также удаляет обрезанные области.

```cpp
virtual bool Aspose::Slides::IPictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Если true, метод удалит обрезанные области изображения, что может дополнительно уменьшить его размер. |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | Целевое разрешение для сжатия, указываемое как значение перечисления [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/). |

### Возвращаемое значение

Булево значение **bool**, указывающее, было ли изображение успешно сжато. Возвращает ****true****

## Примечания


Этот метод изменяет размер и разрешение изображения, аналогично функции PowerPoint «Picture Format -> Compress Pictures».

если изображение было изменено в размере или обрезано, иначе ****false****

. 


Следующий пример демонстрирует, как использовать метод **CompressImage** для уменьшения размера изображения в презентации путем установки целевого разрешения и удаления обрезанных областей: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// Сжать изображение с целевым разрешением 150 DPI (разрешение для Web) и удалить обрезанные области
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## IPictureFillFormat::CompressImage(bool, float) метод


Сжимает изображение, уменьшая его размер в зависимости от размера фигуры и указанного разрешения. При необходимости также удаляет обрезанные области.

```cpp
virtual bool Aspose::Slides::IPictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | Если true, метод удалит обрезанные области изображения, что может дополнительно уменьшить его размер. |
| resolution | **float** | Целевое разрешение в DPI. Это значение должно быть положительным и определяет, как будет изменён размер изображения. |

### Возвращаемое значение

Булево значение **bool**, указывающее, было ли изображение успешно сжато. Возвращает ****true****

## Примечания


Этот метод изменяет размер и разрешение изображения, аналогично функции PowerPoint «Picture Format -> Compress Pictures».

если изображение было изменено в размере или обрезано, иначе ****false****

. 


Следующий пример демонстрирует, как использовать метод **CompressImage** для уменьшения размера изображения в презентации путем установки целевого разрешения и удаления обрезанных областей: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Получаем PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Сжать изображение с целевым разрешением 150 DPI (разрешение для Web) и удалить обрезанные области
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // Разрешение для Web
```

## Смотрите также

* Перечисление [PicturesCompression](../../../aspose.slides.export/picturescompression/)
* Класс [IPictureFillFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)