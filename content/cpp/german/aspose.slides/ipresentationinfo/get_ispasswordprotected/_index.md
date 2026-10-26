---
title: get_IsPasswordProtected()
second_title: Aspose.Slides für C++ API Referenz
description: Gibt einen Wert zurück, der angibt, ob eine gebundene Präsentation durch ein Passwort zum Öffnen geschützt ist.
type: docs
weight: 14
url: /de/aspose.slides/ipresentationinfo/get_ispasswordprotected/
---
## IPresentationInfo::get_IsPasswordProtected() Methode

Gibt einen Wert zurück, der angibt, ob eine gebundene Präsentation durch ein Passwort zum Öffnen geschützt ist.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::get_IsPasswordProtected()=0
```

## Hinweise



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by a password to open.");
}
```

## Siehe auch

* Klasse [IPresentationInfo](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)