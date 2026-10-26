---
title: set_PresentationLockingBehavior()
second_title: Aspose.Slides pro C++ API Reference
description: "Tato vlastnost určuje, zda může být instance třídy Presentation vlastníkem zdroje - souboru nebo proudu během životnosti instance. Pokud je instance vlastníkem, zamkne zdroj. To pomáhá zlepšit spotřebu paměti a výkon při práci s BLOBs, ale zdroj (proud nebo soubor) nemůže být během životnosti instance Presentation změněn. Toto je příklad:"
type: docs
weight: 14
url: /cs/aspose.slides/iblobmanagementoptions/set_presentationlockingbehavior/
---
## IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior) metoda


Tato vlastnost určuje, zda může být instance třídy [Presentation](../../presentation/) vlastníkem zdroje – souboru nebo proudu během životnosti instance. Pokud je instance vlastníkem, zamkne zdroj. To pomáhá zlepšit spotřebu paměti a výkon při práci s BLOBy, ale zdroj (proud nebo soubor) nemůže být během životnosti instance [Presentation](../../presentation/) změněn. Toto je příklad:

```cpp
virtual void Aspose::Slides::IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior value)=0
```

## Poznámky



```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // IOException bude vyhozena, protože pres.pptx je zamčen po dobu životnosti Presentation
    // File::Delete(u"pres.pptx");
}
// po zničení objektu Presentation je soubor odemčen a může být smazán
IO::File::Delete(u"pres.pptx");
```

## Viz také

* Výčet [PresentationLockingBehavior](../../presentationlockingbehavior/)
* Třída [IBlobManagementOptions](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)