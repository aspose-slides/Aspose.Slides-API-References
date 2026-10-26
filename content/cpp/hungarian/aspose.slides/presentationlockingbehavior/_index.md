---
title: PresentationLockingBehavior
second_title: Aspose.Slides for C++ API-referencia
description: "Képviseli azt a viselkedést, amely az IPresentation forrás (fájl vagy System::IO::Stream) betöltésekor és egy IPresentation példány használata során történő kezelésére vonatkozik."
type: docs
weight: 6748
url: /hu/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior enum

Képviseli a viselkedést, amely a [IPresentation](../ipresentation/) forrás (fájl vagy [System::IO::Stream](../../system.io/stream/)) kezelésére vonatkozik betöltéskor és egy [IPresentation](../ipresentation/) példány használata során.

```cpp
enum class PresentationLockingBehavior
```

### Értékek

| Név | Érték | Leírás |
| --- | --- | --- |
| LoadAndRelease | 0 | A forrás csak a [IPresentation](../ipresentation/) konstruktor végrehajtásának ideje alatt lesz zárolva. |
| KeepLocked | 1 | A forrás a [IPresentation](../ipresentation/) példány teljes élettartama alatt lesz zárolva, amíg a példány el nem lesz engedve. |

## Megjegyzés

A forrás a [IPresentation](../ipresentation/) konstruktorba átadott paraméter. Az alábbi példában a forrás a \"pres.pptx\" fájl:

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
}
```

Ebben a példában a forrás (\"pres.pptx\" fájl) a [IPresentation](../ipresentation/) példány élettartama alatt lesz zárolva, azaz nem módosítható vagy törölhető a másik folyamat által.

## Lásd még

* Névtér [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)