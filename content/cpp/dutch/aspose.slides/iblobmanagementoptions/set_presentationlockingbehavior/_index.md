---
title: set_PresentationLockingBehavior()
second_title: Aspose.Slides voor C++ API-referentie
description: "Deze eigenschap bepaalt of een instantie van de Presentation-klasse een eigenaar kan zijn van de bron - bestand of stream gedurende de levensduur van de instantie. Als de instantie een eigenaar is, vergrendelt deze de bron. Dit helpt het geheugenverbruik en de prestaties te verbeteren bij het werken met BLOBs, maar de bron (stream of bestand) kan niet worden gewijzigd gedurende de levensduur van Presentation's instantie. Dit is een voorbeeld:"
type: docs
weight: 14
url: /nl/aspose.slides/iblobmanagementoptions/set_presentationlockingbehavior/
---
## IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior) methode

Deze eigenschap bepaalt of een instantie van de [Presentation](../../presentation/) klasse een eigenaar kan zijn van de bron - bestand of stream gedurende de levensduur van de instantie. Als de instantie een eigenaar is, vergrendelt deze de bron. Dit helpt om het geheugenverbruik en de prestaties te verbeteren tijdens het werken met BLOBs, maar de bron (stream of bestand) kan niet worden gewijzigd gedurende de levensduur van [Presentation](../../presentation/)'s instantie. Dit is een voorbeeld:

```cpp
virtual void Aspose::Slides::IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior value)=0
```

## Opmerkingen



```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // IOException wordt gegooid omdat pres.pptx vergrendeld is voor de levensduur van de Presentation
    // File::Delete(u"pres.pptx");
}
// na vernietiging van het Presentation-object is het bestand ontgrendeld en kan het worden verwijderd
IO::File::Delete(u"pres.pptx");
```

## Zie ook

* Enum [PresentationLockingBehavior](../../presentationlockingbehavior/)
* Klasse [IBlobManagementOptions](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)