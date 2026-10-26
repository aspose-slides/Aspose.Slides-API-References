---
title: get_PresentationLockingBehavior()
second_title: Aspose.Slides C++ API Referencia
description: "Ez a tulajdonság meghatározza, hogy a Presentation osztály egy példánya lehet-e a forrás – fájl vagy stream – tulajdonosa a példány életciklusa során. Ha a példány tulajdonos, akkor zárolja a forrást. Ez segít csökkenteni a memóriahasználatot és a teljesítményt BLOB-ok használata közben, de a forrás (stream vagy fájl) nem változtatható meg a Presentation példány életciklusa során. Ez egy példa:"
type: docs
weight: 1
url: /hu/aspose.slides/iblobmanagementoptions/get_presentationlockingbehavior/
---
## IBlobManagementOptions::get_PresentationLockingBehavior() metódus


Ez a tulajdonság meghatározza, hogy a [Presentation](../../presentation/) osztály egy példánya lehet-e a forrás – fájl vagy stream – tulajdonosa a példány életciklusa során. Ha a példány tulajdonos, akkor zárolja a forrást. Ez segít csökkenteni a memóriahasználatot és a teljesítményt BLOB-ok használata közben, de a forrás (stream vagy fájl) nem változtatható meg a [Presentation](../../presentation/) példányának életciklusa során. Ez egy példa:

```cpp
virtual Aspose::Slides::PresentationLockingBehavior Aspose::Slides::IBlobManagementOptions::get_PresentationLockingBehavior()=0
```

## Megjegyzések



```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // IOException lesz dobva, mert a pres.pptx egy Presentation életciklusa idejére zárolt
    // File::Delete(u"pres.pptx");
}
// miután a Presentation objektum megsemmisült, a fájl feloldódik és törölhető
IO::File::Delete(u"pres.pptx");
```

## Lásd még

* Enum [PresentationLockingBehavior](../../presentationlockingbehavior/)
* Osztály [IBlobManagementOptions](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)