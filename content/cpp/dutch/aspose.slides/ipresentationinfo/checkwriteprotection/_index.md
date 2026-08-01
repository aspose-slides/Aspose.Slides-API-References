---
title: CheckWriteProtection()
second_title: Aspose.Slides voor C++ API-referentie
description: Controleert of een wachtwoord om de presentatie te wijzigen correct is voor een met schrijfbescherming beveiligde presentatie.
type: docs
weight: 66
url: /nl/aspose.slides/ipresentationinfo/checkwriteprotection/
---
## IPresentationInfo::CheckWriteProtection(System::String) methode

Controleert of een wachtwoord om de presentatie te wijzigen correct is voor een met schrijfbescherming beveiligde presentatie.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckWriteProtection(System::String password)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Het te controleren wachtwoord. |

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

1. U moet de [IPresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) eigenschap controleren voordat u deze methode aanroept.
1. Wanneer wachtwoord null of leeg is, retourneert deze methode false.

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [IPresentationInfo](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)