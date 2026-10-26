---
title: get_AllCustomXmlParts()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar alla anpassade datadelar i presentationen. Skrivskyddad ICustomXmlPart[].
type: docs
weight: 287
url: /sv/aspose.slides/presentation/get_allcustomxmlparts/
---
## Presentation::get_AllCustomXmlParts() metod

Returnerar alla anpassade datadelar i presentationen. Skrivskyddad [ICustomXmlPart](../../icustomxmlpart/)[].

```cpp
System::ArrayPtr<System::SharedPtr<ICustomXmlPart>> Aspose::Slides::Presentation::get_AllCustomXmlParts() override
```

## Anmärkningar

Följande exempel visar hur man rensar alla anpassade xml-delar från PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>(u"PresentationWithCustomXml.pptx");

// Iterera alla anpassade XML-delar
for (System::SharedPtr<ICustomXmlPart> item : pres->get_AllCustomXmlParts())
{
    item->Remove();
}

pres->Save(u"out.pptx", SaveFormat::Pptx);
```

## Se också

* Typdefinition [ArrayPtr](../../../system/arrayptr/)
* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [ICustomXmlPart](../../icustomxmlpart/)
* Klass [Presentation](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)