---
title: get_AllCustomXmlParts()
second_title: Αναφορά API Aspose.Slides για C++
description: Επιστρέφει όλα τα προσαρμοσμένα τμήματα δεδομένων στην παρουσίαση. Μόνο για ανάγνωση ICustomXmlPart[].
type: docs
weight: 287
url: /el/aspose.slides/presentation/get_allcustomxmlparts/
---
## Presentation::get_AllCustomXmlParts() μέθοδος

Επιστρέφει όλα τα προσαρμοσμένα τμήματα δεδομένων στην παρουσίαση. Μόνο για ανάγνωση [ICustomXmlPart](../../icustomxmlpart/)[].

```cpp
System::ArrayPtr<System::SharedPtr<ICustomXmlPart>> Aspose::Slides::Presentation::get_AllCustomXmlParts() override
```

## Παρατηρήσεις

Τα παρακάτω παραδείγματα δείχνουν πώς να διαγράψετε όλα τα προσαρμοσμένα xml τμήματα από το PowerPoint [Presentation](../).
```cpp
auto pres = System::MakeObject<Presentation>(u"PresentationWithCustomXml.pptx");

// Iterate all custom XML Parts
for (System::SharedPtr<ICustomXmlPart> item : pres->get_AllCustomXmlParts())
{
    item->Remove();
}

pres->Save(u"out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICustomXmlPart](../../icustomxmlpart/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)