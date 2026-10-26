---
title: PresentationLockingBehavior
second_title: Odwołanie API Aspose.Slides dla C++
description: "Reprezentuje zachowanie dotyczące traktowania źródła IPresentation (pliku lub System::IO::Stream) podczas ładowania i pracy z instancją IPresentation."
type: docs
weight: 6748
url: /pl/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior enum

Reprezentuje zachowanie dotyczące traktowania źródła [IPresentation](../ipresentation/) (pliku lub [System::IO::Stream](../../system.io/stream/)) podczas ładowania i pracy z instancją [IPresentation](../ipresentation/).

```cpp
enum class PresentationLockingBehavior
```

### Wartości

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| LoadAndRelease | 0 | Źródło będzie zablokowane tylko na czas wykonywania konstruktora [IPresentation](../ipresentation/). |
| KeepLocked | 1 | Źródło będzie zablokowane na cały okres życia instancji [IPresentation](../ipresentation/), aż zostanie zwolnione. |

## Uwagi

Źródło jest parametrem przekazywanym do konstruktora [IPresentation](../ipresentation/). W poniższym przykładzie źródłem jest plik "pres.pptx":

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
}
```

W tym przykładzie źródło (plik "pres.pptx") będzie zablokowane na okres życia instancji [IPresentation](../ipresentation/), tzn. nie może być zmienione ani usunięte przez inny proces.

## Zobacz też

* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)