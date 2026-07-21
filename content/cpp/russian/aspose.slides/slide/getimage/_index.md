---
title: GetImage()
second_title: Aspose.Slides для C++: справочник API
description: Возвращает объект Thumbnail Image с пользовательским масштабированием.
type: docs
weight: 144
url: /ru/aspose.slides/slide/getimage/
---
## Slide::GetImage(float, float) метод


Возвращает объект Thumbnail Image с пользовательским масштабированием.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(float scaleX, float scaleY) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| scaleX | **float** | Значение, на которое масштабировать эту Thumbnail вдоль оси X. |
| scaleY | **float** | Значение, на которое масштабировать эту Thumbnail вдоль оси Y. |

### Возвращаемое значение

[IImage](../../iimage/) объект.

## Замечания



Следующий пример показывает, как создавать миниатюры из PowerPoint [Presentation](../../presentation/): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"ThumbnailFromSlide.pptx");

// Access the first slide
System::SharedPtr<ISlide> sld = pres->get_Slide(0);
// Create a full scale image
System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
// Save the image to disk in JPEG format
bmp->Save(u"Thumbnail_out.jpg", Aspose::Slides::ImageFormat::Jpeg);
```
 Следующий пример показывает, как конвертировать слайды в bitmap и сохранять изображения в PNG: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Преобразует первый слайд презентации в объект Bitmap
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage();
// Сохраняет изображение в формате PNG
bmp->Save(u"Slide_0.png", Aspose::Slides::ImageFormat::Png);
```
 Следующий пример показывает, как конвертировать PowerPoint PPT/PPTX в JPG: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.ppt");

for (auto&& sld : pres->get_Slides())
{
    // Создать изображение в полном масштабе
    System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
    // Сохранить изображение на диск в формате JPEG
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```
 Следующий пример показывает, как конвертировать PowerPoint PPT/PPTX в JPG с пользовательскими размерами: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.pptx");

// Задать размеры
int32_t desiredX = 1200;
int32_t desiredY = 800;
// Получить масштабированные значения X и Y
float scaleX = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Width()) * desiredX;
float scaleY = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Height()) * desiredY;

for (auto&& sld : pres->get_Slides())
{
    // Создать изображение в полном масштабе
    System::SharedPtr<IImage> bmp = sld->GetImage(scaleX, scaleY);
    // Сохранить изображение на диск в формате JPEG
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```

## Slide::GetImage() метод


Возвращает объект Thumbnail Image (20 % от реального размера).

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage() override
```

## Slide::GetImage(System::Drawing::Size) метод


Возвращает объект Thumbnail Image с указанным размером.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::Drawing::Size imageSize) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Размер создаваемого изображения. |

### Возвращаемое значение

Объект Image.

## Замечания



Следующий пример показывает, как конвертировать слайды в изображения с пользовательскими размерами, используя C#. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Преобразует первый слайд презентации в Bitmap указанного размера
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage(System::Drawing::Size(1820, 1040));

// Сохраняет изображение в формате JPEG
bmp->Save(u"Slide_0.jpg", Aspose::Slides::ImageFormat::Jpeg);
```




## Slide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) метод


Возвращает объект Thumbnail tiff image с указанными параметрами.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::ITiffOptions> options) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Опции tiff. |

### Возвращаемое значение

Объект Image.

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) метод


Возвращает объект Thumbnail Image.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Опции рендеринга. |

### Возвращаемое значение

Объект Image.

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) метод


Возвращает объект Thumbnail Image с пользовательским масштабированием.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Опции рендеринга. |
| scaleX | **float** | Значение, на которое масштабировать эту Thumbnail вдоль оси X. |
| scaleY | **float** | Значение, на которое масштабировать эту Thumbnail вдоль оси Y. |

### Возвращаемое значение

Объекты Bitmap.

## Замечания



Следующий пример показывает, как конвертировать слайды с примечаниями и комментариями в [Images](../../images/) с использованием C#. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PresentationNotesComments.pptx");

// Создать параметры рендеринга
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
// Создать параметры компоновки заметок и комментариев
System::SharedPtr<NotesCommentsLayoutingOptions> notesCommentsLayouting = System::MakeObject<NotesCommentsLayoutingOptions>();
// Устанавливает положение заметок на странице
notesCommentsLayouting->set_NotesPosition(NotesPositions::BottomTruncated);
// Устанавливает положение комментариев на странице
notesCommentsLayouting->set_CommentsPosition(CommentsPositions::Right);
// Устанавливает ширину области вывода комментариев
notesCommentsLayouting->set_CommentsAreaWidth(500);
// Устанавливает цвет области комментариев
notesCommentsLayouting->set_CommentsAreaColor(System::Drawing::Color::get_AntiqueWhite());
// Установить параметры компоновки для рендеринга
options->set_SlidesLayoutOptions(notesCommentsLayouting);
// Преобразует первый слайд презентации в объект IImage
System::SharedPtr<IImage> image = pres->get_Slide(0)->GetImage(options, 2.0f, 2.0f);
// Сохраняет изображение в формате GIF
image->Save(u"Slide_Notes_Comments_0.gif", ImageFormat::Gif);
```

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) метод


Возвращает объект Thumbnail Image с указанным размером.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Опции рендеринга. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Размер создаваемого изображения. |

### Возвращаемое значение

Объект Image.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IImage](../../iimage/)
* Класс [Slide](../)
* Класс [Size](../../../system.drawing/size/)
* Класс [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Класс [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)