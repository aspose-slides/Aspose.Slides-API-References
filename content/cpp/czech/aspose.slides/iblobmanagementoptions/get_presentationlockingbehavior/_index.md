---
title: get_PresentationLockingBehavior()
second_title: Aspose.Slides pro C++ API Reference
description: "Tato vlastnost určuje, zda instance třídy Presentation může být vlastníkem zdroje - souboru nebo proudu během životnosti instance. Pokud je instance vlastníkem, zamkne zdroj. To pomáhá zlepšit spotřebu paměti a výkon při práci s BLOBy, ale zdroj (proud nebo soubor) nelze během životnosti instance Presentation změnit. Toto je příklad:"
type: docs
weight: 1
url: /cs/aspose.slides/iblobmanagementoptions/get_presentationlockingbehavior/
---
## IBlobManagementOptions::get_PresentationLockingBehavior() metoda


Tato vlastnost určuje, zda instance třídy [Presentation](../../presentation/) může být vlastníkem zdroje - souboru nebo proudu během životnosti instance. Pokud je instance vlastníkem, zamkne zdroj. To pomáhá zlepšit spotřebu paměti a výkon při práci s BLOBy, ale zdroj (proud nebo soubor) nelze změnit během životnosti instance [Presentation](../../presentation/). Toto je příklad:

```cpp
virtual Aspose::Slides::PresentationLockingBehavior Aspose::Slides::IBlobManagementOptions::get_PresentationLockingBehavior()=0
```

## Poznámky



```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // Bude vyvolána výjimka IOException, protože soubor pres.pptx je uzamčen po celou dobu životnosti Presentation
    // File::Delete(u"pres.pptx");
}
// po zničení objektu Presentation je soubor odemčen a může být smazán
IO::File::Delete(u"pres.pptx");
```

## Viz také

* Enum [PresentationLockingBehavior](../../presentationlockingbehavior/)
* Třída [IBlobManagementOptions](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)