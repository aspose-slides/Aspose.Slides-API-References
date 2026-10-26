---
title: GetEffective()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar effektiv formatdata för textstil med ärftlighet tillämpad.
type: docs
weight: 27
url: /sv/aspose.slides/textstyle/geteffective/
---
## TextStyle::GetEffective() metod

Hämtar effektiv formatering av textstil med ärftlighet tillämpad.

```cpp
System::SharedPtr<ITextStyleEffectiveData> Aspose::Slides::TextStyle::GetEffective() override
```

### Returvärde

En [ITextStyleEffectiveData](../../itextstyleeffectivedata/).

## Anmärkningar

Detta exempel visar hur man hämtar några av de effektiva textstilegenskaperna.
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

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ITextStyleEffectiveData](../../itextstyleeffectivedata/)
* Klass [TextStyle](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)