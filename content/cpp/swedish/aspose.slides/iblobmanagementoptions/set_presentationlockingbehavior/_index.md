---
title: set_PresentationLockingBehavior()
second_title: Aspose.Slides för C++ API-referens
description: "Denna egenskap definierar om en instans av Presentation-klassen kan vara ägare till källan - fil eller ström under instansens livstid. Om instansen är en ägare låser den källan. Detta hjälper till att förbättra minnesanvändning och prestanda när man arbetar med BLOBs, men källan (ström eller fil) kan inte ändras under Presentations instanslivstid. Detta är ett exempel:"
type: docs
weight: 14
url: /sv/aspose.slides/iblobmanagementoptions/set_presentationlockingbehavior/
---
## IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior) metod

Denna egenskap definierar om en instans av klassen [Presentation](../../presentation/) kan vara ägare till källan - fil eller ström under instansens livstid. Om instansen är en ägare låser den källan. Detta hjälper till att förbättra minnesanvändning och prestanda när man arbetar med BLOBs, men källan (ström eller fil) kan inte ändras under [Presentation](../../presentation/)'s instanslivstid. Detta är ett exempel:

```cpp
virtual void Aspose::Slides::IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior value)=0
```

## Anmärkningar



```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // IOException kommer att kastas eftersom pres.pptx är låst under Presentationens livstid
    // File::Delete(u"pres.pptx");
}
// efter att Presentation-objektet har förstörts är filen olåst och kan raderas
IO::File::Delete(u"pres.pptx");
```

## Se även

* Enum [PresentationLockingBehavior](../../presentationlockingbehavior/)
* Klass [IBlobManagementOptions](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)