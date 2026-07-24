---
title: CheckWriteProtection()
second_title: Aspose.Slides für C++ API-Referenz
description: Überprüft, ob ein Passwort zum Ändern für eine schreibgeschützte Präsentation korrekt ist.
type: docs
weight: 66
url: /de/aspose.slides/ipresentationinfo/checkwriteprotection/
---
## IPresentationInfo::CheckWriteProtection(System::String) Methode


Überprüft, ob ein Passwort zum Ändern für eine schreibgeschützte Präsentation korrekt ist.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckWriteProtection(System::String password)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Das zu prüfende Passwort. |

### Rückgabewert

True, wenn die Präsentation schreibgeschützt ist und das Passwort korrekt ist. False andernfalls.
## Anmerkungen



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```



1. Sie sollten die [IPresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) Eigenschaft prüfen, bevor Sie diese Methode aufrufen.
1. Wenn das Passwort null oder leer ist, gibt diese Methode false zurück.



## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [IPresentationInfo](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)