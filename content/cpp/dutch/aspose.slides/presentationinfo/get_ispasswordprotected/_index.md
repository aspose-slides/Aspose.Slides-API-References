---
title: get_IsPasswordProtected()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt een waarde op die aangeeft of een gekoppelde presentatie is beveiligd met een wachtwoord om te openen.
type: docs
weight: 14
url: /nl/aspose.slides/presentationinfo/get_ispasswordprotected/
---
## PresentationInfo::get_IsPasswordProtected() methode


Haalt een waarde op die aangeeft of een gekoppelde presentatie is beveiligd met een wachtwoord om te openen.

```cpp
bool Aspose::Slides::PresentationInfo::get_IsPasswordProtected() override
```

## Opmerkingen



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by password to open.");
}
```

## Zie ook

* Klasse [PresentationInfo](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)