---
title: GetEffective()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt effectieve alinea-opmaakgegevens op met de toegepaste overerving.
type: docs
weight: 365
url: /nl/aspose.slides/paragraphformat/geteffective/
---
## ParagraphFormat::GetEffective() methode


Haalt effectieve alinea-opmaakgegevens op met de toegepaste overerving.

```cpp
System::SharedPtr<IParagraphFormatEffectiveData> Aspose::Slides::ParagraphFormat::GetEffective() override
```


### Retourwaarde

Een [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/).
## Opmerkingen



Dit voorbeeld laat zien hoe enkele effectieve alinea-opmaak eigenschappen worden opgehaald. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveParagraphFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->GetEffective();

Console::WriteLine(String(u"Text alignment: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Alignment()));
Console::WriteLine(String(u"Indent: ") + effectiveParagraphFormat->get_Indent());
Console::WriteLine(String(u"Bullet type: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Bullet()->get_Type()));
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/)
* Klasse [ParagraphFormat](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)