---
title: CheckWriteProtection()
second_title: Aspose.Slides voor C++ API-referentie
description: Controleert of een wachtwoord om te wijzigen correct is voor een met schrijfbescherming beveiligde presentatie.
type: docs
weight: 66
url: /nl/aspose.slides/presentationinfo/checkwriteprotection/
---
## PresentationInfo::CheckWriteProtection(System::String) methode

Controleert of een wachtwoord om te wijzigen correct is voor een met schrijfbescherming beveiligde presentatie.

```cpp
bool Aspose::Slides::PresentationInfo::CheckWriteProtection(System::String password) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Het wachtwoord om te controleren. |

### Retourwaarde

True if the presentation is write protected and the password is correct. False otherwise.

## Opmerkingen



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```

1. U moet de [PresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) eigenschap controleren voordat u deze methode aanroept.
1. Wanneer password null of leeg is, retourneert deze methode false.

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [PresentationInfo](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)