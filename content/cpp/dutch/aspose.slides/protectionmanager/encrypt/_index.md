---
title: Encrypt()
second_title: Aspose.Slides voor C++ API-referentie
description: Versleutelt Presentation met opgegeven wachtwoord.
type: docs
weight: 105
url: /nl/aspose.slides/protectionmanager/encrypt/
---
## ProtectionManager::Encrypt(System::String) methode

Versleutelt [Presentation](../../presentation/) met het opgegeven wachtwoord.

```cpp
void Aspose::Slides::ProtectionManager::Encrypt(System::String encryptionPassword) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| encryptionPassword | [System::String](../../../system/string/) | The password. |
## Opmerkingen



De volgende voorbeeldcode laat zien hoe u een PowerPoint [Presentation](../../presentation/) kunt versleutelen. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.pptx", SaveFormat::Pptx);
```

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [ProtectionManager](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)