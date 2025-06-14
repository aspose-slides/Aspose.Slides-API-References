---
title: Persistence
second_title: Aspose.Slides für .NET API Referenz
description: Holt die verwendete Methode zum Speichern von Eigenschaften des ActiveX-Steuerelements. Nur lesen PersistenceTypeaspose.slides/persistencetype.
type: docs
weight: 50
url: /de/aspose.slides/control/persistence/
---

## Control.Persistence-Eigenschaft

Holt die verwendete Methode zum Speichern von Eigenschaften des ActiveX-Steuerelements. Nur lesen [`PersistenceType`](../../persistencetype).

```csharp
public PersistenceType Persistence { get; }
```

### Beispiele

Das nächste Beispiel zeigt die Verwendung der Persistence-Eigenschaft, um zu überprüfen, ob die Eigenschaften des ActiveX-Objekts als XML-basierte ActiveX-Eigenschaften geändert werden können:

```csharp
[C#]
if (control.Persistence == PersistenceType.PersistPropertyBag)
{
    control.Properties["Value"] = value;
}
else
{
    YourMethodHere(control.ActiveXControlBinary); //Verwenden Sie Ihre eigene Methode zum Verwalten von ActiveX-Eigenschaften, die in seiner Binärdatei gespeichert sind
}
```

### Siehe auch

* enum [PersistenceType](../../persistencetype)
* class [Control](../../control)
* namespace [Aspose.Slides](../../control)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->