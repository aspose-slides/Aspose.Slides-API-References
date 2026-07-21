---
title: GetEffective()
second_title: Aspose.Slides для C++ API справочник
description: Получает данные форматирования эффективного стиля текста с применённым наследованием.
type: docs
weight: 27
url: /ru/aspose.slides/textstyle/geteffective/
---
## TextStyle::GetEffective() метод


Получает данные форматирования эффективного стиля текста с применённым наследованием.

```cpp
System::SharedPtr<ITextStyleEffectiveData> Aspose::Slides::TextStyle::GetEffective() override
```


### Возвращаемое значение

A [ITextStyleEffectiveData](../../itextstyleeffectivedata/).
## Замечания



Этот пример демонстрирует получение некоторых свойств эффективного стиля текста. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveTextStyle = shape->get_TextFrame()->get_TextFrameFormat()->get_TextStyle()->GetEffective();

for (int32_t i = 0; i <= 8; i++)
{
    auto effectiveStyleLevel = effectiveTextStyle->GetLevel(i);
    Console::WriteLine(String(u"= Effective paragraph formatting for style level #") + i + u" =");

    Console::WriteLine(String(u"Depth: ") + effectiveStyleLevel->get_Depth());
    Console::WriteLine(String(u"Indent: ") + effectiveStyleLevel->get_Indent());
    Console::WriteLine(String(u"Alignment: ") + ObjectExt::ToString(effectiveStyleLevel->get_Alignment()));
    Console::WriteLine(String(u"Font alignment: ") + ObjectExt::ToString(effectiveStyleLevel->get_FontAlignment()));
}
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ITextStyleEffectiveData](../../itextstyleeffectivedata/)
* Класс [TextStyle](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)