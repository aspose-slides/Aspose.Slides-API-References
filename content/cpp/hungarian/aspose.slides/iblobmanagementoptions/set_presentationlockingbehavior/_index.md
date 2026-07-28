---
title: set_PresentationLockingBehavior()
second_title: Aspose.Slides C++ API-referencia
description: "Ez a tulajdonság meghatározza, hogy a Presentation osztály egy példánya lehet-e a forrás - fájl vagy adatfolyam - tulajdonosa az élettartama alatt. Ha a példány tulajdonos, akkor zárolja a forrást. Ez segít a memóriahasználat és a teljesítmény javításában BLOB-ok kezelése közben, de a forrás (adatfolyam vagy fájl) nem módosítható a Presentation példányának élettartama alatt. Ez egy példa:"
type: docs
weight: 14
url: /hu/aspose.slides/iblobmanagementoptions/set_presentationlockingbehavior/
---
## IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior) metódus

Ez a tulajdonság határozza meg, hogy a [Presentation](../../presentation/) osztály egy példánya lehet-e a forrás – fájl vagy adatfolyam – tulajdonosa az élettartama alatt. Ha a példány tulajdonos, akkor zárolja a forrást. Ez segít a memóriafelhasználás és a teljesítmény javításában BLOB-ok kezelésénél, de a forrás (adatfolyam vagy fájl) nem módosítható a [Presentation](../../presentation/) példányának élettartama alatt. Ez egy példa:

```cpp
virtual void Aspose::Slides::IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior value)=0
```

## Megjegyzés

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // IOException lesz dobva, mert a pres.pptx le van zárva egy Presentation élettartama alatt
    // File::Delete(u"pres.pptx");
}
// Miután a Presentation objektum megsemmisült, a fájl feloldódik és törölhető
IO::File::Delete(u"pres.pptx");
```

## Lásd még

* Enum [PresentationLockingBehavior](../../presentationlockingbehavior/)
* Osztály [IBlobManagementOptions](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)