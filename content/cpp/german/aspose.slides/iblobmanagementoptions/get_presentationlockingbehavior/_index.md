---
title: get_PresentationLockingBehavior()
second_title: Aspose.Slides für C++ API-Referenz
description: "Diese Eigenschaft definiert, ob eine Instanz der Presentation-Klasse Eigentümer der Quelle - Datei oder Stream während der Lebensdauer der Instanz sein kann. Ist die Instanz Eigentümer, sperrt sie die Quelle. Dies hilft, den Speicherverbrauch und die Leistung beim Arbeiten mit BLOBs zu verbessern, jedoch kann die Quelle (Stream oder Datei) während der Lebensdauer der Presentation-Instanz nicht geändert werden. Dies ist ein Beispiel:"
type: docs
weight: 1
url: /de/aspose.slides/iblobmanagementoptions/get_presentationlockingbehavior/
---
## IBlobManagementOptions::get_PresentationLockingBehavior() Methode


Diese Eigenschaft definiert, ob eine Instanz der [Presentation](../../presentation/) Klasse Eigentümer der Quelle - Datei oder Stream während der Lebensdauer der Instanz sein kann. Ist die Instanz Eigentümer, sperrt sie die Quelle. Dies hilft, den Speicherverbrauch und die Leistung beim Arbeiten mit BLOBs zu verbessern, jedoch kann die Quelle (Stream oder Datei) während der Lebensdauer der [Presentation](../../presentation/)-Instanz nicht geändert werden. Dies ist ein Beispiel:

```cpp
virtual Aspose::Slides::PresentationLockingBehavior Aspose::Slides::IBlobManagementOptions::get_PresentationLockingBehavior()=0
```

## Anmerkungen



```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // Eine IOException wird ausgelöst, weil pres.pptx für die Lebensdauer einer Presentation gesperrt ist
    // File::Delete(u"pres.pptx");
}
// nachdem das Presentation-Objekt zerstört wurde, ist die Datei entsperrt und kann gelöscht werden
IO::File::Delete(u"pres.pptx");
```

## Siehe auch

* Enum [PresentationLockingBehavior](../../presentationlockingbehavior/)
* Klasse [IBlobManagementOptions](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)