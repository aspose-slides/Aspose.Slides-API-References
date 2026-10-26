---
title: get_Masters()
second_title: Aspose.Slides для C++ справка по API
description: Возвращает список всех мастер-слайдов, определённых в презентации. Только для чтения IMasterSlideCollection.
type: docs
weight: 118
url: /ru/aspose.slides/presentation/get_masters/
---
## Presentation::get_Masters() метод

Возвращает список всех мастер-слайдов, определённых в презентации. Только для чтения [IMasterSlideCollection](../../imasterslidecollection/).

```cpp
System::SharedPtr<IMasterSlideCollection> Aspose::Slides::Presentation::get_Masters() override
```

## Примечания

Следующие примеры показывают, как добавить [Images](../../images/) к мастеру [Slides](../../) презентации PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto masterSlide = slide->get_LayoutSlide()->get_MasterSlide();

auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
masterSlide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
Следующие примеры показывают, как изменить цвет фона мастер-слайда PowerPoint [Presentation](../). 
```cpp
// Создайте объект класса Presentation, представляющий файл презентации
auto pres = System::MakeObject<Presentation>();

// Установите цвет фона мастер-слайда ISlide в Forest Green
auto masterSlide = pres->get_Masters()->idx_get(0);
auto background = masterSlide->get_Background();
background->set_Type(BackgroundType::OwnBackground);
background->get_FillFormat()->set_FillType(FillType::Solid);
background->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
// Записать презентацию на диск
pres->Save(u"SetSlideBackgroundMaster_out.pptx", SaveFormat::Pptx);
```
Следующие примеры показывают, как добавить макет слайда в PowerPoint [Presentation](../). 
```cpp
// Создать объект класса Presentation, представляющего файл презентации
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// Попробовать найти по типу макета слайда
auto layoutSlides = presentation->get_Masters()->idx_get(0)->get_LayoutSlides();
auto layoutSlide = System::ObjectExt::Coalesce(
    layoutSlides->GetByType(SlideLayoutType::TitleAndObject),
    [&](){ return layoutSlides->GetByType(SlideLayoutType::Title); });

if (layoutSlide == nullptr)
{
    // Ситуация, когда презентация не содержит некоторый тип макетов.
    // Файл презентации содержит только типы макетов Blank и Custom.
    // Но макетные слайды с типом Custom имеют разные имена слайдов,
    // такие как "Title", "Title and Content", и т.д. И их можно использовать
    // имена для выбора макетного слайда.
    // Также можно использовать набор типов заполнителей фигур. Например,
    // Слайд заголовка должен иметь только тип заполнителя Title и т.д.
    for (auto&& titleAndObjectLayoutSlide : layoutSlides)
    {
        if (titleAndObjectLayoutSlide->get_Name() == u"Title and Object")
        {
            layoutSlide = titleAndObjectLayoutSlide;
            break;
        }
    }

    if (layoutSlide == nullptr)
    {
        for (auto&& titleLayoutSlide : layoutSlides)
        {
            if (titleLayoutSlide->get_Name() == u"Title")
            {
                layoutSlide = titleLayoutSlide;
                break;
            }
        }

        if (layoutSlide == nullptr)
        {
            layoutSlide = layoutSlides->GetByType(SlideLayoutType::Blank);
            if (layoutSlide == nullptr)
            {
                layoutSlide = layoutSlides->Add(SlideLayoutType::TitleAndObject, u"Title and Object");
            }
        }
    }
}

// Добавление пустого слайда с добавленным макетным слайдом
presentation->get_Slides()->InsertEmptySlide(0, layoutSlide);
// Сохранить презентацию
presentation->Save(u"AddLayoutSlides_out.pptx", SaveFormat::Pptx);
```

## Смотрите также

* typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMasterSlideCollection](../../imasterslidecollection/)
* Класс [Presentation](../)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)