---
title: get_AllCustomXmlParts()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja a prezentáció összes egyéni adat részét. Írásvédett ICustomXmlPart[].
type: docs
weight: 287
url: /hu/aspose.slides/presentation/get_allcustomxmlparts/
---
## Presentation::get_AllCustomXmlParts() metódus


Visszaadja a prezentáció összes egyéni adat részét. Írásvédett [ICustomXmlPart](../../icustomxmlpart/)[].

```cpp
System::ArrayPtr<System::SharedPtr<ICustomXmlPart>> Aspose::Slides::Presentation::get_AllCustomXmlParts() override
```

## Megjegyzések


Az alábbi példák bemutatják, hogyan lehet minden egyéni XML részt törölni a PowerPointból [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>(u"PresentationWithCustomXml.pptx");

// Iterate all custom XML Parts
for (System::SharedPtr<ICustomXmlPart> item : pres->get_AllCustomXmlParts())
{
    item->Remove();
}

pres->Save(u"out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ICustomXmlPart](../../icustomxmlpart/)
* Osztály [Presentation](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)