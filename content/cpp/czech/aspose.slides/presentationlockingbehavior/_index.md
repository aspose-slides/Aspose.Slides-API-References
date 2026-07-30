---
title: PresentationLockingBehavior
second_title: Aspose.Slides pro C++ API Reference
description: "Representuje chování týkající se zpracování zdroje IPresentation (souboru nebo System::IO::Stream) během načítání a práce s instancí IPresentation."
type: docs
weight: 6748
url: /cs/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior výčet

Reprezentuje chování týkající se zpracování zdroje [IPresentation](../ipresentation/) (soubor nebo [System::IO::Stream](../../system.io/stream/)) během načítání a práce s instancí [IPresentation](../ipresentation/).

```cpp
enum class PresentationLockingBehavior
```

### Hodnoty

| Name | Value | Description |
| --- | --- | --- |
| LoadAndRelease | 0 | Zdroj bude uzamčen pouze po dobu vykonávání konstruktoru [IPresentation](../ipresentation/). |
| KeepLocked | 1 | Zdroj bude uzamčen po celou dobu existence instance [IPresentation](../ipresentation/), dokud nebude uvolněn. |

## Poznámky

Zdroj je parametr předaný konstruktoru [IPresentation](../ipresentation/). V níže uvedeném příkladu je zdrojem soubor \"pres.pptx\":

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
}
```

V tomto příkladu bude zdroj (soubor \"pres.pptx\") uzamčen po dobu existence instance [IPresentation](../ipresentation/), tj. nelze jej změnit ani smazat jiným procesem.

## Viz také

* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)