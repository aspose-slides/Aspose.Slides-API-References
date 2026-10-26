---
title: GetEffective()
second_title: Aspose.Slides pro C++ API Reference
description: Získá data formátování efektivního stylu textu s aplikovaným děděním.
type: docs
weight: 27
url: /cs/aspose.slides/textstyle/geteffective/
---
## TextStyle::GetEffective() metoda

Získá data formátování efektivního stylu textu s aplikovaným děděním.

```cpp
System::SharedPtr<ITextStyleEffectiveData> Aspose::Slides::TextStyle::GetEffective() override
```

### Návratová hodnota

A [ITextStyleEffectiveData](../../itextstyleeffectivedata/).

## Poznámky

Tento příklad demonstruje získání některých vlastností efektivního stylu textu.
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

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITextStyleEffectiveData](../../itextstyleeffectivedata/)
* Class [TextStyle](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)