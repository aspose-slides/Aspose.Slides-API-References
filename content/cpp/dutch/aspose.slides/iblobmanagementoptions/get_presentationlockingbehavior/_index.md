---
title: get_PresentationLockingBehavior()
second_title: Aspose.Slides voor C++ API-referentie
description: "Deze eigenschap bepaalt of een instantie van de Presentation-klasse eigenaar kan zijn van de bron - bestand of stream gedurende de levensduur van de instantie. Als de instantie eigenaar is, vergrendelt deze de bron. Dit helpt het geheugengebruik en de prestaties te verbeteren bij het werken met BLOB's, maar de bron (stream of bestand) kan niet worden gewijzigd gedurende de levensduur van Presentation. Dit is een voorbeeld:"
type: docs
weight: 1
url: /nl/aspose.slides/iblobmanagementoptions/get_presentationlockingbehavior/
---
## IBlobManagementOptions::get_PresentationLockingBehavior() methode

Deze eigenschap bepaalt of een instantie van de [Presentation](../../presentation/) klasse eigenaar kan zijn van de bron - bestand of stream gedurende de levensduur van de instantie. Als de instantie eigenaar is, vergrendelt deze de bron. Dit helpt het geheugengebruik en de prestaties te verbeteren tijdens het werken met BLOB's, maar de bron (stream of bestand) kan niet worden gewijzigd gedurende de levensduur van [Presentation](../../presentation/). Dit is een voorbeeld:

```cpp
virtual Aspose::Slides::PresentationLockingBehavior Aspose::Slides::IBlobManagementOptions::get_PresentationLockingBehavior()=0
```

## Opmerkingen

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // IOException wordt gegooid omdat pres.pptx vergrendeld is voor de levensduur van een Presentation
    // File::Delete(u"pres.pptx");
}
// na het vernietigen van het Presentation-object, is het bestand ontgrendeld en kan het worden verwijderd
IO::File::Delete(u"pres.pptx");
```

## Zie ook

* Enum [PresentationLockingBehavior](../../presentationlockingbehavior/)
* Klasse [IBlobManagementOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)