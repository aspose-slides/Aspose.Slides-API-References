---
title: get_InkEffect()
second_title: Справочник API Aspose.Slides для C++
description: "Получает тип эффекта чернил (например, Galaxy, Gold, Silver), определяющий визуальный стиль штриха чернил. Значение извлекается из свойства кисти \"inkEffects\". Если не указан распознаваемый эффект, возвращается InkEffectType::NotDefined."
type: docs
weight: 53
url: /ru/aspose.slides.ink/iinkbrush/get_inkeffect/
---
## IInkBrush::get_InkEffect() метод

Получает тип эффекта чернил (например, Galaxy, Gold, Silver), определяющий визуальный стиль штриха чернила. Значение извлекается из свойства кисти "inkEffects". Если не указан распознаваемый эффект, возвращается [InkEffectType::NotDefined](../../inkeffecttype/).

```cpp
virtual InkEffectType Aspose::Slides::Ink::IInkBrush::get_InkEffect()=0
```

## Примечания

Пример:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<Ink> ink = System::AsCast<Ink>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IInkBrush> brush = ink->get_Traces()->idx_get(0)->get_Brush();
System::Console::WriteLine(u"InkEffects = {0}", brush->get_InkEffect());
```

## См. также

* Перечисление [InkEffectType](../../inkeffecttype/)
* Класс [IInkBrush](../)
* Пространство имён [Aspose::Slides::Ink](../../)
* Библиотека [Aspose.Slides](../../../)