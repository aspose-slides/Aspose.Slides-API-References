---
title: CheckPassword()
second_title: Aspose.Slides für C++ API Referenz
description: Überprüft, ob ein Passwort für eine Präsentation, die mit einem offenen Passwort geschützt ist, korrekt ist.
type: docs
weight: 53
url: /de/aspose.slides/presentationinfo/checkpassword/
---
## PresentationInfo::CheckPassword(System::String) Methode


Überprüft, ob ein Passwort für eine Präsentation, die mit einem offenen Passwort geschützt ist, korrekt ist.

```cpp
bool Aspose::Slides::PresentationInfo::CheckPassword(System::String password) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Das zu prüfende Passwort. |

### Rückgabewert

True, wenn die Präsentation mit einem offenen Passwort geschützt ist und das Passwort korrekt ist, andernfalls false.
## Hinweise



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```



Wenn das Passwort null oder leer ist, gibt diese Methode false zurück. 

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [PresentationInfo](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)