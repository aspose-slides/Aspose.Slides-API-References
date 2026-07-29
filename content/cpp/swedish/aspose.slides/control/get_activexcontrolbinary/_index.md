---
title: get_ActiveXControlBinary()
second_title: Aspose.Slides för C++ API-referens
description: Anger beständigheten för en ActiveX-kontroll när den metod som används för att spara är antingen PersistStream, PersistStreamInit eller PersistStorage.
type: docs
weight: 118
url: /sv/aspose.slides/control/get_activexcontrolbinary/
---
## Control::get_ActiveXControlBinary() metod


Anger beständigheten för en ActiveX kontroll när den metod som används för att bestå är antingen PersistStream, PersistStreamInit eller PersistStorage.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::Control::get_ActiveXControlBinary() override
```

## Anmärkningar


Nästa exempel visar hur man använder egenskapen ActiveXControlBinary för att ändra ActiveX egenskaper: 
```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // Använd din egen metod för att hantera ActiveX-egenskaper som lagras i dess binära fil
    YourMethodHere(control->get_ActiveXControlBinary());
}
```

## Se även

* Typdef [ArrayPtr](../../../system/arrayptr/)
* Klass [Control](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)