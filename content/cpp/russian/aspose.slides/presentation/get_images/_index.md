---
title: get_Images()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает коллекцию всех изображений в презентации. Только для чтения IImageCollection.
type: docs
weight: 209
url: /ru/aspose.slides/presentation/get_images/
---
## Presentation::get_Images() method

Возвращает коллекцию всех изображений в презентации. Только для чтения [IImageCollection](../../iimagecollection/).

```cpp
System::SharedPtr<IImageCollection> Aspose::Slides::Presentation::get_Images() override
```

## Примечания

Следующий пример показывает, как добавить изображение в виде BLOB в PowerPoint [Presentation](../). 
```cpp
System::String pathToLargeImage = u"large_image.jpg";
// создаёт новую презентацию, в которую будет добавлено изображение.
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToLargeImage, System::IO::FileMode::Open);

// Добавим изображение в презентацию — выбираем поведение KeepLocked, потому что мы
// не планируем обращаться к файлу "largeImage.png" file.
auto img = pres->get_Images()->AddImage(fileStream, LoadingStreamBehavior::KeepLocked);
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 300.0f, 200.0f, img);
// Сохраняет презентацию. Пока выводится большая презентация, потребление памяти
// остаётся низким на протяжении жизненного цикла объекта pres
pres->Save(u"presentationWithLargeImage.pptx", SaveFormat::Pptx);
```
Следующий пример добавляет гиперссылку к изображению в PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Добавляет изображение в презентацию
auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
// Создаёт рамку изображения на слайде 1 на основе ранее добавленного изображения
auto pictureFrame = slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pictureFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
pictureFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IImageCollection](../../iimagecollection/)
* Класс [Presentation](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)