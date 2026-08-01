---
title: CheckWriteProtection()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt of een presentatie met een wachtwoord is beveiligd om te wijzigen.
type: docs
weight: 157
url: /nl/aspose.slides/iprotectionmanager/checkwriteprotection/
---
## IProtectionManager::CheckWriteProtection(System::String) methode

Bepaalt of een presentatie met een wachtwoord is beveiligd om te wijzigen.

```cpp
virtual bool Aspose::Slides::IProtectionManager::CheckWriteProtection(System::String password)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Het wachtwoord voor controle. |

### Retourwaarde

True if the password is valid; otherwise, false.

## Opmerkingen

```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```

1. U moet de [IProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) eigenschap controleren voordat u deze methode aanroept.
1. Wanneer het wachtwoord null of leeg is, geeft deze methode false terug.

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [IProtectionManager](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)