---
title: GetEffective()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt effectieve tekststijl-opmaakgegevens op met de toegepaste overerving.
type: docs
weight: 27
url: /nl/aspose.slides/textstyle/geteffective/
---
## TextStyle::GetEffective() methode

Krijgt effectieve opmaakgegevens voor tekststijl met de geërfde instellingen toegepast.

```cpp
System::SharedPtr<ITextStyleEffectiveData> Aspose::Slides::TextStyle::GetEffective() override
```


### Retourwaarde

A [ITextStyleEffectiveData](../../itextstyleeffectivedata/).
## Opmerkingen



Dit voorbeeld toont het ophalen van enkele effectieve tekststijl-eigenschappen. 
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

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ITextStyleEffectiveData](../../itextstyleeffectivedata/)
* Klasse [TextStyle](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)