---
title: get_Persistence()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de methode op die wordt gebruikt om eigenschappen van het ActiveX-besturingselement op te slaan. Alleen-lezen PersistenceType.
type: docs
weight: 1
url: /nl/aspose.slides/control/get_persistence/
---
## Control::get_Persistence() methode


Haalt de methode op die wordt gebruikt om eigenschappen van het ActiveX-besturingselement op te slaan. Alleen-lezen [PersistenceType](../../persistencetype/).

```cpp
PersistenceType Aspose::Slides::Control::get_Persistence() override
```

## Opmerkingen


Het volgende voorbeeld toont het gebruik van de Persistence-eigenschap om te controleren of eigenschappen van het ActiveX-object kunnen worden gewijzigd als op XML gebaseerde ActiveX-eigenschappen:
```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // Gebruik uw eigen methode voor het beheren van ActiveX-eigenschappen die zijn opgeslagen in het binaire bestand
    YourMethodHere(control->get_ActiveXControlBinary());
}
```

## Zie ook

* Enum [PersistenceType](../../persistencetype/)
* Klasse [Control](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)