---
title: get_IsPasswordProtected()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een waarde die aangeeft of een gekoppelde presentatie is beveiligd met een wachtwoord om te openen.
type: docs
weight: 14
url: /nl/aspose.slides/ipresentationinfo/get_ispasswordprotected/
---
## IPresentationInfo::get_IsPasswordProtected() methode


Retourneert een waarde die aangeeft of een gekoppelde presentatie is beveiligd met een wachtwoord om te openen.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::get_IsPasswordProtected()=0
```

## Opmerkingen



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by a password to open.");
}
```

## Zie ook

* Klasse [IPresentationInfo](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)