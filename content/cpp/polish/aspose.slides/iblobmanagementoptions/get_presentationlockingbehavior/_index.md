---
title: get_PresentationLockingBehavior()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Ta właściwość określa, czy instancja klasy Presentation może być właścicielem źródła - pliku lub strumienia podczas czasu życia instancji. Jeśli instancja jest właścicielem, blokuje źródło. Pomaga to poprawić zużycie pamięci i wydajność podczas pracy z BLOB-ami, ale źródło (strumień lub plik) nie może być zmieniane w czasie życia instancji Presentation. Oto przykład:"
type: docs
weight: 1
url: /pl/aspose.slides/iblobmanagementoptions/get_presentationlockingbehavior/
---
## IBlobManagementOptions::get_PresentationLockingBehavior() metoda

Ta właściwość określa, czy instancja klasy [Presentation](../../presentation/) może być właścicielem źródła - pliku lub strumienia podczas życia instancji. Jeśli instancja jest właścicielem, blokuje źródło. Pomaga to poprawić zużycie pamięci i wydajność podczas pracy z BLOB-ami, ale źródło (strumień lub plik) nie może być zmieniane podczas życia instancji [Presentation](../../presentation/). Oto przykład:

```cpp
virtual Aspose::Slides::PresentationLockingBehavior Aspose::Slides::IBlobManagementOptions::get_PresentationLockingBehavior()=0
```

## Uwagi

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // Zostanie zgłoszony wyjątek IOException, ponieważ plik pres.pptx jest zablokowany na czas życia obiektu Presentation
    // File::Delete(u"pres.pptx");
}
// po zniszczeniu obiektu Presentation plik jest odblokowany i może zostać usunięty
IO::File::Delete(u"pres.pptx");
```

## Zobacz także

* Enum [PresentationLockingBehavior](../../presentationlockingbehavior/)
* Klasa [IBlobManagementOptions](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)