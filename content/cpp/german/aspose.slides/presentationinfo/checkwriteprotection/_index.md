---
title: CheckWriteProtection()
second_title: Aspose.Slides für C++ API-Referenz
description: Überprüft, ob ein Kennwort zum Ändern für eine schreibgeschützte Präsentation korrekt ist.
type: docs
weight: 66
url: /de/aspose.slides/presentationinfo/checkwriteprotection/
---
## PresentationInfo::CheckWriteProtection(System::String) Methode


Überprüft, ob ein Kennwort zum Ändern für eine schreibgeschützte Präsentation korrekt ist.

```cpp
bool Aspose::Slides::PresentationInfo::CheckWriteProtection(System::String password) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Das zu prüfende Kennwort. |

### Rückgabewert

True, wenn die Präsentation schreibgeschützt ist und das Kennwort korrekt ist. Andernfalls False.

## Bemerkungen



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```



1. Sie sollten die [PresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) Eigenschaft überprüfen, bevor Sie diese Methode aufrufen.
1. Wenn das Kennwort null oder leer ist, gibt diese Methode false zurück.



## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [PresentationInfo](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)