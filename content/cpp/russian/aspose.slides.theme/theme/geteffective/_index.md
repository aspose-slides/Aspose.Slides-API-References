---
title: GetEffective()
second_title: Справочник API Aspose.Slides для C++
description: Получает эффективные данные темы с учётом наследования.
type: docs
weight: 53
url: /ru/aspose.slides.theme/theme/geteffective/
---
## Theme::GetEffective() метод

Получает эффективные данные темы с учётом наследования.

```cpp
System::SharedPtr<IThemeEffectiveData> Aspose::Slides::Theme::Theme::GetEffective() override
```

### Возвращаемое значение

A [IThemeEffectiveData](../../ithemeeffectivedata/).

## Замечания

Этот пример демонстрирует получение эффективных свойств темы. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveTheme = pres->get_Slides()->idx_get(0)->get_ThemeManager()->get_OverrideTheme()->GetEffective();

Console::WriteLine(String(u"Font scheme name: ") + effectiveTheme->get_FontScheme()->get_Name());
Console::WriteLine(String(u"Major latin font: ") + effectiveTheme->get_FontScheme()->get_Major()->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Minor latin font: ") + effectiveTheme->get_FontScheme()->get_Minor()->get_LatinFont()->get_FontName());
```

## Смотрите также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IThemeEffectiveData](../../ithemeeffectivedata/)
* Класс [Theme](../)
* Пространство имён [Aspose::Slides::Theme](../../)
* Библиотека [Aspose.Slides](../../../)