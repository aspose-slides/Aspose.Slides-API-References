---
title: get_MasterTheme()
second_title: Справочник API Aspose.Slides для C++
description: "Возвращает мастер-тему. Только для чтения Theme::IMasterTheme."
type: docs
weight: 404
url: /ru/aspose.slides/presentation/get_mastertheme/
---
## Presentation::get_MasterTheme() метод

Возвращает мастер-тему. Только для чтения [Theme::IMasterTheme](../../../aspose.slides.theme/imastertheme/).

```cpp
System::SharedPtr<Theme::IMasterTheme> Aspose::Slides::Presentation::get_MasterTheme() override
```

## Примечания

Следующие примеры показывают, как изменить эффект темы, изменяя части элементов PowerPoint [Presentation](../).
```cpp
// Создать объект презентации, представляющий файл презентации
auto pres = System::MakeObject<Presentation>(u"Subtle_Moderate_Intense.pptx");
auto masterTheme = pres->get_MasterTheme();
auto formatScheme = masterTheme->get_FormatScheme();

formatScheme->get_LineStyles()->idx_get(0)->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
formatScheme->get_FillStyles()->idx_get(2)->set_FillType(FillType::Solid);
formatScheme->get_FillStyles()->idx_get(2)->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
formatScheme->get_EffectStyles()->idx_get(2)->get_EffectFormat()->get_OuterShadowEffect()->set_Distance(10.0f);
pres->Save(u"Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat::Pptx);
```

## Смотрите также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMasterTheme](../../../aspose.slides.theme/imastertheme/)
* Класс [Presentation](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)