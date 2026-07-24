---
title: get_AllCustomXmlParts()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt alle benutzerdefinierten Datenteile in der Präsentation zurück. Nur lesbar ICustomXmlPart[].
type: docs
weight: 287
url: /de/aspose.slides/presentation/get_allcustomxmlparts/
---
## Presentation::get_AllCustomXmlParts() Methode

Gibt alle benutzerdefinierten Datenteile in der Präsentation zurück. Nur lesbar [ICustomXmlPart](../../icustomxmlpart/)[].

```cpp
System::ArrayPtr<System::SharedPtr<ICustomXmlPart>> Aspose::Slides::Presentation::get_AllCustomXmlParts() override
```

## Hinweise

Die folgenden Beispiele zeigen, wie man alle benutzerdefinierten XML-Teile aus PowerPoint [Presentation](../) löscht. 
```cpp
auto pres = System::MakeObject<Presentation>(u"PresentationWithCustomXml.pptx");

// Durchlaufe alle benutzerdefinierten XML-Teile
for (System::SharedPtr<ICustomXmlPart> item : pres->get_AllCustomXmlParts())
{
    item->Remove();
}

pres->Save(u"out.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ICustomXmlPart](../../icustomxmlpart/)
* Klasse [Presentation](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)