---
title: get_ActiveXControlBinary()
second_title: Aspose.Slides für C++ API-Referenz
description: Legt die Persistenz eines ActiveX-Steuerelements fest, wenn die zum Persistieren verwendete Methode entweder PersistStream, PersistStreamInit oder PersistStorage ist.
type: docs
weight: 118
url: /de/aspose.slides/control/get_activexcontrolbinary/
---
## Control::get_ActiveXControlBinary() Methode


Legt die Persistenz eines ActiveX-Steuerelements fest, wenn die zum Persistieren verwendete Methode entweder PersistStream, PersistStreamInit oder PersistStorage ist.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::Control::get_ActiveXControlBinary() override
```

## Hinweise


Das nächste Beispiel zeigt die Verwendung der ActiveXControlBinary-Eigenschaft zum Ändern von ActiveX-Eigenschaften: 
```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // Verwenden Sie Ihre eigene Methode zum Verwalten von ActiveX-Eigenschaften, die in ihrer Binärdatei gespeichert sind
    YourMethodHere(control->get_ActiveXControlBinary());
}
```

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Control](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)