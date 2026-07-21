---
title: GetEffective()
second_title: Справочник API Aspose.Slides для C++
description: Получает фактические данные форматирования текстовой рамки с учётом наследования.
type: docs
weight: 391
url: /ru/aspose.slides/textframeformat/geteffective/
---
## TextFrameFormat::GetEffective() метод

Получает фактические данные форматирования текстовой рамки с учётом наследования.

```cpp
System::SharedPtr<ITextFrameFormatEffectiveData> Aspose::Slides::TextFrameFormat::GetEffective() override
```

### Возвращаемое значение

A [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/).

## Замечания

Этот пример демонстрирует получение некоторых фактических свойств форматирования текстовой рамки. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveTextFrameFormat = shape->get_TextFrame()->get_TextFrameFormat()->GetEffective();

Console::WriteLine(String(u"Anchoring type: ") + ObjectExt::ToString(effectiveTextFrameFormat->get_AnchoringType()));
Console::WriteLine(String(u"Autofit type: ") + ObjectExt::ToString(effectiveTextFrameFormat->get_AutofitType()));
Console::WriteLine(String(u"Text vertical type: ") + ObjectExt::ToString(effectiveTextFrameFormat->get_TextVerticalType()));
Console::WriteLine(u"Margins");
Console::WriteLine(String(u"   Left: ") + effectiveTextFrameFormat->get_MarginLeft());
Console::WriteLine(String(u"   Top: ") + effectiveTextFrameFormat->get_MarginTop());
Console::WriteLine(String(u"   Right: ") + effectiveTextFrameFormat->get_MarginRight());
Console::WriteLine(String(u"   Bottom: ") + effectiveTextFrameFormat->get_MarginBottom());
```

## См. также

* Тип-определение [SharedPtr](../../../system/sharedptr/)
* Класс [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/)
* Класс [TextFrameFormat](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)