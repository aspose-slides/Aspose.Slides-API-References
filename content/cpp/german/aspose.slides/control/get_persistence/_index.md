---
title: get_Persistence()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt die Methode, die zum Speichern von Eigenschaften des ActiveX-Steuerelements verwendet wird. Nur lesbar PersistenceType.
type: docs
weight: 1
url: /de/aspose.slides/control/get_persistence/
---
## Control::get_Persistence() Methode

Ermittelt die Methode, die zum Speichern von Eigenschaften des ActiveX-Steuerelements verwendet wird. Nur lesbar [PersistenceType](../../persistencetype/).

```cpp
PersistenceType Aspose::Slides::Control::get_Persistence() override
```

## Anmerkungen

Das nächste Beispiel zeigt die Verwendung der Persistence-Eigenschaft, um zu prüfen, ob Eigenschaften des ActiveX-Objekts als XML-basierte ActiveX-Eigenschaften geändert werden können: 
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

* Aufzählung [PersistenceType](../../persistencetype/)
* Klasse [Control](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)