---
title: get_IsWriteProtected()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt einen Wert zurück, der angibt, ob eine gebundene Präsentation schreibgeschützt ist.
type: docs
weight: 27
url: /de/aspose.slides/presentationinfo/get_iswriteprotected/
---
## PresentationInfo::get_IsWriteProtected() Methode

Gibt einen Wert zurück, der angibt, ob eine gebundene Präsentation schreibgeschützt ist.

```cpp
NullableBool Aspose::Slides::PresentationInfo::get_IsWriteProtected() override
```

## Bemerkungen

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```

Wenn die Präsentation durch ein Passwort zum Öffnen geschützt ist, ist der Eigenschaftswert gleich NotDefined. 
## Siehe auch

* Enum [NullableBool](../../nullablebool/)
* Klasse [PresentationInfo](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)