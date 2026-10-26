---
title: get_IsWriteProtected()
second_title: Aspose.Slides für C++ API Referenz
description: Gibt einen Wert zurück, der angibt, ob eine gebundene Präsentation schreibgeschützt ist.
type: docs
weight: 27
url: /de/aspose.slides/ipresentationinfo/get_iswriteprotected/
---
## IPresentationInfo::get_IsWriteProtected() Methode

Gibt einen Wert zurück, der angibt, ob eine gebundene Präsentation schreibgeschützt ist.

```cpp
virtual NullableBool Aspose::Slides::IPresentationInfo::get_IsWriteProtected()=0
```

## Anmerkungen

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```

Wenn die Präsentation durch ein Passwort zum Öffnen geschützt ist, ist der Eigenschaftswert gleich NotDefined. Siehe die Aufzählung [NullableBool](../../nullablebool/).

## Siehe auch

* Enum [NullableBool](../../nullablebool/)
* Class [IPresentationInfo](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)