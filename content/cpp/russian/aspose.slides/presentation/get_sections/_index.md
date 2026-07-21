---
title: get_Sections()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает список всех разделов слайдов, определённых в презентации. Только для чтения ISectionCollection.
type: docs
weight: 66
url: /ru/aspose.slides/presentation/get_sections/
---
## Presentation::get_Sections() метод

Возвращает список всех разделов слайдов, определённых в презентации. Только для чтения [ISectionCollection](../../isectioncollection/).

```cpp
System::SharedPtr<ISectionCollection> Aspose::Slides::Presentation::get_Sections() override
```

## Примечания

Следующие примеры показывают, как создать разделы в PowerPoint [Presentation](../).
```cpp
auto pres = System::MakeObject<Presentation>();

auto defaultSlide = pres->get_Slides()->idx_get(0);
auto layoutSlide = pres->get_LayoutSlides()->idx_get(0);
auto newSlide1 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide2 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide3 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide4 = pres->get_Slides()->AddEmptySlide(layoutSlide);

System::SharedPtr<ISection> section1 = pres->get_Sections()->AddSection(u"Section 1", newSlide1);
// section1 будет завершён на newSlide2, а после него начнётся section2
System::SharedPtr<ISection> section2 = pres->get_Sections()->AddSection(u"Section 2", newSlide3);

pres->Save(u"pres-sections.pptx", SaveFormat::Pptx);
pres->get_Sections()->ReorderSectionWithSlides(section2, 0);
pres->Save(u"pres-sections-moved.pptx", SaveFormat::Pptx);
pres->get_Sections()->RemoveSectionWithSlides(section2);
pres->get_Sections()->AppendEmptySection(u"Last empty section");
pres->Save(u"pres-section-with-empty.pptx", SaveFormat::Pptx);
```
Следующие примеры показывают, как изменить названия разделов. ```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<ISection> section = pres->get_Sections()->idx_get(0);
section->set_Name(u"My section");
```

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ISectionCollection](../../isectioncollection/)
* Класс [Presentation](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)