---
title: CheckWriteProtection()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt of een presentatie met een wachtwoord beveiligd is voor bewerken.
type: docs
weight: 157
url: /nl/aspose.slides/protectionmanager/checkwriteprotection/
---
## ProtectionManager::CheckWriteProtection(System::String) methode


Bepaalt of een presentatie met een wachtwoord is beveiligd voor wijziging.

```cpp
bool Aspose::Slides::ProtectionManager::CheckWriteProtection(System::String password) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Het wachtwoord voor controle. |

### Retourwaarde

True als het wachtwoord geldig is; anders false.
## Opmerkingen



```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```



1. U moet de [ProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) eigenschap controleren voordat u deze methode aanroept.
1. Wanneer het wachtwoord null of leeg is, retourneert deze methode false.


## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [ProtectionManager](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)