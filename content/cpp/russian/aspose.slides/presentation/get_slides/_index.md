---
title: get_Slides()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает список всех слайдов, определённых в презентации. Только для чтения ISlideCollection.
type: docs
weight: 53
url: /ru/aspose.slides/presentation/get_slides/
---
## Presentation::get_Slides() метод


Возвращает список всех слайдов, определённых в презентации. Только для чтения [ISlideCollection](../../islidecollection/).

```cpp
System::SharedPtr<ISlideCollection> Aspose::Slides::Presentation::get_Slides() override
```

## Примечания


В следующем примере показано, как установить цвет фона слайдов PowerPoint [Presentation](../). 
```cpp
// Создайте объект класса Presentation, представляющий файл презентации
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Установите цвет фона первого ISlide в синий
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Solid);
slide->get_Background()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Blue());
pres->Save(u"ContentBG_out.pptx", SaveFormat::Pptx);
```
В следующем примере показано, как установить изображение фона слайдов PowerPoint [Presentation](../). 
```cpp
// Создайте объект класса Presentation, представляющий файл презентации
auto pres = System::MakeObject<Presentation>(u"SetImageAsBackground.pptx");
auto slide = pres->get_Slides()->idx_get(0);

// Установите фон с изображением
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Picture);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);
// Установите изображение
auto img = System::ExplicitCast<System::Drawing::Image>(System::MakeObject<System::Drawing::Bitmap>(dataDir + u"Tulips.jpg"));
// Добавьте изображение в коллекцию изображений презентации
auto imgx = pres->get_Images()->AddImage(img);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(imgx);
// Запишите презентацию на диск
pres->Save(u"ContentBG_Img_out.pptx", SaveFormat::Pptx);
```
В следующем примере показано, как добавить переход между слайдами [Presentation](../). 
```cpp
// Создайте объект класса Presentation для загрузки исходного файла презентации
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// Примените переход типа «Круг» к слайду 1
presentation->get_Slides()->idx_get(0)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// Примените переход типа «Гребень» к слайду 2
presentation->get_Slides()->idx_get(1)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// Запишите презентацию на диск
presentation->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```
В следующем примере показано, как добавить расширенный переход слайдов. 
```cpp
// Создайте объект класса Presentation, представляющий файл презентации
auto pres = System::MakeObject<Presentation>(u"BetterSlideTransitions.pptx");

auto slide1 = pres->get_Slides()->idx_get(0);
auto slide2 = pres->get_Slides()->idx_get(1);
auto slide3 = pres->get_Slides()->idx_get(2);

// Примените переход типа «Круг» к слайду 1
slide1->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// Установите время перехода 3 секунды
slide1->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide1->get_SlideShowTransition()->set_AdvanceAfterTime(3000);
// Примените переход типа «Гребень» к слайду 2
slide2->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// Установите время перехода 5 секунд
slide2->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide2->get_SlideShowTransition()->set_AdvanceAfterTime(5000);
// Примените переход типа «Масштаб» к слайду 3
slide3->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Zoom);
// Установите время перехода 7 секунд
slide3->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide3->get_SlideShowTransition()->set_AdvanceAfterTime(7000);
// Запишите презентацию на диск
pres->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ISlideCollection](../../islidecollection/)
* Класс [Presentation](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)