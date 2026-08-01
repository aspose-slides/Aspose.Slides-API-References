---
title: get_AllCustomXmlParts()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert alle aangepaste gegevensonderdelen in de presentatie. Alleen-lezen ICustomXmlPart[].
type: docs
weight: 287
url: /nl/aspose.slides/presentation/get_allcustomxmlparts/
---
## Presentation::get_AllCustomXmlParts() methode


Retourneert alle aangepaste gegevensonderdelen in de presentatie. Alleen-lezen [ICustomXmlPart](../../icustomxmlpart/)[].

```cpp
System::ArrayPtr<System::SharedPtr<ICustomXmlPart>> Aspose::Slides::Presentation::get_AllCustomXmlParts() override
```

## Opmerkingen


De volgende voorbeelden tonen hoe alle aangepaste xml-onderdelen uit PowerPoint [Presentation](../) kunnen worden gewist.
```cpp
auto pres = System::MakeObject<Presentation>(u"PresentationWithCustomXml.pptx");

// Doorloop alle aangepaste XML-onderdelen
for (System::SharedPtr<ICustomXmlPart> item : pres->get_AllCustomXmlParts())
{
    item->Remove();
}

pres->Save(u"out.pptx", SaveFormat::Pptx);
```

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ICustomXmlPart](../../icustomxmlpart/)
* Klasse [Presentation](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)