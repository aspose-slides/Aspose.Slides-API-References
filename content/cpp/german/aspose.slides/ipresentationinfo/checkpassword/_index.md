---
title: CheckPassword()
second_title: Aspose.Slides für C++ API-Referenz
description: Überprüft, ob ein Passwort für eine Präsentation korrekt ist, die mit einem Öffnungspasswort geschützt ist.
type: docs
weight: 53
url: /de/aspose.slides/ipresentationinfo/checkpassword/
---
## IPresentationInfo::CheckPassword(System::String) Methode

Überprüft, ob ein Passwort für eine Präsentation korrekt ist, die mit einem Öffnungspasswort geschützt ist.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckPassword(System::String password)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Das zu prüfende Passwort. |

### Rückgabewert

True, wenn die Präsentation mit einem Öffnungspasswort geschützt ist und das Passwort korrekt ist, andernfalls false.

## Anmerkungen

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```

Wenn das Passwort null oder leer ist, gibt diese Methode false zurück.

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [IPresentationInfo](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)