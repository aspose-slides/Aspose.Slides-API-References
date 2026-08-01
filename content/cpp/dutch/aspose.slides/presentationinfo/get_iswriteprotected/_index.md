---
title: get_IsWriteProtected()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt een waarde op die aangeeft of een gekoppelde presentatie schrijfbeveiligd is.
type: docs
weight: 27
url: /nl/aspose.slides/presentationinfo/get_iswriteprotected/
---
## PresentationInfo::get_IsWriteProtected() methode


Haalt een waarde op die aangeeft of een gekoppelde presentatie schrijfbeveiligd is.

```cpp
NullableBool Aspose::Slides::PresentationInfo::get_IsWriteProtected() override
```

## Opmerkingen



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```


Als de presentatie beschermd is met een wachtwoord om te openen, is de eigenschapswaarde gelijk aan NotDefined. 
 ## Zie ook

* Enum [NullableBool](../../nullablebool/)
* Klasse [PresentationInfo](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)