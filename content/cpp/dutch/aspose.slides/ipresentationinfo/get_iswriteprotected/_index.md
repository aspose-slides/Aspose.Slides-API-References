---
title: get_IsWriteProtected()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een waarde die aangeeft of een gebonden presentatie schrijfbeveiligd is.
type: docs
weight: 27
url: /nl/aspose.slides/ipresentationinfo/get_iswriteprotected/
---
## IPresentationInfo::get_IsWriteProtected() methode


Retourneert een waarde die aangeeft of een gebonden presentatie schrijfbeveiligd is.

```cpp
virtual NullableBool Aspose::Slides::IPresentationInfo::get_IsWriteProtected()=0
```

## Opmerkingen



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```


Als de presentatie met een wachtwoord voor openen is beveiligd, is de eigenschapswaarde gelijk aan NotDefined. Zie [NullableBool](../../nullablebool/) enumeratie. 
## Zie ook

* Enum [NullableBool](../../nullablebool/)
* Klasse [IPresentationInfo](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)