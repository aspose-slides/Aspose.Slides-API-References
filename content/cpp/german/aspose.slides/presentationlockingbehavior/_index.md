---
title: PresentationLockingBehavior
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt das Verhalten bezüglich der Behandlung der IPresentation-Quelle (Datei oder System::IO::Stream) beim Laden und Arbeiten mit einer Instanz von IPresentation dar."
type: docs
weight: 6748
url: /de/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior Enum


Stellt das Verhalten bezüglich der Behandlung der [IPresentation](../ipresentation/)-Quelle (Datei oder [System::IO::Stream](../../system.io/stream/)) beim Laden und Arbeiten mit einer Instanz von [IPresentation](../ipresentation/) dar.

```cpp
enum class PresentationLockingBehavior
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| LoadAndRelease | 0 | Die Quelle wird nur für die Dauer der [IPresentation](../ipresentation/)-Konstruktorausführung gesperrt. |
| KeepLocked | 1 | Die Quelle wird für die gesamte Lebensdauer der [IPresentation](../ipresentation/)-Instanz gesperrt, bis sie entsorgt wird. |

## Bemerkungen


Die Quelle ist der an den [IPresentation](../ipresentation/)-Konstruktor übergebene Parameter. Im folgenden Beispiel ist die Quelle die Datei \"pres.pptx\": 


```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
}
```


In diesem Beispiel wird die Quelle (Datei \"pres.pptx\") für die Lebensdauer einer [IPresentation](../ipresentation/)-Instanz gesperrt, d. h. sie kann von einem anderen Prozess nicht geändert oder gelöscht werden. 

## Siehe auch

* Namensraum [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)