---
title: get_ActiveXControlBinary()
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert de persistentie van een ActiveX-control wanneer de gebruikte methode om te bewaren ofwel PersistStream, PersistStreamInit of PersistStorage is.
type: docs
weight: 118
url: /nl/aspose.slides/control/get_activexcontrolbinary/
---
## Control::get_ActiveXControlBinary() methode


Specificeert de persistentie van een ActiveX-control wanneer de gebruikte methode om te bewaren ofwel PersistStream, PersistStreamInit of PersistStorage is.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::Control::get_ActiveXControlBinary() override
```

## Opmerkingen


Het volgende voorbeeld laat zien hoe de eigenschap ActiveXControlBinary wordt gebruikt om ActiveX-eigenschappen te wijzigen: 
```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // Gebruik uw eigen methode voor het beheren van ActiveX-eigenschappen die in het binaire bestand zijn opgeslagen
    YourMethodHere(control->get_ActiveXControlBinary());
}
```

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Control](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)