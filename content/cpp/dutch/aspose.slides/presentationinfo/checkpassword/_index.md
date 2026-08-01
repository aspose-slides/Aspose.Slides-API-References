---
title: CheckPassword()
second_title: Aspose.Slides voor C++ API-referentie
description: Controleert of een wachtwoord correct is voor een presentatie die is beveiligd met een open wachtwoord.
type: docs
weight: 53
url: /nl/aspose.slides/presentationinfo/checkpassword/
---
## PresentationInfo::CheckPassword(System::String) methode

Controleert of een wachtwoord correct is voor een presentatie die is beveiligd met een open wachtwoord.

```cpp
bool Aspose::Slides::PresentationInfo::CheckPassword(System::String password) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Het wachtwoord om te controleren. |

### Retourwaarde

True als de presentatie is beveiligd met een open wachtwoord en het wachtwoord correct is, en anders false.

## Opmerkingen

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```

Wanneer het wachtwoord null of leeg is, geeft deze methode false terug.

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [PresentationInfo](../)
* Namespace [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)