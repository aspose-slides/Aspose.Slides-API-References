---
title: get_SlideSize()
second_title: Aspose.Slides для C++ справка API
description: Возвращает объект размера слайда. Только для чтения ISlideSize.
type: docs
weight: 79
url: /ru/aspose.slides/presentation/get_slidesize/
---
## Presentation::get_SlideSize() метод


Возвращает объект размера слайда. Только для чтения [ISlideSize](../../islidesize/).

```cpp
System::SharedPtr<ISlideSize> Aspose::Slides::Presentation::get_SlideSize() override
```

## Примечания


В следующем примере показано, как изменить размер слайда в PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres-4x3-aspect-ratio.pptx");

pres->get_SlideSize()->SetSize(SlideSizeType::OnScreen16x9, SlideSizeScaleType::DoNotScale);
pres->Save(u"pres-4x3-aspect-ratio.pptx", SaveFormat::Pptx);
```
 В следующем примере показано, как задать размер слайда с учётом масштабирования содержимого для PowerPoint [Presentation](../). 
```cpp
// Создайте объект Presentation, представляющий файл презентации
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto auxPresentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);

// Установите размер слайда сгенерированных презентаций, соответствующий исходному
presentation->get_SlideSize()->SetSize(540.0f, 720.0f, SlideSizeScaleType::EnsureFit);

// Метод SetSize используется для установки размера слайда с масштабированием содержимого, чтобы обеспечить вписывание
presentation->get_SlideSize()->SetSize(SlideSizeType::A4Paper, SlideSizeScaleType::Maximize);

// Метод SetSize используется для установки размера слайда с максимизацией содержимого
// Сохранить презентацию на диск
auxPresentation->Save(u"Set_Size_Type_out.pptx", SaveFormat::Pptx);
```
 В следующем примере показано, как указать пользовательские размеры слайдов в PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
pres->get_SlideSize()->SetSize(780.0f, 540.0f, SlideSizeScaleType::DoNotScale);

// Размер листа A4
pres->Save(u"pres-a4-slide-size.pptx", SaveFormat::Pptx);
```

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [ISlideSize](../../islidesize/)
* Класс [Presentation](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)