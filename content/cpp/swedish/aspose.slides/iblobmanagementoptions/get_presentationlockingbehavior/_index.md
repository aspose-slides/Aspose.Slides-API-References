---
title: get_PresentationLockingBehavior()
second_title: Aspose.Slides för C++ API-referens
description: "Denna egenskap definierar om en instans av Presentation-klass kan vara en ägare till källan - fil eller ström under instansens livstid. Om instansen är en ägare låser den källan. Detta hjälper till att förbättra minnesförbrukning och prestanda när man arbetar med BLOBs, men källan (ström eller fil) kan inte ändras under Presentation's instanslivstid. Detta är ett exempel:"
type: docs
weight: 1
url: /sv/aspose.slides/iblobmanagementoptions/get_presentationlockingbehavior/
---
## IBlobManagementOptions::get_PresentationLockingBehavior() metod


Denna egenskap definierar om en instans av [Presentation](../../presentation/) klass kan vara ägare till källan - fil eller ström under instansens livstid. Om instansen är ägare låser den källan. Detta hjälper till att förbättra minnesförbrukning och prestanda när man arbetar med BLOBs, men källan (ström eller fil) kan inte ändras under [Presentation](../../presentation/)s instanslivstid. Detta är ett exempel:

```cpp
virtual Aspose::Slides::PresentationLockingBehavior Aspose::Slides::IBlobManagementOptions::get_PresentationLockingBehavior()=0
```

## Anmärkningar



```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // IOException kommer att kastas eftersom pres.pptx är låst för en Presentation livstid
    // File::Delete(u"pres.pptx");
}
// efter att Presentation-objektet förstörts, är filen olåst och kan tas bort
IO::File::Delete(u"pres.pptx");
```

## Se även

* Enum [PresentationLockingBehavior](../../presentationlockingbehavior/)
* Klass [IBlobManagementOptions](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)