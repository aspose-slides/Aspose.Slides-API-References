---
title: get_AllCustomXmlParts()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Zwraca wszystkie części danych niestandardowych w prezentacji. Tylko do odczytu ICustomXmlPart[].
type: docs
weight: 287
url: /pl/aspose.slides/presentation/get_allcustomxmlparts/
---
## Presentation::get_AllCustomXmlParts() metoda


Zwraca wszystkie części danych niestandardowych w prezentacji. Tylko do odczytu [ICustomXmlPart](../../icustomxmlpart/)[].

```cpp
System::ArrayPtr<System::SharedPtr<ICustomXmlPart>> Aspose::Slides::Presentation::get_AllCustomXmlParts() override
```

## Uwagi


Poniższe przykłady pokazują, jak usunąć wszystkie części xml niestandardowe z PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>(u"PresentationWithCustomXml.pptx");

// Iterate all custom XML Parts
for (System::SharedPtr<ICustomXmlPart> item : pres->get_AllCustomXmlParts())
{
    item->Remove();
}

pres->Save(u"out.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ICustomXmlPart](../../icustomxmlpart/)
* Klasa [Presentation](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)