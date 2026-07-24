---
title: set_PresentationLockingBehavior()
second_title: Aspose.Slides für C++ API-Referenz
description: "Diese Eigenschaft definiert, ob eine Instanz der Presentation-Klasse Eigentümer der Quelle - Datei oder Stream während der Lebensdauer der Instanz sein kann. Wenn die Instanz Eigentümer ist, sperrt sie die Quelle. Dies trägt zur Reduzierung des Speicherverbrauchs und zur Leistungssteigerung bei der Arbeit mit BLOBs bei, jedoch kann die Quelle (Stream oder Datei) während der Lebensdauer von Presentation nicht geändert werden. Dies ist ein Beispiel:"
type: docs
weight: 14
url: /de/aspose.slides/iblobmanagementoptions/set_presentationlockingbehavior/
---
## IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior) Methode

Diese Eigenschaft definiert, ob eine Instanz der [Presentation](../../presentation/) Klasse Eigentümer der Quelle – Datei oder Stream während der Lebensdauer der Instanz sein kann. Wenn die Instanz Eigentümer ist, sperrt sie die Quelle. Dies trägt zur Reduzierung des Speicherverbrauchs und zur Leistungssteigerung bei der Arbeit mit BLOBs bei, jedoch kann die Quelle (Stream oder Datei) während der Lebensdauer von [Presentation](../../presentation/) nicht geändert werden. Dies ist ein Beispiel:

```cpp
virtual void Aspose::Slides::IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior value)=0
```

## Bemerkungen

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // IOException wird ausgelöst, weil pres.pptx für die Lebensdauer einer Presentation gesperrt ist
    // File::Delete(u"pres.pptx");
}
// Nachdem das Presentation-Objekt zerstört wurde, ist die Datei freigegeben und kann gelöscht werden
IO::File::Delete(u"pres.pptx");
```

## Siehe auch

* Enum [PresentationLockingBehavior](../../presentationlockingbehavior/)
* Klasse [IBlobManagementOptions](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)