---
title: RemoveWriteProtection()
second_title: Aspose.Slides voor C++ API-referentie
description: Verwijdert de schrijfbeveiliging voor deze presentatie.
type: docs
weight: 144
url: /nl/aspose.slides/protectionmanager/removewriteprotection/
---
## ProtectionManager::RemoveWriteProtection() methode

Verwijdert de schrijfbeveiliging voor deze presentatie.

```cpp
void Aspose::Slides::ProtectionManager::RemoveWriteProtection() override
```

## Opmerkingen

Deze voorbeeldcode laat zien hoe u de schrijfbeveiliging van een PowerPoint [Presentation](../../presentation/) verwijdert.
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"write-protection-removed.pptx", SaveFormat::Pptx);
```

## Zie ook

* Klasse [ProtectionManager](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)