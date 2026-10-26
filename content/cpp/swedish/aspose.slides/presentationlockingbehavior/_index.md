---
title: PresentationLockingBehavior
second_title: Aspose.Slides för C++ API-referens
description: "Representerar beteendet för hur IPresentation-källan (fil eller System::IO::Stream) behandlas vid laddning och arbete med en instans av IPresentation."
type: docs
weight: 6748
url: /sv/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior enum

Representerar beteendet för hur [IPresentation](../ipresentation/) källan (fil eller [System::IO::Stream](../../system.io/stream/)) behandlas vid laddning och arbete med en instans av [IPresentation](../ipresentation/).

```cpp
enum class PresentationLockingBehavior
```

### Values

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| LoadAndRelease | 0 | Källan låses endast under tiden för [IPresentation](../ipresentation/) konstruktorutförandet. |
| KeepLocked | 1 | Källan låses under hela livslängden för en [IPresentation](../ipresentation/)-instans, tills den tas bort. |

## Remarks

Källan är den parameter som skickas till [IPresentation](../ipresentation/)-konstruktorn. I exemplet nedan är källan filen "pres.pptx":

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
}
```

För detta exempel kommer källan ("pres.pptx"-filen) att låsas under en [IPresentation](../ipresentation/)-instans livstid, dvs. den kan inte ändras eller tas bort av den andra processen.

## See Also

* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)