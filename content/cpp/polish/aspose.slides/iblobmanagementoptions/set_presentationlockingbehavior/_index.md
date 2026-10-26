---
title: set_PresentationLockingBehavior()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: "Ta właściwość określa, czy instancja klasy Presentation może być właścicielem źródła - pliku lub strumienia podczas życia instancji. Jeśli instancja jest właścicielem, blokuje źródło. Pomaga to poprawić zużycie pamięci i wydajność podczas pracy z BLOB-ami, ale źródło (strumień lub plik) nie może być zmienione podczas życia instancji klasy Presentation. To jest przykład:"
type: docs
weight: 14
url: /pl/aspose.slides/iblobmanagementoptions/set_presentationlockingbehavior/
---
## IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior) metoda


Ta właściwość określa, czy instancja klasy [Presentation](../../presentation/) może być właścicielem źródła - pliku lub strumienia podczas życia instancji. Jeśli instancja jest właścicielem, blokuje źródło. Pomaga to poprawić zużycie pamięci i wydajność podczas pracy z BLOBs, ale źródło (strumień lub plik) nie może być zmienione podczas życia instancji [Presentation](../../presentation/). To jest przykład:

```cpp
virtual void Aspose::Slides::IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior value)=0
```

## Uwagi



```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // IOException zostanie rzucony, ponieważ plik pres.pptx jest zablokowany na cały okres życia obiektu Presentation
    // File::Delete(u"pres.pptx");
}
// po zniszczeniu obiektu Presentation plik jest odblokowany i może zostać usunięty
IO::File::Delete(u"pres.pptx");
```

## Zobacz także

* Enum [PresentationLockingBehavior](../../presentationlockingbehavior/)
* Class [IBlobManagementOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)